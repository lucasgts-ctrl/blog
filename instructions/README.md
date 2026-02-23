# Git bash ssh key-gen
ssh-keygen -t ed25519 -C "youre-mail@example.com"
or
ssh-keygen -t rsa -b 4096 -C "youre-mail@example.com"

# Commands
copy ssh key in bash
cat ~/.ssh/id_ed25519.pub
ssh -T git@github.com

# Git commands
git add .
git commit -m 'anything'
git push origin main -u (only one time), next time git push

# Port 443
Where i work the port 22 is bloked so i changed
use this:
nano /.ssh/config
Host github.com
  Hostname ssh.github.com
  Port 443
  User git
save and test it
ssh -T git@github.com

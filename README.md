# Git bash ssh key-gen
ssh-keygen -t ed25519 -C "youre-mail@example.com"
or
ssh-keygen -t rsa -b 4096 -C "youre-mail@example.com"

# Commands
copy ssh key in bash
cat ~/.ssh/id_ed25519.pub
ssh -T git@github.com
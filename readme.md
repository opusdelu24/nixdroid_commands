# just to jot down some useful commands for myself

nix-on-droid switch --flake ~/.config/nix-on-droid

## ssh
chmod 700 ~/.ssh
chmod 600 ~/.ssh/config
ssh-keygen -t rsa -b 4096 -f somename



## some github command

(rename the branch from master to main)
(if you already set up your preferred default branch name then you may not use it that much)
git branch -m master main

git remote add main git@...

git commit -m "first commit"

(first push)
git push --set-upstream main main


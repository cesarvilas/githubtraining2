# githubtraining2
GitHub training with Camila

This training was on March 19th 2025.

had a problem with gpg but solved like this


You have config.gpgsign set. This means Git will try to cryptographically sign every commit you make with Gnu Privacy Guard which you don't appear to have installed.

This is not necessary to use Git except in certain special circumstances, so it's probably best to turn it off for now.

You can find out where it's set with git config --show-origin commit.gpgsign. You should see something like this.

$ git config --show-origin commit.gpgsign
file:/Users/schwern/.gitconfig  true
If it's in your own global .gitconfig like above, turn it off.

$ git config --global commit.gpgsign false
                       
                      

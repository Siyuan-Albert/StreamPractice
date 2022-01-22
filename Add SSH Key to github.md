Add SSH Key to github

1. generate ssh key in your computer
   `ssh-keygen -t rsa`

2. copy the ssh key

   `pbcopy < ~/.ssh/id_rsa.pub`

   Or

   `cat ~/.ssh/id_rsa.pub`

   Or 

   `cat ~/.ssh/id_dsa.pub`

3. import your ssh key

   Settings/SSH and GPG keys
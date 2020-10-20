#This is the guide to create git and github conneciton with SSH Key
##Generate ssh key on localhost first
###create a github account

- (sidenote) to create a new file use 'touch cmd' in bash ==> touch filename

```cat id_rsa.pub```

- paste the public key on github in settings GPG SSH key option in your profile menu
- once saved go abck to your terminal 
- run github cmd

git add .
git commit -m 'msg'
git push -u origin main

- go back to github repo to verify the changes and connections

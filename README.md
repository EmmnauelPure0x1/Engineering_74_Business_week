## This is the guide to create git and github connection with SSH key

## Steps to creating Repo:

 - We need to download gitbash from the internet. Click Next next next til download is complete.
 - Create a Directory (preferably on the desktop) mkdir /desktop/Engineeting74 cmd
 - Create Github account. (We will need to link this with our 'ON PREM' device via SSH connection).
 - Create repo (Engineering_74_Business_Week) in my case.
 - A secure connection to github is required therefore we create an SSH with the ssh-keygen cmd => (ssh-keygen -t rsa -b 4096 -C "spartae email address")
 - Change working directory with  ~/.ssh cmd
 - run cat id_rsa.pub cmd in working directory
 - copy the output of the previous command 
 - switch over to github and paste your public key in the settings => SSH and GPG keys => add new SSH key... paste pub-key in.
 - navigated to eng74 on prem directory (bash)
 - git init (initialization of eng74 to github)
 - created README.md file in repo using 'touch README.md' 
 - used 'nano README.md' cmd to edit readme markdown (.md) file
 - run 'git add README.md' cmd
 - run 'git commit -m README.md'
 - run 'git push -u origin main'

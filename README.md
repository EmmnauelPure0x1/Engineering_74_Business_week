## Steps to creating a Git Repo 

- Download Git on localhost
- Create GitHub account online
- Generate SSH Key:
	- ssh-keygen -t rsa -b 4096 -C "<Input email registered with GitHub>"
- On localhost navigate to pub ssh key location with following command:
	- $ cd ~/.ssh
	- $ ls
	- copy content of > id_rsa.pub using cat to initially read content
- On web GitHub account navigate to Settings => SSH & GPG Keys
- Paste SSH key in SSH field.

### Once Complete, you are set up with a secure SSH connection to your GitHub Account.

## Creating a Repository

- On GitHub account go to Repositories and click new.
- Name Repo
- On localhost create folder where work will be saved
- Once work in localhost file, go to GitBash
- In gitbash navigate to folder where work resides and run follwoing cmds:
	- echo "# test" >> README.
	- git init
	- git add README.md
	- git commit -m "first commit"
	- git branch -M main
	- git remote add origin https://github.com/EmmnauelPure0x1/test.git
	- git push -u origin main 

** Once above steps are complete you will be able to commit and push files as desired. **



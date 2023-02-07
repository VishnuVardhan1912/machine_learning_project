# Start Machine Learning project

### Sofware and account requirement.

1. [Github Account](https://github.com)
2. [Heroku Account](https://dashboard.heroku.com/login)
3. [VS Code IDE](https://code.visualstudio.com/download)
4. [GIT cli](https://git-scm.com/downloads)

Creating coda environmet
'''
conda create -p venv python==3.7 -y

It creates in same folder if we use -p, -n is used to create conda env in conda folder
'''
conda activate venv/
'''
OR
'''
conda activate venv
'''

'''
pip install -r requirements.txt
'''

To Add files to git
'''
git add .
'''

OR
'''
git add <filename>
'''

Note: To ignore file or folder from git we can write name of file/folder in .gitignore file

To check the git status
'''
fit status
'''

To check all version maintained by git

'''
git log
'''

To create version/commit all changes by git

'''
git commit -m "message"
'''

To send version/changes to github
'''
git push origin main

url is stored in origin variable
'''

To check remote url 

'''
git remote -v
'''

To check branch

'''
git branch
'''
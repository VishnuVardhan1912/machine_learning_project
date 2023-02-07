# Start Machine Learning project

### Sofware and account requirement.

1. [Github Account](https://github.com)
2. [Heroku Account](https://dashboard.heroku.com/login)
3. [VS Code IDE](https://code.visualstudio.com/download)
4. [GIT cli](https://git-scm.com/downloads)
5. [GET Documentation](https://git-scm.com/docs/gittutorial)

Creating coda environmet
```
conda create -p venv python==3.7 -y
```
It creates in same folder if we use -p, -n is used to create conda env in conda folder

To activate envirnoment
```
conda activate venv/
```
OR
```
conda activate venv
```
To install all packages present in requirements.txt file

```
pip install -r requirements.txt
```

To Add files to git

```
git add .
```

OR

```
git add <filename>
```

Note: To ignore file or folder from git we can write name of file/folder in .gitignore file

To check the git status
```
fit status
```

To check all version maintained by git

```
git log
```

To create version/commit all changes by git

```
git commit -m "message"
```

To send version/changes to github
```
git push origin main
```
url is stored in origin variable

To check remote url 

```
git remote -v
```

To check branch

```
git branch
```

To setup CI/CD pipeline in heroku we need 3 information

1. HEROKU_EMAIL = 
2. HEROKU_API_KEY = 
3. HEROKU_APP_NAME = 

BUILD DOCKER IMAGE

```
docker build -t <image_name>:<tagname> .
```

Note: Image name for docker must be lowercase

To list docker image
```
docker images
```

Run docker image
```
docker run -p 5000:5000 -e PORT=5000 <image_id>
```
To check running container in docker 

```
docker ps
```
To stop docker container

```
docker stop <container_id>
```
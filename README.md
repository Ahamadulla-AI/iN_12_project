

Software and accounts requirements
1. Git Account
2. Heroku Account
3. V.S Code IDE
4.GIT Cli

Creating conda environment
Conda create -p venv python ==3.11 -y

To activate created venv environment
conda activate venv/

To check the git status
'''
git status
'''

To commit changes locally
'''
git commit -m "test-1"
'''

To push changes to the repo from local to git repositories
'''
git push origin main
'''

To check remote URLs
'''
git remote -v
'''

The next step is to create CI/CD Pipe line, to create CI/CD Pipe line we need the below 3 infomation:-
1. Heroku Email Address
2. Heroku API key
3. Heroku APP NAME

Next step- Buld a Docker Image

'''
docker build -t <image_name>:<tagname>
>Note: Image name for docker must be in small letters only.

To list Docker images
'''
docker images
'''

To run docker image

'''
docker run -p 5000:5000 -e PORT=5000 c0f887f9ce07
'''
To check running containers in docker
'''
docker ps
'''

To stop docker container
'''
docker stop <container_id>
# Machine_Learning_project1
This is my first machine learning project

Creating conda environment

```
conda create -p venv python==3.7 -y

```
conda activate venv/

```
pip install -r requirements.txt

```
To check the status
```
git status
```

To add files to git
```
git add .
```

To check all version maintained bt git
```

git log

```

To send changes to github 
``` 
git push origin main

```

To setup CI/CD pipeline in heroku we need 3 information
1. Heroku email id = surajagasti92@gmail.com
2. Heroku_API_key <>
3. Heroku app_name = ml-regression-app1


BUILD DOCKER IMAGE
```

docker build -t <image_name>:<tagname> .
```
> Note: Image name for docker must be lowecase

To list docker image
```
docker images
```

Run docker image
```
docker run -p 5000:5000 -e PORT=5000 87910ff9bcef
```

To check running container in docker
```
docker ps
```

To stop any container 
```
docker stop <container_id>
```


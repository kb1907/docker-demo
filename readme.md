[![This a workflow title](https://github.com/kb1907/docker-demo/actions/workflows/push-docker-image.yaml/badge.svg)](https://github.com/kb1907/docker-demo/actions/workflows/push-docker-image.yaml)

# Docker-Flask-GithubActions-DockerHub Pipeline Demo

Docker-Flask-GithubActions-DockerHub Pipeline demo folder for MLOPS 2022 Data Scientist Trainees and DS Aspirants.

New environment

```bash
    conda create -n Docker-Demo python=3.9 -y
```

Activate the environment

```bash
    conda activate Docker-Demo
```

Requirements File

```bash
    touch requirements.txt
```

Connect to Github

```bash
git init
```

```bash
git add .
```

```bash
git commit -m "first commit"
```

oneliner updates for readme

```bash
git add . && git commit -m "update Readme.md"
```

pushing changes to new repo

```bash
git branch -M main
git remote add origin git@github.com:kb1907/docker-demo.git
git push -u origin main
```

Dockerfile

```bash
touch Dockerfile
```

Build Docker Image

```bash
docker build -t docker-demo .
```

List of Images

```bash
docker image ls
```

Run the Docker image and see the inside of the container

```bash
docker run -it docker-demo bash
```

Run the docker image

```bash
docker run -d -p 5000:5000 docker-demo
```

Then go to 0.0.0.0:5000 to see the page.

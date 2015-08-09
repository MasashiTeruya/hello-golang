# hello-golang

## Goal
- Build distributed web application with golang
- Dockerize your go http server

## Prerequisite
Docker

## Getting Started

Get repository from GitHub
```
git clone https://github.com/MasashiTeruya/hello-golang.git && cd hello-golang/app
```

Build Docker image
```
docker built -t hello-golang .
```

Run app
```
docker run -d -p=8080:8080 hello-golang
```

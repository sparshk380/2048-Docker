
# 2048 Game 

This Docker file consists of the Deployment of the popular game 2048 created by Gabriele Cirulli.






## Deployment

To deploy this project run on your terminal:

```bash
  git clone git@github.com:sparshk380/2048-Docker.git
```
```bash
  cd 2048-Docker
```
```bash
  docker build -t <image-name:tag> .
```
```bash
  docker run -d -p 80:80 --name=2048 <image-name:tag>
```



## To access the game on your machine:

Go to the following address in your browser:

```bash
  http://localhost:80/
```


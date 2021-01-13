# CAP CICD

![Docker build and deploy to KYMA](https://github.com/gopalanand333/CAP-CICD/workflows/Docker%20build%20and%20deploy%20to%20KYMA/badge.svg)

This simple bookshop application triggers a github action to build docker image with latest code and deploy it to kyma runtime. 

### To use the project
1. Make a fork of it.
2. Go to settings and add the following
   1. DOCKER_USER: Add your dockerhub username.
   2. DOCKER_PASSWORD: your dockerhub password.
   3. KYMA: Kubeconfig downloaded from kyma.
3. In .github\workflows\deocker-image.yaml replace the docker user name with your user.
4. Change `image: gopalanand/capcicd:latest` to your user in deployment.yaml with your user.

No push the changes and see the magic.
.
..

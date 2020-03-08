# nanoservice

## Install and deploy
Install [KinD](https://blog.alexellis.io/be-kind-to-yourself/) and create a cluster

Build function, push the image to an image registry and deploy the function:
```
$ faas-cli up
```

## Test function
```
$ curl http://127.0.0.1:8080/function/nanoservice -d hello
hello
```

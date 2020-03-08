# nanoservice

## Install and Deploy
Install [kinD](https://blog.alexellis.io/be-kind-to-yourself/) and create a cluster

Build function and push the image to an image registry
```
$ faas-cli build -f stack.yml
$ faas-cli push -f stack.yml
$ faas-cli deploy -f stack.yml
```


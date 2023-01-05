# URL
~~~
git config -l
https://github.com/darcy-it/docker-container.git
~~~

## Docker command

## ubuntu22.04
```
sudo docker images
sudo docker image build -t ubuntu/only:22.04 --no-cache .
```

## amazonlinux2.0
~~~
sudo docker images
sudo docker image build -t linux2/only:2.0.20211223.0 --no-cache .
~~~
~~~
sudo docker container run -it --rm --name ubuntu22.04 <IMAGE ID>
~~~

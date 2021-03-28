DevOps Chronos
===========================

Welcome to the Docker World!
-----------
This is a docker conteinerization power example.

Each of these two directories contains a docker-compose.yaml file, witch means, all you have to do is compose it up folowing the steps:

To run nginx contaner:
-----------
```console
foo@user:~$ cd nginx-Docker && docker-compose up
```
running in current terminal section.
or
-----------
```console
foo@user:~$ cd nginx-Docker && docker-compose up -d
```
running in background

Stop it folowing:
----------------------
```console
foo@user:~$ docker-compose down
```

To run mysql contaner:
-----------
```console
foo@user:~$ cd mysql-Docker && docker-compose up
```
running in current terminal section.
or
-----------
```console
foo@user:~$ cd nginx-Docker && docker-compose up -d
```
running in background
Stop it folowing:
----------------------
```console
foo@user:~$ docker-compose down
```
or
-----------
```console
foo@user:~$ cd nginx-Docker && docker-compose down -v
```
removing the created data volume
> :warning: **-v flag means all your volume in the docker will be lost**: Be very careful here!


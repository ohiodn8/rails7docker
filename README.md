# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version: 3.2.1

* Rails version: 7.0.4.2

* Configuration

* Database creation: Default SQLite3


## Steps used to build docker image

* For the ubuntu image using DockerfileUbuntu

```
docker build -t rubyonrails7app -f DockerfileUbuntu .
```

* For the alpine image (using the default dockerfile)

```
docker build -t alpinerails7app .
```

* To run the created ruby on rails alpine image

```
docker run -dit -p 3000:3000 alpinerails7app
```

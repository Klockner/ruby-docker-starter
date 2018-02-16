## Docker setup to start a ruby project

#### How to use:
Put these three project files in your ruby on rails project root folder:
1. [Dockerfile](https://github.com/Klockner/ruby-docker-starter/blob/master/Dockerfile)
2. [docker-compose.yml](https://github.com/Klockner/ruby-docker-starter/blob/master/docker-compose.yml)
3. [run.sh](https://github.com/Klockner/ruby-docker-starter/blob/master/run.sh)

Now, run this command to make run.sh executable:
```ssh
$ chmod +x run.sh
```
You can launch it now using:
```ssh
$ docker-compose up
```

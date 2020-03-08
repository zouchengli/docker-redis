# docker-redis
Redis server 3.2.13 build for docker
# quickly local build
$ docker build . -t redis:3.2.13
# quickly load run
$ docker run -d -p 6379:6379 --name redis redis:3.2.13

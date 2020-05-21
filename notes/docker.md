# Docker cheatsheet / notes


Stop and remove all docker containers:
`docker stop $(docker ps -a -q)` and then `docker rm $(docker ps -a -q)`

When number of networks limit reached:
`docker network prune`

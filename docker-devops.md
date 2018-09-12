
[immoc](https://coding.imooc.com/learn/list/189.html)

## 不了解的技术点或工具
* docker-machine
* vagrant
* stress
* top
* telent
* wireshark
* haproxy
* netns
* veth
* brctl
* nat
* vslan ( underlay overlay )
* etcd


## 命令
* docker-compose ps
* docker-compose rm
* docker-compose up -d
* docker-compose down
* docker-compose images
* docker-compose exec [service] bash
* docker-compose up —scale
* docker-compose build

* docker logs [?]
* docker volume ls
* docker volume rm [?]
* docker volume inspect [?]

* docker build
* docker build -t [image name]

* docker network ls
* docker network create
* docker network create -d overlay []
* docker network inspect [ network name ]
* docker network connect [ network ] [ container ]

* docker run
* docker run -d —name=[?]
* docker run -v [alise]:[path]
* docker run -p [ container port ]:[ local port ]
* docker run —memory=200M [?] […cmds]
* docker run —cpu-shares=10 —cpu=1
* docker run —link [?]  // dns
* docker run —network [ none, host, bridge, cus-bridge ]
* docker run -e [var]=[value]

* docker inspect [?]

* docker exec -it 

* docker ps -a
* docker rmi
* docker rm

* docker stop
* docker rm $(docker ps -aq)

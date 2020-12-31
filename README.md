# Dev-tools

Dev-tools is a repository of tools for devs such as: Message or Event provider, Relational/NoSQL database, DevOps tools, etc.

# New Features!

  - Kafka and kafdrop
  - MongoDB and Mongo Express
  - Postgres and PgAdmin4
  - MySQL and Adminer


### Tech

Dev-tools uses:

* [Docker] - Docker is an open platform for developing, shipping, and running applications.
* [Docker-Compose] - Compose is a tool for defining and running multi-container Docker applications.

### Installation

Dev-tools requires [Docker] and [Docker-Compose] to run.

The installation of each dependency is not covered here. You can see how to install them on their official site.

Dev-tools need to be cloned on GitHub.
```sh
$ git clone git@github.com:vfcarmo/dev-tools.git
$ cd dev-tools
```

### Run a tool
To perform any dev-tools, you need to access the specific directory and type docker-compose up, as the example bellow:

```sh
$ cd MongoDB
$ docker-compose up -d
```

### Stop a tool
To stop any dev-tools, you need to access the specific directory and type docker-compose down, as the example bellow:

```sh
$ cd MongoDB
$ docker-compose down
```

### Todos

 - Add more dev-tools

License
----

MIT


**Free Software, Hell Yeah!**

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)


   [Docker]: <https://www.docker.com/>
   [Docker-Compose]: <https://docs.docker.com/compose/>

# react-java-develop-env
Example project on how to set up the development environment

# Maven Dockerイメージであれこれ試した時のメモ

## Dockerホスト側での操作

```
$ git clone https://github.com/bbachi/react-java-develop-env.git
$ cd react-java-develop-env/
$ docker run --name react-java-sample -p 3000:8080 -v "$(pwd)":/citest/react-java-develop-env -w /citest/react-java-develop-env -it maven:3-openjdk-8 /bin/bash
```

## dockerコンテナ側での操作

```
# curl -sL https://deb.nodesource.com/setup_14.x | bash -
# apt-get update
# apt-get install -y nodejs
# node -v
# npm -v
# npm install -g gulp-cli
# gulp --version
# mvn clean install
# echo "" >> src/main/resources/application.properties
# echo "server.address=0.0.0.0" >> src/main/resources/application.properties
# mvn spring-boot:run
```

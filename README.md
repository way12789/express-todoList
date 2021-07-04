# express-todoList

A todoList using express and MongoDB.

> 用express框架和MongoDB，配合ejs模版引擎编写的todoList项目。

<img src="https://ftp.bmp.ovh/imgs/2021/07/e42d0dc481b9809a.png">

## install MongoDB Service
See [MongoDB Manual](https://docs.mongodb.com/manual/administration/install-community/)
- windows
> Just download exe file and install MongoD as a Service.
- mac
> Download tgz file and do some settings.
```shell
# download tgz file
tar -zxvf mongodb-macos-x86_64-4.2.6.tgz
sudo cp /path/to/the/mongodb-directory/bin/* /usr/local/bin/

# create db data path and log path
sudo mkdir -p /usr/local/var/mongodb
sudo mkdir -p /usr/local/var/log/mongodb

# run mongodb service
sudo mongod --dbpath /usr/local/var/mongodb --logpath /usr/local/var/log/mongodb/mongo.log --fork
```
The default mongodb port is 27017.

## run project
```shell
npm i
npm start
```
Open browser at http://localhost:3000.

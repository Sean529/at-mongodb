## 配置全局变量
vim ~/.bash_profile

PATH=${PATH}:/usr/local/mongodb/bin

source ~/.bash_profile

## 启动命令
mongod --config /usr/local/mongodb/etc/mongod.conf
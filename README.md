# 快速启动服务器

## Step1

启动实例，点击「远程连接」进入服务器后台

## Step2

输入命令`screen -ls`检查是否有screen实例运行

如果没有，输入`screen -S minecraft`创建一个名为「minecraft」的screen实例，同时会自动进入到实例后台

输入`cd ./minecraft_server_1.21.1/`进入服务器根目录

## Step3

输入`java -Xms4096M -Xmx4096M -jar server.jar nogui`启动服务器

启动服务器之后，可以通过`stop`命令停止服务器


# QQChat
Java实现的仿制qq聊天，实现注册、登录、忘记密码、修改密码、添加好友、群聊和私聊，连接数据库,IDE为Eclipse，数据库为MySQL8.0
# 提示 
* 如果你是新手，将整个文件下载到本地后，那么打开项目方法为：File -> Open Project from File System -> Directory... -> abc/MyQQClient -> 选择文件夹 -> Finsh。abc代表你下载的目录。同理这样操作MyQQClient。
* 由于Eclipse不自带JDBC， 你需要要引入JDBC（连接数据库用），具体引入办法请百度。
* 由于需要连接数据库，你需要在网上下载MySQL，并创名为 myqquser 的数据库， 并将MySql的登录密码改为 zzzz , 您也可以在项目文件中的密码部分 zzzz 修改成你的数据库密码，在myqquser库中创建tb_user表，表里有user_id, user_name, user_pwd, user_question, user_ans字段， user_id为主键（设为自动增长)  INT类型，其他的都为VARCHAR类型，这样就可以注册用户并登录。
* 这里接受发送消息的时候有点bug，只有第一次启动IDE才能正常通信，如果关闭服务端后，重新打开服务器后再次登录用户可能会收不到消息，这时重新启动IDE就好了。
* 另外我这里的包的命名格式不够规范但不影响项目的运行， 您新建包时注意命名规范。

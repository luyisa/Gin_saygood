# 你好，Gin！
## 配置说明
1. 从GitHUb指定地址下载，使用如下命令：

```
git@github.com:luyisa/Gin_saygood.git
```
2. 依据本地环境重新初始化和构建本项目，使用如下命令：
```
go mod init
go mod tidy
```
3. 下面就可以开始尝试启动服务器，使用如下命令：
```
go run main.go
```
检查控制台日志输出，保证服务器被正常启动，正常显示信息如下：
```
[GIN-debug] [WARNING] Creating an Engine instance with the Logger and Recovery middleware already attached.

[GIN-debug] [WARNING] Running in "debug" mode. Switch to "release" mode in production.
 - using env:   export GIN_MODE=release
 - using code:  gin.SetMode(gin.ReleaseMode)

[GIN-debug] GET    /hello                    --> main.NewRouter.func2 (5 handlers)
[GIN-debug] GET    /hello/                   --> main.NewRouter.func2 (5 handlers)
[GIN] 2024/11/28 - 09:00:32 | 200 |     961.375µs |             ::1 | GET      "/hello"
```
4. 如果已确认服务器正常启动，就可以从浏览器访问定义的API啦，使用如下链接：
[/hello](http://localhost:8080/hello)

5. 从浏览器上可以看到如下信息：
```
{"message":"你好，八维"}
```

# Hello, Say Hello to Gin
## Setup Guidance 
1. Please use Git to clone this sample repository by :

```
git@github.com:luyisa/Gin_saygood.git
```

2. Init this GO repository with your local environment by :
```
go mod init
go mod tidy
```

3. Execute and run backend server by :
```
go run main.go
```

You can check with following information in terminal console :

```
[GIN-debug] [WARNING] Creating an Engine instance with the Logger and Recovery middleware already attached.

[GIN-debug] [WARNING] Running in "debug" mode. Switch to "release" mode in production.
 - using env:   export GIN_MODE=release
 - using code:  gin.SetMode(gin.ReleaseMode)

[GIN-debug] GET    /hello                    --> main.NewRouter.func2 (5 handlers)
[GIN-debug] GET    /hello/                   --> main.NewRouter.func2 (5 handlers)
[GIN] 2024/11/28 - 09:00:32 | 200 |     961.375µs |             ::1 | GET      "/hello"
```

4. If the go server can be started successfully, then you can visit API `/hello` on Browser by link [/hello](http://localhost:8080/hello)

5. You can see following information on UI :
```
{"message":"你好，八维"}
```
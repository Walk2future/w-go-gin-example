# w-go-gin-example
一个example，一个开始

熟悉go+gin目录结构，熟悉各种本地库，第三方库，熟悉错误处理，熟悉日志处理，熟悉简易jwt

```
gin-blog/
├── conf
│   └── app.ini
├── main.go
├── middleware
│   └── jwt
│       └── jwt.go
├── models
│   ├── article.go
│   ├── auth.go
│   ├── models.go
│   └── tag.go
├── pkg
│   ├── e
│   │   ├── code.go
│   │   └── msg.go
│   ├── logging
│   │   ├── file.go
│   │   └── log.go
│   ├── setting
│   │   └── setting.go
│   └── util
│       ├── jwt.go
│       └── pagination.go
├── routers
│   ├── api
│   │   ├── auth.go
│   │   └── v1
│   │       ├── article.go
│   │       └── tag.go
│   └── router.go
├── runtime
```

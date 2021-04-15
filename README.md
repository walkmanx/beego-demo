# beego-demo

## Beego 安装

1. 配置代理
	go env -w GOPROXY=https://goproxy.cn
	
2. 安装并更新beego
	go get github.com/astaxie/beego
	
3. 安装Bee工具
	go get github.com/beego/bee
	
4. 创建Project
	bee new projectname
	
5. 在projectname目录下执行
	go mod download github.com/astaxie/beego
	go get -u github.com/astaxie/beego
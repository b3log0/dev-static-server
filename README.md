# dev-static-server

开发用静态资源 HTTP 伺服器。

## 动机

* 在 Windows 上使用 goexec 实时生成伺服器的话每次使用都需要设置防火墙，长久下来防火墙规则会非常多
* 使用 NGINX 等的话配置有点麻烦，我只需要一个简单的 HTTP 服务在开发时引入静态资源用
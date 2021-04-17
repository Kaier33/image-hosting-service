# github + jsDelivr 来搭建一个免费图床

正常情况下, 要访问我们放在github仓库的图片, 可以在地址后面加个 **?raw=true**  

https://github.com/Kaier33/image-hosting-service/blob/main/avatar.jpeg?raw=true  

但是鉴于我国国情, 不翻墙访问gayhub那是相当的慢, 于是我们借助一下jsDelivr, 一个免费的开源CDN  

> 使用说明  

https://cdn.jsdelivr.net/gh/<你的github用户名>/<你的图床仓库名>@<仓库版本号>/图片的路径

> 举个🌰

源图片地址: https://github.com/Kaier33/image-hosting-service/blob/main/avatar.jpeg?raw=true  

CDN: https://cdn.jsdelivr.net/gh/kaier33/image-hosting-service@main/avatar.jpeg

# 个人CDN加速图床

我在自己Github的README自述文件插入了照片，并存放在仓库中的文件夹下，但是当每次访问该README时，发现图片并不能每次流畅加载，因此有了这篇文章。

### Github

##### 创建图片仓库

- 新建个人仓库，用于存储图片

![](https://cdn.jsdelivr.net/gh/johnrothan/img01/20220420215936.png)

##### 生成Token

- 在Github的Setting页面下侧边栏底部选择Developer settings

![](https://cdn.jsdelivr.net/gh/johnrothan/img01/20220420220316.png)

- 设置Token属性并生成Token

![](https://cdn.jsdelivr.net/gh/johnrothan/img01/20220420220938.png)

- Token生成后仅显示一次，务必用你喜欢的方式记住Token值。当然，如果你不厌其烦，完全可以重新生成Token

### PicGo

- 安装PicGo

PicGo官网：https://molunerfinn.com/PicGo/

选择符合自己机器的PicGo版本下载并完成安装

- 配置PicGo客户端

![](https://cdn.jsdelivr.net/gh/johnrothan/img01/20220420222324.png)

在自定义域名中，我们建议您使用  https://cdn.jsdelivr.net/gh/用户名/仓库名  的格式，在这里我们选择了快速免费共有的CDN-jsdelivr

您可以在PicGo设置中打开时间戳重命名开关，防止图片名字重复（概率很小）

- 遇到上传失败问题

请移步至SM.MS图床https://sm.ms，注册并登录。

接着，选择User->Dashboard，生成Secret Token，并记住。

![](https://cdn.jsdelivr.net/gh/johnrothan/img01/20220420224007.png)

![](https://cdn.jsdelivr.net/gh/johnrothan/img01/20220420224232.png)

然后，回到PicGo配置SM.MS图床Token

![](https://cdn.jsdelivr.net/gh/johnrothan/img01/20220420224358.png)

### 开始上手

现在，你可以使用并享受CDN图床的Amazing表现

- 上传图片，这将会存储到PicGo相册和Github的图床仓库

![](https://cdn.jsdelivr.net/gh/johnrothan/img01/20220420224514.png)

![](https://cdn.jsdelivr.net/gh/johnrothan/img01/20220420224724.png)

- 然后，用相册中每个图片下的选项生成CDN加速的访问链接，并替换之前的链，图片访问速度即可上升。

### 我的使用

我的README文件中的图片链接使用了这篇教程后，对比此前的现象，极大提升了图片访问的流畅度。

- 你可以从[这儿](https://github.com/JohnRothan)查看效果

![](https://cdn.jsdelivr.net/gh/johnrothan/img01/20220420225855.png)

### 帮助文档

如果遇到棘手的问题，请先学会查阅帮助文档或者搜索引擎

- PicGo帮助文档https://picgo.github.io/PicGo-Doc/zh/guide/

- Github帮助文档https://docs.github.com/cn

- JSDELIVRhttps://www.jsdelivr.com/

- SM.MS图床https://sm.ms

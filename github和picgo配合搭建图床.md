## 第一步 GitHub 仓库设置

### 1. 新建仓库

点击 git 主页右上角的 + 创建 New repository；

> 填写仓库名称，例如我就创建了一个名称是pic的仓库。
>
> **这里注意**：，仓库得设置为 Public 。

![创建仓库](https://raw.githubusercontent.com/jincaiw/pic/master/image-20230221212828691.png)





### 2. 创建 token 并复制保存

- 仓库已经建立，点击右上角头像，然后进入设置页面；

![image-20230221213659510](https://raw.githubusercontent.com/jincaiw/pic/master/image-20230221213659510.png)

- 在页面最下找到 Developer settings，点击进入；

![image-20230221213824964](https://raw.githubusercontent.com/jincaiw/pic/master/image-20230221213824964.png)



- 创建 token；


在description随便填写，勾选复选框 repo ，点击确认 Generate token 就可以。

![image-20230221214134462](https://raw.githubusercontent.com/jincaiw/pic/master/image-20230221214134462.png)



生成一串字符 token，这个 token 只出现一次需要保存（建议保存在mac备忘录）

![image-20230221214344779](https://raw.githubusercontent.com/jincaiw/pic/master/image-20230221214344779.png)
---

## 第二步 安装PicGo 客户端配置

### 1. 下载&安装

我的电脑已经安装了brew，直接通过cask库安装就可以，最新版本是：2.3.1。PicGo 是一个开源的图床工具，免费，基本使用够了。

安装命令如下：

```bash
brew install picgo --cask
```

### 2.图床配置

填写仓库名-复制粘贴token，其他的配置保持默认就可以。

![image-20230221215228129](https://raw.githubusercontent.com/jincaiw/pic/master/image-20230221215228129.png)




## git (本地)

### 是否安装git

`git --version`

```js
命令：
git --version
结果：
git version 2.24.3 (Apple Git-128)

```

### 安装git

### 初始化git 

`git init  `

```js
命令：
gi t init
结果：
Initialized empty Git repository in /Users/mac/Desktop/leams/.git/
```



### 到缓存区

`git add .`



### 工作/缓存区状态

`git status`

![工作区](https://chuge25-1306445635.cos.ap-guangzhou.myqcloud.com/typroa/%E5%B7%A5%E4%BD%9C%E5%8C%BA.jpg?imageSlim)



![缓存区](https://chuge25-1306445635.cos.ap-guangzhou.myqcloud.com/typroa/%E7%BC%93%E5%AD%98%E5%8C%BA.jpg?imageSlim)



### 更新版本

`git commit -m "版本备注"`

```js
[master (root-commit) d747c8a] git基础命令

 1 file changed, 41 insertions(+)

 create mode 100644 first_git.md
```



### 版本日志

`git log`

![git日志](https://chuge25-1306445635.cos.ap-guangzhou.myqcloud.com/typroa/git%E6%97%A5%E5%BF%97.jpg?imageSlim)



### 查看分支

`git branch`

### 创建分支

`git branch dev`

### 切换分支


`git checkout master`

![git主分支切换](https://chuge25-1306445635.cos.ap-guangzhou.myqcloud.com/typroa/git%E4%B8%BB%E5%88%86%E6%94%AF%E5%88%87%E6%8D%A2.jpg?imageSlim)


### 合并分支

`git merge`

### 删除分支

`git branch -d 分支名称`


### git基础命令总结

> git --version
>
> git init
>
> git status 
>
> git add . 
>
> git commit -m "版本"
>
>  git log 
>
> git branch
>
> git branch dev
>
> git checkout master
>

> git merge
>
> git branch -d 分支名称

> 


 



## GitHub（云端）
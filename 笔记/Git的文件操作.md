## 文件的4种状态
![Snipaste_2023-01-09_18-56-33.png](https://cdn.nlark.com/yuque/0/2023/png/34325414/1673261804216-6918f4df-80bf-42f8-b499-f2a5b777e1bf.png#averageHue=%2357ac5f&clientId=u05568bf9-85a2-4&crop=0&crop=0&crop=1&crop=1&from=ui&id=u9d8916fd&margin=%5Bobject%20Object%5D&name=Snipaste_2023-01-09_18-56-33.png&originHeight=222&originWidth=919&originalType=binary&ratio=1&rotation=0&showTitle=false&size=218604&status=done&style=none&taskId=uf01111f4-52d2-4399-9b09-6ba6bda7610&title=)
> 查看文件状态

```git
git status [filename]  # 查看指定文件操作
git status # 查看所有文件状态
```
## 文件操作
> 提交操作

```git
# 添加所有文件到暂存区
git add .  # 千万不要漏了点
#  提交暂存区的内容到本地仓库
git commmit -m "注释消息内容" # -m 表示提交信息
```

> 忽略文件

**主目录新建.gitignore"文件**
> **.gitignore文件规则**

![Snipaste_2023-01-10_09-28-44.png](https://cdn.nlark.com/yuque/0/2023/png/34325414/1673314135490-4d5a7dcd-ff37-49b6-bb04-0df35ddbfa74.png#averageHue=%23eef0f0&clientId=u05568bf9-85a2-4&crop=0&crop=0&crop=1&crop=1&from=ui&id=u39174bc1&margin=%5Bobject%20Object%5D&name=Snipaste_2023-01-10_09-28-44.png&originHeight=325&originWidth=889&originalType=binary&ratio=1&rotation=0&showTitle=false&size=196281&status=done&style=none&taskId=u3d81ced6-4b1a-46c7-b8bd-d5feba1d968&title=)
**在.gitconfig文件中添加**
![Snipaste_2023-01-10_21-41-01.png](https://cdn.nlark.com/yuque/0/2023/png/34325414/1673358084132-1d1c0816-f09c-45e2-ba17-e269067727c5.png#averageHue=%23d4d3cc&clientId=u5ac72c15-4b68-4&crop=0&crop=0&crop=1&crop=1&from=ui&id=ude6eff22&margin=%5Bobject%20Object%5D&name=Snipaste_2023-01-10_21-41-01.png&originHeight=38&originWidth=143&originalType=binary&ratio=1&rotation=0&showTitle=false&size=4626&status=done&style=none&taskId=uda13f604-d84c-4f32-963d-d5d41b74e73&title=)等号后面是.gitignore文件地址**注意要用正斜线**

> 查看文件

```git
cat [文件名]
```



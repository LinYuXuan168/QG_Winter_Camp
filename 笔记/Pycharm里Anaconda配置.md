<a name="ih3gw"></a>
## 简介
Anacoonda实质上是一个涵盖python库的软件包，自带conda包管理系统与环境管理系统
<a name="dLdWo"></a>

## Anaconda环境
<a name="coSQJ"></a>

### 环境创建
一.利用原生的Navigator创建<br />![Snipaste_2023-01-10_19-14-02.png](https://cdn.nlark.com/yuque/0/2023/png/34325414/1673349273064-83852d64-5a42-42bb-be98-fdfe8341cd97.png#averageHue=%23f3f3f2&clientId=uf31cfbbe-b2c2-4&crop=0&crop=0&crop=1&crop=1&from=ui&height=393&id=ua6a87dab&margin=%5Bobject%20Object%5D&name=Snipaste_2023-01-10_19-14-02.png&originHeight=657&originWidth=1095&originalType=binary&ratio=1&rotation=0&showTitle=false&size=104619&status=done&style=none&taskId=uc5c62490-9e0f-44e8-a51d-e8eae55f738&title=&width=654.5177001953125)<br />二.利用Anaconda命令行创建
```powershell
# 查看当前存在的虚拟环境
conda env list
conda info -e

# Python创建虚拟环境
conda create -n [环境名] python= [版本号]

# 安装额外的包
conda install -n [环境名] [包]

# 环境激活
conda activate [环境名]

# 退出环境
conda deactivate

# 删除环境 
conda remove -n [环境名] --all

#  使用国内镜像源
conda config --add channels [url]

# 恢复镜像源
conda config --remove-key channels

```

<a name="OMx0B"></a>
### 环境变量配置
**找到安装目录，逐一找到下面的文件，复制文件地址添加即可**<br />![Snipaste_2023-01-10_18-52-38.png](https://cdn.nlark.com/yuque/0/2023/png/34325414/1673348024786-4f3d72c5-fca1-4b75-959b-cdef7b2c51a7.png#averageHue=%23f3f0ed&clientId=uf31cfbbe-b2c2-4&crop=0&crop=0&crop=1&crop=1&from=ui&id=u5e543447&margin=%5Bobject%20Object%5D&name=Snipaste_2023-01-10_18-52-38.png&originHeight=83&originWidth=406&originalType=binary&ratio=1&rotation=0&showTitle=false&size=4077&status=done&style=none&taskId=u5752f1ca-41fa-41ba-bde9-fd1c3c9cab1&title=)
<a name="bHjai"></a>
## Pycharm里Anaconda的配置
一.创建项目，勾选先前配置的解释器<br />![Snipaste_2023-01-10_18-55-52.png](https://cdn.nlark.com/yuque/0/2023/png/34325414/1673348162475-9d94786e-ce1a-4be4-96c4-52302707e5c2.png#averageHue=%233c3f41&clientId=uf31cfbbe-b2c2-4&crop=0&crop=0&crop=1&crop=1&from=ui&height=301&id=u4dbc2d7e&margin=%5Bobject%20Object%5D&name=Snipaste_2023-01-10_18-55-52.png&originHeight=552&originWidth=781&originalType=binary&ratio=1&rotation=0&showTitle=false&size=23309&status=done&style=none&taskId=ue1875250-1bda-45f4-bece-1cf05b5509d&title=&width=426.1725769042969)<br />二.选择添加解释器，添加python解释器即可


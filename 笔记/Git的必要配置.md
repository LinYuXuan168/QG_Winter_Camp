**所有的配置的文件都保存在本地**
<a name="eggEA"></a>
## 查看配置
查看git用户配置 git config -l<br />查看系统配置： git config --system --list<br />查看本地配置 git config --global --list
> 相关配置的位置
> --system系统级 在安装目录下:eg:"D:\Software\Git\etc\gitconfig"
> --global 全局级 用户配置 只适合于当前登录的用户 "C:\Users\LinYuXuan\.gitconfig"


<a name="YNk5t"></a>
## 设置用户名和邮箱（必须进行的）（用户标识）
git config --global user.name "名称"<br /> git config --global user.email "邮箱"


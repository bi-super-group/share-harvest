## 关于提交自己的分享到github的步骤
### 分享的内容
- 可以是文件或文件夹，注意名称中带上自己的名字和分享时间，例如“每周分享-张三20190515”

### 把github上面的仓库克隆到本地
```
git clone https://github.com/CKTim/BlueTooth.git（https://github.com/CKTim/BlueTooth.git替换成远程库的地址）
```
### 进入到克隆下来的文件夹share-harvest下，添加自己的分享
### 点击右键，选择Git Bash Here，依次输入以下指令
```
git add .        （注：别忘记后面的.，此操作是把你分享的文件都添加进来）
```
```
git commit  -m  "提交信息"  （注：“提交信息”里面换成你需要，例如“我分享了什么什么内容”）
```
```
git push -u origin master   （注：此操作目的是把本地仓库push到github上面，此步骤需要你输入帐号和密码。如果本地已登录有账号，需要先注销）
```

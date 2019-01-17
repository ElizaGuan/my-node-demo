我的天，李威真帅

使用 ssh 的方式去连接远程仓库


1. 生成本地电脑的 公钥与私钥
  ssh-keygen -t rsa -C "xxx@xxx.com"

1.1 将本地 生成的  公钥 给写到 远程平台上（github）

2. 将本地仓库与远程仓库建立py关系
  git remote add origin xxxx
github迁移hy-bin，alpine

1.下载

wget https://github.com/apernet/hysteria/releases/download/app/v2.6.2/hysteria-linux-amd64


2.新建你的 GitHub 仓库
比如你叫 xin3351812/hysteria-bin（随便起个名字）


3.在本地新建一个空文件夹，把文件放进去

mkdir hysteria-bin
mv hysteria-linux-amd64 hysteria-bin/
cd hysteria-bin


4.初始化 git 仓库

git init


5. 添加你的二进制文件到 git

git add hysteria-linux-amd64
git commit -m "add hysteria-linux-amd64 v2.6.2"


6. 添加远程仓库（填你自己的）

git remote add origin https://github.com/xin3351812/hysteria-bin.git


7. 推送到 GitHub
如果是 main 分支：

git branch -M main
git push -u origin main

如果你默认 master，直接：

git push -u origin master


8. 现在你的文件就托管在你自己的 GitHub 仓库了
下载链接如下：

https://github.com/3351812/hysteria-bin/raw/main/hysteria-linux-amd64
wget https://github.com/xin3351812/hysteria-bin/raw/main/hysteria-linux-amd64

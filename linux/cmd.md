## 压缩/解压
[Linux下压缩速率比较](https://www.cnblogs.com/joshua317/p/6170839.html)  

## RPM
1. rpm -ivh xxxx.rpm 安装rpm包  
2. rpm -ql jdk1.8  安装包名和版本号，多试几种也许就能找到，jdk安装在了/usr/java/jdk1.8.0_221-amd64  
3. rpm -ivh --prefix=/opt/java xxx.rpm 将rpm包安装在某个文件夹下  
4. 
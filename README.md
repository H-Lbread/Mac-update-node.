# 更新Mac下node环境和npm
1⃣️ 先查看本机node.js版本：
```
1 node -v
```
2⃣️ 清除node.js的cache：
```
1 sudo npm cache clean -f
```
3⃣️ 安装 n 工具，这个工具专门用来管理node.js版本的。
```
1 sudo npm install -g n
```
4⃣️ 安装最新版本的node.js
```
sudo n stable
```
5⃣️ 再次查看node版本
```
1 node -v
```
6⃣️ 更新npm到最新版本
```
1 sudo npm install npm@latest -g
```
7⃣️ 验证
```
1 node -v
2 npm -v
```

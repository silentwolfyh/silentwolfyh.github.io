

## npm和node 
### npm安装指定版本
```
sudo npm install -g braces@3.0.2
sudo npm install -g glob-parent@6.0.2
sudo npm install -g prismjs@1.29.0
sudo npm install -g @react-navigation/native@6.1.7
sudo npm install -g hexo@6.3.0
sudo npm install -g hexo-deployer-git@4.0.0
sudo npm install -g hexo-generator-archive@0.1.5
sudo npm install -g hexo-generator-category@0.1.3
sudo npm install -g hexo-generator-feed@1.2.2
sudo npm install -g hexo-generator-index@0.2.1
sudo npm install -g hexo-generator-search@2.4.0
sudo npm install -g hexo-generator-tag@0.2.0
sudo npm install -g hexo-prism-plugin@2.3.0
sudo npm install -g hexo-renderer-ejs@2.0.0
sudo npm install -g hexo-renderer-marked@6.1.1
sudo npm install -g hexo-renderer-stylus@0.3.3
sudo npm install -g hexo-server@0.3.3


    "@react-navigation/native": "^6.1.7",
    "braces": "^3.0.2",
    "glob-parent": "^6.0.2",
    "hexo": "^6.3.0",
    "hexo-deployer-git": "^4.0.0",
    "hexo-generator-archive": "^0.1.5",
    "hexo-generator-category": "^0.1.3",
    "hexo-generator-feed": "^1.2.2",
    "hexo-generator-index": "^0.2.1",
    "hexo-generator-search": "^2.4.0",
    "hexo-generator-tag": "^0.2.0",
    "hexo-prism-plugin": "^2.3.0",
    "hexo-renderer-ejs": "^2.0.0",
    "hexo-renderer-marked": "^6.1.1",
    "hexo-renderer-stylus": "^0.3.3",
    "hexo-server": "^0.3.3"

```

```
npm 和 node 版本
(base)  yuhui@yuhuideMacBook-Pro  ~/PycharmProjects/ngn_code/ngnlab-website-admin-master  npm  -v
9.6.7
(base)  yuhui@yuhuideMacBook-Pro  ~/PycharmProjects/ngn_code/ngnlab-website-admin-master  node -v
v18.17.0
```

## 参考文献
- [pip和npm使用总结](https://blog.csdn.net/yexudengzhidao/article/details/83588371)
- [github.io使用方法](https://blog.csdn.net/qq_41523340/article/details/127269682)


## NPM查看版本
```
一、查看远程仓库版本
1、查看包所有版本

语法：npm view [软件包名] versions

    # 查看docker的所有版本号
    npm view docker versinos

2、查看包的最新版本

语法：npm view [软件包名] version

    # 查看docker的最新版本号
    npm view docker version

3、查看包的更多版本信息

语法：npm info [软件包名]

    # 查看docker的更多版本信息
    npm info docker

二、查看本地已安装的版本
1、查看当前项目已安装某包的版本

语法：npm ls [软件包名]

    # 查看当前项目安装的vant版本
    npm ls vant
```
npm view prismjs
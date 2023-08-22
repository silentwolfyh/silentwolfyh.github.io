## 修改说明
- [主页](_config.yml)
- [主页的title的名称](themes/matery/_config.yml)
- [主页的联系方式](source/contact/index.md)
- [主页的数字化应用](source/research/index.md)
- [图片](themes/matery/source/medias)

## 目录说明
- node_modules 可以删除，系统会自动重建
- pulic        可以删除，系统会自动重建 （hexo generate 生成的）
- scaffolds 【重要】系统自带目录
- source    【重要】文字内容【核心】
  - source/_posts 主页下面的几个文章
  - source/contact 联系方式
  - source/members  数据治理
  - source/projects 成功案例
  - source/publications 解决方案
  - source/publications 数字化应用
  - source/resources 新闻动态
  - CNAME 域名
- themes    【重要】样式和图片
  - themes/matery/source/medias 网站中的图片

## 参考文献
- [pip和npm使用总结](https://blog.csdn.net/yexudengzhidao/article/details/83588371)
- [github.io使用方法](https://blog.csdn.net/qq_41523340/article/details/127269682)
- [pages.github.com/](https://pages.github.com/)
- [guardui](https://lancemao.github.io/guardui/)
- [数据公司](https://www.datacvg.com/Product/Detail/295153457694863?bd_vid=10293663544104905827)
- [GitHub+Hexo 搭建个人网站详细教程](https://zhuanlan.zhihu.com/p/26625249)
- [hexo.io](https://hexo.io/docs/configuration)
- [github.io创建个人网站](https://blog.csdn.net/weixin_46530492/article/details/130797998?spm=1001.2101.3001.6661.1&utm_medium=distribute.pc_relevant_t0.none-task-blog-2%7Edefault%7ECTRLIST%7EPayColumn-1-130797998-blog-127269682.235%5Ev38%5Epc_relevant_anti_vip&depth_1-utm_source=distribute.pc_relevant_t0.none-task-blog-2%7Edefault%7ECTRLIST%7EPayColumn-1-130797998-blog-127269682.235%5Ev38%5Epc_relevant_anti_vip&utm_relevant_index=1)

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
```

```
npm 和 node 版本
(base)  yuhui@yuhuideMacBook-Pro  ~/PycharmProjects/ngn_code/saibo  npm  -v
9.6.7
(base)  yuhui@yuhuideMacBook-Pro  ~/PycharmProjects/ngn_code/saibo  node -v
v18.17.0

sudo npm install -g node@18.17.0
```

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
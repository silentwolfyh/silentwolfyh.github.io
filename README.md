# 北京赛博恩福科技有限公司

## 依赖

- Linux (比较方便，Windows 没测试过)
- git
- Node.js
- npm
- hexo
- hexo-deployer-git

## 准备工作(查看Study.md，安装 npm安装指定版本 ， 版本都在 package.json 中) 

1. 安装 `npm`

```
sudo apt install npm
sudo ln -s /usr/bin/nodejs /usr/bin/node
```

2. 升级 `node` 版本

```
sudo npm install -g n
sudo n stable
```

3. clone 仓库到本地

```
git clone git@github.com:silentwolfyh/silentwolfyh.github.io.git
cd saibo
```

4. 安装 `hexo` 和 `hexo-deployer-git`

```
sudo npm install hexo --save
sudo npm install hexo-deployer-git --save
```

## 修改 & 部署

1. 清除之前的内容

```
hexo clean
```

2. 将其他机器上的修改内容同步到本地

```
git pull
```

3. 修改对应的文档内容

    - 添加一般 post：在 `source/_posts` 目录下新建文件，填内容即可
        - 需要加 图片 & css & js 等外部资源的时候，在 `source` 目录下创建新目录，然后引用路径写成 `/<dir_name>/<file_name>`
        - 例如，如果需要插入图片 `test.png`，则在 `source` 目录下创建 `image` 目录，然后 `<img src="/image/test.png">`
    - 添加纯 html post：在 `source/_posts` 目录下新建文件，在 html 前面抬头部分添加选项：`layout: false`，之后填 html 内容即可
    - 修改其他内容：直接在其他目录的 `index.md` 上修改，新建文件没有效果。

4. 生成 public 目录（即 push 到 `github.io` 仓库里的内容）

```
hexo generate
```

5. （可选，推荐）在本地查看修改后的网站

```
hexo server
```

6. 确认无误后将网站部署至远程服务器

```
hexo deploy
```

7. （勿忘！！！）将修改内容同步至 GitHub Repo 
```
git add ...
git commit -m "*"
git push origin master
```
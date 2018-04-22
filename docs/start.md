# 开始使用

## 安装依赖

使用「StatusKit」需要 NodeJS 和 Git。你可以查阅 [Hexo 官方文档的介绍](https://hexo.io/docs/)。  
建议在 NodeJS 8+ 以上运行「StatusKit」。

## 安装 StatusKit

安装完 NodeJS 和 Git 以后，执行以下指令即可安装「StatusKit」：

```bash
git clone https://github.com/neoFelhz/statuskit.git
cd statuskit
npm install
```

然后将 `/themes/statuskit/` 目录中找到 `_config.template.yml`，将其重命名为 `_config.yml`。

## 启动 StatusKit

执行以下指令：

```bash
npm run serve
```

然后在浏览器中访问 `localhost:4000` 即可看到 StatusKit 已经启动。  
按下 `Ctrl + C` 即可停止「StatusKit」。

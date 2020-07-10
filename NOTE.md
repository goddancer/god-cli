### 安装依赖

`npm install`

### 启动

`npm run watch`

### 执行 `npm link`

* 在未link `god-clis` command之前，需要先去掉钩子`"postinstall": "god-clis config set"`，否则会一直报错而无法成功安装

此时就可以使用 `god-clis` 命令了。

`god-clis` commands:

- `god-clis init babel-template myNpm`
- `god-clis config get`
- `god-clis config set type orgs`
- `god-clis config set registry babel-template`

- `god-clis config set type users`
- `god-clis config set registry goddancer`

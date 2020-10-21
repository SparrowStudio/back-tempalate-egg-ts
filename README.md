<!--
 * @description: 
 * @author: bubao
 * @date: 2020-10-20 20:20:31
 * @last author: bubao
 * @last edit time: 2020-10-20 20:35:31
-->

# hackernews-async-ts

Sparrow Studio 项目组后端项目开发模板，方便快速创建新项目。

[Hacker News](https://news.ycombinator.com/) showcase using typescript && egg

## QuickStart

使用 vscode 开发，需要安装一下插件

- [eggjs](https://github.com/eggjs/vscode-eggjs): eggjs 开发提示插件。
- [egg-jump-definition](https://marketplace.visualstudio.com/items?itemName=egg-jump-definition.egg-jump-definition): egg 文件跳转。
- [eslint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint): eslint 插件
使用 vscode 开发，需要安装一下插件

- [eggjs](https://github.com/eggjs/vscode-eggjs): eggjs 开发提示插件。
- [egg-jump-definition](https://marketplace.visualstudio.com/items?itemName=egg-jump-definition.egg-jump-definition): egg 文件跳转。
- [eslint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint): eslint 插件

该项目使用 yarn 代替 npm。

获取项目代码

```sh
git clone https://gitee.com/sparrow-studio/back-template-egg.git
```

查看远程地址

```sh
git remote get-url origin
```

删除原来的远程地址

```sh
git remote remove origin
```

添加新的远程地址

```sh
git remote add origin <新项目的地址>
```

推送远程仓库

```sh
git push -u origin master
```

see [egg docs][egg] for more detail.

### Development

```bash
$ yarn
$ yarn run dev
$ open http://localhost:7001/
```

Don't tsc compile at development mode, if you had run `tsc` then you need to `npm run clean` before `npm run dev`.

### Deploy

```bash
$ yarn run tsc
$ yarn start
```

### Yarn Scripts

- Use `yarn run lint` to check code style
- Use `yarn test` to run unit test
- se `yarn run clean` to clean compiled js at development mode once

### Requirement

- Node.js 8.x
- Typescript 2.8+

## 代码推送

因为该模板为了更好的团队协作，使用`husky`和`commitizen`规范了代码的提交，并使用`eslint`检查并修复代码格式。所以在提交时，使用`commitizen`的命令`yarn run cz`代替`git commit`来提交代码。

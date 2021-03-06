# bgm-scripts-dev

用于`bangumi.tv` 的用户脚本

## bgm-eps-editor: 章节列表编辑器

![Screenshot](screenshots/bgm-eps-editor.png)

- 在 `批量编辑...的章节列表` 页面 增加一个表格编辑器, 数据和原本的文本编辑器联动
- 在表格编辑器中粘贴多行文本时, 会覆盖当前和下方的单元格 (类似Excel)
- 表格编辑器和文本编辑器一样可撤销功能

[下载](bgm-eps-editor.user.js)

## 如何编译

本repo代码使用了yarn, TypeScript和Webpack. 相关的编译命令如下:

```text
# (在源代码目录: mono/src 下)

# 安装npm包
$ yarn

# 在 dist/ 下重新生成各脚本
$ ./dist.sh

```

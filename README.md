# felikschu research notes

这是一个可离线打开、也可直接发布到 GitHub Pages 的静态站点。

## 目录

- `index.html`: 首页
- `about/`: 站点说明
- `thesis/`: 毕业论文工作页
- `review/`: 长文综述页
- `slides/`: reveal.js 演示页

## 本地使用

直接用浏览器打开 `index.html` 即可。整个 `site/` 文件夹可以复制到 U 盘带走。

## GitHub Pages 发布

最简单做法：

1. 新建一个 GitHub 仓库
2. 把当前 `site/` 目录内容推到仓库根目录
3. 在仓库设置中启用 GitHub Pages
4. 选择从默认分支根目录发布

## 更新流程

源文件位于 `../websrc/` 和 `../reading_pack_core/`。

```bash
cd /Users/wangxiaomao/Desktop/毕业论文/thesis/websrc
npm run build
```

重新构建后，把新的 `site/` 内容提交并推送即可。

# 张家怡实习周报网页

这个文件夹是一个通过 GitHub Pages 发布的静态周报网页。

## 当前内容

- 第二周：2026.05.22 - 2026.06.04
- 第三周：2026.06.08 - 2026.06.12
- 第四周：2026.06.15 - 2026.06.18
- 第五周：2026.06.22 - 2026.06.26
- 第六周：2026.06.29 - 2026.07.03
- 第七周：2026.07.06 - 2026.07.10
- 第八周：2026.07.13 - 2026.07.17

## 文件结构

```text
index.html        页面内容
style.css         页面样式
WEEK 2/           第二周周报图和项目图
WEEK 3/           第三周周报图和项目图
WEEK 4/           第四周周报图和项目图
WEEK 5/           第五周项目图
WEEK 6/           第六周项目图
WEEK 7/           第七周项目图
WEEK 8/           第八周项目图
WEEK 9/           第九周项目图
scripts/          发布前检查脚本
```

## 本地检查

直接双击 `index.html`，用浏览器打开即可预览。

## 后续新增一周

1. 新建一个新的周文件夹，例如 `WEEK 6`
2. 把本周项目图片放进去
3. 在 `index.html` 里复制一整段 `<section>...</section>`
4. 把标题、时间、工作总结、项目总结和图片路径替换成本周内容

## 发布到 GitHub Pages

当前线上地址：

```text
https://mollusccaneat.github.io/iworkhere/
```

每次更新周报后，在 GitHub 上传：

```text
index.html
README.md
新的 WEEK X 文件夹
```

如果只替换图片且文件名不变，只需要上传对应图片。

上传完成后，进入 GitHub 的 `Actions` 页面，等待 `pages build and deployment` 显示成功。成功后打开线上地址并强制刷新。

Mac 强制刷新：

```text
Command + Shift + R
```

发布前建议先运行：

```bash
bash scripts/prepublish_check.sh
```

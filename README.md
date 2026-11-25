# 个人主页（骨架）

版式对齐 [Junhang Cheng](https://cjhcoder7.github.io/)：暖纸底、右上头像、教育/实习时间线。  
**没有**荣誉墙、**没有**论文列表。GitHub 已写成 [ethus007](https://github.com/ethus007)。

## 你要改的

全部灰色「在此填写」都在 `index.html`：

1. 标题 / 姓名 / 学校
2. 两段介绍
3. 邮箱
4. Education 时间线
5. MiniMax：组、时间、贡献列表
6. SWE / Coding 四张卡（不用就删）

头像：`assets/images/portrait.jpg`

## 本地预览

```bash
cd 个人主页
python3 -m http.server 8080
```

浏览器打开 http://127.0.0.1:8080

## 挂到 GitHub Pages

仓库名做成 `ethus007.github.io`，把本目录内容放进仓库根目录（`index.html` 在根上），Settings → Pages → Deploy from branch `main`。

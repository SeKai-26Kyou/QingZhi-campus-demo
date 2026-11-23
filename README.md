# 青志 Campus 公网演示页

本目录可以直接发布到 GitHub Pages。

## 发布步骤

1. 在 GitHub 创建一个公开仓库，例如 `qingzhi-campus-demo`。
2. 上传本目录中的全部文件，确保仓库根目录存在 `index.html`。
3. 打开仓库的 `Settings`。
4. 在左侧选择 `Pages`。
5. 将 `Build and deployment` 的来源设为 `Deploy from a branch`。
6. 分支选择 `main`，目录选择 `/ (root)`，保存。
7. 等待约 1–3 分钟，GitHub 会生成类似下面的公开链接：

```text
https://你的GitHub用户名.github.io/qingzhi-campus-demo/
```

把这个链接放进提交 PPT、报名表或答辩材料即可。

## 内容

- `index.html`：单文件跨平台离线演示，包含学生、组织和管理员页面；
- `演示说明.txt`：打开方式和演示顺序；
- `.nojekyll`：避免 GitHub Pages 对静态文件进行 Jekyll 处理。

## 说明

GitHub Pages 只托管静态页面，因此公网链接展示的是完整交互演示，不连接真实 Python 服务端。

如果需要真实账号、照片上传、组织审核和管理员核定，需要另行部署 Python 服务端。GitHub Pages 本身不能运行 Python。

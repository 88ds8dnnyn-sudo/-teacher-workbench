# 教师工作台（永久版部署说明）

单文件网页版教师工作台，数据保存在浏览器本地（localStorage），部署一次永久有效。

## 部署到 GitHub Pages（约 3 分钟）

1. 打开 https://github.com 注册并登录（手机浏览器或 GitHub App 均可）
2. 右上角 `+` → New repository
   - Repository name 填：`teacher-workbench`
   - 选 **Public**（免费 Pages 需要公开仓库）
   - 点 Create repository
3. 进入新仓库 → `Add file` → `Upload files`
   - 把本目录下的 **全部文件**（index.html、sw.js、manifest.json、icon-192.png、icon-512.png、apple-touch-icon.png、icon.svg）一起上传
   - Commit changes
4. 仓库页面 → `Settings` → 左侧 `Pages`
   - Branch 选 `main`，文件夹 `/ (root)` → Save
5. 等 1~2 分钟，访问：
   `https://你的用户名.github.io/teacher-workbench/`

## 备注

- 数据存在浏览器本地，不会上传到 GitHub，隐私无忧
- 想换新设备用：旧设备导出备份 → 新设备导入
- 更新代码：仓库里重新上传 index.html 覆盖即可

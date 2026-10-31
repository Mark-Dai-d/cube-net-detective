# 展开图侦探社｜正方体展开图互动课堂

适合小学三年级《观察物体》学习的免费交互式数学教具。

## 功能

- **课本 A/B/C**：先判断能否折成正方体，再验证。
- **35 种六格展开图**：11 种可折成、24 种不可折成；随机选择及自主练习。
- **3D 渐进折叠**：拖动进度条逐步折叠、播放动画、旋转观察和缩放。
- **错误原因**：折叠失败时提示重叠的面。
- **相对面练习**：使用“礼、乐、射、御、书、数”进行配对验证。

无需安装、无需登录，电脑和手机都可以使用。全部交互代码都在 `index.html`，不依赖外部 CDN。

## GitHub Pages 部署说明

1. 登录 GitHub，新建公开仓库：**`cube-net-detective`**，不必初始化 README（避免上传时重名）。
2. 将本文件夹中的 `index.html`、`.nojekyll` 和 `README.md` 上传到仓库的**根目录**。确保首页文件名是 `index.html`。
3. 打开仓库 **Settings → Pages → Build and deployment**：
   - Source：`Deploy from a branch`
   - Branch：`main`
   - Folder：`/(root)`
   - 点击 `Save`。
4. 等 GitHub Pages 发布成功后，在 **Settings → Pages → Visit site** 点击访问，并测试答题及折叠。

如用户名是 `Mark-Dai-d` 且仓库名为 `cube-net-detective`，网站地址通常为：

`https://mark-dai-d.github.io/cube-net-detective/`

**说明：这个地址是根据命名规则推导的，只有成功发布后才可使用；仓库公开也不代表搜索引擎会立即收录。**

## 提醒

这个仓库作为公开教学工具，不要上传学生的个人信息、作业照片、登录凭据或其他私人数据。

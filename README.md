# 万象百应客户触达演示

这是一个单文件静态网站，可直接使用 GitHub Pages 发布。

## 发布步骤

1. 登录 GitHub，点击右上角加号，选择 `New repository`。
2. 仓库名称建议填写 `wanxiang-notification-demo`。
3. 选择 `Public`，点击 `Create repository`。
4. 在新仓库页面点击 `uploading an existing file`，上传本目录里的全部文件。
5. 点击 `Commit changes`。
6. 打开仓库的 `Settings`，进入 `Pages`。
7. 在 `Build and deployment` 中将 `Source` 设为 `Deploy from a branch`。
8. Branch 选择 `main`，目录选择 `/ (root)`，点击 `Save`。
9. 等待约 1 至 3 分钟，刷新 Pages 页面即可看到网站地址。

网站地址通常是：

`https://你的GitHub用户名.github.io/wanxiang-notification-demo/`

## 注意事项

- `index.html` 必须放在仓库根目录，不要再套一层文件夹。
- 页面不需要服务器、数据库或安装依赖。
- 演示不会发送真实微信消息，也不会保存用户输入。
- 如果修改页面，重新上传并覆盖 `index.html`，GitHub Pages 会自动更新。

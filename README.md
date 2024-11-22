# ServerStatus 美化主题使用方法

1. 把`theme-custom`和`static-custom`文件夹放到`/opt/nezha/dashboard`目录下
2. 在管理后台把前端主题设置为`custom`
3. 重启容器即可

## 修改地方

1. 修改面板的背景色和背景图
2. 静态文件切到南方科技大学开源镜像CDNJS
3. 切不了的静态文件放本地
4. 杂七杂八的优化, 具体看[演示站点](https://svr.czl.net)

## 注意

1. `logo.svg`在`static-custom/static/logo.svg`，可以自行更换

## 哪吒主题开发环境

仅支持 `dashboard v0.20.4` 及更新版本。

1. 克隆当前仓库到本地
2. 修改 `data/config.yaml` oauth2 配置（回调连接可以填 `http://localhost` 的）
3. `docker-compose up`
4. 开始开发
5. 主题制作完成之后可以将 `theme-custom`(前台主题)、`static-custom`(前台主题静态文件) 和 `dashboard-custom`(后台主题) 放置到服务器上的 `/opt/nezha/dashboard/` 中（如使用 Docker 安装）

## FAQ

- 如果不能使用 `80` 端口，在 `docker-compose.yaml` 中修改配置。

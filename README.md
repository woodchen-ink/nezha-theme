# ServerStatus 美化主题使用方法

1. 把`theme-custom/template`里的所有文件放到服务器`/opt/nezha/dashboard/theme-custom/template`目录下
2. 在管理后台把前端主题设置为`custom`
3. 重启容器即可

## 修改地方

1. 修改面板的背景色和背景图
2. 静态文件切到cdnjs和unpkg
3. 切不了的静态文件用github文件, 不用本地文件
4. 杂七杂八的优化, 具体看[演示站点](https://svr.czl.net)

## 注意

`logo.svg`在`header.html`里，可以自行更换

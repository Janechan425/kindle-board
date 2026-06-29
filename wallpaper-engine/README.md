# Kindle Board Wallpaper Engine

This folder contains a desktop wallpaper version of Kindle Board for Wallpaper Engine.

## Use Locally

1. Open Wallpaper Engine.
2. Click **Create Wallpaper**.
3. Drag `index.html` from this folder into the editor.
4. Wallpaper Engine will copy the folder into its local project directory.
5. Use the editor snapshot tool to create a preview image.

## Publish

In Wallpaper Engine, open the imported project, then use **Workshop** -> **Share wallpaper on Workshop**.

Suggested metadata:

- Title: `Kindle Board Clock`
- Type: Web
- Genre: Utility
- Description: `A quiet black-and-white desk clock with weather, 7-day forecast, rain hints, city switching, and bilingual decorative text.`

## Notes

- The wallpaper uses the public Open-Meteo forecast API.
- No API key or backend server is required.
- Weather requires internet access.
- The city selector stores the selected city in browser local storage.
- You can also open the page with `?city=Boston`, `?city=Changsha`, or another supported city name.

## 中文说明

这个文件夹是 Kindle Board 的 Wallpaper Engine 桌面壁纸版。

使用方法：

1. 打开 Wallpaper Engine。
2. 点击 **Create Wallpaper**。
3. 把这个文件夹里的 `index.html` 拖进去。
4. Wallpaper Engine 会把文件复制到自己的项目目录。
5. 用 Wallpaper Engine 自带的截图工具生成预览图。

说明：

- 天气使用 Open-Meteo 公共接口。
- 不需要申请 API key。
- 不需要后端服务器。
- 天气需要联网。
- 城市选择会保存在本地。

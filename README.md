# Kindle Board

A quiet, e-ink friendly dashboard designed for Kindle browsers.

Live site: https://janechan425.github.io/kb/

Wallpaper Engine preview: https://janechan425.github.io/kb/wallpaper-engine/

## English

Kindle Board turns an idle Kindle into a simple desk display. It is built as a single static HTML page, with a large readable clock, current weather, a 7-day forecast, rain hints, city switching, and short bilingual decorative text.

### Features

- Large high-contrast clock for e-ink screens
- Current weather from Open-Meteo
- 7-day temperature range forecast
- Rain probability hints
- City selector with multiple preset cities
- Bilingual city note / decorative text
- No build step and no backend server
- Works as a static GitHub Pages site
- Includes a desktop Wallpaper Engine version in `wallpaper-engine/`

### Weather API

This project uses the public Open-Meteo forecast API. For personal/non-commercial use, no API key is required.

### Usage

Open the live URL in a Kindle browser:

```text
https://janechan425.github.io/kb/
```

For local testing, open `index.html` directly in a browser.

### Wallpaper Engine

The `wallpaper-engine/` folder contains a desktop wallpaper version. In Wallpaper Engine, drag `wallpaper-engine/index.html` into **Create Wallpaper** to import it as a web wallpaper.

You can also preview it online:

```text
https://janechan425.github.io/kb/wallpaper-engine/
```

## 中文

Kindle Board 是一个适合 Kindle 浏览器和墨水屏显示的简洁桌面看板。它是一个纯静态 HTML 页面，可以显示大号时钟、当前天气、未来 7 天天气区间、下雨提示、城市切换，以及中英双语的简短文字装饰。

### 功能

- 适合墨水屏的一眼可读大号时钟
- 使用 Open-Meteo 获取当前天气
- 显示未来 7 天高低温区间
- 显示下雨概率提示
- 支持多个预设城市切换
- 中英双语城市短句 / 简短文字装饰
- 不需要构建步骤
- 不需要后端服务器
- 可直接部署在 GitHub Pages

### 天气接口

本项目使用 Open-Meteo 的公开天气预报接口。个人或非商业使用不需要申请 API key。

### 使用方式

在 Kindle 浏览器中打开：

```text
https://janechan425.github.io/kb/
```

本地测试时，也可以直接用浏览器打开 `index.html`。

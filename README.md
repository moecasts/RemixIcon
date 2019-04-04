[![logo](http://cdn.remixicon.com/logo-github.svg)](https://remixicon.com)

[![npm](https://img.shields.io/npm/v/remixicon.svg?labelColor=4A4A4A&color=006AFF&style=flat-square)](https://www.npmjs.com/package/remixicon)
[![downloads](https://img.shields.io/npm/dt/remixicon.svg?labelColor=4A4A4A&color=23AF5F&style=flat-square)](https://www.npmjs.com/package/remixicon)
[![gitter](https://img.shields.io/gitter/room/:user/:repo.svg?labelColor=4A4A4A&color=d73666&style=flat-square)](https://gitter.im/remixicon/community)
[![donate](https://img.shields.io/badge/-Donate-4664DA.svg?style=flat-square)](https://remixicon.com/#donate)

English | [简体中文](./README_CN.md)

Remix Icon is a set of open source neutral style system symbols for designers and developers. Unlike a patchwork icon library, More than 1300 icons are all elaborately crafted so that they are born with the gene of readability, consistency and perfect pixels. Each icon was designed in "Outlined" and "Filled" styles based on a 24x24 grid. Of course, all the icons are free to use for both personal and commercial.

[![icon demo](http://cdn.remixicon.com/preview.svg)](https://remixicon.com)
View the full set of Remix Icons at [remixicon.com](https://remixicon.com).

## Usage

### Basic Usage

Just click the icons you want from [remixicon.com](https://remixicon.com), and the icons will be downloaded directly in SVG format.

> We recommend that designers download icons from our website when needed instead of managing all of them in a local folder. The website's search engine allows you to quickly locate the icon you are looking for and the icons in the website are continuously updating.

Using SVG on the web is as simple as JPEG or PNG. Such as:

```html
<img height="32" width="32" src="img/admin-fill.svg" />
```

### Webfont Usage

#### Installation

> **Note:** If you'd like to use Remix Icon with a CDN, you can skip this installation step.

```
npm install remixicon --save
```

```
import 'remixicon/fonts/remixicon.css'
```

> import CSS to your main.js

#### CDN

Or copy the following code and add it to the &lt;head> tag of your html document.

```html
<link href="http://cdn.remixicon.com/releases/v1.1.1/remixicon.css" rel="stylesheet">
```

#### Use

Add icon with class name, class name rule: remixicon-{name}-{style}

```html
<i class="remixicon-admin-line"></i>
<i class="remixicon-admin-fill"></i>
```

> **Note:** You can go to [remixicon.com](https://remixicon.com) to check the name of the icons. `-line` means the outlined style icon, and `-fill` means the filled style icon.

### SVG Sprite Usage

Download [`remixicon.symbol.svg`](http://remixicon.com/fonts/remixicon.symbol.svg) file into your project directory，use icons with the `<use>` element, such as:

```css
.remix {
  width: 24px;
  height: 24px;
  fill: #333;
}
```

```html
<svg class='remix'>
  <use xlink:href="path/remixicon.symbol.svg#remixicon-admin-fill"></use>
</svg>
```

> **Note:** `remixicon-admin-fill` after the `#` in the above example can be replaced with any valid icon name of Remix Icon. You can go to [remixicon.com](https://remixicon.com) to check the name of the icons. `-line` means the outlined style icon, and `-fill` means the filled style icon.

## Contributing

> **Note:** In order to ensure the quality of each icon, we currently do not accept third-party drawn icons. If you want to contribute an icon to Remix Icon, you can create an issue with a screenshot or add a link to your SVG.

### Icon Request

If there is no suitable icon for your usage scenario, you can create an [issue](https://github.com/Remix-Design/remixicon/issues) with a title of Icon request: <Icon name> and fill the issue template.

### Icon Search Keywords

We use [`tags.json`](https://github.com/Remix-Design/remixicon/blob/master/tags.json) file to manage the search keywords of our [website](https://remixicon.com). But at the moment, we don't have a good automation method to complete the keywords for each icon. So we hope you can help us to improve the `tags.json` file by creating [issues](https://github.com/Remix-Design/remixicon/issues) or pulling requests to make the seach engine better. If you are not famlilar with github, you can also email us directly `jimmy@remixdesign.cn`.

## License

Remix Icon is licensed under the [Apache License Version 2.0](https://github.com/Remix-Design/remixicon/blob/master/License). Feel free to use and re-share these icons in you products. We would be very grateful if you mention "Remix Icon" in your product introduction, but it's not required. The only thing we ask is that you can't re-sell these icons.

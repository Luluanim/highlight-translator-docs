import { LatestVersion } from '../src/components/LatestVersion'

# 安装划词翻译

## 在线安装 {#online}

**划词翻译最新版本为 <LatestVersion />**。如果以下各商店显示的版本不是最新版本，则说明最新版本仍在此商店的审核流程当中。

### Google Chrome 浏览器 {#chrome}

![Chrome 扩展商店版本](https://img.shields.io/chrome-web-store/v/ikhdkkncnoglghljlkmcimlnlhkeamad.svg?style=flat-square&label=版本)
![Chrome 扩展商店用户数](https://img.shields.io/chrome-web-store/d/ikhdkkncnoglghljlkmcimlnlhkeamad.svg?style=flat-square&label=用户数)
![Chrome 扩展商店评分](https://img.shields.io/chrome-web-store/rating/ikhdkkncnoglghljlkmcimlnlhkeamad?style=flat-square&label=评分)

请前往 [Chrome 扩展商店](https://chrome.google.com/webstore/detail/ikhdkkncnoglghljlkmcimlnlhkeamad)在线安装。新版本提交后大概 2 个工作日完成审核。

### Microsoft Edge 浏览器 {#edge}

![Edge 扩展商店版本](https://img.shields.io/static/v1?label=版本&message=v8.1.2&color=informational&style=flat-square)
![Edge 扩展商店评分](https://img.shields.io/static/v1?label=评分&message=4.7/5&color=success&style=flat-square)

请前往 [Edge 扩展商店](https://microsoftedge.microsoft.com/addons/detail/oikmahiipjniocckomdccmplodldodja)在线安装。新版本提交后大概 5 个工作日完成审核。

### Mozilla Firefox 浏览器 {#firefox}

![Firefox 扩展商店版本](https://img.shields.io/amo/v/hcfy?style=flat-square&label=版本)
![Firefox 扩展商店用户数](https://img.shields.io/amo/users/hcfy?style=flat-square&label=用户数)
![Firefox 扩展商店评分](https://img.shields.io/amo/rating/hcfy?style=flat-square&label=评分)
![Firefox 扩展商店周下载量](https://img.shields.io/amo/dw/hcfy?style=flat-square&label=周下载量)

请前往 [Firefox 扩展商店](https://addons.mozilla.org/zh-CN/firefox/addon/hcfy/)在线安装。新版本提交后大概 10 分钟完成审核。

## 下载离线安装包手动安装 {#offline}

在某些情况下，你可能更希望下载离线安装包安装划词翻译，比如：

- 你打不开 [Chrome 扩展商店](https://chrome.google.com/webstore/detail/ikhdkkncnoglghljlkmcimlnlhkeamad)。
- 你想要使用最新版本，但最新版本仍在 Chrome / Edge 扩展商店的审核流程当中，没有上架。
- 最新版本有比较严重的 bug，你希望临时使用旧版本的划词翻译。

:::note 注意
离线安装包仅支持 Chrome 和 Edge 浏览器，不支持 Firefox。
:::

### 一、在网盘里下载离线安装包 {#download}

链接: [https://pan.baidu.com/s/17zF7AksigMwLh8McRBVG0w](https://pan.baidu.com/s/17zF7AksigMwLh8McRBVG0w)
提取码: `hmat`

下载前可能会提示“此类型的文件可能会损害您的计算机，您仍然要保留吗？”，选择“保留”。

下载完成后可能会提示“无法从此网站安装扩展程序”，忽略它即可，此时离线安装包应该已经在你的下载文件夹里了。

### 二、手动安装 {#install}

1. 有了离线安装包之后，在 Chrome / Edge 浏览器里打开 `chrome://extensions/`。
2. 打开【开发者模式】。这个开关在 Chrome 的右上角、Edge 的左下角。
3. 将离线安装包拖放到这个页面。

大功告成！

### 注意 {#note}

- 使用这种方式安装的划词翻译在 Chrome 中也会自动更新。如果你不想自动更新，可以按照以下步骤操作：
  1. 将离线安装包的 `.crx` 后缀改为 `.zip` 并解压。
  2. 进入扩展程序页（`chrome://extensions/`）并打开【开发者模式】，然后点击“加载已解压的扩展程序”，选择刚才解压出来的文件夹。注意：这个文件夹里应该有一个 manifest.json 文件，如果没有，说明你选错文件夹了。
- 虽然 Edge 也可以安装这个离线安装包，但会显示为“来自其他源 Chrome Web Store”，我不确定它未来会不会自动更新，所以最好在 Edge 扩展商店上架最新版本后，使用 Edge 扩展商店的版本。

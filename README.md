# ts-gmscript-boilerplate (gm脚本的模板)
[![Build Status](https://travis-ci.org/axetroy/ts-gmscript-boilerplate.svg?branch=master)](https://travis-ci.org/axetroy/ts-gmscript-boilerplate)
[![npm version](https://badge.fury.io/js/ts-gmscript-boilerplate.svg)](https://badge.fury.io/js/ts-gmscript-boilerplate)
![Node](https://img.shields.io/badge/node-%3E=6.0-blue.svg?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-green.svg)

If this can help you let me know, your support is my motivation to update (如果这能够帮助到你, 不妨点个start, 你的支持就是我更新的动力)

## Issues (反馈地址)

- [Issues can be submitted here](https://github.com/axetroy/ts-gmscript-boilerplate/issues)

## How to use (使用)

1. Install one of the extensions below (安装扩展)

2. Make sure your browser has the following extensions installed before installation (安装前确保你的浏览器已安装如下扩展)

Browser (浏览器) | Support extension (支持扩展)
------------ | -------------
Chrome | **Tampermonkey** or **Violent monkey**
Firefox | **Greasemonkey** or **Tampermonkey**
Safari | **Tampermonkey**
Microsoft Edge | **Tampermonkey**
Opera | **Tampermonkey**
Maxthon | **Violentmonkey**
Dolphin | **Tampermonkey**
UC | **Tampermonkey**
Qupzilla | No additional software required (不需要额外软件)

3. Installation (安装脚本)

Create a script in the above extension that you have installed

example:
```javascript
// ==UserScript==
// @name         New Userscript
// @version      0.1
// @description  try to take over the world!
// @author       You
// @match        http://*/*
// @grant        none
// ==/UserScript==

(function() {
    'use strict';

    // Your code here...
})();
```

*or*

Install one of the pre-made scripts below, note: it is best to review what you are **install**ing

[点击从Github安装](https://github.com/axetroy/ts-gmscript-boilerplate/raw/gh-pages/ts-gmscript-boilerplate.min.user.js)

[点击从GreasyFork安装](https://greasyfork.org/scripts/11915-ts-gmscript-boilerplate-typescript/code/ts-gmscript-boilerplate%20(typescript).user.js)

## Getting started in development (贡献代码)

```bash
git clone https://github.com/axetroy/ts-gmscript-boilerplate.git

cd ./ts-gmscript-boilerplate

npm install
npm run start
```

Typescript will compile on code change and generate Javascript in the `dist/` directory.  Copy and paste the generated file `dist/index.user.js` to your browser extension.

## Automatically reloading the generated script for quick development

[Tampermonkey (Chrome)](https://stackoverflow.com/a/55568568)
1.  in Chrome, enable "Allow access to file URLs"
2.  Add this to the `webpack.config.js` -> `// @require file:///path/to/userscript.user.js`

## Open source license (开源许可)

The [MIT License](https://github.com/axetroy/ts-gmscript-boilerplate/blob/master/LICENSE)

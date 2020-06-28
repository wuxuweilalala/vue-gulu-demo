# vue 造轮子之 ui 组件库
[![Build Status](https://www.travis-ci.org/wuxuweilalala/vue-gulu-demo.svg?branch=master)](https://www.travis-ci.org/wuxuweilalala/vue-gulu-demo)

## 介绍
这是偶在学习 Vue 过程中做的一个 UI 框架。

## 开始使用
1. 添加 CSS 样式
    使用本框架钱前，请在 CSS 中开启 border-box
    ```css
       *,*::before,*::after {box-sizing: border-box;}
    ```
   IE 8 及以上浏览器都支持此样式。
   你还需要设置默认颜色等变量。
   ```css
      html {
           --button-height: 32px;
           --font-size: 14px;
           --button-bg: white;
           --button-active-bg: #eee;
           --button-radius: 4px;
           --color: #333;
           --border-color: #999;
           --border-color-hover: #666;
       }
    ```
2. 安装 gulu
    ```
        npm i --save wxw-vue-ui-test
   ```
3. 引入 gulu
     ```javascript
    import {Button,ButtonGroup,Icon} from 'wxw-vue-ui-test';
    import 'wxw-vue-ui-test/dist/index.css'
   
    export default {
     name:'app',
      components:{
         'g-button':Button,
         'g-Icon':Icon,
         'g-button-group':ButtonGroup
       }
    }
    ```
## 文档

## 提问

## 变更记录

## 联系方式

## 安装
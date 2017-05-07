# weex-trap
占坑...weex开发踩过的坑

坑1: 在实现多行省略功能的时候,文档的教程是`<text lines="2"></text>`,但是这样会导致H5端的实现出现不一致,正确的做法是继续写上相关的CSS属性`display: -webkit-box;overflow: hidden;word-break: break-all;-webkit-box-orient:vertical;-webkit-line-clamp:2;`这一点在文档中并未提及

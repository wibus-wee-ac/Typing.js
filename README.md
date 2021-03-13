# Typing.js
Using simple JavaScript to achieve typewriter effects

## 引入js

下载Typing.js到你的服务器，使用HTML引入

```html
<!-- 生产环境（压缩） -->
<script src="Typing.min.js"></script>
<!-- 开发环境（无压缩）-->
<script src="Typing.js"></script>
```

## 调用

```javascript
  let source = '修改这里的文字'//需要做到打字机效果的文字
  let output = document.getElementById('output') //打字机效果挂载位置
  let typing = new Typing({
    source,
    output
  })
  typing.start()
```
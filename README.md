### use strict, es6, unique key

es5 严格模式下不允许对象字面量的 key 不唯一，但 es6 允许。
可能导致你的代码在 es5 的浏览器里报错。

### SVG 1.1 `<use>`元素

`event.target` 不是元素本身，而是一个 `interface` ，在 SVG 2 中为元素。

### 不要依赖 `location` 的特殊行为

对 `location.port` 等属性赋值会导致跳转，但在 firefox 上无效。

### safari, iframe, localStorage

safari 的 iframe 中， `cookies` 和 `localStorage` 是独立的。

### flexible.js

flexible.js 库在 `DOMContentLoaded` 后才设置 body 字号。


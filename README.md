# refLine
拖拽时提供 参考线 和 磁性吸附 元素 

[https://think2011.net/ref-line/](https://think2011.net/ref-line/)

z-Dragify

```js
    new Dragify(document.querySelector('#box'),{
                target: document.querySelector("#box-title")
            })
            .on('start', function () {
                console.log('s')
            })
            .on('move', function () {
                console.log('m')
            })
            .on('end', function () {
                console.log('e')
            })
    new Dragify("#box",{
        target: "#box-title"
    })
```
# css_vertical_center

### CSS垂直居中
1. 容器高度已知，而且元素是单行文本时，可以用行高（line-height）实现垂直居中 http://localhost:8080/LineHeight
2. 使用flex布局的 `align-items: center;` http://localhost:8080/Flex
3. 元素的包含块是相对定位，元素是绝对定位 `top: 50%; transform: translateY(-50%);` http://localhost:8080/PositionAbsolute
4. 当容器的上下内边距（padding）相同的时候，容器中的内容就变成了垂直居中。使用这种方法后，容器不能有固定高度，它的高度需要有内容撑起 `padding: 50px 0;`
5. 模拟表格的效果，在表格的单元格（td）中，用 vertical-align 属性就能让内容垂直居中
```
<div style="display: talbe;">
    <p style="display: table-cell; vertical-align: middle;">垂直居中</p>
</div>
```

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

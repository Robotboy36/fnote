## BFC 块级格式化上下文

#### 什么是块级格式化上下文
```
将元素按照块级元素的渲染方式渲染
```

#### 哪些元素会生成BFC
* 根元素
* float属性不为none
* position 为 absolute或fixed
* display 为 inline-block, block, table-cell, table-caption, flex, inline-flex
* overflow 不为 visible
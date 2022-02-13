### uni-skeleton
uni-app 骨架屏组件

### 基本使用

``` html
<template>
    <uni-skeleton animated :loading="loading"></uni-skeleton>
</template>
```
``` js
<script>
export default {
  data() {
    return {
        loading: true
    }
  },
};
</script>
```


### 配置选项
| 参数 | 说明 | 类型 | 可选值 | 默认值 |
|-|-|-|-|-|
| animated | 是否使用动画 | Boolean | true / false | false |
| loading | 是否显示加载结束后的 DOM 结构 | Boolean | true / false | false |
| rows | 骨架屏段落数量 | Number | - | 3 |
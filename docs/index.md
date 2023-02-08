# Bar 柱形图 <Badge type="warning" text="alpha" />

> 柱形图 3D 图表

## 安装
::: code-group
```bash [npm]
npm i element-plus
```

```bash [yarn]
yarn add element-plus
```

```bash [pnpm]
pnpm add element-plus
```
:::

## 基础用法

<ClientOnly>
  <ElButton type="primary">{{text}}</ElButton>
</ClientOnly>

::: details 查看代码

```vue
<ClientOnly>
  <ElButton type="primary">{{text}}</ElButton>
</ClientOnly>
<script>
import 'element-plus/dist/index.css'
import { ElButton } from 'element-plus'
export default {
  components: {ElButton},
  data() {
    return {
      text: '按钮'
    }
  }
}
</script>
```

:::

## Button 属性

| 属性名               |      说明                 | 类型              |  默认值        |
| ------------------- | ----------------------   | ---------------   | -------------  |
| type               |   类型   | String          |            |


## 贡献者

<script>
import 'element-plus/dist/index.css'
import { ElButton } from 'element-plus'
export default {
  components: {ElButton},
  data() {
    return {
      text: '按钮'
    }
  }
}
</script>
:: BASE_DOC ::


## API
### Button Props

名称 | 类型 | 默认值 | 说明 | 必传
-- | -- | -- | -- | --
className | String | - | 类名 | N
style | Object | - | 样式，TS 类型：`React.CSSProperties` | N
block | Boolean | false | 是否为块级元素 | N
children | TNode | - | 按钮内容，同 content。TS 类型：`string | TNode`。[通用类型定义](https://github.com/TDesignOteam/tdesign-mobile-react/blob/develop/src/common.ts) | N
content | TNode | - | 按钮内容。TS 类型：`string | TNode`。[通用类型定义](https://github.com/TDesignOteam/tdesign-mobile-react/blob/develop/src/common.ts) | N
disabled | Boolean | false | 是否禁用按钮 | N
ghost | Boolean | false | 是否为幽灵按钮（镂空按钮） | N
icon | TElement | - | 按钮内部图标，可完全自定义。TS 类型：`TNode`。[通用类型定义](https://github.com/TDesignOteam/tdesign-mobile-react/blob/develop/src/common.ts) | N
loading | Boolean | false | 是否显示为加载状态 | N
shape | String | square | 按钮形状，有二种：方形、圆角方形。可选项：square/round | N
size | String | medium | 组件尺寸。可选项：small/medium/large。TS 类型：`SizeEnum`。[通用类型定义](https://github.com/TDesignOteam/tdesign-mobile-react/blob/develop/src/common.ts) | N
theme | String | default | 组件风格，依次为品牌色、危险色。可选项：default/primary/danger | N
type | String | button | 按钮类型。可选项：submit/reset/button | N
variant | String | base | 按钮形式，基础、线框、文字。可选项：base/outline/text | N
onClick | Function |  | TS 类型：`(e: MouseEvent) => void`<br/>点击时触发 | N

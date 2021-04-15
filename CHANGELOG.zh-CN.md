---
order: 6
title: 更新日志
toc: false
timeline: true
---

`antd` 严格遵循 [Semantic Versioning 2.0.0](http://semver.org/lang/zh-CN/) 语义化版本规范。

#### 发布周期

- 修订版本号：每周末会进行日常 bugfix 更新。（如果有紧急的 bugfix，则任何时候都可发布）
- 次版本号：每月发布一个带有新特性的向下兼容的版本。
- 主版本号：含有破坏性更新和新特性，不在发布周期内。

---

## 4.16.13

`2021-08-23`

- 🐞 修复 Form `label` 中使用 `<Typography.Text ellipsis />` 时省略不生效的问题。[#31838](https://github.com/ant-design/ant-design/pull/31838)
- 🐞 修复 Collapse 在 HMR 时报错的问题。[#31827](https://github.com/ant-design/ant-design/pull/31827) [@v4](https://github.com/v4)
- 🐞 修复 Modal 和 Input 组件中的循环依赖。[#31817](https://github.com/ant-design/ant-design/pull/31817) [@zhyupe](https://github.com/zhyupe)
- RTL
  - 🐞 修复 Modal.confirm 自定义内容全局 rtl 配置缺失的问题。[#31828](https://github.com/ant-design/ant-design/pull/31828)

## 4.16.12

`2021-08-16`

- Form
  - 🐞 修复 Form 帮助图标和可选文案上有 `title` 提示的问题。[#31785](https://github.com/ant-design/ant-design/pull/31785)
  - 💄 修复 Form 内 `<Input bordered={false} />` 错误样式有异常外框样式的问题。[#31754](https://github.com/ant-design/ant-design/pull/31754)
- Button
  - 💄 修复 Button `ghost` 和 `danger` 一起使用时的样式问题。[#31780](https://github.com/ant-design/ant-design/pull/31780)
  - 🐞 修复 Button 图标在 Chrome 下没有居中对齐的问题。[#31755](https://github.com/ant-design/ant-design/pull/31755)
- Input
  - 🐞 修复 Input 清除图标和 `suffix` 之间边距丢失的问题。[#31745](https://github.com/ant-design/ant-design/pull/31745)
  - 💄 修复 Input 禁用状态下依然有 focus 样式的问题。[#31738](https://github.com/ant-design/ant-design/pull/31738)
- 🐞 修复 Transfer `showSelectAll={false}` 没有隐藏选择下拉框的问题。[#31746](https://github.com/ant-design/ant-design/pull/31746)
- 💄 修复 Checkbox.Group 中打勾样式没有居中对齐的问题。[#31726](https://github.com/ant-design/ant-design/pull/31726)

## 4.16.11

`2021-08-08`

- 🐞 修复 ConfigProvider 切换国际化时子组件 rerender 的问题。[#31630](https://github.com/ant-design/ant-design/pull/31630) [@Map1en](https://github.com/Map1en)
- 💄 简化 ghost 按钮的样式代码，去掉 `!important` 样式规则。[#31659](https://github.com/ant-design/ant-design/pull/31659)
- 💄 优化 RangePicker 的范围样式的 transition 效果。[#31645](https://github.com/ant-design/ant-design/pull/31645)
- 🤖 修复 Dropdown `destroyPopupOnHide` TypeScript 定义丢失的问题。[#31700](https://github.com/ant-design/ant-design/pull/31700) [@linxianxi](https://github.com/linxianxi)
- 🤖 移除多余的 Omit 类型定义。[#31661](https://github.com/ant-design/ant-design/pull/31661) [@Dreamerryao](https://github.com/Dreamerryao)

## 4.16.10

`2021-08-02`

- 🐞 修复 Badge 设置自定义 `color` 不显示数字的问题。[#31617](https://github.com/ant-design/ant-design/pull/31617) [@eokoneyo](https://github.com/eokoneyo)
- 🐞 修复 Progress 环形进度条 `success.strokeColor` 不生效的问题。[#31589](https://github.com/ant-design/ant-design/pull/31589)
- 🐞 修复 Select 组件没有忽略 `getRawInputElement` 属性导致的类型报错问题。[#31566](https://github.com/ant-design/ant-design/pull/31566) [@aoilti](https://github.com/aoilti)
- 🐞 修复 Pagination 的 `totalBoundaryShowSizeChanger` 属性类型错误。[#31549](https://github.com/ant-design/ant-design/pull/31549) [@Monty-Ma](https://github.com/Monty-Ma)
- 🐞 修复 Skeleton.Avatar `className` 重复应用的问题。 [#31536](https://github.com/ant-design/ant-design/pull/31536) [@Greatshock](https://github.com/Greatshock)
- 🌐 国际化
  - 🇹🇷 为 Image 组件中 `预览` 文案增加土耳其语翻译。[#31593](https://github.com/ant-design/ant-design/pull/31593) [@mburakkalkan](https://github.com/mburakkalkan)
  - 🇰🇷 修复韩语中的错别字。[#31575](https://github.com/ant-design/ant-design/pull/31575) [@chatoo2412](https://github.com/chatoo2412)

## 4.16.9

`2021-07-27`

- 🐞 修复 Typography `ellipsis` 在屏幕放大缩小时计算错误的问题。[#31449](https://github.com/ant-design/ant-design/pull/31449)
- 💄 修复 Input 使用 `prefixCls` class 错误的问题。[#31479](https://github.com/ant-design/ant-design/pull/31479) [@spawnia](https://github.com/spawnia)
- 💄 修复 Input.Password 校验错误时的聚焦样式。[#31456](https://github.com/ant-design/ant-design/pull/31456)
- 💄 修复 Badge 切换显隐时的颜色问题。[#31458](https://github.com/ant-design/ant-design/pull/31458)
- 💄 修复 Tabs `tabBarGutter` 的一些样式异常行为。[#31469](https://github.com/ant-design/ant-design/pull/31469)
- 🌐 国际化
  - 🇷🇺 更新 ru_RU 中 Image 字段。[#31448](https://github.com/ant-design/ant-design/pull/31448) [@KirillSBarsukov](https://github.com/KirillSBarsukov)
  - 🇩🇰 补充 da_DK 中 Table 文案。[#31486](https://github.com/ant-design/ant-design/pull/31486) [@bischmlb](https://github.com/bischmlb)

## 4.16.8

`2021-07-19`

- 🐞 修复 TextArea `style` 在配置 `allowClear` 时失效的问题。[#31391](https://github.com/ant-design/ant-design/pull/31391)
- 🐞 修复 BackTop 隐出后仍然可以交互的问题。[#31357](https://github.com/ant-design/ant-design/pull/31357)
- 💄 修复 Cascader 在 Input `addonBefore` 中的样式问题。[#31350](https://github.com/ant-design/ant-design/pull/31350)
- 💄 修复 DatePicker 自定义 `dateRender` 时禁用日期样式错误的问题。[#31349](https://github.com/ant-design/ant-design/pull/31349)
- 💄 修复 Select 组件 disabled 时背景颜色错误的问题。[#31430](https://github.com/ant-design/ant-design/pull/31430) [@DerrickTel](https://github.com/DerrickTel)
- 💄 修复 Radio.Group 和 Button 不对齐的问题。[#31421](https://github.com/ant-design/ant-design/pull/31421) [@gtb104](https://github.com/gtb104)
- 💄 修复 Input 清除按钮某些情况下颜色不对的问题。[#31378](https://github.com/ant-design/ant-design/pull/31378)
- Table
  - 💄 修复 Table `sticky` 列头一个背景色透明的问题。[#31373](https://github.com/ant-design/ant-design/pull/31373)
  - 💄 修复表格总结栏第一个单元格上边框消失的问题。[#31363](https://github.com/ant-design/ant-design/pull/31363)
- 🌐 国际化
  - 🇷🇺 俄语本地化增加 Table.SELECTION_NONE 文案。[#31361](https://github.com/ant-design/ant-design/pull/31361) [@wwyx778](https://github.com/wwyx778)
  - 🇭🇰 补充 zh_HK 中 Transfer 组件缺失的部分字段。[#31404](https://github.com/ant-design/ant-design/pull/31404) [@kanweiwei](https://github.com/kanweiwei)
  - 🇪🇸 补充 es_ES 中 Image 组件缺失的字段。[#31330](https://github.com/ant-design/ant-design/pull/31330) [@Andu15](https://github.com/Andu15)

## 4.16.7

`2021-07-12`

- 🐞 修复 DatePicker 在 Table 内使用时日期未居中的问题。[#31306](https://github.com/ant-design/ant-design/pull/31306) [@Map1en](https://github.com/Map1en)
- 🐞 修复 Descriptions 在 Table 内边框丢失的问题。[#31307](https://github.com/ant-design/ant-design/pull/31307)
- 🐞 修复 InputNumber 边框和交互范围不匹配的问题。[#31300](https://github.com/ant-design/ant-design/pull/31300) [@diyews](https://github.com/diyews)
- Table
  - 🐞 修复 Table 当窗口过小时上边框显示不完全的问题。[#31298](https://github.com/ant-design/ant-design/pull/31298) [@Map1en](https://github.com/Map1en)
  - 🐞 修复 Table `rowSelection` 的 `selectedRows` 属性在初始化时不同步问题。[#31224](https://github.com/ant-design/ant-design/pull/31224) [@kerm1it](https://github.com/kerm1it)
  - 🐞 修复 Table 组合列上的筛选状态 `filteredValue` 不生效的问题。[#30815](https://github.com/ant-design/ant-design/pull/30815) [@moraispgsi](https://github.com/moraispgsi)
- Form
  - 🐞 修复 Form 错误校验状态下 Input 的聚焦外框色。[#31240](https://github.com/ant-design/ant-design/pull/31240)
  - 🆕 Form 增加 `name` 作为验证消息 `label` 的默认值。[#30179](https://github.com/ant-design/ant-design/pull/30179) [@jameslahm](https://github.com/jameslahm)
- 💄 修复 Rate 在 Safari 下聚焦外框的样式。[#31241](https://github.com/ant-design/ant-design/pull/31241)
- 💄 微调 Select 箭头垂直位置。[#31234](https://github.com/ant-design/ant-design/pull/31234)
- 🐞 清除 Input 内容时不再触发 `onBlur`，修复可编辑表格 Input 无法正确清除内容的问题。[#31202](https://github.com/ant-design/ant-design/pull/31202)
- 🐞 修复 Tooltip `arrowPointAtCenter` 有一像素偏移的问题。[#31201](https://github.com/ant-design/ant-design/pull/31201)
- 💄 修复 Menu 项 hover 文字色彩的渐变效果。[#31189](https://github.com/ant-design/ant-design/pull/31189)
- 🐞 修复 Dropdown.Button 不支持 `overlayClassName` 和 `overlayStyle` 的问题。[#31187](https://github.com/ant-design/ant-design/pull/31187)
- 💄 使 Pagination 选中禁用状态的按钮样式与单选框相应按钮的样式一致。[#31185](https://github.com/ant-design/ant-design/pull/31185) [@Map1en](https://github.com/Map1en)
- 🐞 修复在 Windows 环境下打包组件样式导出文件时路径错误。[#31277](https://github.com/ant-design/ant-design/pull/31277) [@aoxiang78](https://github.com/aoxiang78)
- 🌐 en_GB 语言文件中增添 `selectNone`。[#31264](https://github.com/ant-design/ant-design/pull/31264) [@Map1en](https://github.com/Map1en)
- TypeScript
  - 🤖 调整 Transfer `listStyle` 属性为可选属性。[#31322](https://github.com/ant-design/ant-design/pull/31322) [@geekrainy](https://github.com/geekrainy)

## 4.16.6

`2021-06-29`

- 🐞 修复 Tree `loadData` 失败后节点 `loading` 效果没有重置的问题。[#31170](https://github.com/ant-design/ant-design/pull/31170)
- ⚡️ 优化 Progress 动画性能，显著降低 CPU 使用率。[#31128](https://github.com/ant-design/ant-design/pull/31128) [@stygian-desolator](https://github.com/stygian-desolator)
- 🐞 修复 Popover 箭头颜色和内容不匹配的问题。[#31127](https://github.com/ant-design/ant-design/pull/31127) [@A113n1003](https://github.com/A113n1003)

## 4.16.5

`2021-06-23`

- 🐞 修复 Menu 直接导入 `@ant-design/icons` 的方式以减少不使用 Tree Shaking 的打包尺寸。[#31011](https://github.com/ant-design/ant-design/pull/31011)
- 🐞 修复 Menu 过长省略弹层没有跟随 `theme` 配置的问题。[#31043](https://github.com/ant-design/ant-design/pull/31043)
- 🐞 修复 Table 某处样式代码没有使用 `@{table-prefix-cls}` less 变量可能导致样式覆盖失效的问题。[#30983](https://github.com/ant-design/ant-design/pull/30983)
- 🐞 修复 Input.Password 校验失败时的 hover 边框色。[#30999](https://github.com/ant-design/ant-design/pull/30999)
- 🐞 修复 Space 设置 `wrap` 时额外设置了负 `margin` 的样式问题。[#31000](https://github.com/ant-design/ant-design/pull/31000)
- 🐞 修复 Typography 配置 `italic` 时会警告不是一个合法 DOM 属性的问题。[#31004](https://github.com/ant-design/ant-design/pull/31004)
- 🐞 修复 Badge 没有通过 html 标签嵌套校验的问题。[#31042](https://github.com/ant-design/ant-design/pull/31042) [@conwnet](https://github.com/conwnet)

## 4.16.4

`2021-06-23`

- npm 发布出问题了，这个版本无法使用。

## 4.16.3

`2021-06-14`

- 🐞 修复 Tooltip 的 getPopupContainer 属性为 undefined 时，Tooltip 只能挂载到 body 上的问题。[#30963](https://github.com/ant-design/ant-design/pull/30963) [@ymrdf](https://github.com/ymrdf)
- 🐞 修复 Button 加载中图标间距丢失的问题。[#30962](https://github.com/ant-design/ant-design/pull/30962)
- Table
  - 🐞 Table 增加内外部 `filteredKeys` 状态不一致的提示。[#30882](https://github.com/ant-design/ant-design/pull/30882) [@wendellhu95](https://github.com/wendellhu95)
  - 🐞 修复 Table 固定列上有排序按钮时背景透明的问题。[#30972](https://github.com/ant-design/ant-design/pull/30972)
- 💄 调整 Dropdown 条目宽度，使其展示时尽可能多的利用空间。[#30911](https://github.com/ant-design/ant-design/pull/30911)
- 💄 修复 Menu 暗色模式下，部分样式被亮色模式污染的问题。[#30907](https://github.com/ant-design/ant-design/pull/30907)
- 🐞 修复 Dropdown/DatePicker/Select/Cascader 组件自适应位置后动画方向错误的问题。[#30892](https://github.com/ant-design/ant-design/pull/30892)
- 🌐 国际化
  - 🇵🇱 调整 Table 波兰语国际化文案。[#30899](https://github.com/ant-design/ant-design/pull/30899) [@MichalJani](https://github.com/MichalJani)

## 4.16.2

`2021-06-07`

- 🐞 修复 Menu `horizontal` 模式下的自动省略布局会被 `float` 破坏的问题。[#30879](https://github.com/ant-design/ant-design/pull/30879)
- Typography
  - 🐞 修复 Typography.Paragraph 的 `copyable` 会将 React.Fragment 当做数组处理的问题。[#30869](https://github.com/ant-design/ant-design/pull/30869) [@crazyair](https://github.com/crazyair)
  - 🐞 修复 Typography 自定义 `font-size` 时省略宽度不正确的问题。[#30840](https://github.com/ant-design/ant-design/pull/30840)
- 🐞 修复 Progress `type="circle"` 有时会报错 `Rendered more hooks than during the previous render` 的问题。[#30855](https://github.com/ant-design/ant-design/pull/30855)
- 💄 优化 Tooltip 内容的宽度。[#30822](https://github.com/ant-design/ant-design/pull/30822) [@donysukardi](https://github.com/donysukardi)
- Table
  - 🛠 优化 Table 中全选复选框的状态显示逻辑。[#30811](https://github.com/ant-design/ant-design/pull/30811) [@kerm1it](https://github.com/kerm1it)
  - 🐞 修复 Table 列筛选和排序时 `column.title` 设置 `onClick` 和 `ellipsis` 无效的问题。[#30799](https://github.com/ant-design/ant-design/pull/30799)
- 💄 修复 Dropdown 条目包含超链接时的颜色样式，另外现在点击图标也能触发超链接效果。[#30802](https://github.com/ant-design/ant-design/pull/30802)
- 💄 移除重复的通配符 reset 样式以优化样式渲染性能。[#30660](https://github.com/ant-design/ant-design/pull/30660) [@renzhao1113](https://github.com/renzhao1113)
- TypeScript
  - 🤖 调整 Form, Input, Locale, PageHeader 组件类型定义使其更精确。[#30776](https://github.com/ant-design/ant-design/pull/30776) [@qqabcv520](https://github.com/qqabcv520)

## 4.16.1

`2021-05-30`

- Menu
  - 🐞 修复超长省略不能按照预期工作的问题。[#30672](https://github.com/ant-design/ant-design/pull/30672)
  - 🐞 修复在卸载时报 `Can't perform a React state update on an unmounted component` 的警告信息。[#30678](https://github.com/ant-design/ant-design/pull/30678)
  - 🐞 修复 `inline` 模式下，没有 `icon` 的条目不能正确处理省略样式的问题。[#30682](https://github.com/ant-design/ant-design/pull/30682)
- Typography
  - 🐞 修复 Typography.Text 在 css 省略可用时监听 ResizeObserver 的无用操作。[#30664](https://github.com/ant-design/ant-design/pull/30664)
  - 🐞 修复 `ellipsis` 在开发环境 HMR 生效后不再工作的问题。[#30754](https://github.com/ant-design/ant-design/pull/30754)
- Table
  - 🐞 修复筛选/排序列的 `align` 属性。[#30744](https://github.com/ant-design/ant-design/pull/30744)
  - 🐞 修复 Table.Summary `sticky` 模式下，配置 `bordered` 边框样式丢失的问题。[#30666](https://github.com/ant-design/ant-design/pull/30666)
- 🐞 修复 Collapse `expandIconPosition="right"` 未生效的问题。[#30680](https://github.com/ant-design/ant-design/pull/30680) [@hongdeyuan](https://github.com/hongdeyuan)
- TypeScript
  - 🤖 导出 TableColumnsType 类型。[#30747](https://github.com/ant-design/ant-design/pull/30747) [@alwaysloseall](https://github.com/alwaysloseall)
  - 🤖 导出 TreeDataNode 类型。[#30745](https://github.com/ant-design/ant-design/pull/30745) [@alwaysloseall](https://github.com/alwaysloseall)

## 4.16.0

`2021-05-24`

- 🔥 重构 Menu，支持键盘操作以及无障碍体验优化。[#30382](https://github.com/ant-design/ant-design/pull/30382)
- 💄 重新设计 Table 筛选和排序按钮的位置，使其归属列更明确。[#30651](https://github.com/ant-design/ant-design/pull/30651)
- Table
  - 🆕 Table.Summary 支持 `sticky` 模式。[#30631](https://github.com/ant-design/ant-design/pull/30631)
  - 🐞 修复有固定列的 Table 内嵌 Table 的额外边距丢失的问题。[#30587](https://github.com/ant-design/ant-design/pull/30587)
  - 🆕 Table 新增 `expandable.fixed` 属性用于设置扩展图标固定。[#29959](https://github.com/ant-design/ant-design/pull/29959)
- Upload
  - 🆕 Upload 组件 `itemRender` 添加 `actions` 调用参数。[#30236](https://github.com/ant-design/ant-design/pull/30236)
  - 🆕 Upload 从拖动事件中删除 `stopPropagation`，并添加`onDrop` 回调。[#30319](https://github.com/ant-design/ant-design/pull/30319) [@ebonow](https://github.com/ebonow)
- Typography
  - 🆕 Typography 增加斜体字支持。[#30458](https://github.com/ant-design/ant-design/pull/30458) [@alwaysloseall](https://github.com/alwaysloseall)
  - 🐞 修复 Typography 配置 `ellipsis={{ suffix: 'xxx' }}` 时换行闪动问题。[#30582](https://github.com/ant-design/ant-design/pull/30582)
- Collapse
  - 💄 修复 Collapse 不指定 `header` 时箭头错位的问题。[#30586](https://github.com/ant-design/ant-design/pull/30586)
  - 🐞 修复 Collapse 隐藏时设置 `activeKey` 时内容会消失的问题。[#30555](https://github.com/ant-design/ant-design/pull/30555) [@zjffun](https://github.com/zjffun)
- 🐞 修复 Menu.SubMenu 的 `icon` 设置为第三方 icon 库时的样式问题。[@#30642](https://github.com/ant-design/ant-design/pull/30642)
- 🐞 修复 Descriptions 单独引入样式丢失的问题。[@#30602](https://github.com/ant-design/ant-design/pull/30602) [@lisenenkov](https://github.com/lisenenkov)
- 🆕 Radio.Group 支持 `data-*` 和 `aria-*` 属性。[#30507](https://github.com/ant-design/ant-design/pull/30507)
- 🆕 Statistic.CountDown 组件增加 `onChange` 事件。[#30265](https://github.com/ant-design/ant-design/pull/30265) [@appleshell](https://github.com/appleshell)
- 🆕 PageHeader 的 `breadcrumb` 中允许设置为组件。[#30019](https://github.com/ant-design/ant-design/pull/30019) [@gepd](https://github.com/gepd)
- 🆕 ConfigProvider 支持动态设置 `prefixCls`。[#30625](https://github.com/ant-design/ant-design/pull/30625)
- 🐞 修复 Anchor 指定 `getCurrentAnchor` 后无法触发 `onChange` 的问题。[#30601](https://github.com/ant-design/ant-design/pull/30601)
- 🐞 修复 Notification `useNotification` 生成的通知框 `className` 作用范围不一致的问题。[#30588](https://github.com/ant-design/ant-design/pull/30588)
- 🐞 修复 Tabs `tabBarGutter` 属性失效的问题。[#30545](https://github.com/ant-design/ant-design/pull/30545)
- 💄 改写 Space 使用 `flexGap` 以代替 `margin` 样式以处理某些边界情况下的布局问题。[#30023](https://github.com/ant-design/ant-design/pull/30023)
- 🐞 修复 Form 校验错误状态下 Input.Group 和 Cascader 边框颜色错误。[#30640](https://github.com/ant-design/ant-design/pull/30640)
- 🌐 国际化
  - 🇷🇴 补充罗马尼亚语国际化。[#30419](https://github.com/ant-design/ant-design/pull/30419) [@stefy](https://github.com/stefy)
  - 🌐 补充荷兰语（荷兰 🇳🇱）及荷兰语（比利时 🇧🇪）国际化。[#30389](https://github.com/ant-design/ant-design/pull/30389) [@lewis-fidlers](https://github.com/lewis-fidlers)
- TypeScript
  - 🤖 Space TypeScript 定义支持 HTMLAttribute 属性。[#30590](https://github.com/ant-design/ant-design/pull/30590)

## 4.15.6

`2021-05-18`

- 🐞 Upload `accept` 将无视无效的 MIME 类型，以更贴近原生行为。[#30549](https://github.com/ant-design/ant-design/pull/30549)
- 💄 移除全局样式中对 `th` 的 `text-align` 属性的重置。[#30399](https://github.com/ant-design/ant-design/pull/30399) [@lbwa](https://github.com/lbwa)
- 🌐 国际化
  - 🇮🇳 补充印地语国际化文案。[#30541](https://github.com/ant-design/ant-design/pull/30541) [@jaideepghosh](https://github.com/jaideepghosh)
  - 🇧🇷 补充葡萄牙语（巴西）国际化文案。[#30532](https://github.com/ant-design/ant-design/pull/30532) [@buzs](https://github.com/buzs)

## 4.15.5

`2021-05-10`

- 🐞 修复 Upload 在 IE 下，`beforeUpload` 返回 `false` 的报错问题。[#30391](https://github.com/ant-design/ant-design/pull/30391) [@OleksandrAntonenko1](https://github.com/OleksandrAntonenko1)
- Calendar
  - 🐞 修复 Calendar 在 Form.Item 下样式错乱的问题。[#30442](https://github.com/ant-design/ant-design/pull/30442)
  - 🐞 修复 Calendar `value` 设置 `null` 和 `undefined` 时报错的问题。[#30442](https://github.com/ant-design/ant-design/pull/30442)。[#30442](https://github.com/ant-design/ant-design/pull/30442)
- Table
  - 🐞 修复 Table `filterDropdown` 调用 `confirm({ closeDropdown: true })` 时也会触发 `onFilterDropdownVisibleChange` 的问题。[#30457](https://github.com/ant-design/ant-design/pull/30457)
  - 🐞 修复 Table 展开图标在 Windows Firefox 下显示异常的问题。[#30410](https://github.com/ant-design/ant-design/pull/30410)
- 🐞 修复 Dropdown.Button 不支持 `mouseEnterDelay` 和 `mouseLeaveDelay` 的问题。[#30452](https://github.com/ant-design/ant-design/pull/30452)
- 💄 优化 Rate 聚焦行为从 `:focus` 到 `:focus-visible`。[#30451](https://github.com/ant-design/ant-design/pull/30451)
- 🐞 修复 Steps 进度条圆圈在底部被切掉的问题。[#30373](https://github.com/ant-design/ant-design/pull/30373) [@fachreza73](https://github.com/fachreza73)
- 🐞 修复在 DatePicker 里设置 `locale` 不能覆盖 ConfigProvider `locale` 的问题。[#30380](https://github.com/ant-design/ant-design/pull/30380) [@Map1en](https://github.com/Map1en)
- 国际化
  - 🇫🇮 改进 DatePicker 芬兰语国际化。[#30433](https://github.com/ant-design/ant-design/pull/30433) [@hiiri](https://github.com/hiiri)
  - 🇫🇷 更新法语国际化。[#30436](https://github.com/ant-design/ant-design/pull/30436) [@LoicUV](https://github.com/LoicUV)
  - 🇷🇸 更新塞尔维亚语国际化。[#30401](https://github.com/ant-design/ant-design/pull/30401) [@vmedar](https://github.com/vmedar)
- TypeScript
  - 🤖 Tooltip 导出 `zIndex` 类型定义。[#30432](https://github.com/ant-design/ant-design/pull/30432)

## 4.15.4

`2021-04-30`

- 🐞 修复 Menu.Item 设置 `collapsedWidth` 时宽度错误的问题。[#30357](https://github.com/ant-design/ant-design/pull/30357) [@Map1en](https://github.com/Map1en)
- 🐞 修复 Radio 选中样式有时高度略长的问题。[#30367](https://github.com/ant-design/ant-design/pull/30367)
- 🐞 修复 Typography.Link 在 `editable` 模式下点击编辑会触发链接跳转的问题。[#30354](https://github.com/ant-design/ant-design/pull/30354) [@John60676](https://github.com/John60676)
- 🐞 InputNumber 现在清空输入框时会触发 `onChange(null)`。[#30337](https://github.com/ant-design/ant-design/pull/30337)
- 🐞 修复 Modal `footer` 里放置 Dropdown.Button 的样式错乱问题。[#30328](https://github.com/ant-design/ant-design/pull/30328) [@Map1en](https://github.com/Map1en)
- 💄 替换 Anchor 默认背景颜色从 `#FFFFFF` 改至 `transparent`。[#30336](https://github.com/ant-design/ant-design/pull/30336)
- 🌐 添加 TimePicker.RangePicker `ko_KR` 和 `ja_JP` 的 `placeholder` 国际化。[#30285](https://github.com/ant-design/ant-design/pull/30285) [@ChalkPE](https://github.com/ChalkPE)
- TypeScript
  - 🤖 修复 Upload `beforeUpload` 和 `UploadFile` 类型声明。[#30351](https://github.com/ant-design/ant-design/pull/30351) [#30343](https://github.com/ant-design/ant-design/pull/30343) [@kerm1it](https://github.com/kerm1it)

## 4.15.3

`2021-04-25`

- Table
  - 🐞 修复选择列和边框冲突的问题。[#30304](https://github.com/ant-design/ant-design/pull/30304)
  - 🚨 当 `current` 为负数时将在显示控制台警告。[#30242](https://github.com/ant-design/ant-design/pull/30242) [@wadezhan](https://github.com/wadezhan)
- 🐞 修复 Button `type="link"` 添加 `disabled` 后仍然可点击跳转的问题。[#30209](https://github.com/ant-design/ant-design/pull/30209)
- 🐞 修复 Upload 当文件 url 为 `null` 时渲染出错问题。[#30215](https://github.com/ant-design/ant-design/pull/30215)
- 🐞 修复 SubMenu 在 ItemGroup 内时的内边距。[#30218](https://github.com/ant-design/ant-design/pull/30218) [@sebakerckhof](https://github.com/sebakerckhof)
- 🐞 修复 Checkbox 和 Radio 在 flex 布局下的对齐问题。[#30260](https://github.com/ant-design/ant-design/pull/30260)
- 🐞 修复 Badge 上放置旋转图标的动画问题。[#30275](https://github.com/ant-design/ant-design/pull/30275)
- 🐞 修复 Form 错误校验状态下 Input `disabled` 的 hover 样式。[#30302](https://github.com/ant-design/ant-design/pull/30302) [@Fog3211](https://github.com/Fog3211)
- TypeScript
  - 🤖 修复 Upload 组件 `beforeUpload` 类型声明。[#30213](https://github.com/ant-design/ant-design/pull/30213) [@hello-chinese](https://github.com/hello-chinese)

## 4.15.2

`2021-04-19`

- 🐞 修复 Tabs `centered` 失效问题。[#30106](https://github.com/ant-design/ant-design/pull/30106) [@kerm1it](https://github.com/kerm1it)
- 💄 修复 Badge `status="warning"` 时切换样式异常的问题。[#30090](https://github.com/ant-design/ant-design/pull/30090) [@jameslahm](https://github.com/jameslahm)
- 💄 修复 Button 为 `type="link"` 时禁用手型丢失的问题。[#30197](https://github.com/ant-design/ant-design/pull/30197)
- 🐞 修复 TextArea `onChange` 事件返回 `target` 对象不是 HTMLTextArea 对象的问题。[#30124](https://github.com/ant-design/ant-design/pull/30124)
- 🐞 Upload `fileList` 中的文件将总是有 uid。[#30087](https://github.com/ant-design/ant-design/pull/30087) [@jameslahm](https://github.com/jameslahm)
- 🌐 补充遗漏的 TimePicker 丹麦语国际化。[#30128](https://github.com/ant-design/ant-design/pull/30128) [@themitvp](https://github.com/themitvp)
- 🌐 增加 Image 组件 `preview` 繁體文案。[#30100](https://github.com/ant-design/ant-design/pull/30100) [@jameslahm](https://github.com/jameslahm)
- TypeScript
  - 🤖 修改 LIST_IGNORE 字段为 string 类型。[#30188](https://github.com/ant-design/ant-design/pull/30188) [@hello-chinese](https://github.com/hello-chinese)

## 4.15.1

`2021-04-10`

- 🐞 修复 Descriptions `labelStyle` `contentStyle` 当设置 `layout="vertical"` 和 `bordered={true}` 时不生效的问题。[#29942](https://github.com/ant-design/ant-design/pull/29942)
- 🐞 Upload 的 `fileList` 为冻结对象时不再崩溃。[#29944](https://github.com/ant-design/ant-design/pull/29944)
- 🐞 修复 Tabs 在 Safari 13.1 垂直模式下不能滚动问题。[#29983](https://github.com/ant-design/ant-design/pull/29983)
- 🐞 修复点击 Button 时有时会报错 `Cannot read property 'removeChild' of null` 的问题。[#29961](https://github.com/ant-design/ant-design/pull/29961) [@JohnDeved](https://github.com/JohnDeved)
- 🐞 修复 Transfer 按钮区域 box-shadow 被截断的问题。[#30030](https://github.com/ant-design/ant-design/pull/30030) [@jinchaofs](https://github.com/jinchaofs)
- 🐞 修复 CheckBox.Group 和 `@ant-design/compatible` 的 Form 无法一起工作的问题。[#30039](https://github.com/ant-design/ant-design/pull/30039) [@jameslahm](https://github.com/jameslahm)
- 🐞 修复 PageHeader 下卡片类型 `tabs` 样式问题。[#29819](https://github.com/ant-design/ant-design/pull/29819)
- Table
  - 💄 优化 Table 分页器在狭窄空间的样式问题。[#30065](https://github.com/ant-design/ant-design/pull/30065)
  - 🐞 修复 Table `@table-border-radius-base` 没有被应用到 `.ant-table` 节点上。[#29966](https://github.com/ant-design/ant-design/pull/29966) [@VoliBearCat](https://github.com/VoliBearCat)
- 🐞 修复 Input.TextArea `maxLength` 在受控时无效的问题。[#30070](https://github.com/ant-design/ant-design/pull/30070)
- TypeScript
  - 🤖 修复 Select 类型不能指定为 `undefined` 的问题。[#30068](https://github.com/ant-design/ant-design/pull/30068) [@Gamote](https://github.com/Gamote)
  - 🤖 修复 Popconfirm `okButtonProps` 和 `cancelButtonProps` 定义。[#29928](https://github.com/ant-design/ant-design/pull/29928) [@IggsGrey](https://github.com/IggsGrey)
- 国际化
  - 🇪🇸 添加西班牙语 `Table.SELECTION_NONE` 文案。[#29962](https://github.com/ant-design/ant-design/pull/29962) [@liquorxm](https://github.com/liquorxm)

## 4.15.0

`2021-03-29`

- 🆕 Table 新增 `rowSelection.defaultSelectedRowKeys` 支持。[#29879](https://github.com/ant-design/ant-design/pull/29879) [@keelii](https://github.com/keelii)
- 🐞 修复 TextArea 受控时展示值会被 `maxLength` 截取的问题；修复 `maxLength` 下超出部分无法触发 `onCompositionEnd` 事件的问题；修复使用 emoji 时 `maxLength` 和 `showCount` 计数逻辑不一致的问题。[#29867](https://github.com/ant-design/ant-design/pull/29867)
- 🐞 修复 Button 点击效果在 Shadow Root 下不生效的问题。[#29897](https://github.com/ant-design/ant-design/pull/29897) [@JohnDeved](https://github.com/JohnDeved)
- Pagination
  - 💄 优化 Pagination 切换页码后 focus 样式遗留的问题。[#29891](https://github.com/ant-design/ant-design/pull/29891)
  - 🐞 修复 Pagination 使用 `modifyVars` 自定义主题时，页面跳转输入框高度没有按照预期改变。[#29886](https://github.com/ant-design/ant-design/pull/29886) [@SyMind](https://github.com/SyMind)
- 🐞 修复 Steps 进度在边缘会被截断的问题。[#29893](https://github.com/ant-design/ant-design/pull/29893)
- 🛠 Upload 默认阻止拖拽冒泡事件以支持嵌套结构。[#29832](https://github.com/ant-design/ant-design/pull/29832) [@jojonarte](https://github.com/jojonarte)
- 🐞 ConfigProvider 的 `componentSize` 现在也会作用到 Tabs 上。[#29844](https://github.com/ant-design/ant-design/pull/29844) [@bn3t](https://github.com/bn3t)
- 💄 移除 Tag 鼠标悬浮样式以避免其误以为是可点击交互组件。[#29874](https://github.com/ant-design/ant-design/pull/29874)
- 🇫🇷 补充 `fr_FR` 语言缺失内容。[#29839](https://github.com/ant-design/ant-design/pull/29839) [@bn3t](https://github.com/bn3t)
- 🇸🇪 补充 `sv_SE` 语言缺失内容。[#29896](https://github.com/ant-design/ant-design/pull/29896) [@isakol](https://github.com/isakol)

## 4.14.1

`2021-03-22`

- 🐞 修复 Tabs 切换时标题宽度变化的问题。[#29781](https://github.com/ant-design/ant-design/issues/29781)
- 🐞 修复 Image 从缓存加载图片时，`placeholder` 不会隐藏的问题。[#29829](https://github.com/ant-design/ant-design/pull/29829)
- 💄 优化 Checkbox/Radio 文本的换行展示样式。[#29788](https://github.com/ant-design/ant-design/pull/29788)
- TypeScript
  - 🤖 修复 Upload `beforeUpload` 属性类型声明。[#29766](https://github.com/ant-design/ant-design/pull/29766)

## 4.14.0

`2021-03-14`

- Upload
  - 🆕 Upload `onChange` 改回原本行为（`beforeUpload` 返回时 false 参数返回原始文件，其余场景返回封装对象）。现在你始终可以通过 `onChange.info.originFileObj` 获得原始文件。为了未来升级，请优先使用该方式访问原始文件。[#29737](https://github.com/ant-design/ant-design/pull/29737)
  - 🐞 修复 Upload `onChange` 参数 `file` 不能被 lodash `cloneDeep` 的问题。[#29718](https://github.com/ant-design/ant-design/pull/29718)
  - 🐞 修复 Upload 当 `fileList` 为 `null` 时崩溃的问题。[#29702](https://github.com/ant-design/ant-design/pull/29702)
  - 💄 Upload 添加 2 秒时限以防止开发者手工移除动画样式时导致动画卡住的问题。[#29686](https://github.com/ant-design/ant-design/pull/29686)
- 🆕 为不同的 Notification 类型添加相应默认类名。[#29634](https://github.com/ant-design/ant-design/pull/29634) [@n0ruSh](https://github.com/n0ruSh)
- 🆕 Typography editable 新增 `onCancel` 和 `onEnd` 回调。[#29615](https://github.com/ant-design/ant-design/pull/29615) [@jueinin](https://github.com/jueinin)
- Tabs
  - 🆕 Tabs 新增 `moreIcon` 参数。[#29744](https://github.com/ant-design/ant-design/pull/29744) [@tianyuan233](https://github.com/tianyuan233)
  - 🐞 修复 Tabs 设置 `centered` 后居中位置偏移。[#29495](https://github.com/ant-design/ant-design/pull/29495) [@jinchaofs](https://github.com/jinchaofs)
- 🐞 Form 表单现在可以自动响应 reset 事件。[#29752](https://github.com/ant-design/ant-design/pull/29752) [@jueinin](https://github.com/jueinin)
- 🐞 修复 AutoComplete 自定义 input 上 `className` 属性丢失的问题。[#29725](https://github.com/ant-design/ant-design/pull/29725)
- 💄 修复 Row 设置 `margin` 样式时控制台警告的问题。[#29688](https://github.com/ant-design/ant-design/pull/29688)
- 🐞 修复 Modal 页脚里使用 href 按钮导致的间距丢失问题。[#29681](https://github.com/ant-design/ant-design/pull/29681) [@n0ruSh](https://github.com/n0ruSh)
- 💄 修复 Input 组件配置附件元素时禁用样式异常的问题。[#29670](https://github.com/ant-design/ant-design/pull/29670)
- 💄 优化 Form.Item 提示信息的鼠标显示样式。[#29650](https://github.com/ant-design/ant-design/pull/29650)
- 🇨🇿 修复 cs_CZ 语言环境中的错字。 [#29675](https://github.com/ant-design/ant-design/pull/29675) [@jvaclavik](https://github.com/jvaclavik)
- 🇨🇦 添加 fr_CA 语言。[#29748](https://github.com/ant-design/ant-design/pull/29748) [@liufenghua808](https://github.com/liufenghua808)

## 4.13.1

`2021-03-06`

- 🐞 修复 `message.config` 配置 `prefixCls` 时丢失淡入淡出动画的问题。[#29574](https://github.com/ant-design/ant-design/pull/29574)
- 🐞 修复 Tooltip 在某些情况下设置 `visible` 为 `true` 却无法交互的问题。[#29555](https://github.com/ant-design/ant-design/pull/29555)
- 🐞 修复多页面使用 ConfigProvider 切换时 `locale` 会丢失的问题。[#29570](https://github.com/ant-design/ant-design/pull/29570)
- 🐞 修复 Modal 的 hooks 在渲染前调用 `update` 与 `destroy` 无效的问题。[#29584](https://github.com/ant-design/ant-design/pull/29584)
- 🐞 修复 Grid ssr 时报错 `Prop style did not match`。[#29586](https://github.com/ant-design/ant-design/pull/29586)
- 🐞 修复小号 Select `tags` 模式的光标错位问题。[#29561](https://github.com/ant-design/ant-design/pull/29561)
- 🐞 修复 Carousel `dotPosition` 导致 `pauseOnHover` 失效的问题。[#29587](https://github.com/ant-design/ant-design/pull/29587) [@zgoby](https://github.com/zgoby)
- 🐞 修复 Steps 使用 `responsive` 时控制台抛出警告的问题。[#29599](https://github.com/ant-design/ant-design/pull/29599)
- 🐞 修复 Upload `onChange` 参数 `file.originFileObj` 返回嵌套 Proxy 对象的问题。[#29614](https://github.com/ant-design/ant-design/pull/29614)
- 🐞 修复 Descriptions 在 Table 下没有 100% 宽度的问题。[#29630](https://github.com/ant-design/ant-design/pull/29630)
- TypeScript
  - 🤖 修复 Drawer `contentWrapperStyle` 属性类型声明。[#29571](https://github.com/ant-design/ant-design/pull/29571)

## 4.13.0

`2021-02-28`

- 🔥 InputNumber 添加 `stringMode` 属性以支持高精度 `step`。`value` 受控并超出范围时展示警告样式而不是强制改值。动态修改 `min` 和 `max` 不再触发 `onChange` 事件。[#29373](https://github.com/ant-design/ant-design/pull/29373)
- 🆕 Upload 支持 `beforeUpload` 返回 `Upload.LIST_IGNORE` 时不将文件展示在列表中。[#29474](https://github.com/ant-design/ant-design/pull/29474)
- 🆕 Image 支持配置动画相关类型。[#29394](https://github.com/ant-design/ant-design/pull/29394) [@crazyair](https://github.com/crazyair)
- ConfigProvider
  - 🆕 ConfigProvider 添加全局静态配置以支持部分静态方法。[#29285](https://github.com/ant-design/ant-design/pull/29285) [@crazyair](https://github.com/crazyair)
  - 🆕 动画相关 css `className` 全部添加 `ant-` 前缀以防止重名问题。[#29268](https://github.com/ant-design/ant-design/pull/29268) [@crazyair](https://github.com/crazyair)
- 🆕 Form.List 嵌套多层 Form.Item 支持 `preserve` 属性。[#29267](https://github.com/ant-design/ant-design/pull/29267)
- 🆕 Drawer 支持 `contentWrapperStyle`。[#29219](https://github.com/ant-design/ant-design/pull/29219) [@kerm1it](https://github.com/kerm1it)
- 🆕 Layout.Sider 組件添加了 `ref` 支持。[#29169](https://github.com/ant-design/ant-design/pull/29169) [@qramilq](https://github.com/qramilq)
- 🐞 修复 Table 当过滤结果为空时，`pagination.current` 展示错误。[#29386](https://github.com/ant-design/ant-design/pull/29386) [@jinchaofs](https://github.com/jinchaofs)
- 🐞 修复 Anchor `target` 不是 html 元素时会出错的问题。[#29523](https://github.com/ant-design/ant-design/pull/29523) [@bcd337](https://github.com/bcd337)
- 🐞 修复 Steps 小尺寸时图标偏上的问题。[#29484](https://github.com/ant-design/ant-design/pull/29484)
- Select
  - 🐞 修复 Select 标签模式下大号控件的高度多了 `1px` 的问题。[#29437](https://github.com/ant-design/ant-design/pull/29437)
  - 📖 更新 Select 防抖示例封装成 DebounceSelect 组件以便于用户使用。[#29414](https://github.com/ant-design/ant-design/pull/29414)
- Dropdown
  - 🐞 修复 Dropdown 带图标的菜单项禁用样式丢失的问题。[#29433](https://github.com/ant-design/ant-design/pull/29433)
  - 🐞 修复 Dropdown 内 Menu 不支持 `expandIcon` 的问题。[#29338](https://github.com/ant-design/ant-design/pull/29338)
- 🐞 Fix 在本地开发时会报 tree-shaking 警告信息的问题。[#29378](https://github.com/ant-design/ant-design/pull/29378)
- 🇰🇷 修复 TimePicker 本地化。[#29540](https://github.com/ant-design/ant-design/pull/29540)
- TypeScript
  - 🤖 修复 Form.Item 的泛型定义问题。[#29397](https://github.com/ant-design/ant-design/pull/29397) [@mumiao](https://github.com/mumiao)
  - 🤖 优化 Table `filter` 相关类型声明。[#29385](https://github.com/ant-design/ant-design/pull/29385) [@mumiao](https://github.com/mumiao)

## 4.12.3

`2021-02-10`

- 🛠 使用 React hooks 重构 Drawer。[#29229](https://github.com/ant-design/ant-design/pull/29229)
- 🐞 修复 Table 的 `pagination. position` 为 `['none', 'none']`时分页器仍然展示的问题。[#29256](https://github.com/ant-design/ant-design/pull/29256) [@mumiao](https://github.com/mumiao)
- 🐞 修复 TextArea `showCount` 字数会遮挡 Form.Item `extra` 的问题。[#29245](https://github.com/ant-design/ant-design/pull/29245)
- 🐞 修复多选 Select 在暗黑模式下禁用的背景颜色异常的问题。[#29242](https://github.com/ant-design/ant-design/pull/29242)
- ⚡️ 优化 Slider 提示的对齐性能。[#29308](https://github.com/ant-design/ant-design/pull/29308) [@kerm1it](https://github.com/kerm1it)
- ⚡️ 升级 `@ant-design/colors` 依赖到 6.x，减少 gzipped 包体积 `1KB`。[#29307](https://github.com/ant-design/ant-design/pull/29307) [@07akioni](https://github.com/07akioni)
- 🇷🇺 为 Image 组件添加 `ru_RU` 俄语翻译。[#29271](https://github.com/ant-design/ant-design/pull/29271) [@mumiao](https://github.com/mumiao)
- 🇮🇷 为 DatePicker、Form、Table、TimePicker 和 Transfer 组件添加 `fa_IR` 波斯语翻译。[#29232](https://github.com/ant-design/ant-design/pull/29232) [@amiralitaheri](https://github.com/amiralitaheri)
- TypeScript
  - 🤖 修复 Table FilterDropdownProps 的 `confirm` 入参为可选类型。[#29241](https://github.com/ant-design/ant-design/pull/29241) [@mumiao](https://github.com/mumiao)

## 4.12.2

`2021-02-04`

- 💄 调整 Table 展开图标和选择框的大小一致并对齐。[#29214](https://github.com/ant-design/ant-design/pull/29214)
- 🐞 修复 List 配置 `gutter` 时列会折行的问题。[#29211](https://github.com/ant-design/ant-design/pull/29211)

## 4.12.1

`2021-02-03`

- 🐞 修复 antd 在页面加载之前载入导致的页面崩溃问题。[#29202](https://github.com/ant-design/ant-design/pull/29202)
- 🐞 修正 Table 改变 `pageSize` 重置 `current` 的逻辑，现在若超出会重置到最大页数。[#29184](https://github.com/ant-design/ant-design/pull/29184)

## 4.12.0

`2021-02-03`

- 🆕 Image.PreviewGroup 添加 `current` 属性支持受控模式。[#29153](https://github.com/ant-design/ant-design/pull/29153)
- InputNumber
  - 🆕 InputNumber 支持 `bordered` 属性。[#29105](https://github.com/ant-design/ant-design/pull/29105)
  - 🆕 InputNumber 添加 `keyboard` 属性以支持禁用键盘行为。[#29110](https://github.com/ant-design/ant-design/pull/29110) [@kerm1it](https://github.com/kerm1it)
- 💄 加深 Tag 文字颜色以提升可读性。[#29144](https://github.com/ant-design/ant-design/pull/29144)
- 💄 修复 Row 配置垂直 `gutter` 时会额外添加 `margin-bottom` 样式的问题。[#29059](https://github.com/ant-design/ant-design/pull/29059)
- 🐞 修复 Collapse 标题区域隐藏延迟的问题。[#29158](https://github.com/ant-design/ant-design/pull/29158)
- 🐞 修复 TextArea 输入 emoji 时 `showCount` 展示数据不正确的问题。[#29057](https://github.com/ant-design/ant-design/pull/29057) [@HomyeeKing](https://github.com/HomyeeKing)
- 📦 优化 ConfigProvider 在未开启 tree shaking 的项目中引入所有图标的问题。[#29045](https://github.com/ant-design/ant-design/pull/29045)
- 🇬🇧 为表格添加 `en-GB` 翻译。[#29131](https://github.com/ant-design/ant-design/pull/29131) [@eberjoe](https://github.com/eberjoe)
- Badge
  - 🐞 修复 Badge 的数字动画方向问题。[#29100](https://github.com/ant-design/ant-design/pull/29100)
  - 💄 修复 Badge 修改 `count` 内容以隐藏时的样式问题。[#29089](https://github.com/ant-design/ant-design/pull/29089)
- Table
  - 🆕 Table `showSorterTooltip` 属性支持 Tooltip 的配置。[#29002](https://github.com/ant-design/ant-design/pull/29002) [@harrisoff](https://github.com/harrisoff)
  - ⚡️ 优化 Table `rowSelection` 中 `onChange` 和 `onSelectAll` 的调用顺序。[#29079](https://github.com/ant-design/ant-design/pull/29079) [@kerm1it](https://github.com/kerm1it)
- TypeScript
  - 🤖 更新 Table TypeScript 定义 `dataSource` 至 `readonly`。[#29084](https://github.com/ant-design/ant-design/pull/29084)
- Less
  - 💄 增加 less 变量 `@progress-info-text-color`。 [#28981](https://github.com/ant-design/ant-design/pull/28981) [@yuxuan](https://github.com/yuxuan)

## 4.11.3

`2021-02-03`

错误的发布，与 `4.12.0` 相同，如果需要锁定版本，需要锁定到 `4.11.2`。

## 4.11.2

`2021-01-26`

- 🐞 修复 rc-trigger BuildInPlacements TypeScript 编译错误。[#29029](https://github.com/ant-design/ant-design/pull/29029) [@waiwaiku](https://github.com/waiwaiku)

## 4.11.1

`2021-01-24`

- 💄 Layout 内联子表单添加背景颜色以更好的区分层级。[#28842](https://github.com/ant-design/ant-design/pull/28842)
- 🆕 PageHeader 支持 `breadcrumbRender` 属性。[#28999](https://github.com/ant-design/ant-design/pull/28999)
- 🆕 Typography `ellipsis` 属性添加 `tooltip` 支持以自定义收缩时的提示信息。[#28821](https://github.com/ant-design/ant-design/pull/28821)
- Image
  - 🆕 Image 支持配置 `preview.maskClassName`。[#28681](https://github.com/ant-design/ant-design/pull/28681)
  - 🐞 修复预览图片会跟随鼠标移动的问题。[react-component/image#61](https://github.com/react-component/image/pull/61) [@simonwong](https://github.com/simonwong)
  - 🐞 修复 Image `placeholder` 不显示的问题。[#28953](https://github.com/ant-design/ant-design/issues/28953)
  - 🐞 修复多个 Image.PreviewGroup 之间图片互串的问题。[#28881](https://github.com/ant-design/ant-design/issues/28881)
- ConfigProvider
  - 🆕 ConfigProvider 支持 `iconPrefixCls` 修改图标样式前缀。[#28924](https://github.com/ant-design/ant-design/pull/28924)
  - ⚡️ 优化 ConfigProvider 切换属性的性能。[#28792](https://github.com/ant-design/ant-design/pull/28792) [@zxc0328](https://github.com/zxc0328)
- 💄 调整 TreeSelect 搜索高亮条目的颜色。[#28984](https://github.com/ant-design/ant-design/pull/28984)
- 💄 修复 Select 自定义 `tagRender` 时不对齐的问题。[#28962](https://github.com/ant-design/ant-design/pull/28962)
- Form
  - 🐞 修复 Form.Item 无法正确清理嵌套的 `noStyle` 错误信息问题。[#28918](https://github.com/ant-design/ant-design/pull/28918)
  - 🐞 Form.Item 配置 `preserve=false` 时，移除该字段将自动重置对应值为 `initialValues`。[#28908](https://github.com/ant-design/ant-design/pull/28908)
- 🐞 修复 Button 点击效果在 Shadow Root 下不生效的问题。[#28995](https://github.com/ant-design/ant-design/pull/28995) [@rinick](https://github.com/rinick)
- 🐞 修复 Table 自定义筛选器时未正确关闭菜单的问题。[#28688](https://github.com/ant-design/ant-design/pull/28688) [@alekye](https://github.com/alekye)
- Less
  - 💄 新增 less 变量 `@drawer-footer-padding-horizontal`。[#28975](https://github.com/ant-design/ant-design/pull/28975) [@yuxuan](https://github.com/yuxuan)
  - 💄 新增 `@menu-inline-submenu-bg` 变量，且 `@menu-dark-submenu-bg` 改名为 `@menu-dark-inline-submenu-bg`。[#28842](https://github.com/ant-design/ant-design/pull/28842)
- RTL
  - 💄 修复 Card 按钮在 RTL 模式下的样式问题。[#28915](https://github.com/ant-design/ant-design/pull/28915) [@Aghosey](https://github.com/Aghosey)
- TypeScript
  - 🤖 从 antd 默认入口中直接暴露 TypeScript 定义。[#28963](https://github.com/ant-design/ant-design/pull/28963)
  - 🤖 优化 Input/Skeleton 组件的 `style` 定义。[#28966](https://github.com/ant-design/ant-design/pull/28966) [@yingpengsha](https://github.com/yingpengsha)

## 4.11.0

`2021-01-24`

发布失误，此版本与 `4.10.3` 无区别，不要使用这个版本。

## 4.10.3

`2021-01-18`

- 🐞 修复按钮在 loading 加载时 `@btn-border-width` 失效问题。[#28886](https://github.com/ant-design/ant-design/pull/28886) [@jjanssen](https://github.com/jjanssen)
- Table
  - 🐞 修复 Table 自定义过滤器时 `onChange` 参数 `filters` 被错误转换及为空数组的问题。[#28850](https://github.com/ant-design/ant-design/pull/28850) [@Meowu](https://github.com/Meowu)
  - 💄 调整 Table 选中列宽度至 `32px`。[#28073](https://github.com/ant-design/ant-design/pull/28073)
  - 💄 新增 `@table-border-color` less 变量。[#28903](https://github.com/ant-design/ant-design/pull/28903)
- Transfer
  - 🛠 穿梭框 Search 组件使用 React Hooks 重构。[#28895](https://github.com/ant-design/ant-design/pull/28895) [@susiwen8](https://github.com/susiwen8)
  - 🌐 增加了 German 德语翻译。[#28826](https://github.com/ant-design/ant-design/pull/28826) [@aequi42](https://github.com/aequi42)
- Upload
  - 🐞 支持 Upload 报错提示对 Error 文本信息的捕获（Tooltip）。[#28716](https://github.com/ant-design/ant-design/pull/28716) [@wangcch](https://github.com/wangcch)
  - 🆕 Upload 在 `fileList` 没有提供 `uid` 时，会自动对其进行填充。[#28832](https://github.com/ant-design/ant-design/pull/28832)
- 🐞 修复 Slider `getPopupContainer` 属性没有默认值 `document.body` 问题。[#28865](https://github.com/ant-design/ant-design/pull/28865) [@rinick](https://github.com/rinick)
- 🐞 修复 Empty `description` 内使用 div 会报 `validateDOMNesting` 的问题。[#28862](https://github.com/ant-design/ant-design/pull/28862)
- 💄 修复 Tree `filterTreeNode` 高亮样式丢失的问题。[#28866](https://github.com/ant-design/ant-design/pull/28866)
- 💄 修复 Badge `dot` 宽度样式。[#28854](https://github.com/ant-design/ant-design/pull/28854)

## 4.10.2

`2021-01-11`

- 🐞 修复 commonjs 下引入 antd 报错的问题。[#28715](https://github.com/ant-design/ant-design/issues/28804)

## 4.10.1

`2021-01-10`

- 🛠 优化 Select 搜索性能。[#28715](https://github.com/ant-design/ant-design/pull/28715) [@kerm1it](https://github.com/kerm1it)
- 🐞 修复 Slider 在卸载时报 `forcePopupAlign` 错的问题。[#28699](https://github.com/ant-design/ant-design/pull/28699) [@Kerumen](https://github.com/Kerumen)
- 🐞 修复 Transfer `dataSource` 为 immutable 数据时报 `Cannot add property key, object is not extensible` 的问题。[#28675](https://github.com/ant-design/ant-design/pull/28675)
- 🐞 修复 Notification 使用 `useNotification` 生成的提示框关闭时高度跳动的问题。[#28660](https://github.com/ant-design/ant-design/pull/28660)
- 🐞 修复 Drawer 和 Modal 关闭后滚动条被禁用的问题。[#28749](https://github.com/ant-design/ant-design/pull/28749)
- 🛠 优化包体积 gzipped `2kB`。[#28678](https://github.com/ant-design/ant-design/pull/28678)
- TypeScript
  - 🤖 InputNumber `onChange` 的 `value` 的类型增加 `null`。[#28769](https://github.com/ant-design/ant-design/pull/28769) [@lengfangbing](https://github.com/lengfangbing)

## 4.10.0

`2021-01-04`

🎉 新年快乐！

- 🐞 修复不兼容 less 4.0.0 的问题。
- 🐞 修复 Typography 可编辑态光标跳动的问题。[#28545](https://github.com/ant-design/ant-design/pull/28545)
- 🐞 修复 Tree 动态加载数据时重复点击展开节点会导致状态错误的问题。[#28349](https://github.com/ant-design/ant-design/issues/28349) [@liuchao233](https://github.com/react-component/tree/pull/401)
- 🐞 修复 TreeSelect 和 Select `searchValue` 在受控且有值时，下拉菜单无法打开的问题。[#28574](https://github.com/ant-design/ant-design/pull/28574)
- 🐞 修复 Dropdown 禁用菜单项内的链接样式。[#28578](https://github.com/ant-design/ant-design/pull/28578)
- 🐞 修复 Progress `steps` 显示精度问题。[#28530](https://github.com/ant-design/ant-design/pull/28530) [@gaoryrt](https://github.com/gaoryrt)
- 🐞 修复 Radio 在 Chrome 下的对齐样式问题。[#28616](https://github.com/ant-design/ant-design/pull/28616)
- 🐞 修复 Collapse 修改 `@collapse-header-padding` 时箭头位置不居中的问题。[#28507](https://github.com/ant-design/ant-design/pull/28507)
- 💄 优化 Card 图片白边样式。[#28624](https://github.com/ant-design/ant-design/pull/28624)
- Input
  - 🐞 修复 Input.TextArea 有 `maxLength` 时输入中文被截断的问题。[#28456](https://github.com/ant-design/ant-design/pull/28456)
  - 🆕 Input.TextArea 的 `showCount` 属性现在支持传入一个方法来自定义数字的展示格式了。[#28145](https://github.com/ant-design/ant-design/pull/28145) [@MrHeer](https://github.com/MrHeer)
  - 🆕 Input `focus` 支持配置获取焦点时的光标位置。[#28602](https://github.com/ant-design/ant-design/pull/28602)
- Modal
  - 🐞 修复 Modal 可以被拖拽到窗口外的问题。[#28438](https://github.com/ant-design/ant-design/pull/28527) [@mumiao](https://github.com/mumiao)
  - 🆕 Modal.method 新增 `afterClose` 回调，会在 Modal 完全关闭后触发。[#28053](https://github.com/ant-design/ant-design/pull/28053) [@liuchao233](https://github.com/liuchao233)
- Table
  - 🐞 修复 `childrenColumnName` 和 `checkStrictly={false}` 无法一起使用的问题。[#28568](https://github.com/ant-design/ant-design/pull/28568)
  - 🐞 修复 Checkbox.Group 内选择行为异常的问题。[#28576](https://github.com/ant-design/ant-design/pull/28576)
  - 🐞 修复无数据时固定表头样式错乱的问题。[#28323](https://github.com/ant-design/ant-design/issues/28323)
  - 🐞 修复自定义 `filterDropdown` 时 `onChange` 事件的 `filters` 参数总是接收空数组的问题。[#28627](https://github.com/ant-design/ant-design/pull/28627) [@Meowu](https://github.com/Meowu)
  - 🆕 新增 `expandable.columnWidth` 以自定义展开列的宽度。[#28249](https://github.com/ant-design/ant-design/pull/28249)
  - 🆕 选择项新增清空所有选项。[#28580](https://github.com/ant-design/ant-design/pull/28580) [@n0ruSh](https://github.com/ant-design/ant-design/pull/285)
- Image
  - 🐞 修复错位问题。[#28439](https://github.com/ant-design/ant-design/pull/28439) [@MoeCasts](https://github.com/MoeCasts)
  - 💄 添加预览样式。[#28235](https://github.com/ant-design/ant-design/pull/28235)
  - 🆕 支持使用鼠标滚轮缩放图片。[#react-component/image/52](https://github.com/react-component/image/pull/52) [@OmriGM](https://github.com/OmriGM)
  - 🆕 支持单独设置预览图片。[#react-component/image/56](https://github.com/react-component/image/pull/56) [@wangcch](https://github.com/wangcch)
- Upload
  - 🐞 修复不使用 `transformFile` 时也会有警告的问题。[#28455](https://github.com/ant-design/ant-design/pull/28455) [@YanYuanFE](https://github.com/YanYuanFE)
  - 🐞 修复 Upload 的 `fileList` 和 immer 数据配合使用报错问题。[#28636](https://github.com/ant-design/ant-design/pull/28636) [@mumiao](https://github.com/mumiao)
  - 🆕 Upload 新增 `maxCount` 属性以限制文件数量。[#28367](https://github.com/ant-design/ant-design/pull/28367)
- DatePicker
  - 🚀 优化 `disabledDate` 逻辑。[#react-component/picker/191](https://github.com/react-component/picker/pull/191)
  - 🆕 新增 `onKeyDown` 回调。[#react-component/picker/138](https://github.com/react-component/picker/pull/138) [@conquera99](https://github.com/react-component/picker/pull/138)
- Select
  - 🐞 修复 `options` 更新不会触发选择框内容更新的问题。[#react-component/select/580](https://github.com/react-component/select/pull/580) [@jameslahm](https://github.com/jameslahm)
  - 🐞 修复使用 `tagRender` 后点击选项无法打开下拉框的问题。[react-component/select/582](https://github.com/react-component/select/pull/582) [@mumiao](https://github.com/mumiao)
  - 🐞 修复 `tokenSeparators` 在中文输入法下无法正确识别分隔符的问题。[#28564](https://github.com/ant-design/ant-design/issues/28564)
  - 🆕 `ref` 新增 `scrollTo` 方法。[#react-component/select/565](https://github.com/react-component/select/pull/565)
  - 🆕 多选模式下 `maxTagCount` 支持 `responsive`。[#28520](https://github.com/ant-design/ant-design/pull/28520)
- 🆕 Slider 新增 range.draggableTrack 以支持范围刻度整体可拖拽。[#28592](https://github.com/ant-design/ant-design/pull/28592)
- 🆕 `message` 新增 `onClick` 回调，会在消息被点击时触发。[#28148](https://github.com/ant-design/ant-design/pull/28148) [@ZeroTo0ne](https://github.com/ant-design/ant-design/pull/28148)
- 🆕 Descriptions 上可以统一设置 `labelStyle` 和 `contentStyle`。 [#28613](https://github.com/ant-design/ant-design/pull/28613)
- 🆕 Form 的 `scrollToFirstError` 属性支持设置滚动的位置参数。[#28272](https://github.com/ant-design/ant-design/pull/28272) [@vouis](https://github.com/vouis)
- 🆕 Steps 新增 reponsive 属性用于关闭响应式样式。[#28459](https://github.com/ant-design/ant-design/pull/28459)
- 🌐 国际化
  - 🇭🇷 改进克罗地亚语的支持。[#28458](https://github.com/ant-design/ant-design/pull/28458)
- TypeScript
  - 🛠 修复 PageHeader 的 `title` 的类型问题。[#28374](https://github.com/ant-design/ant-design/pull/28374) [@zhukovvandrei](https://github.com/zhukovvandrei)

## 4.9.4

`2020-12-16`

- 🐞 修复 Menu 在 Chrome 下 hover 色延迟变化的问题。[#28372](https://github.com/ant-design/ant-design/pull/28372)
- 🐞 修复 Tree 的节点连接线在滚动时位置偏移的问题。[#28354](https://github.com/ant-design/ant-design/pull/28354) [@maksnester](https://github.com/maksnester)
- 💄 修复 Table 固定列 `z-index` 样式让 Dropdown 无法展示在最顶层的问题。[#28346](https://github.com/ant-design/ant-design/pull/28346)
- TypeScript
  - 🤖 修复 `message.loading()` 返回函数的定义。[#28362](https://github.com/ant-design/ant-design/pull/28362)

## 4.9.3

`2020-12-14`

- 💄 修复 Badge 独立使用时展示/收起动画跳动的问题。[#28240](https://github.com/ant-design/ant-design/pull/28240)
- 🐞 修复 Table `filters` 不支持数字和 boolean 类型的问题。[#28220](https://github.com/ant-design/ant-design/pull/28220) [@Meowu](https://github.com/Meowu)
- 💄 修复 Tree 当 `selectable={false}` 时节点依然有 hover 背景色的问题。[#28269](https://github.com/ant-design/ant-design/pull/28269)
- 💄 修复 Statistics 小数点字体大小问题。[#28223](https://github.com/ant-design/ant-design/pull/28223)
- TypeScript
  - 🤖 修复 Tree `draggable` 支持函数的定义。[#28262](https://github.com/ant-design/ant-design/pull/28262) [@DavidSichau](https://github.com/DavidSichau)
  - 🤖 修复 Image.PreviewGroup 类型。[#28263](https://github.com/ant-design/ant-design/pull/28263) [@liuchao233](https://github.com/liuchao233)
  - 🤖 优化 `message().then` 的 TS 定义。[#28304](https://github.com/ant-design/ant-design/pull/28304)
  - 🤖 修正 TransferProps 的 `titles` 类型为 ReactNode。[#28326](https://github.com/ant-design/ant-design/pull/28326) [@jacklee814](https://github.com/jacklee814)

## 4.9.2

`2020-12-06`

- Table
  - 🐞 修复 Table 选择功能有时会 crash 的问题。[#28193](https://github.com/ant-design/ant-design/pull/28193) [@yanguoyu](https://github.com/yanguoyu)
  - 💄 修复 Table 选择列标题的对齐样式问题。[#28173](https://github.com/ant-design/ant-design/pull/28173)
- Dropdown
  - 💄 修复 Dropdown 下拉菜单箭头样式。[#28181](https://github.com/ant-design/ant-design/pull/28181)
  - 🐞 修复 Dropdown 点击触发区域不匹配的问题。[#28180](https://github.com/ant-design/ant-design/pull/28180)
- 🐞 修复 Tooltip `overlayInnerStyle` 属性无效。[#27682](https://github.com/ant-design/ant-design/pull/27682) [@jasepellerin](https://github.com/jasepellerin)
- 💄 修复 Layout 内部使用 Table `sticky` 属性失效的问题。[#28176](https://github.com/ant-design/ant-design/pull/28176)
- 💄 修复 Steps `progressDot` 第一个步骤点错位的问题。[#28126](https://github.com/ant-design/ant-design/pull/28126) [@ZeroTo0ne](https://github.com/ZeroTo0ne)
- 💄 优化 Modal `useModal` 性能，避免元素渲染导致组件渲染。[#28122](https://github.com/ant-design/ant-design/pull/28122) [@TotooriaHyperion](https://github.com/TotooriaHyperion)
- 💄 修复 TextArea 结合 Form 使用时的字数提示样式问题。[#28130](https://github.com/ant-design/ant-design/pull/28130) [@AlanCutFlim](https://github.com/AlanCutFlim)
- 💄 修复 Tree 里使用 Tag 时鼠标手型样式问题。[#28219](https://github.com/ant-design/ant-design/pull/28219)
- 🛠 移除对 `@ant-design/css-animation` 的依赖以优化包体积。[#28201](https://github.com/ant-design/ant-design/pull/28201)
- RTL
  - 💄 修复 Alert rtl 样式。[#28108](https://github.com/ant-design/ant-design/pull/28108) [@jesse3mh9a](https://github.com/jesse3mh9a)
  - 🐞 修复 Tree `dropIndicator` 默认 ltr 方向下的样式问题。[#28150](https://github.com/ant-design/ant-design/pull/28150) [@kagawagao](https://github.com/kagawagao)
- TypeScript
  - 🤖 修复 Table `SelectionSelectFn` 类型定义中 `selectedRows` 属性改为 T 范型。[#28206](https://github.com/ant-design/ant-design/pull/28206) [@weiyuc](https://github.com/weiyuc)
  - 🤖 Breadcrumb 的 `BreadcrumbItem` 中增加 `className` 类型。[#28182](https://github.com/ant-design/ant-design/pull/28182) [@ccloveak](https://github.com/ccloveak)
  - 🤖 Form.List `initialValue` 增加类型支持。[#28153](https://github.com/ant-design/ant-design/pull/28153) [@Debiancc](https://github.com/Debiancc)
  - 🤖 修复 Carousel 中 `dontAnimate` 参数为可选类型。[#28090](https://github.com/ant-design/ant-design/pull/28090) [@jarretmoses](https://github.com/jarretmoses)

## 4.9.1

`2020-12-01`

- TypeScript
  - 🤖 修复 Collapse.Panel 可折叠属性 `collapsible` 为可选。[#28092](https://github.com/ant-design/ant-design/pull/28092) [@sammarks](https://github.com/sammarks)

## 4.9.0

`2020-11-30`

- Modal
  - 🆕 Modal 支持 `focusTriggerAfterClose` 以关闭自动恢复焦点的功能。[#27985](https://github.com/ant-design/ant-design/pull/27985) [@molokovev](https://github.com/molokovev)
  - 🐞 修复 Modal hooks 没有触发 `onCancel` 的问题。[#28063](https://github.com/ant-design/ant-design/pull/28063) [@JuniorTour](https://github.com/JuniorTour)
  - 🐞 修复 Modal 有时不在点击位置弹出的问题。[#28037](https://github.com/ant-design/ant-design/pull/28037)
  - 🆕 Modal.method 支持 `closable` 和 `closeIcon`。[#27909](https://github.com/ant-design/ant-design/pull/27909) [@MrHeer](https://github.com/MrHeer)
- 💄 减少 Table 选中列宽度至 `32px`。[#28073](https://github.com/ant-design/ant-design/pull/28073)
- Image
  - 🔥 Image 增加 PreviewGroup 组件支持多张图片预览。[#28069](https://github.com/ant-design/ant-design/pull/28069)
  - 🐞 修复 Image style 属性未作用于 img 元素的问题。[#27446](https://github.com/ant-design/ant-design/pull/27446)
- Collapse
  - 🔥 Collapse 添加 `collapsible` 以支持指定可折叠触发区域并废弃 Panel 的 `disabled` 属性。[#27790](https://github.com/ant-design/ant-design/pull/27790)
  - 🐞 修复 Collapse 内使用 `<Table sticky />` 时不生效的问题。[#28039](https://github.com/ant-design/ant-design/pull/28039)
- 🐞 修复 Cascader 空数据可以被选择的问题。[#28062](https://github.com/ant-design/ant-design/pull/28062) [@n0ruSh](https://github.com/n0ruSh)
- 🆕 Alert 支持 `action` 属性。[#25892](https://github.com/ant-design/ant-design/pull/25892) [@jesse3mh9a](https://github.com/jesse3mh9a)
- 🔥 Tree 重构拖拽行为，增加 `dropIndicatorRender` 和 `allowDrop` 属性。[#26462](https://github.com/ant-design/ant-design/pull/26462) [@07akioni](https://github.com/07akioni)
- 🆕 Space 增加 `wrap` 属性以配置自动换行。[#27910](https://github.com/ant-design/ant-design/pull/27910)
- 🆕 Descriptions.Item 支持 `labelStyle` 和 `contentStyle` 属性。[#27897](https://github.com/ant-design/ant-design/pull/27897)
- 🆕 Form.List 支持 `initialValue`。[#27872](https://github.com/ant-design/ant-design/pull/27872)
- 🆕 Menu 新增 `expandIcon` 属性以支持自定义展开图标，同时优化了默认图标的样式。[#27565](https://github.com/ant-design/ant-design/pull/27565)
- 🆕 Input 和 TextArea 组件的 `ref` 属性增加`setSelectionRange`方法。[#27584](https://github.com/ant-design/ant-design/pull/27584) [@appleshell](https://github.com/appleshell)
- 🆕 Select 组件新增 `filterSort` 属性以支持筛选模式下选项排序功能。[#27523](https://github.com/ant-design/ant-design/pull/27523) [@n0ruSh](https://github.com/n0ruSh)
- 🇰🇿 新增哈萨克语。[#27589](https://github.com/ant-design/ant-design/pull/27589) [@nodkz](https://github.com/nodkz)

## 4.8.6

`2020-11-27`

- 🐞 修复 Badge 在初始化时样式抖动的问题。[#28003](https://github.com/ant-design/ant-design/pull/28003)
- 💄 优化 Modal 相关样式的冗余。[#27998](https://github.com/ant-design/ant-design/pull/27998)
- 🐞 修复 Layout.Sider 在 `width='0'` 时不能展开的问题。[#28000](https://github.com/ant-design/ant-design/pull/28000)
- 🐞 修复 Menu 使用非 Ant Design 图标时的样式问题。[#27983](https://github.com/ant-design/ant-design/pull/27983)
- Input
  - 🐞 修复 Input.Search 自定义 less 变量时的按钮高度问题。[#27986](https://github.com/ant-design/ant-design/pull/27986)
  - 🐞 修复 Input.Search `addonBefore` 样式异常。[#27960](https://github.com/ant-design/ant-design/pull/27960)
- 🐞 修复 Typography.Link 点击复制按钮会触发链接跳转的问题。[#27982](https://github.com/ant-design/ant-design/pull/27982)
- 🐞 修复 Carousel `Unable to preventDefault inside passive event listener` 报错问题。[#27957](https://github.com/ant-design/ant-design/pull/27957)
- 🌐 改进 DatePicker 的 `en_GB` 与 `zh_TW` 本地化支持。[#28016](https://github.com/ant-design/ant-design/pull/28016) [@abz53378](https://github.com/abz53378)
- RTL
  - 💄 优化 Descriptions 在 RTL 模型下的边框样式。[#28010](https://github.com/ant-design/ant-design/pull/28010)
  - 💄 修复 Steps 垂直方向在 RTL 模式下的样式。[#27996](https://github.com/ant-design/ant-design/pull/27996)
- TypeScript
  - 🤖 修复 Upload 的 `beforeUpload` 定义问题。[#27946](https://github.com/ant-design/ant-design/pull/27946) [@bingling0084](https://github.com/bingling0084)
  - 🤖 为 Carousel 提供单独的 ref 定义。[#27935](https://github.com/ant-design/ant-design/pull/27935) [@ocassio](https://github.com/ocassio)

## 4.8.5

`2020-11-22`

- 🐞 修复 Spin 组件不能渲染 `0` 的问题。[#27839](https://github.com/ant-design/ant-design/pull/27839) [@liuchao233](https://github.com/liuchao233)
- 💄 修复 RangePicker 面板的交互样式。[#27894](https://github.com/ant-design/ant-design/pull/27894)
- 💄 修复 Switch `loading` 的样式问题。[#27860](https://github.com/ant-design/ant-design/pull/27860)
- 💄 优化 Skeleton 默认色彩使其能放置在暗色背景中。[#27836](https://github.com/ant-design/ant-design/pull/27836)
- 💄 调整 Statistic 小数的字体大小。[#27884](https://github.com/ant-design/ant-design/pull/27884)
- 🛠 使用 React hooks 重构 Checkbox、Layout.Sider 和 TextArea。[#27739](https://github.com/ant-design/ant-design/pull/27739) [#27719](https://github.com/ant-design/ant-design/pull/27719) [#27693](https://github.com/ant-design/ant-design/pull/27693)
- 🛠 使用 `rc-motion` 动画库代替 `rc-animate` 重构 BackTop、Badge、UploadList。[#27840](https://github.com/ant-design/ant-design/pull/27840) [#27848](https://github.com/ant-design/ant-design/pull/27848) [#27923](https://github.com/ant-design/ant-design/pull/27923)
- RTL
  - 💄 修复 Tree 切换按钮在 RTL 模式下的样式问题。[#27876](https://github.com/ant-design/ant-design/pull/27876)
- TypeScript
  - 🤖 修复 AutoComplete `DataSourceItemType` 的类型定义。[#27892](https://github.com/ant-design/ant-design/pull/27892)
  - 🤖 导出 Image 的 `ImageProps` 接口。[#27846](https://github.com/ant-design/ant-design/pull/27846) [@wangcch](https://github.com/wangcch)

## 4.8.4

`2020-11-16`

- 💄 修复 Button 和 Form 校验 loading 样式错误的问题。[#27794](https://github.com/ant-design/ant-design/pull/27794)
- 🐞 修复 Modal.confirm 关闭时国际化丢失的问题。[#27797](https://github.com/ant-design/ant-design/pull/27797)
- 🐞 修复 Button 和 Anchor 等组件在 React 17 下 `findDOMNode is deprecated` 的警告。[#27755](https://github.com/ant-design/ant-design/pull/27755) [@hosseinmd](https://github.com/hosseinmd)

## 4.8.3

`2020-11-14`

- 🛠 使用 React hooks 重构 Carousel。[#27694](https://github.com/ant-design/ant-design/pull/27694)
- 🛠 使用 React hooks 重构 `<Typography editable />`。[#27655](https://github.com/ant-design/ant-design/pull/27655)
- 🐞 修复 Form 在 namePath 为数组的时候表现异常的问题。[#27664](https://github.com/ant-design/ant-design/pull/27664)
- 💄 修复 DateRangePicker 选择已选范围内一行的首尾日期时的悬浮样式位置异常问题。[#27731](https://github.com/ant-design/ant-design/pull/27731) [@AlanCutFlim](https://github.com/AlanCutFlim)
- 🐞 修复 Select `tags` 模式下无法输入空格的问题。[#27726](https://github.com/ant-design/ant-design/pull/27726) [@baxtergu](https://github.com/baxtergu)
- 💄 修复 Typography.Link 禁用时鼠标样式问题。[#27734](https://github.com/ant-design/ant-design/pull/27734)
- 🐞 修复 Menu 下拉框显示时动画会播放两次的问题。[#27663](https://github.com/ant-design/ant-design/pull/27663)
- 💄 修复 Avatar src 为 Image 时的样式问题。[#27691](https://github.com/ant-design/ant-design/pull/27691)
- 💄 修复 Select `mode="multiple"` 的光标位置偏左的问题。[#27689](https://github.com/ant-design/ant-design/pull/27689)
- 🐞 修复 TextArea 使用 emoji 时被裁切的问题。[#27679](https://github.com/ant-design/ant-design/pull/27679) [@372623460jh](https://github.com/372623460jh)
- 🐞 修复 RangePicker `size="small"` 时高亮线没有对齐的问题。[#27673](https://github.com/ant-design/ant-design/pull/27673) [@Ifeinstein](https://github.com/Ifeinstein)
- 💄 新增 `@radio-border-width` less 变量。[#27703](https://github.com/ant-design/ant-design/pull/27703)

## 4.8.2

`2020-11-09`

- 🐞 修复 Pagination 快速跳转 margin 丢失的问题。[#27650](https://github.com/ant-design/ant-design/pull/27650)
- 🐞 修复 Steps `type="navigation"` 最后一项的样式问题。[#27654](https://github.com/ant-design/ant-design/pull/27654)

## 4.8.1

`2020-11-08`

- 🛠 使用 React hooks 重构 TreeSelect。[#27593](https://github.com/ant-design/ant-design/pull/27593)
- 🛠 使用 React hooks 重构 Layout。[#27595](https://github.com/ant-design/ant-design/pull/27595)
- 🐞 再次修复 Select 组件在 Form 中触发校验时外边框样式异常的问题。[#27607](https://github.com/ant-design/ant-design/pull/27607)
- 🐞 修复 Pagination 开启页码切换器时右侧多余的 `margin`。[#27610](https://github.com/ant-design/ant-design/pull/27610)
- 🐞 修复 Input.Search `enterButton={null}` 报错的问题。[#27591](https://github.com/ant-design/ant-design/pull/27591) [@davidebianchi](https://github.com/davidebianchi)
- 🐞 修复 Avatar.Group `size` 不生效的问题。[#27531](https://github.com/ant-design/ant-design/pull/27531)
- 🐞 修复垂直 Tabs 标题文字很长时导致页签宽度跳动的问题。[#27569](https://github.com/ant-design/ant-design/pull/27569)
- 🐞 修复 Table `column.children` 内的筛选功能不展示的问题。[#27435](https://github.com/ant-design/ant-design/pull/27435) [@JhonXY](https://github.com/JhonXY)
- 💄 修复 Steps 内嵌 Steps 时的样式。[#27514](https://github.com/ant-design/ant-design/pull/27514)
- TypeScript
  - 🤖 修复 Select `ref` 属性 TS 错误。[#27482](https://github.com/ant-design/ant-design/pull/27482)
  - 🤖 修复 Avatar `src` 类型。[#27524](https://github.com/ant-design/ant-design/pull/27524) [@n0ruSh](https://github.com/n0ruSh)
- RTL
  - 💄 修复 Progress.Line `strokeColor` 在 RTL 模式下方向错误。[#27515](https://github.com/ant-design/ant-design/pull/27515)

## 4.8.0

`2020-11-02`

- Image
  - 🔥 Image 支持 `preview.getContainer` 属性用于指定预览对话框的容器。[#26713](https://github.com/ant-design/ant-design/pull/26713) [@rfreling](https://github.com/rfreling)
  - 🐞 修复 Image `style` 属性未作用于 img 元素的问题。[#27446](https://github.com/ant-design/ant-design/pull/27446)
- 🆕 ConfigProvider 增加 `form.requiredMark` 配置。[#27322](https://github.com/ant-design/ant-design/pull/27322)
- 🆕 Statistic 组件增加 `loading` 属性。[#26811](https://github.com/ant-design/ant-design/pull/26811) [@appleshell](https://github.com/appleshell)
- Avatar
  - 🔥 Avatar 组件支持直接传入 Image 元素。[#27448](https://github.com/ant-design/ant-design/pull/27448) [@n0ruSh](https://github.com/n0ruSh)
  - 🆕 Avatar.Group 增加 `size` 属性。[#27348](https://github.com/ant-design/ant-design/pull/27348)
- 🆕 Row 支持 `noWrap` 属性以使 Col 不错行。[#27469](https://github.com/ant-design/ant-design/pull/27469)
- Tree
  - 🐞 修复 Tree 双击折叠图标时会选中文字的问题。[#27476](https://github.com/ant-design/ant-design/pull/27476)
  - 🐞 修复 Tree 配置 `showLine` 下 `title` 多行的时候，线会截断的问题。[#27386](https://github.com/ant-design/ant-design/pull/27386)
- Modal
  - 🆕 `modal.update()` 支持函数式更新。[#27163](https://github.com/ant-design/ant-design/pull/27163) [@Mongkii](https://github.com/Mongkii)
  - 🆕 Modal method 增加 `bodyStyle` 属性。[#27292](https://github.com/ant-design/ant-design/pull/27292)
  - 🐞 Fix Modal missing `modalRender` prop。[#27272](https://github.com/ant-design/ant-design/pull/27272) [@jieny](https://github.com/jieny)
  - 🐞 `Modal.config` 中设置的 `rootPrefixCls` 可以对 `title` 和 `content` 下使用的 antd 组件生效。[#27376](https://github.com/ant-design/ant-design/pull/27376) [@Chersquwn](https://github.com/Chersquwn)
- Input
  - 🆕 Input.Textarea 支持 `size` 属性。[#27110](https://github.com/ant-design/ant-design/pull/27110)
  - 🐞 修复 Input `allowClear` 时 `className` 丢失的问题。[#27462](https://github.com/ant-design/ant-design/pull/27462)
- Table
  - 🆕 Table.Summary.Cell 支持 `align` 配置。[#27365](https://github.com/ant-design/ant-design/pull/27365)
  - 🐞 修复 Table 切换页长时 `onShowSizeChange` 触发两次的问题。[#27417](https://github.com/ant-design/ant-design/pull/27417)
  - 🐞 修复 Table `pagination` 有时候会缓存先前设置的问题。[#27412](https://github.com/ant-design/ant-design/pull/27412)
- Typography
  - 🐞 修复 Typography 特定内容出现非法正则表达式错误的问题。[#27383](https://github.com/ant-design/ant-design/pull/27383) [@ttys026](https://github.com/ttys026)
  - 💄 修复 Typography.Link 禁用时鼠标悬浮或点击的颜色问题。[@27487](https://github.com/ant-design/ant-design/pull/27487) [@Liu-Ya](https://github.com/Liu-Ya)
- Steps
  - 🐞 修复当开启 `progressDot` 时，标题未居中对齐的问题。[#27406](https://github.com/ant-design/ant-design/pull/27406)
  - 🐞 修复在小屏幕下的各类样式错乱问题。[#27499](https://github.com/ant-design/ant-design/pull/27499)
- 🐞 修复 PageHeader `title` 为空时，会展示空 DOM 的问题。[#27485](https://github.com/ant-design/ant-design/pull/27485)
- 🐞 修复 Slider 拖拽时提示内容对齐问题。[#27489](https://github.com/ant-design/ant-design/pull/27489)
- 🐞 修复 RangePicker 选择同一时间后再次选择时边框样式异常的问题。[#27438](https://github.com/ant-design/ant-design/pull/27438)
- 💄 调整 Collapse 折叠箭头的位置与第一行文字对齐。[#27363](https://github.com/ant-design/ant-design/pull/27363)
- 💄 修复 Descriptions 在 `label` 自定义为块状元素时的样式问题。[#27375](https://github.com/ant-design/ant-design/pull/27375)
- 💄 修复 Select 组件在 Form 中触发校验时边框样式异常的问题。[#27378](https://github.com/ant-design/ant-design/pull/27378)

## 4.7.3

`2020-10-24`

- Form
  - 🐞 修复 Form 在 ConfigProvider 下会警告 `non-boolean attribute 'virtual'` 的问题。[#27343](https://github.com/ant-design/ant-design/pull/27343)
  - 🛠 调整 Form.Item `initialValue` 的同步时机改由与 `initialValues` 相同。[#27319](https://github.com/ant-design/ant-design/pull/27319)
- Typography
  - 🛠 优化 Typography 省略时的 `title` 提示，现在会在 `...` 上展现剩余文本。[#27328](https://github.com/ant-design/ant-design/pull/27328)
  - 💄 修复 Typography 在 Card title 中编辑样式问题。[#27221](https://github.com/ant-design/ant-design/pull/27221)
- Input
  - 🐞 修复 Input.Search 指定 `allowClear` 时 `className` 重复出现的问题。[#27261](https://github.com/ant-design/ant-design/pull/27261)
  - 🐞 修复 修复 Input.Search 激活 `allowClear` 时边框样式异常的问题。[#27325](https://github.com/ant-design/ant-design/pull/27325)
- 🐞 修复 Upload.List 图片预览显示不全的问题。[#27312](https://github.com/ant-design/ant-design/pull/27312) [@JuniorTour](https://github.com/JuniorTour)
- 🐞 修复 Notification 长文本不换行的问题。[#27285](https://github.com/ant-design/ant-design/pull/27285) [@littleee](https://github.com/littleee)
- 🐞 修复 Menu 在 flex 容器内不会正常收缩省略的问题。[#27253](https://github.com/ant-design/ant-design/pull/27253)
- 🌐 修复 en_US、en_GB、ga_IE 国际化语法问题。[#27259](https://github.com/ant-design/ant-design/pull/27259) [@yasikovsky](https://github.com/yasikovsky)
- 🐞 修复 Tag 标签自定义关闭图标会导致换行的问题。[#27226](https://github.com/ant-design/ant-design/pull/27226) [@handycode](https://github.com/handycode)

## 4.7.2

`2020-10-19`

- 💄 修复 Layout.Sider `light` 主题失效问题。[#27227](https://github.com/ant-design/ant-design/pull/27227) [@lingjieee](https://github.com/lingjieee)
- 💄 修复 TextArea 没有设置 `showCount` 时仍然会包裹 div 的问题，同时解决 `showCount` 下 `className` 和 `style` 没有传递给最外层节点的问题。[#27216](https://github.com/ant-design/ant-design/pull/27216)
- 🐞 修复 Checkbox.Group TS2559 错误。[#27231](https://github.com/ant-design/ant-design/pull/27231)

## 4.7.1

`2020-10-18`

- DatePicker
  - 🐞 修复 DatePicker `showTime` 为 `true` 并且 `format` 为一个函数时报错的问题。[#27156](https://github.com/ant-design/ant-design/pull/27156)
  - 💄 修复 DatePicker 在下拉空间不足时的动画方向问题。[#27101](https://github.com/ant-design/ant-design/pull/27101)
- Typography
  - 💄 修复 Typography 没有 `pre` 和 `blockquote` 样式的问题。[#27150](https://github.com/ant-design/ant-design/pull/27150)
  - 🐞 修复 Typography.Link 悬浮颜色错误的问题。[#27119](https://github.com/ant-design/ant-design/pull/27119)
  - 🐞 修复 Typography.Link 危险类型的悬浮颜色问题。[#27104](https://github.com/ant-design/ant-design/pull/27104)
- 💄 修复 Descriptions 组件的内容含有超长数字时无法换行的问题。[#27195](https://github.com/ant-design/ant-design/pull/27195) [@WLyKan](https://github.com/WLyKan)
- 🐞 修复 Password 在受控模式下未清除 `value` 属性的问题。[#27191](https://github.com/ant-design/ant-design/pull/27191)
- 🐞 修复 Notification 在小尺寸屏幕下的宽度问题。[#27189](https://github.com/ant-design/ant-design/pull/27189)
- 🐞 修复 Cascader 类名重复的问题。[#27187](https://github.com/ant-design/ant-design/pull/27187) [@huntdream](https://github.com/huntdream)
- 🐞 修复 Drawer 会触发 Form 提交事件的问题。[#27175](https://github.com/ant-design/ant-design/pull/27175)
- 🐞 修复 Dropdown 下拉菜单图标间距丢失的问题。[#27165](https://github.com/ant-design/ant-design/pull/27165)
- 💄 修复 Layout.Sider 指定 `collapsedWidth` 后侧边菜单部分宽度不对的问题。[#27154](https://github.com/ant-design/ant-design/pull/27154)
- 🐞 修复 Tabs `animated` 属性为 `true` 时未开启内容切换动画的问题。[#27145](https://github.com/ant-design/ant-design/pull/27145)
- 🐞 修复 Divider 带标题时的分割线颜色。[#27134](https://github.com/ant-design/ant-design/pull/27134)
- 💄 修复 Radio 选项选中并禁用时的鼠标样式。[#27125](https://github.com/ant-design/ant-design/pull/27125)
- 🇪🇸 为西班牙语 es_ES 中添加缺少的翻译。[#27079](https://github.com/ant-design/ant-design/pull/27079) [@gerongams](https://github.com/gersongams)
- RTL
  - 💄 优化 Input.TextArea 字数提示在 RTL 模式下的样式。[#27098](https://github.com/ant-design/ant-design/pull/27098)
- TypeScript
  - 🤖 Button `shape` 移除文档中未声明的类型。[#27159](https://github.com/ant-design/ant-design/pull/27159)
  - 🤖 修复 Form.List `rules` 属性缺失的问题。[#27164](https://github.com/ant-design/ant-design/pull/27164) [@huntdream](https://github.com/huntdream)

## 4.7.0

`2020-10-10`

- 🔥 Input.TextArea 支持字数统计功能。[#26952](https://github.com/ant-design/ant-design/pull/26952) [@zhangchen915](https://github.com/zhangchen915)
- DatePicker
  - 🔥 DatePicker `format` 支持传入一个函数以自定义显示内容。[#26845](https://github.com/ant-design/ant-design/pull/26845)
  - 🐞 修复 RangePicker 结束日期初始值无法选择的问题。[#23167](https://github.com/ant-design/ant-design/issues/23167)
- Form
  - 🔥 Form.Item 支持 `tooltip` 属性自定义提示信息。[#26780](https://github.com/ant-design/ant-design/pull/26780)
  - 🆕 Form.List 支持 `rules` 校验并添加 Form.ErrorList 组件用于展示。[#26676](https://github.com/ant-design/ant-design/pull/26676)
  - 🆕 Form.Item 支持 `messageVariables` 属性。[#26597](https://github.com/ant-design/ant-design/pull/26597)
  - 🐞 修复 Form `onValuesChange` 第二个参数返回整个 `store` 的值而不是有效字段值的问题。[#26808](https://github.com/ant-design/ant-design/pull/26808)
- Upload
  - 🔥 Upload 添加 `itemRender` 用于自定义文件列表项。[#26333](https://github.com/ant-design/ant-design/pull/26333)
  - 🆕 Upload `removeIcon` 和 `downloadIcon` 现在支持传入一个函数。[#26684](https://github.com/ant-design/ant-design/pull/26684) [@mwaddell](https://github.com/mwaddell)
- Table
  - 🆕 Table `sticky` 支持 `getContainer` 以指定滚动容器。[#26973](https://github.com/ant-design/ant-design/pull/26973)
  - 🐞 修复 Table `column.filterDropdown` 为 `undefined` 时依旧会展示筛选菜单的问题。[#27002](https://github.com/ant-design/ant-design/pull/27002) [@shangyilim](https://github.com/shangyilim)
- Modal
  - 🛠 重构 Modal 组件动画，现在 `destroyOnClose` 关闭时将完全清理相关 Dom 节点。[#26940](https://github.com/ant-design/ant-design/pull/26940)
  - 🆕 Modal 新增 `modalRender` 属性，支持可拖拽的对话框。[#26507](https://github.com/ant-design/ant-design/pull/26507) [@jhoneybee](https://github.com/jhoneybee)
- 🆕 Space 增加 `split` 属性以支持分隔符间隔。[#26948](https://github.com/ant-design/ant-design/pull/26948)
- 🆕 Image `preview` 属性扩展支持 `visible` 和 `onVisibleChange`。[#26915](https://github.com/ant-design/ant-design/pull/26915)
- 🆕 InputNumber 点击上下按钮时将触发 `onStep`。[#27075](https://github.com/ant-design/ant-design/pull/27075)
- 🆕 Avatar `size` 可以进行响应式的大小配置。[#26244](https://github.com/ant-design/ant-design/pull/26244) [@willamesoares](https://github.com/willamesoares)
- 🐞 修复 Radio.Button 内无法使用 Tooltip 的问题。[#27050](https://github.com/ant-design/ant-design/pull/27050)
- RTL
  - ⬅️ 修复 List 按钮在 RTL 模式下的样式。[#26964](https://github.com/ant-design/ant-design/pull/26964)
  - ⬅️ 优化 Transfer 分页在 RTL 模式下的样式。[#26960](https://github.com/ant-design/ant-design/pull/26960)
  - ⬅️ 修复 Upload RTL 模式下样式。[#26961](https://github.com/ant-design/ant-design/pull/26961)
  - ⬅️ 优化 Tag 样式避免主题和 RTL 模式互相影响。[#26955](https://github.com/ant-design/ant-design/pull/26955)
  - ⬅️ 优化 Cascader/Tree 组件中数据扩展 `loading` 按钮在 RTL 模式下的样式。[#27010](https://github.com/ant-design/ant-design/pull/27010)
- TypeScript
  - 🤖 修复 `TimeLineItemProps` 为 `TimelineItemProps`。[#27001](https://github.com/ant-design/ant-design/pull/27001) [@mgcrea](https://github.com/mgcrea)
  - 🤖 修复 Slider `autoFocus` 属性定义。[#26995](https://github.com/ant-design/ant-design/pull/26995) [@shangyilim](https://github.com/shangyilim)
  - 🤖 修复 Slider `step` 属性不接收 `null` 的问题。[#26984](https://github.com/ant-design/ant-design/pull/26984) [@shangyilim](https://github.com/shangyilim)
  - 🤖 修复 Slider.Range `trackStyle` 和 `handleStyle` 应该接受数组的问题。[#27033](https://github.com/ant-design/ant-design/pull/27033)
  - 🤖 优化 Tag `onClose` TypeScript 定义。[#26932](https://github.com/ant-design/ant-design/pull/26932)
  - 🤖 调整 Form 定义，现在当 `getFieldsValue` 不配置 `namePath` 时返回类型为 FormValue 的泛型定义。[#26791](https://github.com/ant-design/ant-design/pull/26791)
- 国际化
  - 🇧🇾 新增白俄罗斯语支持。[#27028](https://github.com/ant-design/ant-design/pull/27028) [@StIvan8](https://github.com/StIvan8)
  - 🇯🇵 调整日语国际化文案。[#27043](https://github.com/ant-design/ant-design/pull/27043) [@iorikingdom](https://github.com/iorikingdom)
  - 🇵🇱 补充 Table 波兰语国际化文案。[#26913](https://github.com/ant-design/ant-design/pull/26913) [@daczczcz1](https://github.com/daczczcz1)
  - 🇹🇷 补充土耳其语可选文案。[#27017](https://github.com/ant-design/ant-design/pull/27017) [@alperTunca](https://github.com/alperTunca)
  - 🇹🇭 补充 DatePicker 的泰语国际化文案。[#26993](https://github.com/ant-design/ant-design/pull/26993) [@anawinwz](https://github.com/anawinwz)

## 4.6.6

`2020-09-27`

- 🐞 修复 Steps 在小屏幕下第一项偏移的问题。[#26894](https://github.com/ant-design/ant-design/pull/26894)
- 💄 修复 Divider 在有文字时，设置边框颜色无效的问题。[#26863](https://github.com/ant-design/ant-design/pull/26863)
- 🐞 修复 Radio.Button 错误校验高亮样式的问题。[#26849](https://github.com/ant-design/ant-design/pull/26849) [@dhorelik](https://github.com/dhorelik)
- 💄 修复 Typography 链接下划线样式。[#26854](https://github.com/ant-design/ant-design/pull/26854) [@vineetvk01](https://github.com/vineetvk01)
- 国际化
  - 🌐 添加泰语支持。[#26906](https://github.com/ant-design/ant-design/pull/26906) [@anawinwz](https://github.com/anawinwz)
- TypeScript
  - 🤖 修复 message.destroy 参数类型错误。[#26864](https://github.com/ant-design/ant-design/pull/26864) [@lihqi](https://github.com/lihqi)
  - 🤖 优化 Slider 类型定义。[#26884](https://github.com/ant-design/ant-design/pull/26884)
  - 🤖 导出 Form 中的 `FormListProps` 类型。[#26831](https://github.com/ant-design/ant-design/pull/26831) [@mgcrea](https://github.com/mgcrea)

## 4.6.5

`2020-09-20`

- 💄 修复 Descriptions 长文本溢出的样式问题。[#26820](https://github.com/ant-design/ant-design/pull/26820)
- 🐞 修复 Menu 子菜单展开/收起时会出现滚动条的问题。[#26817](https://github.com/ant-design/ant-design/pull/26817)
- 🐞 修复 `@layout-sider-background` 变量不能设置为渐变色的问题。[#26810](https://github.com/ant-design/ant-design/pull/26810)
- 🐞 修复 Select 搜索时输入第一个字符后中文输入法状态丢失的问题。[#26796](https://github.com/ant-design/ant-design/pull/26796)
- 🐞 修复 Table `@table-sticky-zindex` less 报错问题。[#26800](https://github.com/ant-design/ant-design/pull/26800) [@chimp1nski](https://github.com/chimp1nski)
- Button
  - 💄 修复 Button 只有图标时的对齐问题。[#26785](https://github.com/ant-design/ant-design/pull/26785)
  - 🐞 修复 Button 和 react-router 一起使用时抛出 `Invalid value for prop navigate` 的问题。[#26740](https://github.com/ant-design/ant-design/pull/26740) [@knobo](https://github.com/knobo)
- 💄 修复 TimePicker 选择框 hover 时文字内容左移的问题，并新增 `@picker-time-panel-column-width` 和 `@picker-time-panel-column-height` less 变量。[#26784](https://github.com/ant-design/ant-design/pull/26784)
- 🐞 修复 AutoComplete 使用 `placeholder` 和 `allowClear` 时抛出警告的问题。[#26765](https://github.com/ant-design/ant-design/pull/26765)
- 🐞 修复 Space 空条目会占据一格的样式问题。[#26721](https://github.com/ant-design/ant-design/pull/26721) [@knobo](https://github.com/knobo)
- 🛠 去重多版本 `rc-trigger` 以降低打包尺寸。[#26803](https://github.com/ant-design/ant-design/pull/26803)
- TypeScript
  - 🤖 Cascader 增加 `name` 和 `id` 属性。[#26660](https://github.com/ant-design/ant-design/pull/26660) [@alwaysloseall](https://github.com/alwaysloseall)

## 4.6.4

`2020-09-13`

- 💄 修复 Card 封面图片上有 1px 白边的问题。[#26659](https://github.com/ant-design/ant-design/pull/26659)
- 💄 修复 Select 的 `placeholder` 颜色与 Input 不一致的问题。[#26651](https://github.com/ant-design/ant-design/pull/26651) [@wangcch](https://github.com/wangcch)
- 🐞 修复 Menu 不支持 React.Fragment 的问题。[#26656](https://github.com/ant-design/ant-design/pull/26656)
- 🐞 修复 TextArea 设置 `value` 为 `undefined` 时和 Input 行为不一致的问题。[#26652](https://github.com/ant-design/ant-design/pull/26652)
- 🐞 修复 Motion 相关问题例如 Upload 对齐闪烁与 Form.Item 配置 `help` 的 ssr 问题。[#26628](https://github.com/ant-design/ant-design/pull/26628)
- 🐞 修复 Typography.Link 和 react-router 一起使用时抛出 `Invalid value for prop navigate` 的问题。[#26623](https://github.com/ant-design/ant-design/pull/26623)
- 🐞 修复 Table 分页器在表格上方消失的问题。[#26618](https://github.com/ant-design/ant-design/pull/26618)
- 🐞 修复 Upload 受控时同时上传多份文件会丢失部分文件的问题。[#26612](https://github.com/ant-design/ant-design/pull/26612)
- TypeScript
  - 🤖 修复 Table sorter 的 `compare` 和 `multiple` 不是可选的问题。[#26686](https://github.com/ant-design/ant-design/pull/26686)

## 4.6.3

`2020-09-06`

- 🛎 移动 props 中的 `className` 到最后。[#26602](https://github.com/ant-design/ant-design/pull/26602)
- Table
  - 💄 修复 Table 嵌套表格样式会影响所有子层级表格的问题。[#26568](https://github.com/ant-design/ant-design/pull/26568) [@willc001](https://github.com/willc001)
  - 🐞 修复 Table 上方元素 `float: right;` 后无法交互的问题。[#26599](https://github.com/ant-design/ant-design/pull/26599)
- 🐞 修复 Modal 关闭时导致滚动条向上跳动的问题。[#26538](https://github.com/ant-design/ant-design/pull/26538)
- 🐞 修复 Upload 组件中 `customRequest` 的 `onError` 的类型定义。[#26601](https://github.com/ant-design/ant-design/pull/26601) [@yingpengsha](https://github.com/yingpengsha)
- 🐞 修复 Select/TreeSelect 在 Chrome 下出现原生自动完成列表的问题。[#26590](https://github.com/ant-design/ant-design/pull/26590)
- 🐞 修复 Cascader 搜索时 value 被覆盖的情况。[#26569](https://github.com/ant-design/ant-design/pull/26569) [@lich-yoo](https://github.com/lich-yoo)
- 🐞 修复 Modal 在某些情况下溢出视窗的问题。[#25765](https://github.com/ant-design/ant-design/pull/25765) [@tanmoyopenroot](https://github.com/tanmoyopenroot)
- 🐞 修复 Radio.Group 在 legacy Form 中，不能正常工作的问题。[#26555](https://github.com/ant-design/ant-design/pull/26555) [@willc001](https://github.com/willc001)
- 🐞 修复 Pagination 切换按钮在 windows 下的对齐问题。[#26549](https://github.com/ant-design/ant-design/pull/26549)
- 🐞 修复 Form 使用 `help` 时出现的同构问题。[#26542](https://github.com/ant-design/ant-design/pull/26542)
- 🐞 修复 Avatar 在 `display: none` 时不会正确缩放 fallback 文字的问题。[#26522](https://github.com/ant-design/ant-design/pull/26522) [@zhangyu1818](https://github.com/zhangyu1818)
- TypeScript
  - 🤖 Col 增加 `ColSize` 增加 `flex` 的定义。 [#26578](https://github.com/ant-design/ant-design/pull/26578) [@blaiz](https://github.com/blaiz)
  - 🤖 修复 Tooltip/Popover `children` 定义不接受 ReactNode 的问题。[#26534](https://github.com/ant-design/ant-design/pull/26534)

## 4.6.2

`2020-08-31`

- Upload
  - 🐞 修复 Upload 在受控模式下同步更新导致的状态错误问题。[#26481](https://github.com/ant-design/ant-design/pull/26481)
  - 💄 修复 Upload 图片样式在 Form.Item 中有异常 margin 的问题。[#26367](https://github.com/ant-design/ant-design/pull/26367)
- 💄 修复 Select focus 状态样式无阴影。[#26465](https://github.com/ant-design/ant-design/pull/26465) [@Rainy](https://github.com/Rainy)
- Table
  - 🐞 修复 Table Pagination 展示于上侧且没有数据时不消失的问题。[#26143](https://github.com/ant-design/ant-design/pull/26143) [@zhangchen915](https://github.com/zhangchen915)
  - 💄 修复 Table 展开图标在 `@font-size-base` 为 `12px` 时样式错位的问题。[#26409](https://github.com/ant-design/ant-design/pull/26409)
- Space
  - 🐞 修复 Space 不支持 React.Fragment 的问题。[#26444](https://github.com/ant-design/ant-design/pull/26444)
  - 🐞 修复 Space 在 `children` 中包含空节点时会出现空 dom 的问题。[#26389](https://github.com/ant-design/ant-design/pull/26389)
- 🐞 修复 Badge 在 `status` 或 `color` 为空时不展示。[#26375](https://github.com/ant-design/ant-design/pull/26375) [@zhangchen915](https://github.com/zhangchen915)
- 💄 修复 Tree `draggable` 切换时样式 transition 变化的问题。[#26387](https://github.com/ant-design/ant-design/pull/26387)
- 🐞 修复使用主题有时会报 `colorPalette is not defined` 的问题。[#26395](https://github.com/ant-design/ant-design/pull/26395)
- TypeScript
  - 🐞 修复 TimePicker.RangePicker 定义需要 `picker` 的问题。[#26446](https://github.com/ant-design/ant-design/pull/26446)
  - 🐞 Upload 组件 `showUploadList` 类型添加 `removeIcon` 和 `downloadIcon` 属性声明。[#26406](https://github.com/ant-design/ant-design/pull/26406) [@bencallaway](https://github.com/bencallaway)
- RTL
  - 🐞 修复 Col RTL 样式。[#26479](https://github.com/ant-design/ant-design/pull/26479) [#26482](https://github.com/ant-design/ant-design/pull/26482) [@TrueMoein](https://github.com/TrueMoein)

## 4.6.1

`2020-08-24`

- TypeScript
  - 🐞 修复 Upload 类型声明丢失 `children` 的问题。[#26347](https://github.com/ant-design/ant-design/pull/26347)

## 4.6.0

`2020-08-23`

- 💄 加深默认文本 `@text-color` 以满足 WCAG 2.0 对比度的规范。[#25630](https://github.com/ant-design/ant-design/pull/25630)
- 🔥 新增图片组件 Image。[#26296](https://github.com/ant-design/ant-design/pull/26296)
- 🔥 Table 新增 `sticky` 属性以支持固定表头和滚动条。[#25939](https://github.com/ant-design/ant-design/pull/25939)
- 🛠 用 hooks 重构 Upload。[#26196](https://github.com/ant-design/ant-design/pull/26196)
- Form
  - 🆕 Form 添加 `requiredMark` 属性以支持设置必选样式，废弃原 `hideRequiredMark`。[#26309](https://github.com/ant-design/ant-design/pull/26309)
  - 🆕 Form.List 中的 `add` 方法支持第二个 `index` 参数。[#26081](https://github.com/ant-design/ant-design/pull/26081)
- 🆕 虚拟滚动支持无闪动滚动，修复 Select/TreeSelect 滚动时列表空白的问题。[#26306](https://github.com/ant-design/ant-design/pull/26306)
- Typography
  - 🆕 新增 Typography.Text `success` 类型。[#26145](https://github.com/ant-design/ant-design/pull/26145) [@llwslc](https://github.com/llwslc)
  - 🆕 Typography `copyable` 支持隐藏提示，`editable` 支持设置图标与提示。[#25953](https://github.com/ant-design/ant-design/pull/25953) [@llwslc](https://github.com/llwslc)
  - 🆕 新增 Typography.Title 5 级标题。[#25861](https://github.com/ant-design/ant-design/pull/25861)
  - 🆕 Typography 的 `editable` 配置中增加了 `maxLength` 和 `autoSize` 属性。[#25373](https://github.com/ant-design/ant-design/pull/25373) [@CornerSkyless](https://github.com/CornerSkyless)
- 🐞 修复 Transfer 搜索空格时 `filterOption` 没有触发的问题。[#26335](https://github.com/ant-design/ant-design/pull/26335)
- Progress
  - 🐞 修复 Progress `steps` 属性对于 `trailColor` 不生效的问题。[#26323](https://github.com/ant-design/ant-design/pull/26323)
  - 🐞 修复 Progress 当 `type="circle"` 时 `success.percent` 不生效的问题。[#26307](https://github.com/ant-design/ant-design/pull/26307)
- 🐞 修复 Textarea 当 `value` 为 `undefined` 时未显示 `defaultValue` 问题。[#26327](https://github.com/ant-design/ant-design/pull/26327)
- Cascader
  - 🐞 修复 Cascader 在按下 ESC 键，然后通过输入进行搜索时 `options` 不展开的问题。[#26271](https://github.com/ant-design/ant-design/pull/26271) [@flyerH](https://github.com/flyerH)
  - 💄 优化 Cascader 清除动画效果。[#26186](https://github.com/ant-design/ant-design/pull/26186)
- 🗑 移除遗留的 Button.Group 支持，请使用 Space 代替。[#26260](https://github.com/ant-design/ant-design/pull/26260)
- Select
  - 🆕 Select 支持 `onClear` 属性。[#25907](https://github.com/ant-design/ant-design/pull/25907)
  - 🐞 修复 Select `mode="tags"` 搜索显示两条重复条目的问题。[#25907](https://github.com/ant-design/ant-design/pull/25907)
  - 🐞 修复 Select 聚焦时被禁用的样式异常问题。[#26255](https://github.com/ant-design/ant-design/pull/26255)
  - 🐞 修复多选模式的 Select 在 `showArrow` 时图标重叠问题。[#26168](https://github.com/ant-design/ant-design/pull/26168) [@zhangchen915](https://github.com/zhangchen915)
- DatePicker
  - 🐞 修复 `picker` 属性改变时渲染面板不会改变的问题。[#26093](https://github.com/ant-design/ant-design/issues/26093)
  - 🐞 修复 RangePicker 点击清除按钮面板不会关闭的问题。[#26188](https://github.com/ant-design/ant-design/issues/26188)
- 🐞 修复 Pagination 字体相关样式问题。[#26230](https://github.com/ant-design/ant-design/pull/26230) [@albertms10](https://github.com/albertms10)
- 🐞 修复 Space `children` 有时会重新渲染的问题。[#26219](https://github.com/ant-design/ant-design/pull/26219)
- Badge
  - 💄 新增 `@badge-color` less 变量。[#26159](https://github.com/ant-design/ant-design/pull/26159)
  - 🆕 Badge 新增 `size` 属性用于设置大小。[#25851](https://github.com/ant-design/ant-design/pull/25851) [@moonrailgun](https://github.com/moonrailgun)
- 🆕 Tabs 可自定义 `tabBarExtraContent` 的渲染位置。[#25138](https://github.com/ant-design/ant-design/pull/25138) [@jesse3mh9a](https://github.com/jesse3mh9a)
- 💄 优化 Descriptions 在内容比较多时的显示效果。[#25903](https://github.com/ant-design/ant-design/pull/25903)
- 🆕 message 支持通过 `message.desctroy(key)` 销毁。[#26052](https://github.com/ant-design/ant-design/pull/26052) [@lihqi](https://github.com/lihqi)
- 💄 调整 InputNumber 操作栏在 `readOnly` 时为隐藏。[#25998](https://github.com/ant-design/ant-design/pull/25998)
- 国际化
  - 🌐 添加加利西亚语支持。[#26015](https://github.com/ant-design/ant-design/pull/26015) [@barreeeiroo](https://github.com/barreeeiroo)
  - 🇱🇹 添加立陶宛语支持。[#26312](https://github.com/ant-design/ant-design/pull/26312) [@mslotvinskij](https://github.com/mslotvinskij)
  - 🌐 新增 `kmr_IQ` 语言包用以代替 ku_IQ。[#26030](https://github.com/ant-design/ant-design/pull/26030)
- RTL
  - 💄 优化 Tree RTL 模式下连接线的样式。[#26205](https://github.com/ant-design/ant-design/pull/26205)
  - 💄 优化 Dropdown RTL 写法避免暗黑模式样式覆盖。[#26206](https://github.com/ant-design/ant-design/pull/26206)
- TypeScript
  - 🤖 修复 Form.Item `initialValue` 定义丢失问题。[#26292](https://github.com/ant-design/ant-design/pull/26292) [@miaoyuxinbaby](https://github.com/miaoyuxinbaby)
  - 🤖 Form 支持泛型。[#25937](https://github.com/ant-design/ant-design/pull/25937)

## 4.5.4

`2020-08-12`

- 🐞 修复 Form.Item 在 `hidden` 时引用 less 样式时失效的问题。[#26152](https://github.com/ant-design/ant-design/pull/26152)
- 🐞 修复 Dropdown `overlay` 为 string 时渲染错误的问题。[#26135](https://github.com/ant-design/ant-design/pull/26135)
- 🐞 修复 Table 删除最后一页的最后一条记录时分页消失的问题。[#26133](https://github.com/ant-design/ant-design/pull/26133) [@QoVoQ](https://github.com/QoVoQ)
- Tree
  - 🐞 修复 Tree.DirectoryTree 不能通过 `ref` 调用 `scrollTo` 的问题。[#26129](https://github.com/ant-design/ant-design/pull/26129)
  - 🐞 修复 Tree 开启 `showLine` 时顶级节点间缺少连接线的问题。[#25991](https://github.com/ant-design/ant-design/pull/25991) [@zhangchen915](https://github.com/zhangchen915)
- 💄 新增 `@badge-color` less 变量。[#26159](https://github.com/ant-design/ant-design/pull/26159)
- RTL
  - 🐞 修复 Input.Search 在 RTL 模式下的边框样式。[#26156](https://github.com/ant-design/ant-design/pull/26156)
  - 🐞 修复 Input 在 RTL 模式下 `addonBefore` 的样式问题。[#26153](https://github.com/ant-design/ant-design/pull/26153)
  - 🐞 修复 DatePicker 在 RTL 模式下的多个样式问题。[#26149](https://github.com/ant-design/ant-design/pull/26149) [#26157](https://github.com/ant-design/ant-design/pull/26157) [#26158](https://github.com/ant-design/ant-design/pull/26158)
- TypeScript
  - 🐞 修复 Slider `handleStyle` 和 `trackStyle` 属性的类型定义。[#26160](https://github.com/ant-design/ant-design/pull/26160)

## 4.5.3

`2020-08-08`

- Menu
  - 🐞 修复水平 Menu 黑暗 `theme` 在暗黑主题下的样式。[#26062](https://github.com/ant-design/ant-design/pull/26062)
  - 🐞 修复水平方向 Menu 在暗黑主题 RTL 模式下的位置。[#26032](https://github.com/ant-design/ant-design/pull/26032)
- Table
  - 🐞 修复 Table `dataSource` 中含有非法数值时会报错的问题。[#26042](https://github.com/ant-design/ant-design/pull/26042)
  - 🐞 修复 Table 空筛选项在控制台抛出 warning 的问题。[#26001](https://github.com/ant-design/ant-design/pull/26001)
- Form
  - 🐞 修复 Form.Item `hidden` 不能和 `noStyle` 一同使用的问题。[#26020](https://github.com/ant-design/ant-design/pull/26020)
  - 💄 修复 Form 紧凑模式下表单项 margin 计算错误。[#26069](https://github.com/ant-design/ant-design/pull/26069)
- Transfer
  - 🐞 修复 Transfer 禁用时分页未禁用的问题。[#26009](https://github.com/ant-design/ant-design/pull/26009)
  - 🐞 修复 Transfer 禁用时头部下拉按钮的鼠标样式。[#26005](https://github.com/ant-design/ant-design/pull/26005)
- Cascader
  - 🐞 修复 Cascader 在 Firefox 下文本和箭头重叠的问题。[#26011](https://github.com/ant-design/ant-design/pull/26011)
  - 💄 Cascader 的选择器箭头不再旋转。[#26078](https://github.com/ant-design/ant-design/pull/26078) [@07akioni](https://github.com/07akioni)
  - 🐞 修复 Cascader 禁用时鼠标悬浮边框颜色异常的问题。[#25970](https://github.com/ant-design/ant-design/pull/25970)
- Select
  - 💄 优化 Select 多选模式 `disabled` 样式。[#25980](https://github.com/ant-design/ant-design/pull/25980)
  - 🐞 修复 Select 禁用时自定义图标的鼠标样式。[#26002](https://github.com/ant-design/ant-design/pull/26002)
- 🐞 修复 Breadcrumb.Item 封装后丢失分隔符的问题。[#25984](https://github.com/ant-design/ant-design/pull/25984) [@flyerH](https://github.com/flyerH)
- 🐞 修复 Avatar.Group key 缺失的问题。[#26098](https://github.com/ant-design/ant-design/pull/26098)
- 💄 调整 Mentions `readOnly` 鼠标样式为原生样式。[#25977](https://github.com/ant-design/ant-design/pull/25977)
- 💄 新增 `@btn-line-height` 变量。[#26014](https://github.com/ant-design/ant-design/pull/26014)
- 💄 优化 Pagination 简洁分页禁用样式。[#26008](https://github.com/ant-design/ant-design/pull/26008)
- 🐞 修复 Modal `useModal` 丢失样式的问题。[#25967](https://github.com/ant-design/ant-design/pull/25967)
- 🐞 修复 InputNumber 暗黑主题下操作栏背景色。[#26072](https://github.com/ant-design/ant-design/pull/26072)
- 🐞 修复 Steps 使用 `progress` 时的 RTL 样式问题。[#26075](https://github.com/ant-design/ant-design/pull/26075)
- 🌐 改进阿拉伯语 Arabic 的国际化。[#26094](https://github.com/ant-design/ant-design/pull/26094) [@Mohelm97](https://github.com/Mohelm97)
- 🌐 改进法语 fr_FR 国际化。[#26034](https://github.com/ant-design/ant-design/pull/26034) [@Thanaen](https://github.com/Thanaen)

## 4.5.2

`2020-08-02`

- 🐞 修复 Slider `tooltip` 显隐异常的问题。[#25945](https://github.com/ant-design/ant-design/pull/25945) [@lihqi](https://github.com/lihqi)
- 🐞 修复 Divider 暗黑模式下分割线颜色。[#25922](https://github.com/ant-design/ant-design/pull/25922)
- 🐞 修正 Radio.Button 在 `disabled` 和 `checked` 状态下的文字颜色。[#25911](https://github.com/ant-design/ant-design/pull/25911)
- 🐞 修复 Carousel 内子节点高度和容器相差几个像素的问题。[#25906](https://github.com/ant-design/ant-design/pull/25906)
- 🐞 修复 Table `indentSize` 设置为 `0` 无效的问题。[#25890](https://github.com/ant-design/ant-design/pull/25890) [@OmriGM](https://github.com/OmriGM)
- 🐞 修复 List `actions` 不必要的 `cursor: pointer` 样式。[#25961](https://github.com/ant-design/ant-design/pull/25961)
- 🇷🇺 补充俄罗斯语本地化文案。[#25958](https://github.com/ant-design/ant-design/pull/25958) [@addictional](https://github.com/addictional)
- RTL
  - 🐞 修复嵌套 Table 在其他主题下的 RTL 样式。[#25938](https://github.com/ant-design/ant-design/pull/25938)
  - 🐞 修复 Tabs `card` 类型的 RTL 样式。[#25936](https://github.com/ant-design/ant-design/pull/25936)
  - 🐞 修复垂直方向 Slider 在 RTL 模式下默认的 `tooltipPlacement`。[#25909](https://github.com/ant-design/ant-design/pull/25909)

## 4.5.1

`2020-07-28`

- 🐞 修复 Badge 样式导致构建出错的问题。[#25863](https://github.com/ant-design/ant-design/pull/25863)
- 🐞 修复 Menu 在 `horizontal` `dark` 状态下 Menu.Item 背景样式出错。[#25850](https://github.com/ant-design/ant-design/pull/25850)
- 💄 优化 Divider 颜色在非白底背景上的表现。[#25855](https://github.com/ant-design/ant-design/pull/25855)
- 💄 移除多选 Select 选项的动画效果使交互更流畅。[#25852](https://github.com/ant-design/ant-design/pull/25852)
- TypeScript
  - 导出 Form `FormList` 接口。[#25849](https://github.com/ant-design/ant-design/pull/25849)

## 4.5.0

`2020-07-28`

- 🆕 Input 和 Input.TextArea 支持 `bordered` 属性。[#25617](https://github.com/ant-design/ant-design/pull/25617)
- 🆕 Message 新增 `useMessage` hook，以支持 `context` 访问。[#25422](https://github.com/ant-design/ant-design/pull/25422)
- 🆕 Tree 添加 `titleRender` 以支持定制所有节点内容。[#25624](https://github.com/ant-design/ant-design/pull/25624)
- 🆕 Descriptions 新增 `extra` 属性。[#25512](https://github.com/ant-design/ant-design/pull/25512) [@zzz111](https://github.com/zzz111)
- 🆕 新增 `Modal.config` 用于全局配置 Modal 静态方法的 `rootPrefixCls`。[#25613](https://github.com/ant-design/ant-design/pull/25613)
- 🆕 Drawer 增加 `push` 属性用于自定义多层级 Drawer 之间的联动。[#25445](https://github.com/ant-design/ant-design/pull/25445) [@jinxin0112](https://github.com/jinxin0112)
- 🆕 新增 Badge.Ribbon 缎带组件。[#25456](https://github.com/ant-design/ant-design/pull/25456)
- 🆕 Steps 新增 `percent` 属性来展示步骤图标的进度。[#25839](https://github.com/ant-design/ant-design/pull/25839)
- 💄 **Menu.Item 水平模式的蓝色指示线和下拉菜单宽度现在和其文字内容宽度一致。**[#25622](https://github.com/ant-design/ant-design/pull/25622)
- Avatar
  - 🆕 新增 Avatar.Group 用于展现一组头像集合。[#25192](https://github.com/ant-design/ant-design/pull/25192)
  - 🐞 修复 Avatar `src` 图片地址失效时没有正确 fallback 的问题。[#25806](https://github.com/ant-design/ant-design/pull/25806)
- DatePicker
  - 🆕 DatePicker 支持 [date-fns](https://date-fns.org/) 日期库。[#25822](https://github.com/ant-design/ant-design/pull/25822) [@fireairforce](https://github.com/fireairforce)
  - 🆕 提升日期组件悬停体验，当悬停在某个日期上时占位符将变为对应的日期格式化后的值。([#25050](https://github.com/ant-design/ant-design/issues/25050))。[#25784](https://github.com/ant-design/ant-design/pull/25784) [@Kermit-Xuan](https://github.com/Kermit-Xuan)
  - 🆕 RangePicker `onCalendarChange` 参数中增加 `range` 用于指示当前触发面板。[#25568](https://github.com/ant-design/ant-design/pull/25568) [@Kim-Wing-Fung](https://github.com/Kim-Wing-Fung)
  - 🆕 DatePicker 支持 `panelRender` 以自定义渲染面板。[#25488](https://github.com/ant-design/ant-design/pull/25488)
  - 🐞 修复 QuarterPicker 无法使用的问题，同时更新官网示例将 XxxPicker 调整为 `picker='xxx'`，这是 v4 更推荐的写法。[#25768](https://github.com/ant-design/ant-design/pull/25768)
- Form
  - 🆕 Form.List 中的 `remove` 方法支持数组类型。[#25638](https://github.com/ant-design/ant-design/pull/25638) [@fireairforce](https://github.com/fireairforce)
  - 🆕 Form.Item 在 `children` 形为 `render props` 时支持使用 `dependencies` 控制更新逻辑。[#25408](https://github.com/ant-design/ant-design/pull/25408)
  - 🆕 调整 Form.Item `validateFirst` 属性为依次执行校验，原并行逻辑改由配置 `parallel` 开启。[#25321](https://github.com/ant-design/ant-design/pull/25321)
  - 🐞 修复 Form.Item 有时候没有清理之前的错误信息的问题。[#25737](https://github.com/ant-design/ant-design/pull/25737)
  - 🐞 修复 Form.Item 在子 Form.Item 设置 `noStyle` 并校验失败时没有更新 `validateStatus` 的问题。[#25734](https://github.com/ant-design/ant-design/pull/25734)
  - 🐞 修复 Form 垂直布局时 Form.Item 设置 `labelCol={{ offset: number }}` 不生效的问题。[#25713](https://github.com/ant-design/ant-design/pull/25713) [@zhangchen915](https://github.com/zhangchen915)
  - ⌨️ Form 错误信息节点增加属性 `role="alert"` 以增强可访问性。[#25735](https://github.com/ant-design/ant-design/pull/25735) [@AlbertAZ1992](https://github.com/AlbertAZ1992)
- Calendar
  - 🐞 修复 Calendar 组件的 `validRange` 导致 `disabledDate` 不生效。[#25626](https://github.com/ant-design/ant-design/pull/25626) [@zhangchen915](https://github.com/zhangchen915)
  - 🐞 修复 Calendar `validRange` 对月份下拉菜单不生效的问题。[#25626](https://github.com/ant-design/ant-design/pull/25626) [@zhangchen915](https://github.com/zhangchen915)
- 🐞 修复 Table `getCheckboxProps` 返回的 `indeterminate` 不生效。[#25649](https://github.com/ant-design/ant-design/pull/25649)
- 🐞 修复 Select 清除按钮在 Form.Item 下位置不对的问题。[#25728](https://github.com/ant-design/ant-design/pull/25728)
- 🐞 修复 Pagination 翻页按钮的鼠标样式。[#25772](https://github.com/ant-design/ant-design/pull/25772)
- 🐞 修复 TreeSelect `treeNodeLabelProp` 会影响树节点展示内容的问题。[#25755](https://github.com/ant-design/ant-design/pull/25755)
- 🐞 修复 Carousel 在 React 严格模式下的 `findDOMNode` 废弃警告。[#25744](https://github.com/ant-design/ant-design/pull/25744)
- 🐞 修复 Radio 在 `webpack@4.44.0` SSR 构建出错的问题。[25821](https://github.com/ant-design/ant-design/pull/25821) [@Kermit-Xuan](https://github.com/Kermit-Xuan)
- 🐞 修复 Tabs 禁用时 focus & active 状态的颜色。[25827](https://github.com/ant-design/ant-design/pull/25827) [hsuanxyz](https://github.com/hsuanxyz)
- 💄 Card 操作面板颜色与主体颜色统一。[#25722](https://github.com/ant-design/ant-design/pull/25722)
- ⌨️ 提升 Alert/message/notification 组件的可访问性。[#25774](https://github.com/ant-design/ant-design/pull/25774)
- 🇭🇰 增加中文繁体（香港） zh_HK 本地化。[#25731](https://github.com/ant-design/ant-design/pull/25731) [@wuchu](https://github.com/wuchu)
- 🇩🇪 新增 Form 校验文案的德语 de_DE 本地化。[#25823](https://github.com/ant-design/ant-design/pull/25823) [@LukeTimeWalker](https://github.com/LukeTimeWalker)

## 4.4.3

`2020-07-20`

- 🐞 修复 Layout `trigger` 属性无法定制零宽触发器的问题。[#25653](https://github.com/ant-design/ant-design/pull/25653)
- 🐞 修复 Form.Item `help` 在校验失败时的样式。[#25582](https://github.com/ant-design/ant-design/pull/25582) [@zhangchen915](https://github.com/zhangchen915)
- 🐞 修复 Descriptions 在 Table `expandedRowRender` 样式异常的问题。[#25593](https://github.com/ant-design/ant-design/pull/25593)
- 💄 新增 `@zindex-popconfirm: 1060` less 变量，并将 `@zindex-tooltip` 提升为 `1070`。[#25693](https://github.com/ant-design/ant-design/pull/25693)
- 🛠 更新 `react-slick` 依赖优化包大小。[#25599](https://github.com/ant-design/ant-design/pull/25599)
- 🌐 改进加泰罗尼亚语 ca_ES 国际化。[#25583](https://github.com/ant-design/ant-design/pull/25583) [@albertms10](https://github.com/albertms10)
- 🇸🇦 改进阿拉伯语 ar_EG 国际化。[#25587](https://github.com/ant-design/ant-design/pull/25587) [@amir5000](https://github.com/amir5000)
- TypeScript
  - 🐞 修复 Upload `customRequest` 的 File 定义。[#25598](https://github.com/ant-design/ant-design/pull/25598) [@AlbertAZ1992](https://github.com/AlbertAZ1992)

## 4.4.2

`2020-07-11`

- 🛠 调整 Alert 组件关闭动画实现移除直接的 dom 操作。[#dd8e9f8](https://github.com/ant-design/ant-design/commit/dd8e9f8) [@Yunfly](https://github.com/Yunfly)
- Select
  - 🐞 修正了 Select 在搜索时纵向位移的问题。[#25536](https://github.com/ant-design/ant-design/pull/25536)
  - 💄 增加 `@select-item-selected-color` 以控制 Select 选项选中时的颜色。[#25476](https://github.com/ant-design/ant-design/pull/25476)
- 🐞 修复 Form.Item 警告 `preserve` 是无效 dom 属性的问题。[#25518](https://github.com/ant-design/ant-design/pull/25518)
- 🐞 修复当 Card 组件无边框时封面图边距的问题。[#25515](https://github.com/ant-design/ant-design/pull/25515) [@yutingzhao1991](https://github.com/yutingzhao1991)
- 💄 调整 Typography 样式添加 `overflow-wrap: break-word` 默认样式。[#25516](https://github.com/ant-design/ant-design/pull/25516)
- 🐞 修复 Table `expandedRowRender` 内嵌 Table 时单元格背景丢失的问题。[#25498](https://github.com/ant-design/ant-design/pull/25498)
- 🐞 修复 Radio.Button 上使用 Popover 时的位置异常问题。[#25449](https://github.com/ant-design/ant-design/pull/25449) [@zgoby](https://github.com/zgoby)
- 🐞 修复 RangePicker 在 `size=small` 时清除按钮的位置问题。[#25458](https://github.com/ant-design/ant-design/pull/25458)
- 🆕 Upload 支持上传非图片文件时在 `onChange` 事件中设置 `thumbUrl` 来展示缩略图。[#25432](https://github.com/ant-design/ant-design/pull/25432) [@AlbertAZ1992](https://github.com/AlbertAZ1992)
- 🐞 修复 Table 切换页条目数时 `onChange` 触发多次的问题。[#25520](https://github.com/ant-design/ant-design/pull/25520) [@zhangchen915](https://github.com/zhangchen915)
- 🛠 移除 `babel-runtime` 并添加 `@babel/runtime` 依赖，减少 gzipped 包体积 `18.6KB`。[#25530](https://github.com/ant-design/ant-design/pull/25530)
- 🇪🇸 改进 es_ES 国际化。[#25460](https://github.com/ant-design/ant-design/pull/25460) [@gersongams](https://github.com/gersongams)

## 4.4.1

`2020-07-06`

- Menu
  - 🐞 修复 Menu.Item 中内嵌的 `a` 标签颜色样式问题。[#25414](https://github.com/ant-design/ant-design/pull/25414) [@kaysonwu](https://github.com/kaysonwu)
  - 🐞 修复 Menu 内嵌菜单动画不正确问题。[#25341](https://github.com/ant-design/ant-design/pull/25341)
  - 💄 优化 Menu 菜单收缩动画。[#25301](https://github.com/ant-design/ant-design/pull/25301)
- 🐞 修复 Input 在禁用状态下背景颜色被 `error` 或 `warning` 的 Form.Item 覆盖的问题。[#25385](https://github.com/ant-design/ant-design/pull/25385)
- 🐞 修复 Table 固定列头最右侧的多余边框样式。[#25378](https://github.com/ant-design/ant-design/pull/25378)
- 🐞 修复 Grid 响应式监听函数没有正确销毁的问题。[#25319](https://github.com/ant-design/ant-design/pull/25319) [@zhangchen915](https://github.com/zhangchen915)
- 🐞 修复 Progress `successPercent` 警告信息修复 Progress `success.progress` 为 `success.percent`。[#25356](https://github.com/ant-design/ant-design/pull/25356) [@fireairforce](https://github.com/fireairforce)
- 🐞 修复 PageHeader 内 Tabs 不必要的 `margin-bottom`。[#25340](https://github.com/ant-design/ant-design/pull/25340) [@dickeylth](https://github.com/dickeylth)
- Form
  - 🐞 修复 Form.Item `hidden` 属性不生效的问题。[#25336](https://github.com/ant-design/ant-design/pull/25336)
  - 🐞 修复 Form.Item 在 `display: none` 的容器中提示信息可能不会消失的问题。[#25297](https://github.com/ant-design/ant-design/pull/25297)
- Radio
  - 🐞 修复 Radio.Group 报错 `Function components cannot be given refs` 的问题。[#25328](https://github.com/ant-design/ant-design/pull/25328)
  - 🐞 修复 Radio.Group 中 `children` 使用空格出现的样式异常问题。[#25304](https://github.com/ant-design/ant-design/pull/25304) [@ElderJames](https://github.com/ElderJames)
- 🐞 修复 Drawer 点击遮罩可能会触发多次关闭事件的问题。[#25313](https://github.com/ant-design/ant-design/pull/25313)
- 🐞 修复 Skeleton 中 Button/Avatar/Input/Image 默认宽度为 auto。[#25303](https://github.com/ant-design/ant-design/pull/25303)
- 🇺🇦 更新 uk_UA 国际化。[#25402](https://github.com/ant-design/ant-design/pull/25402) [@kitsoRik](https://github.com/kitsoRik)
- 🇳🇴 更新 nb_NO 国际化。[#25374](https://github.com/ant-design/ant-design/pull/25374) [@Johannes-Andersen](https://github.com/Johannes-Andersen)
- TypeScript
  - 🐞 修复 Slider `onChange` 定义问题。[#25358](https://github.com/ant-design/ant-design/pull/25358) [@CornerSkyless](https://github.com/CornerSkyless)
  - 🐞 修复 Tooltip 自定义颜色类型定义。[#25315](https://github.com/ant-design/ant-design/pull/25315) [@CornerSkyless](https://github.com/CornerSkyless)

## 4.4.0

`2020-06-29`

- 🔥 优化 RangePicker 交互，现在任意面板选择完毕后，另一个面板会自动弹出。[#25135](https://github.com/ant-design/ant-design/pull/25135)
- 🔥 新增 Skeleton.Image 组件。[#24805](https://github.com/ant-design/ant-design/pull/24805) [@fireairforce](https://github.com/fireairforce)
- Form
  - 🆕 Form 实例支持 `getFieldInstance`。[#24711](https://github.com/ant-design/ant-design/pull/24711)
  - 🆕 Form.Item 新增 `hidden` 属性用于隐藏表单项。[#25108](https://github.com/ant-design/ant-design/pull/25108)
  - 🆕 Form.Item 添加 `preserve` 属性以支持字段值清理。[#25186](https://github.com/ant-design/ant-design/pull/25186)
- Table
  - 🆕 Table 添加 `rowSelection.dirty` 以支持异步数据下保留 `key`。[#24718](https://github.com/ant-design/ant-design/pull/24718)
  - 🆕 Table `onChange` 添加 `action` 参数用于标示操作类型。[#24697](https://github.com/ant-design/ant-design/pull/24697)
  - 🐞 Table 支持 `rowSelection.checkStrictly`，现在父子节点选择状态可以关联了。[#24931](https://github.com/ant-design/ant-design/pull/24931)
  - 🐞 修复 Table `onSelectAll` 的 `changeRows` 参数不正确的问题。[#24931](https://github.com/ant-design/ant-design/pull/24931)
  - 🐞 修复 Table 树形数据叶节点行的展开按钮仍能被点击的问题。[#24931](https://github.com/ant-design/ant-design/pull/24931)
  - 🐞 修复 Table 展开图标隐藏时仍然有鼠标手型的问题。[#25170](https://github.com/ant-design/ant-design/pull/25170)
- TimePicker
  - 🐞 修复 TimePicker 面板 12 AM 显示为 0 AM 的问题。[#25174](https://github.com/ant-design/ant-design/pull/25174)
  - 🐞 修复 TimePicker 在 use12Hours 时没有用 0 ～ 23 来禁用小时的问题。[#25174](https://github.com/ant-design/ant-design/pull/25174)
  - 🐞 修复 TimePicker 没有根据小时禁用情况禁用 AM PM 的问题。[#25174](https://github.com/ant-design/ant-design/pull/25174)
  - 🐞 修复 TimePicker `Now` 按钮没有和 `hour|minute|second|step` 保持一致的问题。[#25174](https://github.com/ant-design/ant-design/pull/25174)
- Cascader
  - 🆕 Cascader 新增 `expandIcon` 来自定义次级菜单展开图标。[#24865](https://github.com/ant-design/ant-design/pull/24865)
  - 🆕 Cascader 增加 `dropdownRender` 属性用于扩展菜单。[#24812](https://github.com/ant-design/ant-design/pull/24812)
- Menu
  - 🆕 Menu 增加 `triggerSubMenuAction` 属性以支持配置菜单弹出的交互方式。[#25127](https://github.com/ant-design/ant-design/pull/25127) [@hydRAnger](https://github.com/hydRAnger)
  - 🐞 修复 Menu `theme="dark"` 时子菜单背景色为白色的问题。[#25205](https://github.com/ant-design/ant-design/pull/25205)
- Tabs
  - 🆕 Tabs 支持 `addIcon` 以自定义添加图标。[#25006](https://github.com/ant-design/ant-design/pull/25006)
  - 🐞 修复 Tabs 在 IE11 下无法关闭的问题。[#25200](https://github.com/ant-design/ant-design/pull/25200)
- Pagination
  - 🆕 Pagination 支持当 `pageSize` 改变时，`onChange` 的调用。[#24964](https://github.com/ant-design/ant-design/pull/24964) [@fireairforce](https://github.com/fireairforce)
  - 🐞 优化 Pagination 可访问性，修复一个 W3C 属性错误。[#25119](https://github.com/ant-design/ant-design/pull/25119)
- DatePicker
  - 🐞 修复 DatePicker 组件的月份和季度前后选择器 icon 的大小。[#25035](https://github.com/ant-design/ant-design/pull/25035) [@fireairforce](https://github.com/fireairforce)
  - 🆕 TimePicker 支持 `showNow` 属性。[#25032](https://github.com/ant-design/ant-design/pull/25032)
- Drawer
  - 🆕 Drawer 支持 `closeIcon` 属性。[#24842](https://github.com/ant-design/ant-design/pull/#24842)
  - 🐞 修复 Drawer 使用 `getContainer={false}` 时可能导致页面滚动条消失的问题。[#25273](https://github.com/ant-design/ant-design/pull/25273)
- 🆕 Rate `character` 支持通过 `(RateProps) => ReactNode` 自定义。[#24903](https://github.com/ant-design/ant-design/pull/24903)
- 💄 移除了垂直点状 Steps.Step 的 140px 宽度限制。[#24907](https://github.com/ant-design/ant-design/pull/24907)
- 🆕 Menution 新增 `autoSize` 属性以支持高度自适应。[#24961](https://github.com/ant-design/ant-design/pull/24961) [@Kermit-Xuan](https://github.com/Kermit-Xuan)
- 🆕 调整 Result `children` 显示位置到组件尾部。[#24945](https://github.com/ant-design/ant-design/pull/24945)
- 🆕 Radio.Group 新增 `optionType` 来设置 `options` 的 Radio 类型。[#24809](https://github.com/ant-design/ant-design/pull/24809)
- 🆕 Tag 新增 `closeIcon` 用以自定义关闭按钮。[#24885](https://github.com/ant-design/ant-design/pull/24885)
- 🆕 Dropdown 组件支持下拉框箭头。[#23869](https://github.com/ant-design/ant-design/pull/23869) [@wendellhu95](https://github.com/wendellhu95)
- 🆕 Collapse 增加了 `ghost` 属性来设置透明背景。[#24734](https://github.com/ant-design/ant-design/pull/24734)
- 🆕 Progress 组件支持自定义已完成进度条颜色。[#24655](https://github.com/ant-design/ant-design/pull/24655) [@fireairforce](https://github.com/fireairforce)
- 🆕 Typography copyable 属性支持 `icon` 和 `tooltips` 用于自定义图标和提示文案。[#25274](https://github.com/ant-design/ant-design/pull/25274) [@israelKusayev](https://github.com/israelKusayev)
- 🆕 Tree `showLine` 属性支持配置隐藏叶节点图标。[#25271](https://github.com/ant-design/ant-design/pull/25271)
- 🆕 BackTop 支持 `duration` 来设置回到顶部所需时间。[#25254](https://github.com/ant-design/ant-design/pull/25254)
- 🐞 修复 Select 点击下拉箭头时输入框不能获得焦点的问题。[#25212](https://github.com/ant-design/ant-design/pull/25212)
- 🐞 修复 Rate 半选时 `value` 被四舍五入的问题。[#24993](https://github.com/ant-design/ant-design/pull/24993)
- 🐞 修复 Notification 修改 `width` 时没有相对屏幕边缘对齐的问题。[#25168](https://github.com/ant-design/ant-design/pull/25168)
- 🐞 修正 InputNumber `max` 属性没有默认值的问题。[#25243](https://github.com/ant-design/ant-design/pull/25243)
- 🛠 给 Modal 组件增加了更多的 less 变量。[#24773](https://github.com/ant-design/ant-design/pull/24773) [@hicrystal](https://github.com/hicrystal)
- 💄 更快的 Switch 动画切换效果。[#25160](https://github.com/ant-design/ant-design/pull/25160)
- 🐞 修复 PageHeader 内 Tabs 多余的边框样式。[#25159](https://github.com/ant-design/ant-design/pull/25159)
- 🌐 增加了德语，意大利语和捷克语缺失的翻译。[#25233](https://github.com/ant-design/ant-design/pull/25233) [@karelsoupaEMZ](https://github.com/karelsoupaEMZ)
- 🇯🇵 增加了 Form 的日语国际化。[#25244](https://github.com/ant-design/ant-design/pull/25244) [@kentaro84207](https://github.com/kentaro84207)
- RTL
  - 🐞 修复 Table RTL 模式下的嵌套表格样式。[#25156](https://github.com/ant-design/ant-design/pull/25156)
  - 🐞 修复 Table RTL 模式下，筛选和排序的头部样式。[#25152](https://github.com/ant-design/ant-design/pull/25152)
  - 🐞 修复 InputNumber RTL 模式下输入框内显示。[#25146](https://github.com/ant-design/ant-design/pull/25146)

## 4.3.5

`2020-06-21`

- 🐞 修复 Input.Search 作为 AutoComplete 自定义组件会崩溃的问题。[#25049](https://github.com/ant-design/ant-design/pull/25049)
- 🛠 使用 hooks 重写 Input.Password。[#25012](https://github.com/ant-design/ant-design/pull/25012) [@Rustin-Liu](https://github.com/Rustin-Liu)
- 🐞 修复 PageHeader 从 `4.3.0` 后的 `tabs` 样式错误。[#24991](https://github.com/ant-design/ant-design/pull/24991)
- 🐞 修复 Backtop 没有完全隐藏的问题。[#25132](https://github.com/ant-design/ant-design/pull/25132) [@jesse3mh9a](https://github.com/jesse3mh9a)
- 🐞 修复 Upload 不支持包裹 Popover 的问题。[#25090](https://github.com/ant-design/ant-design/pull/25090)
- 🐞 修复 Tabs 内容会超出容器宽度的问题。[#25072](https://github.com/ant-design/ant-design/pull/25072)
- 🐞 修复 DataPicker/TimePicker 时间下拉选对齐问题。[#25019](https://github.com/ant-design/ant-design/pull/25019)
- Table
  - 💄 优化 Table 筛选菜单为空时的 UI。[#25073](https://github.com/ant-design/ant-design/pull/25073)
  - 🐞 修复 Table 嵌套 Table 时的边框样式问题。[#24995](https://github.com/ant-design/ant-design/pull/24995)
  - 💄 缩小了 Table 筛选菜单的最大高度。[#25001](https://github.com/ant-design/ant-design/pull/25001)
- Descriptions
  - 🐞 修复 Descriptions 双击会同时选中标签和内容的问题。[#24983](https://github.com/ant-design/ant-design/pull/24983) [@harupy](https://github.com/harupy)
  - 💄 修正了 Descriptions 在 Safari 下标签文本没有左侧对齐的问题。[#25018](https://github.com/ant-design/ant-design/pull/25018)
- 💄 修正了 List.Item.Meta 内容宽度有时会溢出的问题。[#24992](https://github.com/ant-design/ant-design/pull/24992)
- 🐞 修复 Menu.SubMenu 在紧凑模式下暗黑主题的背景颜色。[#24997](https://github.com/ant-design/ant-design/pull/24997)
- ⚡️ 减少 Button `3KB` 样式打包体积。[#24996](https://github.com/ant-design/ant-design/pull/24996)
- 🇹🇷 优化土耳其语语言包。[#25100](https://github.com/ant-design/ant-design/pull/25100) [@smddzcy](https://github.com/smddzcy)
- TypeScript
  - 导出 Tree `DataNode` 定义。[#25065](https://github.com/ant-design/ant-design/pull/25065) [@jinxin0112](https://github.com/jinxin0112)

## 4.3.4

`2020-06-14`

- Form
  - 🐞 修复 Form 中配置 `validateTrigger` 无效的问题。[#24979](https://github.com/ant-design/ant-design/pull/24979)
  - 🐞 修复 Form.Item 在组件设置 `id` 时仍然会替换它的问题。[#24929](https://github.com/ant-design/ant-design/pull/24929)
  - 🐞 修复 Form.List 嵌套使用 `noStyle` 时，错误信息展示混乱的问题。[#24867](https://github.com/ant-design/ant-design/pull/24867)
- Table
  - 🐞 修复 Table 的 `shouldCellUpdate` 缺少 `prevRecord` 参数的问题。[#24963](https://github.com/ant-design/ant-design/pull/24963)
  - 🐞 修复 Table 受控状态下列的过滤菜单显示的值和 `filteredValue` 不同步的问题。[#24952](https://github.com/ant-design/ant-design/pull/24952)
  - 🐞 修复 Table 在多列排序时 `onChange` 获得错误排序状态的问题。[#24852](https://github.com/ant-design/ant-design/pull/24852)
- 🐞 修复 Modal 缺少 `confirm()` 默认图标。[#24956](https://github.com/ant-design/ant-design/pull/24956)
- 🐞 修复 List `grid` 属性在 React.Framgment 或者封装了的 List.Item 上失效的问题。[#24955](https://github.com/ant-design/ant-design/pull/24955)
- 🐞 修复 Avatar 图片加载错误的显示问题。[#24944](https://github.com/ant-design/ant-design/pull/24944) [@sosohime](https://github.com/sosohime)
- 🐞 修复 Drawer `getTargetContainer` 属性没有被忽略的问题。[#24938](https://github.com/ant-design/ant-design/pull/24938)
- 🐞 修复 Tabs 下拉框标题过长时被截断的问题。[#24928](https://github.com/ant-design/ant-design/pull/24928)
- 🐞 修复 Carousel 在 Tabs 下切换时会跳跃的问题。[#24873](https://github.com/ant-design/ant-design/pull/24873)
- 🐞 修复 Transfer 在关闭 tree shaking 后打包尺寸增加的问题。[#24847](https://github.com/ant-design/ant-design/pull/24847) [@DavidSichau](https://github.com/DavidSichau)
- 💄 新增 `@rate-star-hover-scale` 控制 Rate 鼠标悬浮放大比例。[#24917](https://github.com/ant-design/ant-design/pull/24917)
- 💄 新增 `@divider-orientation-margin` less 变量，以控制 Divider 设置了 `orientation` 时的左侧距离。[#24877](https://github.com/ant-design/ant-design/pull/24877)
- 🌐 Localization
  - 🇫🇷 改进 fr_FR 语言包。[#24962](https://github.com/ant-design/ant-design/pull/24962) [@sharkyze](https://github.com/sharkyze)
- TypeScript
  - 🛠 导出 Select 的 `OptionProps` 接口。[#24870](https://github.com/ant-design/ant-design/pull/24870) [@nitinknolder](https://github.com/nitinknolder)
  - 🛠 导出 Card 的 `CardInterface` 接口。[#24866](https://github.com/ant-design/ant-design/pull/24866) [@THPubs](https://github.com/THPubs)
  - 🛠 从 Table `TableProps` 中去除 `emptyText` 定义。[#24948](https://github.com/ant-design/ant-design/pull/24948) [@hehex9](https://github.com/hehex9)
  - 🛠 为 Upload `method` 属性添加 `patch` 类型。[#24936](https://github.com/ant-design/ant-design/pull/24936) [@miclle](https://github.com/miclle)

## 4.3.3

`2020-06-07`

- 🐞 修复 Drawer 无法显示的问题。[#24802](https://github.com/ant-design/ant-design/pull/24802)
- 🐞 修复 Menu.SubMenu 滚动区域无法交互的问题。[#24806](https://github.com/ant-design/ant-design/pull/24806)

## 4.3.2

`2020-06-06`

- 🐞 修复 Tag.CheckableTag 不支持 `onClick` 和 `stopPropagation` 的问题。[#24743](https://github.com/ant-design/ant-design/pull/24743)
- 🐞 修复 Drawer 支持通过 ConfigProvider 来全局设置 `getPrefixCls` 和 `getPopupContainer`。[#24727](https://github.com/ant-design/ant-design/pull/24727)
- 🐞 修复 Button 在父组件重新渲染时 `loading.delay` 会重复触发的问题。[#24713](https://github.com/ant-design/ant-design/pull/24713)
- 🐞 修复 Dropdown 带图标 `icon` 菜单项的链接色彩。[#24707](https://github.com/ant-design/ant-design/pull/24707) [#24702](https://github.com/ant-design/ant-design/pull/24702)
- Select
  - 🐞 修复 Select 在紧凑模式下表现不正常。[#24706](https://github.com/ant-design/ant-design/pull/24706)
  - ⚡️ 优化 Select 多选模式的性能。[#24785](https://github.com/ant-design/ant-design/pull/24785) [@Kermit-Xuan](https://github.com/Kermit-Xuan)
- 🐞 修复 Calendar 在同一个面板下选择日期也会触发 `onPanelChange` 的问题。[#24695](https://github.com/ant-design/ant-design/pull/24695)
- 🐞 修复 Input 组件在 IE11 中高度异常问题。[#24673](https://github.com/ant-design/ant-design/pull/24673) [@xiaosongxiaosong](https://github.com/xiaosongxiaosong)
- 🐞 修复 Radio 的 TypeScript 定义错误。[#24693](https://github.com/ant-design/ant-design/pull/24693) [@hengkx](https://github.com/hengkx)
- 🐞 修复 Statistic 不能包裹 Tooltip 的问题。[#24782](https://github.com/ant-design/ant-design/pull/24782)
- 🐞 修复 TimePicker.RangePicker 指定 `className` 后无边框样式失效的问题。[#24781](https://github.com/ant-design/ant-design/pull/24781)
- 🐞 修复 List 翻页时 `onChange` 不触发的问题。[#24514](https://github.com/ant-design/ant-design/pull/24514)
- 🌐 国际化
  - 🇮🇱 Form 校验文案增加希伯来语（以色列）。[#24716](https://github.com/ant-design/ant-design/pull/24716) [@israelKusayev](https://github.com/israelKusayev)
  - 🇰🇷 Form 校验文案增加韩文。[#24783](https://github.com/ant-design/ant-design/pull/24783) [@Jaewoook](https://github.com/Jaewoook)
- 💄 新增 less 变量 `@table-font-size`，`@table-font-size-md` 和 `@table-font-size-sm`，用于自定义 Table 文字大小。[#24714](https://github.com/ant-design/ant-design/pull/24714) [@morenyang](https://github.com/morenyang)
- RTL
  - 💄 优化 Tabs 标签下拉框在 RTL 模式下样式。[#24715](https://github.com/ant-design/ant-design/pull/24715)
  - 💄 增加 `Modal.method()` RTL 模式支持，仅限 hooks 用法。[#24682](https://github.com/ant-design/ant-design/pull/24682)
  - 💄 修复 Badge RTL 模式位置偏移量设置。[#24724](https://github.com/ant-design/ant-design/pull/24724)

## 4.3.1

`2020-06-02`

- Tabs
  - 🐞 修复 Tabs `hideAdd` 无效的问题。[#24621](https://github.com/ant-design/ant-design/pull/24621)
  - 🐞 修复 Tabs 下拉菜单内在 Firefox 下出现水平滚动条。[#24677](https://github.com/ant-design/ant-design/pull/24677)
  - 🐞 修复 Tabs 配合 `react-sticky` 使用时下划线遗失问题。[#24643](https://github.com/ant-design/ant-design/pull/24643)
  - 💄 调整 Tabs `tabBarStyle` 的展示样式。[#24620](https://github.com/ant-design/ant-design/pull/24620)
- Button
  - 🐞 修复 Button 将 `loading` 从 `delay` 快速切换至 `false` 时仍然会变成加载状态的问题。[#24678](https://github.com/ant-design/ant-design/pull/24678)
  - 🐞 修复 Text Button 在 `danger` 时样式不一致的问题。[#24622](https://github.com/ant-design/ant-design/pull/24622) [@morenyang](https://github.com/morenyang)
- 🐞 修复 Table 包裹在 Row 中时无法展现横向滚动条的问题。[#24661](https://github.com/ant-design/ant-design/pull/24661) [@zt123123](https://github.com/zt123123)
- 🐞 修复 Drawer 会报 dom 节点设置 `dropdownMatchSelectWidth` 的警告信息。[#24651](https://github.com/ant-design/ant-design/pull/24651)
- 🐞 调整 Steps 现支持 `children` 下使用 React.Fragment。[#24644](https://github.com/ant-design/ant-design/pull/24644)
- 🐞 解决 Upload 删除图标键盘无法导航操作的问题。[#24615](https://github.com/ant-design/ant-design/pull/24615) [@morenyang](https://github.com/morenyang)
- 🐞 修复多选 Select 输入框的光标展示问题。[#24631](https://github.com/ant-design/ant-design/pull/24631)
- 🐞 修复 Radio.Group 设置 `options` 报错的问题。[#24631](https://github.com/ant-design/ant-design/pull/24631)
- RTL
  - 💄 调整 Notification RTL 模式下默认弹窗位置为左上。[#24632](https://github.com/ant-design/ant-design/pull/24632)
- TypeScript
  - 🛠 导出 Tabs `TabPaneProps` 定义。[#24648](https://github.com/ant-design/ant-design/pull/24648)

## 4.3.0

`2020-05-31`

- 🔥 重做 Tabs 以提升多标签在不同环境下的用户体验，**DOM 结构完全重写**，请注意覆盖样式丢失的问题。[#24552](https://github.com/ant-design/ant-design/pull/24552)
- 📖 新增组件[总览页面](https://ant.design/components/overview-cn)。[#24491](https://github.com/ant-design/ant-design/pull/24491) [@arvinxx](https://github.com/arvinxx)
- 🛠 增加大量功能，同时减少了包体积（相比 `4.2.5` 减少了 2KB）。[#24584](https://github.com/ant-design/ant-design/pull/24584)
- Button
  - 🆕 新增文本类型按钮 `type="text"`。[#22552](https://github.com/ant-design/ant-design/pull/22552)
  - 💄 优化 Button 背景 less 变量的影响范围。[#24372](https://github.com/ant-design/ant-design/pull/24372) [@morenyang](https://github.com/morenyang)
- Upload
  - 🆕 `data` 属性支持返回 `Promise`。[#24546](https://github.com/ant-design/ant-design/pull/24546) [@Kermit-Xuan](https://github.com/Kermit-Xuan)
  - 🆕 添加 `progress` 属性以支持自定义进度条。[#24319](https://github.com/ant-design/ant-design/pull/24319) [@morenyang](https://github.com/morenyang)
  - 🐞 修复进度条类型会被意外覆盖的问题。[#24339](https://github.com/ant-design/ant-design/pull/24339) [@morenyang](https://github.com/morenyang)
- Table
  - 🆕 Table 新增 `rowSelection.hideSelectAll` 用于隐藏全选框。[#24592](https://github.com/ant-design/ant-design/pull/24592) [@Kermit-Xuan](https://github.com/Kermit-Xuan)
  - 🆕 `ellipsis` 支持 `showTitle` 以关闭自动设置 `title` 属性。[#24056](https://github.com/ant-design/ant-design/pull/24056) [@lijinke666](https://github.com/lijinke666)
  - 🆕 Table `columns` 支持 `shouldCellUpdate` 属性。[#23872](https://github.com/ant-design/ant-design/pull/23872)
- Input
  - 🆕 Input.Passowrd 支持自定义图标。[#23792](https://github.com/ant-design/ant-design/pull/23792)
  - 🐞 修复 Input.Password 一个明文显示 `value` 的问题。[#24535](https://github.com/ant-design/ant-design/pull/24535)
  - 💄 添加 `@input-disabled-color` less 变量。[#23775](https://github.com/ant-design/ant-design/pull/23775) [@alwaysloseall](https://github.com/alwaysloseall)
- Form
  - 🆕 Form 添加 `validateTrigger` 支持全局设置子字段校验时机。[#23972](https://github.com/ant-design/ant-design/pull/23972)
  - 🐞 修复 Form.Item 内联样式下 `label` 在狭窄空间被挤压的问题。[#24531](https://github.com/ant-design/ant-design/pull/24531)
  - 🐞 修复 Form.List 字段状态同步逻辑并添加嵌套字段示例。[#24009](https://github.com/ant-design/ant-design/pull/24009)
- Menu
  - 🆕 调整 Menu `inline` 模式下未设置 `icon` 的菜单收起时文字显示第一个字符。[#24330](https://github.com/ant-design/ant-design/pull/24330)
  - 🆕 Menu.Item 支持 `danger` 属性。[#23785](https://github.com/ant-design/ant-design/pull/23785)
- Avatar
  - 🆕 Avatar 新增 `gap` 来设置字符类型距离左右两侧边界单位像素。[#24357](https://github.com/ant-design/ant-design/pull/24357)
  - 🐞 修复 Avatar `onError` 会触发两次的问题。[#24506](https://github.com/ant-design/ant-design/pull/24506) [@sanonz](https://github.com/sanonz)
- Typography
  - 🆕 Typography.Paragraph 支持自定义展开样式。[#24385](https://github.com/ant-design/ant-design/pull/24385) [@fireairforce](https://github.com/fireairforce)
  - 🆕 Typography.Text 支持 `keyboard` 样式。[#24195](https://github.com/ant-design/ant-design/pull/24195)
  - 🆕 添加 Link 组件。[#24019](https://github.com/ant-design/ant-design/pull/24019)
  - 🐞 修复 Typography 不支持 `title` 属性的问题。[#24440](https://github.com/ant-design/ant-design/pull/24440) [@Kermit-Xuan](https://github.com/Kermit-Xuan)
- 🆕 Tooltip 支持配置背景颜色。[#23155](https://github.com/ant-design/ant-design/pull/23155)
- 🆕 Popconfirm 支持按 `ESC` 关闭。[#24420](https://github.com/ant-design/ant-design/pull/24420)
- 🆕 Tooltip `destroyTooltipOnHide` 支持 `keepParent` 配置。[#24362](https://github.com/ant-design/ant-design/pull/24362) [@Kermit-Xuan](https://github.com/Kermit-Xuan)
- 🆕 Notification 支持全局配置 `prefixCls`。[#24295](https://github.com/ant-design/ant-design/pull/24295) [@tdida](https://github.com/tdida)
- 🆕 RangePicker `dateRender` 支持额外参数来判断是 `start` 还是 `end` 字段。[#24278](https://github.com/ant-design/ant-design/pull/24278)
- 🆕 Skeleton 添加 `round` 属性，允许段落和标题显示圆角。[#24137](https://github.com/ant-design/ant-design/pull/24137) [@xilihuasi](https://github.com/xilihuasi)
- 🆕 Transfer 支持 `oneWay` 配置单向选择以及 `pagination` 配置分页。[#24041](https://github.com/ant-design/ant-design/pull/24041)
- 🆕 Message 支持自定义样式通过使用`className`和`style`。[#24024](https://github.com/ant-design/ant-design/pull/24024) [@Kermit-Xuan](https://github.com/Kermit-Xuan)
- 🆕 ConfigProvider 支持 `virtual` 和 `dropdownMatchSelectWidth` 配置。[#23841](https://github.com/ant-design/ant-design/pull/23841) [@hengkx](https://github.com/hengkx)
- 🐞 修复 Cascader 下拉框中扩展按钮在禁用时的颜色。[#24521](https://github.com/ant-design/ant-design/pull/24521)
- 🐞 修复 Alert 关闭按钮 `padding` 样式。[#24471](https://github.com/ant-design/ant-design/pull/24471)
- 🐞 修复 Tree `@tree-directory-selected-bg` 变量不生效的问题。[#24468](https://github.com/ant-design/ant-design/pull/24468) [@morenyang](https://github.com/morenyang)
- 🐞 修复 `@ant-prefix` 变量在部分样式里不生效的问题。[#24459](https://github.com/ant-design/ant-design/pull/24459) [@morenyang](https://github.com/morenyang)
- 🐞 修复 Steps `subtitle` hover 渐变过渡。[#24593](https://github.com/ant-design/ant-design/pull/24593)
- 🐞 修复 List 报 `React does not recognize colStyle prop` 的问题。[#24568](https://github.com/ant-design/ant-design/pull/24568)
- 🐞 修复步骤 Progress `percent` 样式未正确更新的问题。[#24534](https://github.com/ant-design/ant-design/pull/24534) [@ChuckJonas](https://github.com/ChuckJonas)
- 🐞 修复 Breadcrumb 内使用链接时图标间距丢失的问题。[#24490](https://github.com/ant-design/ant-design/pull/24490) [@EscapeB](https://github.com/EscapeB)
- 💄 Descriptions 新增 `@descriptions-item-trailing-colon` 等 less 变量。[#24032](https://github.com/ant-design/ant-design/pull/24032) [@hengkx](https://github.com/hengkx)
- 🌐 国际化
  - 🇮🇪 新增爱尔兰语言包。[#24609](https://github.com/ant-design/ant-design/pull/24609) [@AbhijeetGaware](https://github.com/AbhijeetGaware)
  - 🇫🇮 改进 Typography `fi_FI` 国际化。[#24591](https://github.com/ant-design/ant-design/pull/24591) [@sagge](https://github.com/sagge)
  - 🇧🇷 改进 `pt_BR` 国际化。[#24518](https://github.com/ant-design/ant-design/pull/24518) [@arturpfb](https://github.com/arturpfb)
  - 🇬🇧 改进 Form `en_GB` 国际化。[#24404](https://github.com/ant-design/ant-design/pull/24404) [@morenyang](https://github.com/morenyang)
- RTL
  - 💄 优化 Tree RTL 模式下选项框样式。[#24563](https://github.com/ant-design/ant-design/pull/24563)
  - 💄 优化 Calendar 通知事项文字在 RTL 模式下的样式。[#24528](https://github.com/ant-design/ant-design/pull/24528)
  - 💄 优化 Table 筛选下拉框在 RTL 模式下样式。[#24529](https://github.com/ant-design/ant-design/pull/24529)
  - 💄 优化 Cascader RTL 模式下拉框的样式。[#24520](https://github.com/ant-design/ant-design/pull/24520)
- TypeScript
  - 🛠 Form 导出 `RuleObject` 与 `RuleRender` 定义。[#24541](https://github.com/ant-design/ant-design/pull/24541) [@sorteam](https://github.com/sorteam)

## 4.2.5

`2020-05-25`

- 🐞 修复 Table 在 `dataSource` 移除条目时，`rowSelection.onChange` 仍然会缓存的问题。[#24338](https://github.com/ant-design/ant-design/pull/24338)
- 🐞 修复 Table 的选中箭头在 `size=small/middle` 时超出的问题。[#24394](https://github.com/ant-design/ant-design/pull/24394)
- 🐞 修复 Input.Group 内 Input.TextArea `hover` 时清除图标消失的问题。[#24360](https://github.com/ant-design/ant-design/pull/24360) [@Mr-jiangzhiguo](https://github.com/Mr-jiangzhiguo)
- 🐞 修复 Notificiation 使用 `useNotificiation` 时无限 render 的行为。[#24337](https://github.com/ant-design/ant-design/pull/24337)
- 🐞 修复 Button `loading` 切换动画丢失和 Modal `confirmLoading` 按钮未复位的问题。[#24328](https://github.com/ant-design/ant-design/pull/24328)
- 🐞 修复 Drawer 关闭后依然会遮挡页面元素的问题。[#24290](https://github.com/ant-design/ant-design/pull/24290)
- 🐞 修复 Cascader/Select/Table/TreeSelect 空数据时字体的颜色。[#24279](https://github.com/ant-design/ant-design/pull/24279)
- 💄 优化 InputNumber 操作按钮居中样式。[#24266](https://github.com/ant-design/ant-design/pull/24266)
- 🐞 修复 Table 在 `filteredValue` 使用空数组时仍然会高亮过滤图标的问题。[#24263](https://github.com/ant-design/ant-design/pull/24263)
- 🐞 修复 Cascader 不支持 `number[]` 类型 `value` 的问题。[#24247](https://github.com/ant-design/ant-design/pull/24247)
- ⌨️ 修复 Switch `autoFocus` 在 `disabled` 移除后会触发的问题，调整样式以避免切换时额外的抖动，并移除鼠标点击失焦逻辑以提升无障碍体验。[#24254](https://github.com/ant-design/ant-design/pull/24254)
- 💄 增加 Menu 默认 `text-align` 样式定义以修复被外部样式影响的问题。[#24253](https://github.com/ant-design/ant-design/pull/24253)
- 🛠 用 hooks 重构 List。[#24280](https://github.com/ant-design/ant-design/pull/24280) [@hengkx](https://github.com/hengkx)
- 🛠 用 hooks 重构 Alert 以支持严格模式。[#24236](https://github.com/ant-design/ant-design/pull/24236) [@hengkx](https://github.com/hengkx)
- 🐞 修复 Card 和 `react-split` 一起使用时卡顿的问题。[#24425](https://github.com/ant-design/ant-design/pull/24425)
- TypeScript
  - 🛠 优化 Cascader 的 TypeScript 定义。[#24393](https://github.com/ant-design/ant-design/pull/24393) [@zhangyu1818](https://github.com/zhangyu1818)
  - 🐞 修复 Upload TypeScript 报错：`Could not find a declaration rc-upload` 的问题。[#24325](https://github.com/ant-design/ant-design/pull/24325)
  - 🛠 BackTop 增加 `children` 定义。[#24235](https://github.com/ant-design/ant-design/pull/24235)

## 4.2.4

`2020-05-18`

- 🐞 回滚 Switch 以修复配置 `unCheckedChildren` 时，控制点位置样式问题。[#24242](https://github.com/ant-design/ant-design/pull/24242)
- 💄 调整 Upload 错误状态图标的颜色默认为红色。[#24160](https://github.com/ant-design/ant-design/pull/24160)
- 💄 向上微调 Dropdown 箭头位置。[#24215](https://github.com/ant-design/ant-design/pull/24215)
- 🌐 Form `defaultValidateMessages` 支持 `ru_RU`。[#24219](https://github.com/ant-design/ant-design/pull/24219) [@aivinog1](https://github.com/aivinog1)

## 4.2.3

`2020-05-16`

- 🐞 重构 `rc-progress` 以解决 `<script src="antd.min.js" />` 会抛出 `h3g is not defined` 的问题。[#24127](https://github.com/ant-design/ant-design/pull/24127)
- 📖 重写了 [在 create-react-app 中使用](https://ant.design/docs/react/use-with-create-react-app-cn)。[#24184](https://github.com/ant-design/ant-design/pull/24184)
- Drawer
  - 🐞 修复 Drawer `getContainer={false}` 时的高度问题。[#24082](https://github.com/ant-design/ant-design/pull/24082)
  - 🐞 修复 Drawer `mask={false}` 时隐藏动画不生效的问题。[#24082](https://github.com/ant-design/ant-design/pull/24082)
- BackTop
  - 🛠 BackTop 使用 hooks 重构。[#23575](https://github.com/ant-design/ant-design/pull/23575)
  - 🐞 修复 BackTop 在 Chrome 的 iframe 里不生效的问题。[#24194](https://github.com/ant-design/ant-design/pull/24194)
- DatePicker
  - 🐞 修复 DatePicker `disabledDate` 不会作用到 `showToday` 上的问题。[#24190](https://github.com/ant-design/ant-design/pull/24190)
  - 🐞 修复 DatePicker `renderExtraFooter` 内容过长超出容器宽度的问题。[#24145](https://github.com/ant-design/ant-design/pull/24145)
- Button
  - 🐞 修复 Button 内图标无法使用 Tooltip 的问题。[#24095](https://github.com/ant-design/ant-design/pull/24095)
  - 🐞 修复定制主题时小号 Button 错位的问题。[#24097](https://github.com/ant-design/ant-design/pull/24097)
- 🛠 Tooltip 使用 hooks 重构。[#23699](https://github.com/ant-design/ant-design/pull/23699)
- 🐞 修复 Upload.Dragger 禁用时依然会被 Form `label` 触发的问题。[#24202](https://github.com/ant-design/ant-design/pull/24202)
- 🐞 修复 Select 回填选项无法进行交互的问题（如 `title` 不生效）。[#24170](https://github.com/ant-design/ant-design/pull/24170)
- 🐞 修复 Switch 在 Safari 和 iOS Chrome 上点击时错位的问题。[#24122](https://github.com/ant-design/ant-design/pull/24122) [@lexlexa](https://github.com/lexlexa)
- 🐞 Carousel 更新依赖到 `react-slick@0.26.1` 以修正一些问题。[#24067](https://github.com/ant-design/ant-design/pull/24067)
- 🐞 Cascader 没有匹配任何选项时展示 `defaultValue` 而不是空字符串。[#24058](https://github.com/ant-design/ant-design/pull/24058) [@Kermit-Xuan](https://github.com/Kermit-Xuan)
- 🌎 完善繁体中文国际化。[#24065](https://github.com/ant-design/ant-design/pull/24065) [@wx1322](https://github.com/wx1322)
- 🐞 修复 Table `onChange` pagination 参数定义。[#24114](https://github.com/ant-design/ant-design/pull/24114) [@sorteam](https://github.com/sorteam)
- 💄 新增 less 变量 `@card-head-extra-color`。[#24189](https://github.com/ant-design/ant-design/pull/24189)
- 💄 调整 Pagination 简洁模式下按钮的背景色为透明。[#24152](https://github.com/ant-design/ant-design/pull/24152)
- 💄 修复暗色 Menu 内的链接颜色。[#24110](https://github.com/ant-design/ant-design/pull/24110)
- RTL
  - 💄 修复 Dropdown.Button 下拉框在 RTL 模式下默认位置。[#24150](https://github.com/ant-design/ant-design/pull/24150)
  - 💄 优化 Pagination 分隔符在 RTL 下的样式。[#24154](https://github.com/ant-design/ant-design/pull/24154)
  - 💄 修复 Menu 在 RTL 下的 `border` 样式。[#24101](https://github.com/ant-design/ant-design/pull/24101)
  - 💄 优化 Select 多选项在 RTL 模式下样式。[#24112](https://github.com/ant-design/ant-design/pull/24112)
  - 💄 优化 Typography `expand` 在 RTL 下的样式。[#24084](https://github.com/ant-design/ant-design/pull/24084)

## 4.2.2

`2020-05-11`

- 🐞 修复安装 antd `npm run version` 报错的问题。[#24059](https://github.com/ant-design/ant-design/pull/24059)
- 🐞 修复 Menu `@menu-item-font-size` 变量失效的问题。[#24052](https://github.com/ant-design/ant-design/pull/24052)
- 💄 新增 `@modal-close-color` less 变量。[#24053](https://github.com/ant-design/ant-design/pull/24053)

## 4.2.1

`2020-05-11`

- Form
  - 🐞 修复 Form.Item 使用 `getValueProps` React 会报警的问题。[#23875](https://github.com/ant-design/ant-design/pull/23875)
  - 🐞 修复 Form.Item `help` 在 `validateStatus` 不是 `error` 时的样式问题。[#23945](https://github.com/ant-design/ant-design/pull/23945)
- Table
  - 🐞 修复 Table 固定表头时选择列的宽度问题。[#23806](https://github.com/ant-design/ant-design/pull/23806)
  - 💄 调整 Table 选择列 css 选择器优先级以支持自定义宽度。[#23914](https://github.com/ant-design/ant-design/pull/23914)
- DatePicker
  - 🐞 修复在 `placeholder` 为 `undefined` 时不展示的问题。[#23818](https://github.com/ant-design/ant-design/pull/23818)
  - 🐞 修复清除图标的颜色。[#23811](https://github.com/ant-design/ant-design/pull/23811)
- Switch
  - 🐞 修复暗色主题下的加载样式。[#23766](https://github.com/ant-design/ant-design/pull/23766) [@vsn4ik](https://github.com/vsn4ik)
  - 🐞 修复 `unCheckedChildren` 不显示的问题。[#23791](https://github.com/ant-design/ant-design/pull/23791)
- 🐞 修复 Upload 在浮层中错误提示滚动定位问题。[#24001](https://github.com/ant-design/ant-design/pull/24001) [@mraiguo](https://github.com/mraiguo)
- 💄 调整 Comment 中 `avatar` 为空时不必要的 div 样式[#23994](https://github.com/ant-design/ant-design/pull/23994) [@Xuhao](https://github.com/Xuhao)
- 🐞 修复 Input.Group 中 Select 选项 `focus` 边框样式[#23985](https://github.com/ant-design/ant-design/pull/23985)
- 🐞 修复 Steps `subTitle` 上会显示 `[object Object]` 提示的问题。[#23989](https://github.com/ant-design/ant-design/pull/23989)
- 💄 微调 Select 移除图标的位置。[#23963](https://github.com/ant-design/ant-design/pull/23963)
- 🐞 修复无遮罩的 Drawer 设置 `50%` 宽度时不显示的问题。[#23925](https://github.com/ant-design/ant-design/pull/23925)
- 🐞 修复 Textarea 开启 `allowClear` 时高度错误的问题。[#23835](https://github.com/ant-design/ant-design/pull/23835)
- 💄 调整 Modal.xxx 方法为异步以防止其影响 React 事件响应。[#23826](https://github.com/ant-design/ant-design/pull/23826)
- 🐞 修复受控模式 Menu `inlineCollapsed` 折叠时的表现。[#23822](https://github.com/ant-design/ant-design/pull/23822)
- 🐞 修复 Button `loading` 动画切换不平滑的问题。[#23783](https://github.com/ant-design/ant-design/pull/23783)
- 🐞 修复 Slider 拖拽中选中 `marks` 文本的问题。[#23773](https://github.com/ant-design/ant-design/pull/23773)
- 🛠 Timeline 使用 React Hooks 重构。[#23631](https://github.com/ant-design/ant-design/pull/23631) [@hengkx](https://github.com/hengkx)
- 🌎 国际化
  - 🇮🇷 增加波斯语 `fa_IR` 国际化默认提示模板。[#23926](https://github.com/ant-design/ant-design/pull/23926) [@NarimanMov](https://github.com/NarimanMov)
  - 🇺🇸 增加 Form `en` 国际化默认提示模板[#23859](https://github.com/ant-design/ant-design/pull/23859) [@mjfwebb](https://github.com/mjfwebb)
- 📦 包体积优化
  - 🗑 移除 `react-lifecycles-compat` 依赖以优化包体积。[#23969](https://github.com/ant-design/ant-design/pull/23969)
  - 🛠 源码中不再引用 `package.json` 从而优化了一点包体积。[#23957](https://github.com/ant-design/ant-design/pull/23957)
  - 🛠 更新 `rc-animate` 到 3.x 以优化包体积。[#23937](https://github.com/ant-design/ant-design/pull/23937)
- RTL
  - 🐞 修复 Input 在 RTL 模式下清空按钮的样式。[#23999](https://github.com/ant-design/ant-design/pull/23999)
  - 🐞 修复 DatePicker 下拉框在 RTL 模式下样式。[#24028](https://github.com/ant-design/ant-design/pull/24028) [@xrkffgg](https://github.com/xrkffgg)
  - 💄 优化 DatePick 在 `RTL` 模式下的激活条样式。[#23981](https://github.com/ant-design/ant-design/pull/23981)
  - 🐞 修复 Transfer 查询框在 `RTL` 模式下的边距样式。[#23962](https://github.com/ant-design/ant-design/pull/23962)
  - 💄 优化 Layout RTL 样式。[#23921](https://github.com/ant-design/ant-design/pull/23921)
  - 💄 优化 Button `loading` 状态在 RTL 下样式。[#23776](https://github.com/ant-design/ant-design/pull/23776)
  - 💄 优化 Input.Search RTL 样式。[#23797](https://github.com/ant-design/ant-design/pull/23797)
- TypeScript
  - 🐞 修复 InputNumber `onChange` 类型。[#23871](https://github.com/ant-design/ant-design/pull/23871) [@jjhbw](https://github.com/jjhbw)

## 4.2.0

`2020-04-29`

- 🆕 List `grid` 支持所有分栏数字，比如分为 5 栏。[#23630](https://github.com/ant-design/ant-design/pull/23630)
- 🆕 Divider 新增 `plain` 属性，可用于设置一个非标题样式的分割文字。[#23405](https://github.com/ant-design/ant-design/pull/23405)
- 🆕 Typography `ellipsis` 支持 `onEllipsis` 事件。[#23414](https://github.com/ant-design/ant-design/pull/23414)
- 🆕 Space 支持 `align` 属性。[#23306](https://github.com/ant-design/ant-design/pull/23306)
- 🆕 Upload 添加 `isImageUrl` 属性以强制将文件作为图标文件。[#23248](https://github.com/ant-design/ant-design/pull/23248) [@onjuju](https://github.com/onjuju)
- 🆕 Form.Item 支持 `initialValue` 和 `getValueProps` 属性。[#22993](https://github.com/ant-design/ant-design/pull/22993)
- ConfigProvider
  - 🆕 ConfigProvider 支持 `getTargetContainer` 以配置 Affix `target` 属性。[#23751](https://github.com/ant-design/ant-design/pull/23751)
  - 🆕 ConfigProvider 添加 `input` 属性以支持全局化配置 Input `autoComplete` 的默认值。[#23455](https://github.com/ant-design/ant-design/pull/23455)
  - 🐞 修复 ConfigProvider `getPopupContainer` 对 DatePicker 和 Slider 不生效的问题。[#23594](https://github.com/ant-design/ant-design/pull/23594) [@hengkx](https://github.com/hengkx)
- Table
  - 🆕 Table `summary` 支持固定列。[#23647](https://github.com/ant-design/ant-design/pull/23647)
  - 🆕 Table 支持响应式展现列。[#23298](https://github.com/ant-design/ant-design/pull/23298) [@vbudovski](https://github.com/vbudovski)
  - 🐞 修复 Table pagination 在 RTL 下默认位置。[#23747](https://github.com/ant-design/ant-design/pull/23747)
  - 🐞 修复 Table 在 `pageSize` 是 `undefined` 时崩溃的问题。[#23724](https://github.com/ant-design/ant-design/pull/23724)
  - 🐞 修复 Table 大小为 `small` 和 `middle` 时嵌套表格错位的问题。[#23602](https://github.com/ant-design/ant-design/pull/23602) [@hengkx](https://github.com/hengkx)
- 🐞 修正 RangePicker 范围标签的颜色为主色。[#23705](https://github.com/ant-design/ant-design/pull/23705)
- 🐞 修复 Transfer 为空自定义图片样式问题。[#23694](https://github.com/ant-design/ant-design/pull/23694) [@hengkx](https://github.com/hengkx)
- Input
  - 🐞 修复 Password 组件输入光标位置。[#23633](https://github.com/ant-design/ant-design/pull/23633) [@huntdream](https://github.com/huntdream)
  - 💄 调整 Input.Search 的搜索图标样式。[#23406](https://github.com/ant-design/ant-design/pull/23406)
- Button
  - 🐞 修复 Button 图标类型按钮的对齐问题。[#23671](https://github.com/ant-design/ant-design/pull/23671)
  - 🐞 修复 Button 图标按钮 `loading` 样式错误的问题。[#23614](https://github.com/ant-design/ant-design/pull/23614)
  - 🐞 解决 Button 无法直接被 `react-dnd` 调用的问题。[#23571](https://github.com/ant-design/ant-design/pull/23571) [@hengkx](https://github.com/hengkx)
- Menu
  - 🆕 Menu Item 和 SubMenu 新增 `icon` 属性。[#23629](https://github.com/ant-design/ant-design/pull/23629)
  - 🐞 修复 Menu 菜单重复阴影的问题。[#23664](https://github.com/ant-design/ant-design/pull/23664)
- 🐞 解决 Tag 无法直接被 `react-dnd` 调用的问题。[#23632](https://github.com/ant-design/ant-design/pull/23632) [@hengkx](https://github.com/hengkx)
- Anchor
  - 🐞 修复 Anchor Link 包含多个 `#` 时无法跳转的问题。[#23595](https://github.com/ant-design/ant-design/pull/23595) [@wuzekang](https://github.com/wuzekang)
  - 🐞 修复 Input 带 `suffix` 时的元素对齐问题。[#23606](https://github.com/ant-design/ant-design/pull/23606)
- 💄 Select 箭头打开时不再翻转。[#23468](https://github.com/ant-design/ant-design/pull/23468)
- 💄 新增 Rate 的 `direction` 支持优化。[#23321](https://github.com/ant-design/ant-design/pull/23321)
- 💄 调整紧凑模式下默认的字体大小。[#23135](https://github.com/ant-design/ant-design/pull/23135)
- RTL
  - 💄 优化 Result RTL 下按钮样式。[#23733](https://github.com/ant-design/ant-design/pull/23733)
  - 💄 新增 Divider RTL 支持。[#23734](https://github.com/ant-design/ant-design/pull/23734)
  - 💄 修复 Alert 在 RTL 下无 icon 的间隔问题。[#23714](https://github.com/ant-design/ant-design/pull/23714)
  - 💄 优化 Table RTL 模式下扩展按钮动画与分页样式问题。[#23706](https://github.com/ant-design/ant-design/pull/23706)
  - 💄 修复 Table 筛选下拉框在 RTL 下的位置。[#23695](https://github.com/ant-design/ant-design/pull/23695)
  - 💄 修复 Table 勾选框图标 RTL 样式。[#23690](https://github.com/ant-design/ant-design/pull/23690)
  - 💄 优化 List RTL 样式。[#23676](https://github.com/ant-design/ant-design/pull/23676)
  - 💄 新增 Calendar RTL 支持。[#23394](https://github.com/ant-design/ant-design/pull/23394)
  - 💄 优化 Input.Search RTL 样式。[#23424](https://github.com/ant-design/ant-design/pull/23424)
  - 💄 增加 Notification RTL 设置。[#23185](https://github.com/ant-design/ant-design/pull/23185)
- TypeScript
  - 🐞 修复 PageHeader `tag` 属性定义错误。[#23712](https://github.com/ant-design/ant-design/pull/23712) [@hengkx](https://github.com/hengkx)
  - 🗑 移除已废弃的 Button `type="danger"` TypeScript 定义并增加警告信息。[#23709](https://github.com/ant-design/ant-design/pull/23709)
  - 🐞 修复 Table pagination `position` Typescript 定义错误。[#23681](https://github.com/ant-design/ant-design/pull/23681) [@hengkx](https://github.com/hengkx)

## 4.1.5

`2020-04-25`

- 🐞 修复 Button.Group 中按钮没有对齐的问题。[#23590](https://github.com/ant-design/ant-design/pull/23590)
- 🐞 修复 Select 箭头图标点击无法触发下拉的问题。[#23448](https://github.com/ant-design/ant-design/pull/23448)
- 🐞 修复 Form 自定义 `@form-item-margin-bottom` 变量时表单校验抖动的问题。[#23436](https://github.com/ant-design/ant-design/pull/23436) [@yoyo837](https://github.com/yoyo837)
- 🐞 修复第一个 Divider 渲染时样式不一致的问题。[#23438](https://github.com/ant-design/ant-design/pull/23438)
- 🐞 修复嵌套 ConfigProvider 会丢失 `prefixCls` 值的问题。[#23423](https://github.com/ant-design/ant-design/pull/23423)
- 🐞 修复 Carousel 键盘切换到非活跃 slide 上的 Radio/Checkbox 的问题。[#23380](https://github.com/ant-design/ant-design/pull/23380)
- 🐞 修复 Tree 使用虚拟滚动时会因为 `loadData` 更新过快而锁死的问题。[#23581](https://github.com/ant-design/ant-design/pull/23581)
- 🐞 修复 Steps 组件竖直展示时在 IE11 下样式错误的问题。[#23561](https://github.com/ant-design/ant-design/pull/23561) [@AdrianoRuberto](https://github.com/AdrianoRuberto)
- 🐞 修复 Input.Search 高度被 `suffix` 撑高的问题和报 `react key` 重复警告的问题。[#23527](https://github.com/ant-design/ant-design/pull/23527)
- 🐞 修复 Menu 鼠标移到缝隙处子菜单会消失的问题。[#23511](https://github.com/ant-design/ant-design/pull/23511)
- 🐞 修复 Tree 自定义图标在加载状态下消失的问题。[#23494](https://github.com/ant-design/ant-design/pull/23494)
- RTL
  - 🐞 修复 Alert 在 `showIcon` 和 `closable` 都存在时的 RTL 样式问题。[#23526](https://github.com/ant-design/ant-design/pull/23526)
  - 🐞 修复 Button 在 RTL 下 loading 样式不正确的问题。[#23399](https://github.com/ant-design/ant-design/pull/23399)
  - 🐞 修复 Collapse 在 RTL 下切换图标位置不正确的问题。[#23445](https://github.com/ant-design/ant-design/pull/23445)
  - 🐞 修复 Select 分组名称的 RTL 样式问题。[#23404](https://github.com/ant-design/ant-design/pull/23404)
  - 🐞 修复 Statistic 的 RTL 样式不正确的问题。[#23397](https://github.com/ant-design/ant-design/pull/23397)
- TypeScript
  - 🐞 修复 Table 的 `selections` 类型定义。[#23462](https://github.com/ant-design/ant-design/pull/23462) [@xiaoxintang](https://github.com/xiaoxintang)

## 4.1.4

`2020-04-18`

- 🐞 修复暗黑主题和紧凑主题不生效的问题。[#23243](https://github.com/ant-design/ant-design/pull/23243)
- 🐞 修复 Modal.info 等方法的 `onOk` 函数有参数时只触发一次的问题。[#23360](https://github.com/ant-design/ant-design/pull/23360)
- 🐞 修复 Dropdown 弹出菜单背景样式问题。[#23296](https://github.com/ant-design/ant-design/pull/23296)
- 💄 优化 PageHeader 的响应式表现。[#23277](https://github.com/ant-design/ant-design/pull/23277)
- 🐞 修复紧凑模式下树选择出现空白。[#23231](https://github.com/ant-design/ant-design/pull/23231)
- 🛎 修改 Checkbox 和 Switch 中控制台输出的错别字 (validate -> a valid)。[#23240](https://github.com/ant-design/ant-design/pull/23240) [@evancharlton](https://github.com/evancharlton)
- 🐞 修复 Table `rowSelection` 在设置 `childrenColumnName` 时事件参数不正确的问题。[#23205](https://github.com/ant-design/ant-design/pull/23205)
- Input
  - 🐞 修复 Input `type="color"` 的高度问题。[#23351](https://github.com/ant-design/ant-design/pull/23351)
  - 🐞 修复 Input 设置 `allowClear` 内联展示时，触发清除按钮样式抖动的问题。[#23259](https://github.com/ant-design/ant-design/pull/23259)
  - 🐞 修复 Input.Search 全局设置 `size` 不生效问题。[#23331](https://github.com/ant-design/ant-design/pull/23331)
- Select
  - 🐞 修复 Select 多选时设置 `disabled` 选项仍然会展示移除按钮的问题。[#23295](https://github.com/ant-design/ant-design/pull/23295)
  - 🐞 修复 Select 自定义 `suffixIcon` 无法交互的问题。[#23274](https://github.com/ant-design/ant-design/pull/23274)
  - 🐞 修复 Select 输入光标在 Collapse 内不显示的问题。[#23250](https://github.com/ant-design/ant-design/pull/23250)
- 国际化
  - 🌐 Form 校验信息支持国际化并增加中文文案。[#23165](https://github.com/ant-design/ant-design/pull/23165) [@hengkx](https://github.com/hengkx)
  - 🌐 完善希伯来语(以色列) 国际化。[#23302](https://github.com/ant-design/ant-design/pull/23302) [@MishaKav](https://github.com/MishaKav)
  - 🌐 完善俄语国际化。[#23303](https://github.com/ant-design/ant-design/pull/23303) [@MishaKav](https://github.com/MishaKav)
- TypeScript
  - 🔷 更新 Tree 的类型定义。[#23348](https://github.com/ant-design/ant-design/pull/23348) [@yoyo837](https://github.com/yoyo837)
  - 🔷 更新 Form Item 的类型定义。[#22962](https://github.com/ant-design/ant-design/pull/22962) [@fa93hws](https://github.com/fa93hws)
  - 🐞 修复 Slider 组件 `value` 和 `defaultValue` 文档与 TypeScript 定义不一致的问题。[#23252](https://github.com/ant-design/ant-design/pull/23252) [@DongchengWang](https://github.com/DongchengWang)
- RTL
  - 🐞 修复 Menu RTL 样式。[#23319](https://github.com/ant-design/ant-design/pull/23319)
  - 💄 修复 Select 的 RTL 样式。[#23235](https://github.com/ant-design/ant-design/pull/23235)

## 4.1.3

`2020-04-13`

- 💄 调整 Form.Item `label` 在垂直布局下的高度样式。[#23192](https://github.com/ant-design/ant-design/pull/23192)
- 🐞 修复引用暗黑或紧凑主题时提示 `Variable is undefined` 的问题，并提供 `getThemeVariables` 方便获取对应主题变量。[#23171](https://github.com/ant-design/ant-design/pull/23171)
- 🐞 修复 PageHeader `title` 超长时布局被破坏的问题并优化响应式表现。[#23133](https://github.com/ant-design/ant-design/pull/23133)
- Tabs
  - 🐞 修复 Tabs `@tabs-card-height` less 变量无效的问题。[#23168](https://github.com/ant-design/ant-design/pull/23168)
  - 🐞 修复 Tabs 在 Safair 浏览器下无法显示的问题。[#23151](https://github.com/ant-design/ant-design/pull/23151) [@imhxc](https://github.com/imhxc)
- Table
  - 🐞 修复 Table 固定列在 Safari 12 中不能固定的问题。[#23161](https://github.com/ant-design/ant-design/pull/23161)
  - 🐞 修复 Table `summary` 在小尺寸下的内边距样式。[#23140](https://github.com/ant-design/ant-design/pull/23140) [@someyoungideas](https://github.com/someyoungideas)
- 🐞 修复 Select 不同尺寸下的对齐样式问题。[#23160](https://github.com/ant-design/ant-design/pull/23160)
- 🐞 修复 RangePicker 在 Input.Group 内的样式问题。[#23149](https://github.com/ant-design/ant-design/pull/23149)
- 🐞 修复 Pagination 缺少 `showTitle` TypeScript 定义的问题。[#23144](https://github.com/ant-design/ant-design/pull/23144) [@DongchengWang](https://github.com/DongchengWang)

## 4.1.2

`2020-04-10`

- Menu
  - 🐞 修复暗色 Menu 弹出菜单背景色为白色的问题。[#22981](https://github.com/ant-design/ant-design/pull/22981) [@AshoneA](https://github.com/AshoneA)
  - 🐞 修复 SubMenu 标题过长而导致被箭头图标部分覆盖的问题。[#23028](https://github.com/ant-design/ant-design/pull/23028) [@wwyx778](https://github.com/wwyx778)
- 🐞 修复紧凑模式和暗黑模式无法同时开启的问题。[#22934](https://github.com/ant-design/ant-design/pull/22934) [@AshoneA](https://github.com/AshoneA)
- 🐞 修复 Notification 非法的 `padding-top` 值。[#22941](https://github.com/ant-design/ant-design/pull/22941)
- Button
  - 🐞 修复带图标 Button 的 `loading` 动画效果。[#23102](https://github.com/ant-design/ant-design/pull/23102)
  - ⚠️ 优化 Button 非法 `type` 的控制台提示。[#22933](https://github.com/ant-design/ant-design/pull/22933)
- 🐞 修复 Statistic 在值为 `-` 时会展示成 `-0` 的问题。[@22950](https://github.com/ant-design/ant-design/pull/22950)
- 🐞 修复 Modal.confirm `onOk` 可以被触发多次的问题。[#22963](https://github.com/ant-design/ant-design/pull/22963)
- Input
  - 🐞 修复 Input.Group 中 Button 不能对齐的问题。[#22975](https://github.com/ant-design/ant-design/pull/22975)
  - 🐞 修复 Input 在暗黑模式下使用 `affix` 的背景样式问题。[#23115](https://github.com/ant-design/ant-design/pull/23115)
- 🐞 修复 Form.Item 在动态切换时没有正确重置错误样式的问题。[#23041](https://github.com/ant-design/ant-design/pull/23041)
- 💄 微调 RangePicker 箭头和后缀的颜色样式。[#23025](https://github.com/ant-design/ant-design/pull/23025)
- Table
  - 🐞 修复 Table 选择行在 hover 时的背景样式问题。[#23110](https://github.com/ant-design/ant-design/pull/23110)
  - 💄 微调 Table 行 hover 时的背景色。[#23113](https://github.com/ant-design/ant-design/pull/23113)
  - ⚠️ Table 在异步数据下 `dataSource` 长度与 `pageSize` 不匹配时，添加警告信息。[#23118](https://github.com/ant-design/ant-design/pull/23118)
- Select
  - 💄 微调多选 Select 的光标位置使其与单选 Select 统一。[#22978](https://github.com/ant-design/ant-design/pull/22978)
  - 🐞 修复 无边框 Select 在 Form.Item 设置 `validateStatus` 时会出现边框的问题。[#23004](https://github.com/ant-design/ant-design/pull/23004)
  - 🐞 修复 Select 在 IE11 下的展示问题。[#23020](https://github.com/ant-design/ant-design/pull/23020)
- 🐞 修复 Calendar 不支持 `style` 属性的问题。[#23081](https://github.com/ant-design/ant-design/pull/23081)
- 🐞 修复 Tabs 下方卡片布局激活标签的高度问题。[#23087](https://github.com/ant-design/ant-design/pull/23087)
- 🐞 修复 Anchor、Select、DatePicker、Grid、Mentions 组件的 RTL 支持。[@xrkffgg](https://github.com/xrkffgg)
- TypeScript
  - 🌟 Upload `UploadProps` 支持泛型定义。[#22921](https://github.com/ant-design/ant-design/pull/22921) [@dpyzo0o](https://github.com/dpyzo0o)
  - 🐞 修复 Modal.confirm 的 `okButtonProps` 定义。[#21165](https://github.com/ant-design/ant-design/pull/21165) [@nicu-chiciuc](https://github.com/nicu-chiciuc)
  - 🌟 暴露 Form `Store` 接口。[#22755](https://github.com/ant-design/ant-design/pull/22755) [@shaodahong](https://github.com/shaodahong)
  - 🌟 优化 Input、Tag、Badge 组件的枚举类型属性定义。[#23026](https://github.com/ant-design/ant-design/pull/23026) [#22999](https://github.com/ant-design/ant-design/pull/22999) [#23006](https://github.com/ant-design/ant-design/pull/23006) [@fjc0k](https://github.com/fjc0k)
  - 🐞 修复 Pagination `position` 定义。[#23048](https://github.com/ant-design/ant-design/pull/23048) [@Arttse](https://github.com/Arttse)

## 4.1.1

`2020-04-05`

- 🐞 移除 Tabs 的内容区域的 focus 蓝色轮廓线。[#22752](https://github.com/ant-design/ant-design/pull/22752) [@MrHeer](https://github.com/MrHeer)
- 🐞 修复 Input 前后缀添加弹出元素不能点击获得焦点的问题。[#22887](https://github.com/ant-design/ant-design/pull/22887)
- Table
  - 🐞 修复 Table 行选择下拉菜单不支持 `getPopupContainer`。[#22787](https://github.com/ant-design/ant-design/pull/22787) [@mikeyshing88](https://github.com/mikeyshing88)
  - 🐞 修复 Table 配 `size` 时，使用过滤和排序的表头尺寸问题。[#22872](https://github.com/ant-design/ant-design/pull/22872)
  - 💄 调整嵌套 Table 样式，只有一个子 Table 时才移除边距。[#22868](https://github.com/ant-design/ant-design/pull/22868)
  - 🐞 修复 Table 列 `align` 在 `sorter` 开启时标题不居中的问题。[#22858](https://github.com/ant-design/ant-design/pull/22858)
  - 🐞 修复 Table 过滤设置在 jsx 结构下无效的问题。[#22888](https://github.com/ant-design/ant-design/pull/22888)
  - 🐞 调整 Table 在无固定列滚动时，展开行将跟随表格一同滚动。[#22832](https://github.com/ant-design/ant-design/pull/22832)
  - 🐞 修复当 `column.children` 为 `undefined` 时整列未显示的问题。[#22832](https://github.com/ant-design/ant-design/pull/22832)
  - 🐞 修复 Table 在 `filters` 为 `undefined` 时仍然展示过滤按钮的问题。[#22833](https://github.com/ant-design/ant-design/pull/22833)
  - 🐞 修复 Table `filters` 未变化时触发 `onChange` 事件的问题。[#22829](https://github.com/ant-design/ant-design/pull/22829)
  - 🐞 修复 Table `loading` 兼容性。[#22739](https://github.com/ant-design/ant-design/pull/22739)
  - 🐞 修复 Table 在 Safari 下滚动阴影的样式。[#22794](https://github.com/ant-design/ant-design/pull/22794)
- 💄 调整 RangePicker 箭头样式。[#22847](https://github.com/ant-design/ant-design/pull/22847)
- 🐞 修复 Text 使用 `ellipsis` 的对齐问题。[#22836](https://github.com/ant-design/ant-design/pull/22836)
- 💄 优化 `@info-color` less 变量，默认为 `@primary-color`。[#22723](https://github.com/ant-design/ant-design/pull/22723)
- 🐞 修复大号多选 Select 未选择时的高度问题。[#22904](https://github.com/ant-design/ant-design/pull/22904)
- 🐞 修复 BackTop 在 iframe 里不生效并提升了组件性能。[#22788](https://github.com/ant-design/ant-design/pull/22788)
- 🐞 修复 Radio less 变量名错误。[#22803](https://github.com/ant-design/ant-design/pull/22803) [@yoyo837](https://github.com/yoyo837)
- 🐞 修复 Card Tabs 不支持小尺寸的问题。[#22666](https://github.com/ant-design/ant-design/pull/22666) [@MrHeer](https://github.com/MrHeer)
- 🐞 修复 Affix 抛出 `React state update on unmounted component` 警告的问题。[#22790](https://github.com/ant-design/ant-design/pull/22790)
- 🐞 修复 Textarea 配置 `clearIcon` 在 Form.Item 下会有额外的 `margin` 的问题。[#22793](https://github.com/ant-design/ant-design/pull/22793)
- 🐞 修复 List 空数据时 `footer` 上分割线缺失的问题。[#22771](https://github.com/ant-design/ant-design/pull/22771)
- 🐞 修复 Slider 中 `tooltipPlacement` 与 `vertical` 配置在顺序上问题。[#22772](https://github.com/ant-design/ant-design/pull/22772) [@phoenixeliot](https://github.com/phoenixeliot)
- 🛠 用新的 React context 重构 LocaleReceiver 以避免严格模式下的警告信息。[#22762](https://github.com/ant-design/ant-design/pull/22762)
- 🐞 修复 Radio 和 Checkbox 上 required 属性没有传给原生 input 的问题。[#22761](https://github.com/ant-design/ant-design/pull/22761)
- 🐞 修复 CSS 变量 `--scroll-bar` 未定义的问题。[#22754](https://github.com/ant-design/ant-design/pull/22754) [@mikeyshing88](https://github.com/mikeyshing88)
- 🐞 修复 Menu 和 Spin 在紧凑模式下样式。[#22908](https://github.com/ant-design/ant-design/pull/22908) [@AshoneA](https://github.com/AshoneA)
- 🐞 修复 Space 子项重复的 `key`。[#22745](https://github.com/ant-design/ant-design/pull/22745)
- 🐞 修复 Select 鼠标手型样式。[#22743](https://github.com/ant-design/ant-design/pull/22743)
- 🇫🇷 DatePicker 和 TimePicker 法语国际化。[#22769](https://github.com/ant-design/ant-design/pull/22769) [@PaulJln](https://github.com/PaulJln)
- RTL
  - 💄 新增 Message RTL 样式。[#22513](https://github.com/ant-design/ant-design/pull/22513) [@xrkffgg](https://github.com/xrkffgg)
  - 🐞 修复 Radio RTL 样式。[#22926](https://github.com/ant-design/ant-design/pull/22926) [@AshoneA](https://github.com/AshoneA)
  - 🐞 修复 Menu RTL 样式问题。[#22841](https://github.com/ant-design/ant-design/pull/22841)
  - 🐞 修复 Form RTL 下 label 样式问题。[#22621](https://github.com/ant-design/ant-design/pull/22621) [@xrkffgg](https://github.com/xrkffgg)
  - 🐞 修复 Space RTL 样式问题。[#22809](https://github.com/ant-design/ant-design/pull/22809) [@xrkffgg](https://github.com/xrkffgg)
- TypeScript
  - 🐞 修复 Table `FilterDropdownProps` 类型定义。[#22895](https://github.com/ant-design/ant-design/pull/22895) [@zhangyu1818](https://github.com/zhangyu1818)
  - 🐞 修复 Form `Store` 和 `StoreValue` 类型定义。[#22755](https://github.com/ant-design/ant-design/pull/22755) [@shaodahong](https://github.com/shaodahong)

## 4.1.0

`2020-03-29`

- 🔥 支持紧凑模式主题。[#22126](https://github.com/ant-design/ant-design/pull/22126) [@AshoneA](https://github.com/AshoneA)
- 🔥 新的 Space 组件以支持内联组件的间距样式。[#22363](https://github.com/ant-design/ant-design/pull/22363)
- 🔥 DatePicker 支持季度选择器。[#22468](https://github.com/ant-design/ant-design/pull/22468)
- 🆕 Tree/TreeSelect/Select 支持 `virtual` 属性以关闭虚拟滚动。[#21955](https://github.com/ant-design/ant-design/pull/21955)
- 🆕 改进 Pagination 使用体验。[#22711](https://github.com/ant-design/ant-design/pull/22711)
  - Pagination 当 `total > 50` 时默认显示切换页数选择器。
  - 统一 Pagination 十页以内的页码个数使其宽度更统一。
  - Pagination 调整默认页数选项为 `10, 20, 50, 100`。
- Table
  - 🆕 Table 分页位置增加更多选项。[#22647](https://github.com/ant-design/ant-design/pull/22647) [@hengkx](https://github.com/hengkx)
  - 🆕 Table 选择列支持 `renderCell`。[#21711](https://github.com/ant-design/ant-design/pull/21711)
  - 🆕 Table 排序增加下次排序的提示，并增加 `showSorterTooltip` 属性开关。[#21631](https://github.com/ant-design/ant-design/pull/21631) [@AshoneA](https://github.com/AshoneA)
- 🆕 Tag 支持 `icon` 属性。[#22418](https://github.com/ant-design/ant-design/pull/22418) [@vtsybulin](https://github.com/vtsybulin)
- 🆕 Grid 添加 `useBreakpoint` hook. [#22226](https://github.com/ant-design/ant-design/pull/22226)
- 🆕 Card 支持 `tabProps`。[#22207](https://github.com/ant-design/ant-design/pull/22207)
- 🆕 Menu.Item 上的 Tooltip 现在可以使用 `title={null}` 来禁用。[#22202](https://github.com/ant-design/ant-design/pull/22202)
- 🆕 Pagination supports `autoResize` prop。[#21959](https://github.com/ant-design/ant-design/pull/21959) [@wendellhu95](https://github.com/wendellhu95)
- 🆕 Popover/Popconfirm 添加 render props 支持。[#22034](https://github.com/ant-design/ant-design/pull/22034) [@nossbigg](https://github.com/nossbigg)
- 🆕 TimePicker.RangePicker 支持 `order` 属性用于设置排序行为。[#21948](https://github.com/ant-design/ant-design/pull/21948)
- 🆕 Carousel `dots` 支持对象传递 `className`。[#21848](https://github.com/ant-design/ant-design/pull/21848)
- 🆕 Form `validateMessages` 支持 `${label}` 变量。[#21835](https://github.com/ant-design/ant-design/pull/21835)
- 🆕 暴露 Breadcrumb.Item 组件的所有 Dropdown 的可配置属性。[#20763](https://github.com/ant-design/ant-design/pull/20763) [@paranoidjk](https://github.com/paranoidjk)
- ⌨️ 增强 Tabs 可访问性。[#22287](https://github.com/ant-design/ant-design/pull/22287)
  - 新增 Tabs keyboard 属性用于开关键盘切换功能。
  - Tabs `extraContent` 里的元素不再触发键盘切换功能。
- 🛠 添加 Form.Item 在受控时使用 `defaultValue` 的警告信息。[#22571](https://github.com/ant-design/ant-design/pull/22571)
- 🛠 Typography `onExpand` 添加事件参数。[#22092](https://github.com/ant-design/ant-design/pull/22092) [@BlazPocrnja](https://github.com/BlazPocrnja)
- 🛠 简化 Popconfirm 和 Popover 的 dom 结构。[#22052](https://github.com/ant-design/ant-design/pull/22052)
- 🐞 修复 Autocomplete `value` 为 `null` 时，值展示 `null` 的问题。[#21955](https://github.com/ant-design/ant-design/pull/21955)
- 🐞 调整 Drawer 无 `title` 时关闭按钮样式以避免遮挡滚动条。[#22710](https://github.com/ant-design/ant-design/pull/22710)
- 🐞 修复 Calendar 的一些样式细节问题。[#22676](https://github.com/ant-design/ant-design/pull/22676)
- Table
  - 🐞 修复 Table 在 Safari 下固定列的阴影样式问题。[#22680](https://github.com/ant-design/ant-design/pull/22680)
  - 🐞 修复 Table 样式影响内嵌 table 的问题。[#22643](https://github.com/ant-design/ant-design/pull/22643)
  - 🐞 修复 Table 同时设置 `rowSelection` 和 `onRow` 事件冒泡问题。[#22566](https://github.com/ant-design/ant-design/pull/22566) [@hengkx](https://github.com/hengkx)
  - 🐞 修复 Table 空文本没有居中的问题与空数据依然展示了分页的问题。[#22548](https://github.com/ant-design/ant-design/pull/22548) [@hengkx](https://github.com/hengkx)
- 🐞 修复 Input 只配置 `suffix` 时的样式对齐问题。[#22603](https://github.com/ant-design/ant-design/pull/22603)
- 🐞 修复 Alert 无法和 Tooltip/Popover 一起使用的问题。[#22594](https://github.com/ant-design/ant-design/pull/22594)
- 🐞 修复嵌套动态 Form.Item 会被 react 警告更新移除节点的信息。[#22575](https://github.com/ant-design/ant-design/pull/22575)
- 💄 调整 Tag `processing` 状态颜色。[#22303](https://github.com/ant-design/ant-design/pull/22303)
- 💄 移除 Select 下拉组标题的鼠标可点击样式。[#22581](https://github.com/ant-design/ant-design/pull/22581)
- 💄 迁移 `@form-item-label-height` less 变量到主题变量中。[#22600](https://github.com/ant-design/ant-design/pull/22600) [@slavakam](https://github.com/slavakam)
- 💄 优化 Table 筛选菜单按钮的样式并修复 Dropdown 二级菜单的上下边距。[#22072](https://github.com/ant-design/ant-design/pull/22072)
- 💄 新增 less 变量 `@link-focus-decoration` 和 `@link-focus-outline`。[#22511](https://github.com/ant-design/ant-design/pull/22511)
- 💄 新增 DatePicker `disabled` 时，分隔符鼠标禁用样式。[#22563](https://github.com/ant-design/ant-design/pull/22563)
- RTL
  - 💄 优化 CheckBox `inner` RTL 样式问题。[#22627](https://github.com/ant-design/ant-design/pull/22627)
  - 🐞 优化 Upload `picture-card` RTL 样式问题。[#22630](https://github.com/ant-design/ant-design/pull/22630)
  - 🐞 修复 Badge RTL 数字显示样式问题。[#22665](https://github.com/ant-design/ant-design/pull/22665)
  - 🐞 修复 Select RTL 多选可清空时，选项样式问题。[#22596](https://github.com/ant-design/ant-design/pull/22596)
  - 🐞 修复 Progress RTL 样式问题。[#22558](https://github.com/ant-design/ant-design/pull/22558)
  - 🐞 修复 Badge RTL 样式问题。[#22551](https://github.com/ant-design/ant-design/pull/22551)
  - 🐞 修复 Input RTL 样式问题。[#22525](https://github.com/ant-design/ant-design/pull/22525)
  - 🐞 修复 Steps RTL 样式问题。[#22523](https://github.com/ant-design/ant-design/pull/22523)
  - 💄 优化 Tabs RTL 按钮样式问题。[#22653](https://github.com/ant-design/ant-design/pull/22653)
  - 💄 优化 Input.Group RTL 样式问题。[#22624](https://github.com/ant-design/ant-design/pull/22624)
  - 💄 优化 Timeline label RTL 样式问题。[#22652](https://github.com/ant-design/ant-design/pull/22652)
  - 💄 优化 Select group RTL 样式问题。[#22584](https://github.com/ant-design/ant-design/pull/22584)
  - 💄 优化 Dropdown.Button RTL 样式问题。[#22519](https://github.com/ant-design/ant-design/pull/22519)
- Typescript
  - 🛠 替换废弃的 `React.SFC` 为 `React.FC`。[#22691](https://github.com/ant-design/ant-design/pull/22691) [@Rustin-Liu](https://github.com/Rustin-Liu)
  - 🐞 修复 Form.Item `children` 的类型定义。[#22662](https://github.com/ant-design/ant-design/pull/22662)

## 4.0.4

`2020-03-23`

- 🐞 修复 AutoComplete 下使用 Search 时清除图标和搜索图标重叠样式异常的问题。[#22310](https://github.com/ant-design/ant-design/pull/22310)
- 🐞 修复 Button 为 `disabled` 时被 Tooltip 包裹时的对齐问题。[#22461](https://github.com/ant-design/ant-design/pull/22461)
- 🐞 修复 Cascader 搜索时需要按两次向下箭头才能选中问题。[#22216](https://github.com/ant-design/ant-design/pull/22216) [@Kermit-Xuan](https://github.com/Kermit-Xuan)
- 🐞 修复 Carousel 无法使用 Snowpack 构建的问题。[#22507](https://github.com/ant-design/ant-design/pull/22507)
- 🐞 修复 ConfigProvider `componentSize` 对 DatePicker.RangePicker 无效的问题。[#22486](https://github.com/ant-design/ant-design/pull/22486)
- 🐞 修复 Descriptions 在小尺寸下无法自适应的问题。[#22407](https://github.com/ant-design/ant-design/pull/22407)
- 🐞 修复 Grid 下使用不带 `span` 的 Col 时样式错乱的问题。[#22455](https://github.com/ant-design/ant-design/pull/22455)
- ⚡️ 优化 Form.Item 有多个 `noStyle` 子 Form.Item 时信息收集性能。[#22410](https://github.com/ant-design/ant-design/pull/22410)
- 💄 增加 InputNumber RTL 模式样式。[#22434](https://github.com/ant-design/ant-design/pull/22434)
- Menu
  - 🛠 Menu 继承标题的 `line-height`。[#16142](https://github.com/ant-design/ant-design/pull/16142) [@sheerun](https://github.com/sheerun)
  - 🐞 修复 Menu 子菜单展开/收起时会出现滚动条的问题。[#22248](https://github.com/ant-design/ant-design/pull/22248)
- 🐞 修复 Progress 仪表盘状进度条传入 `gapDeg` 为 `0` 时仍然有缺口的问题。[#22462](https://github.com/ant-design/ant-design/pull/22462) [@thisrabbit](https://github.com/thisrabbit)
- 🛠 调整 Radio.Group 逻辑，`value` 为 `undefined` 时为非受控状态。[#22245](https://github.com/ant-design/ant-design/pull/22245)
- 💄 微调 RangePicker 箭头阴影样式。[#22406](https://github.com/ant-design/ant-design/pull/22406)
- ⚡️ 减少 Row 在 `gutter` 是数组时非必要的额外渲染。[#22475](https://github.com/ant-design/ant-design/pull/22475) [@dolfje](https://github.com/dolfje)
- 🐞 修复 Select 下拉菜单的上下 padding。[#22251](https://github.com/ant-design/ant-design/pull/22251)
- 🐞 修复 Slider 使用 `nullable` 值时弹出提示会崩溃的问题。[#22482](https://github.com/ant-design/ant-design/pull/22482)
- Table
  - 🐞 修复 Table ColumnGroup 使用受控 `sorterOrder` 无效的问题。[#22450](https://github.com/ant-design/ant-design/pull/22450)
  - 🐞 修复 Table 边框圆角样式问题。[#22413](https://github.com/ant-design/ant-design/pull/22413) [@akshatmittal](https://github.com/akshatmittal)
  - 🐞 修复 Table 固定列高度样式问题。[#22367](https://github.com/ant-design/ant-design/pull/22367)
  - 🐞 修复 Table 展开行按钮在 ipad 下的样式问题。[#22334](https://github.com/ant-design/ant-design/pull/22334) [@BugHiding](https://github.com/BugHiding)
  - 🐞 修复 Table 在只设置 `onFilter` 时过滤无效的问题。[#22317](https://github.com/ant-design/ant-design/pull/22317)
  - 🛠 Table `column.filter` 的 value 定义可以支持 `boolean`。[#22277](https://github.com/ant-design/ant-design/pull/22277) [@xudongdev](https://github.com/xudongdev)
- 🐞 重构 DirectoryTree 以修复废弃 API 警告信息。[#22318](https://github.com/ant-design/ant-design/pull/22318)
- 🐞 修复 TreeSelect `treeIcon` 无效的问题。[#22437](https://github.com/ant-design/ant-design/pull/22437)
- 🐞 修复 Typography 嵌套列表的样式问题。[#22284](https://github.com/ant-design/ant-design/pull/22284)
- 🐞 调整 Upload `onChange` 返回参数 `fileList` 为不可变数据以解决渲染问题。[#22322](https://github.com/ant-design/ant-design/pull/22322)
- 🌎 国际化
  - 🇩🇪 更新德语国际化。[#22270](https://github.com/ant-design/ant-design/pull/22270) [@iChebbi](https://github.com/iChebbi)
  - 🇫🇷 更新法语国际化。[#22238](https://github.com/ant-design/ant-design/pull/22238) [@abenhamdine](https://github.com/abenhamdine)
- Typescript
  - 🐞 移除 Table `getCheckboxProps` 的 `checked` 类型定义。[#22391](https://github.com/ant-design/ant-design/pull/22391) [@geekrainy](https://github.com/geekrainy)

## 4.0.3

`2020-03-14`

- Menu
  - 🐞 修复 Menu 水平 Item 使用嵌套结构 Icon 会丢失 `margin` 的问题。[#22021](https://github.com/ant-design/ant-design/pull/22021)
  - 💄 优化 Menu 中 Icon 的样式。[#22090](https://github.com/ant-design/ant-design/pull/22090) [@x1mrdonut1x](https://github.com/x1mrdonut1x)
  - 🐞 修复 Menu 收起模式下设置 `getPopupContainer` 时标题显示错误的问题。[#22182](https://github.com/ant-design/ant-design/pull/22182)
  - 🐞 修复 Avatar 在水平 Menu 中的 `margin` 样式问题。[#22038](https://github.com/ant-design/ant-design/pull/22038) [#22033](https://github.com/ant-design/ant-design/pull/22033)
- Slider
  - 🐞 修复 Slider 垂直情况下拖动节点的位置错误的问题。[#22135](https://github.com/ant-design/ant-design/pull/22135) [@wendellhu95](https://github.com/wendellhu95)
  - 💄 修复 Slider 丢失的 `focus` 样式。[#22161](https://github.com/ant-design/ant-design/pull/22161)
- Table
  - 🐞 修复 Table 筛选功能抛出 `Cannot read property 'map' of undefined` 的问题。[#22096](https://github.com/ant-design/ant-design/pull/22096) [@yoyo837](https://github.com/yoyo837)
  - 🐞 修复 ConfigProvider 没有作用在 Table 过滤弹框上的问题。[#22133](https://github.com/ant-design/ant-design/pull/22133)
  - 🐞 修复 Table 树形结构下展开与固定列配合的样式问题。[#22131](https://github.com/ant-design/ant-design/pull/22131)
  - 🐞 修复 Table 选择列固定时展开列不固定的问题。[#22087](https://github.com/ant-design/ant-design/pull/22087)
  - 🐞 修复 Table 过滤菜单重置失效的问题。[#22079](https://github.com/ant-design/ant-design/pull/22079)
  - 🐞 修复 Table 筛选子菜单高度溢出屏幕的问题。[#22230](https://github.com/ant-design/ant-design/pull/22230)
- Form
  - 💄 优化 Form 的响应式和盒模型表现。[#21907](https://github.com/ant-design/ant-design/pull/21907) [@shaodahong](https://github.com/shaodahong)
  - 🐞 修复 FormItem 在 hooks 中报错的问题。[#22053](https://github.com/ant-design/ant-design/pull/22053) [@kagawagao](https://github.com/kagawagao)
- 🐞 修复 Input.Group 中使用 自定义图标换行的问题。[#22197](https://github.com/ant-design/ant-design/pull/22197) [@xrkffgg](https://github.com/xrkffgg)
- 💄 修复 Calendar 年月选择菜单内容被省略的问题。[#22148](https://github.com/ant-design/ant-design/pull/22148)
- 💄 调整 Select 单选框 `padding` 样式以防止下拉框内容的抖动。[#22167](https://github.com/ant-design/ant-design/pull/22167)
- 💄 修复 Dropdown 内容和图标重叠问题。[#22098](https://github.com/ant-design/ant-design/pull/22098) [@xrkffgg](https://github.com/xrkffgg)
- 🐞 修复 Select 在 Firefox 下异常省略的问题。[#22101](https://github.com/ant-design/ant-design/pull/22101)
- 🐞 移除 PageHeader 中不必要的 `overflow: hidden` 样式以修复弹层隐藏问题，优化 PageHeader 右侧按钮的响应式表现。[#22030](https://github.com/ant-design/ant-design/pull/22030)
- 🐞 修复 Radio 组无法正确换行的问题。[#22229](https://github.com/ant-design/ant-design/pull/22229)
- 🐞 修复 TextArea `autoSize` 时在 Firefox 下不会自动滚动到底的问题。[#22014](https://github.com/ant-design/ant-design/pull/22014)
- 🇫🇷 补全的 fr_FR 国际化文本。[#22122](https://github.com/ant-design/ant-design/pull/22122) [@PaulJln](https://github.com/PaulJln)
- RTL
  - 💄 优化 Pagination 在 RTL 模式下的样式。[#22155](https://github.com/ant-design/ant-design/pull/22155) [@xrkffgg](https://github.com/xrkffgg)
  - 💄 修复 Cascader RTL 模式下 icon 样式的错误的问题。[#22191](https://github.com/ant-design/ant-design/pull/22191) [@xrkffgg](https://github.com/xrkffgg)
  - 💄 优化 Checkbox.Group 在 RTL 模式下样式。[#22186](https://github.com/ant-design/ant-design/pull/22186) [@xrkffgg](https://github.com/xrkffgg)
  - 💄 优化 Radio.Button 在 RTL 模式下样式问题。[#22066](https://github.com/ant-design/ant-design/pull/22066) [@xrkffgg](https://github.com/xrkffgg)
  - 🐞 优化 Table 固定列在 RTL 下的样式问题。[#21914](https://github.com/ant-design/ant-design/pull/21914) [@saeedrahimi](https://github.com/saeedrahimi)
  - 💄 调整 Dropdown 在 RTL 模式的下拉图标方向。[#22104](https://github.com/ant-design/ant-design/pull/22104) [@xrkffgg](https://github.com/xrkffgg)
  - 💄 优化 Breadcrumb 在 RTL 模式下样式。[#22159](https://github.com/ant-design/ant-design/pull/22159) [@xrkffgg](https://github.com/xrkffgg)
  - 💄 优化 Steps 组件在 RTL 模式下的样式。[#22175](https://github.com/ant-design/ant-design/pull/22175) [@xrkffgg](https://github.com/xrkffgg)
  - 💄 优化表单反馈下在 RTL 模式下的样式。[#22222](https://github.com/ant-design/ant-design/pull/22222)
- TypeScript
  - 🔷 更新 FormList 的 `operation` 类型定义。[#22058](https://github.com/ant-design/ant-design/pull/22058) [@kagawagao](https://github.com/kagawagao)
  - 🔷 更新 Tooltip 等组件的 `trigger` 参数的定义。[#22043](https://github.com/ant-design/ant-design/pull/22043) [@wendellhu95](https://github.com/wendellhu95)

## 4.0.2

`2020-03-08`

- Form
  - 🐞 修复嵌套 Form.Item 移除会导致 React 报警告的问题。[#21896](https://github.com/ant-design/ant-design/pull/21896)
  - ⚡️ `Form.useForm` 现在将返回相同的实例以优化重复渲染的问题。[#21927](https://github.com/ant-design/ant-design/pull/21927)
  - ⚡️ 重构 Form.Item 渲染逻辑以使其子元素为纯组件时值变更只会渲染一次。[#21991](https://github.com/ant-design/ant-design/pull/21991)
  - ⚡️ FormContext 使用 memoized 值避免 Form.Item 产生额外的渲染。[#21980](https://github.com/ant-design/ant-design/pull/21980) [@qiqiboy](https://github.com/qiqiboy)
- Table
  - 🐞 修复 Table 内浮层组件弹出方向异常的问题。[#21905](https://github.com/ant-design/ant-design/pull/21905)
  - 🐞 修复 Table `className` 和 `style` 作用在了错误的元素上的问题。[#21974](https://github.com/ant-design/ant-design/pull/21974)
  - 🐞 修复 Table `expandIconColumnIndex` 与 `rowSelection` 共用时的展示顺序问题。[#21915](https://github.com/ant-design/ant-design/pull/21915)
  - 🐞 修复 Table `size="small"` 时表头颜色和其他尺寸不一致的问题。[#21942](https://github.com/ant-design/ant-design/pull/21942)
- Select
  - 🐞 修复 Select 在空字符串值时的样式对齐问题。[#21880](https://github.com/ant-design/ant-design/pull/21880)
  - 🐞 修复小号 Select 在多选模式下 `tag` 文字不居中的问题。[#21940](https://github.com/ant-design/ant-design/pull/21940) [@xrkffgg](https://github.com/xrkffgg)
- Menu
  - 🐞 修复 Menu 弹出菜单底部边距丢失的问题。[#21867](https://github.com/ant-design/ant-design/pull/21867)
  - 🐞 修复 Menu 水平模式下 Menu.Item 只有一个 Icon 时仍然有额外 `margin` 的问题。[#21925](https://github.com/ant-design/ant-design/pull/21925)
  - 🐞 修复 Menu 弹出菜单超出屏幕高度的问题。[#21930](https://github.com/ant-design/ant-design/pull/21930)
- 🐞 修复 Badge 数字在 10 和 11 切换时的动画错误。[#21834](https://github.com/ant-design/ant-design/pull/21834) [@wendellhu95](https://github.com/wendellhu95)
- 🐞 修复 Radio.Button 上使用 Tooltip 会报 `Function components cannot be given refs` 警告。[#21895](https://github.com/ant-design/ant-design/pull/21895)
- 🐞 修复 Descriptions 内容为 falsy 值时样式丢失的问题。[#21901](https://github.com/ant-design/ant-design/pull/21901)
- 🐞 修复 DatePicker 在分隔符上的鼠标手型。[#21937](https://github.com/ant-design/ant-design/pull/21937) [@xrkffgg](https://github.com/xrkffgg)
- 🐞 修复 ConfigProvider `prefixCls` 在 Input.Password 上不生效的问题。[#21953](https://github.com/ant-design/ant-design/pull/21953) [@tdida](https://github.com/tdida)
- 🐞 修复 Carousel `dots` 控件不居中的问题。[#21960](https://github.com/ant-design/ant-design/pull/21960) [@liusiasi](https://github.com/liusiasi)
- 🐞 修复 Input.Search 边框高亮样式在 `rtl` 模式下丢失的问题。[#21946](https://github.com/ant-design/ant-design/pull/21946) [@xrkffgg](https://github.com/xrkffgg)
- Less
  - 🆕 新增 `@outline-fade` 变量。[#20227](https://github.com/ant-design/ant-design/pull/20227) [@Satloff](https://github.com/Satloff)
  - 🆕 新增 `@form-item-label-height` 变量。[#21912](https://github.com/ant-design/ant-design/pull/21912)
- TypeScript
  - 🌟 增强 Form.Item `renderProps` 定义。[#21911](https://github.com/ant-design/ant-design/pull/21911)

## 4.0.1

`2020-03-04`

- Form
  - 🐞 修复 Form help 受控时会导致 `react@16.13` 报警告的问题。[#21800](https://github.com/ant-design/ant-design/pull/21800) [#21702](https://github.com/ant-design/ant-design/pull/21702)
  - 🐞 修复 Form.Item 宽度在内容过长时会超出 Form 的样式问题。[#21682](https://github.com/ant-design/ant-design/pull/21682)
- Input
  - 🐞 修复 TextArea 样式在 `react@16.13` 下会报警告的问题。[#21703](https://github.com/ant-design/ant-design/pull/21703)
  - 🐞 修复 Input.Search 有 `prefix` 时的右边框样式问题。[#21753](https://github.com/ant-design/ant-design/pull/21753)
- Table
  - 🐞 修复 Table column 的 `filtered` 属性无效的问题。[#21825](https://github.com/ant-design/ant-design/pull/21825)
  - 🐞 修复 Table `locale` 无效的问题。[#21772](https://github.com/ant-design/ant-design/pull/21772)
  - 🐞 修复 Table.Column `sortOrder` 在 JSX 模式下无效的问题。[#21719](https://github.com/ant-design/ant-design/pull/21719)
  - 🐞 修复 Table 固定列在排序状态时的样式问题。[#21679](https://github.com/ant-design/ant-design/pull/21679)
- 🐞 修复 Dropdown 菜单里箭头图标的位置。[#21768](https://github.com/ant-design/ant-design/pull/21768) [@xrkffgg](https://github.com/xrkffgg)
- 🐞 修复 List 组件 `bordered` 和 `split` 属性冲突的问题。[#21784](https://github.com/ant-design/ant-design/pull/21784) [@MXWXZ](https://github.com/MXWXZ)
- 🐞 修复 Menu.Item 中 `a` 标签换行无法显示的问题。[#21699](https://github.com/ant-design/ant-design/pull/21699) [@shaodahong](https://github.com/shaodahong)
- 🐞 修复 `message.open` 中 `icon` 为空时报错的问题。[#21747](https://github.com/ant-design/ant-design/pull/21747) [@AshoneA](https://github.com/AshoneA)
- 🐞 修复 Result `status` 属性不能赋值 string 或者 number 类型的问题。[#21691](https://github.com/ant-design/ant-design/pull/21691)
- 🐞 修复 Descriptions 报 `key` 重复的警告信息。[#21688](https://github.com/ant-design/ant-design/pull/21688)
- 💄 优化 Calendar 在窄屏幕下的标题样式。[#21813](https://github.com/ant-design/ant-design/pull/21813)
- 💄 Radio.Group 不再折行。[#21813](https://github.com/ant-design/ant-design/pull/21813)
- 🛠 重构 icons 导入代码以降低没有开启 tree shaking 的打包尺寸。[#21752](https://github.com/ant-design/ant-design/pull/21752)
- Typescript
  - 🐞 修复 Radio.Button 的类型定义。[#21807](https://github.com/ant-design/ant-design/pull/21807) [@jhoneybee](https://github.com/jhoneybee)
  - 🐞 修复了 `TreeSelect.SHOW_*` 的类型问题。[#21791](https://github.com/ant-design/ant-design/pull/21791) [@TennyZhuang](https://github.com/TennyZhuang)
  - 🐞 修复 TreeSelect 缺失 `suffix` 定义。[#21714](https://github.com/ant-design/ant-design/pull/21714)
  - 🐞 修复 Drawer `forceRender` 的 TypeScript 定义。[#21774](https://github.com/ant-design/ant-design/pull/21774)
  - 🐞 修复 Tree `treeData` 定义。[#21756](https://github.com/ant-design/ant-design/pull/21756)
  - 🐞 修复 Form.Item `renderProps` 的类型定义。[#21716](https://github.com/ant-design/ant-design/pull/21716)

## 4.0.0

`2020-02-28`

- 🏆 Ant Design v4 发布！点击[此处](https://github.com/ant-design/ant-design/issues/21656)查看更多信息。
- 🐞 Breadcrumb 使用 `path` 作为默认 key 以修复 `name` 作为 key 重名的冲突问题。[#21583](https://github.com/ant-design/ant-design/pull/21583) [@douxc](https://github.com/douxc)
- 🌟 Timeline.Item 支持 `label`。[#21560](https://github.com/ant-design/ant-design/pull/21560) [@shaodahong](https://github.com/shaodahong)
- 🐞 修复 Table 筛选菜单高度溢出屏幕的问题。[#21602](https://github.com/ant-design/ant-design/pull/21602)
- 💄 增加 Calendar 组件自定义显示内容的默认字体颜色。[#21598](https://github.com/ant-design/ant-design/pull/21598) [@xrkffgg](https://github.com/xrkffgg)
- 🚮 移除 DatePicker 针对自定义单元格的 3.x 的兼容类名。[#21589](https://github.com/ant-design/ant-design/pull/21589)
- 🐞 修复 RangePicker 在 IE11 下的样式渲染问题。[#21587](https://github.com/ant-design/ant-design/pull/21587)
- 🛠 Progress 中 `strokeColor` 属性现在会忽略错误的百分比参数。[#21564](https://github.com/ant-design/ant-design/pull/21564) [@AshoneA](https://github.com/AshoneA)
- 🐞 修复 Progress `trailColor` 属性在 `type=line` 时无效果的问题。[#21552](https://github.com/ant-design/ant-design/pull/21552) [@AshoneA](https://github.com/AshoneA)
- 🐞 修复暗色主题下，组件在弹出层组件下的背景样式问题。[#21299](https://github.com/ant-design/ant-design/pull/21299)
  - 💄 优化暗色主题下色板透明度。
  - 🌟 新增 less 变量 `@popover-customize-border-color`、`@list-customize-card-bg`、`@table-expand-icon-bg`、`@steps-background`、`@pagination-item-input-bg` 用于主题定制。

## 4.0.0-rc.6

`2020-02-24`

- Form
  - 🌟 支持 `scrollToFirstError` 属性以简化提交表单滚动到错误字段的编码量。[#21462](https://github.com/ant-design/ant-design/pull/21462)
  - 🐞 修复 Form.Item 设置 `help` 时的样式问题。[#21476](https://github.com/ant-design/ant-design/pull/21476)
  - 🐞 修复 Form 和 BraftEditor 同时使用时抛错的问题。[#21425](https://github.com/ant-design/ant-design/pull/21425)
  - 🐞 修复 Form 验证信息切换时表单项抖动。[#21302](https://github.com/ant-design/ant-design/pull/21302) [@yoyo837](https://github.com/yoyo837)
- Upload
  - 🌟 Upload 组件 `showUploadList` 新增 `removeIcon` 和 `downloadIcon` 属性。[#21363](https://github.com/ant-design/ant-design/pull/21363) [@sdhr27](https://github.com/sdhr27)
  - 🐞 修复 Upload 识别图片类型逻辑错误。[#21473](https://github.com/ant-design/ant-design/pull/21473) [@holynewbie](https://github.com/holynewbie)
  - 💄 优化 Upload `showDownloadIcon` 默认不展示。[b4636](https://github.com/ant-design/ant-design/commit/b4636ab2dfdb006c14bdb3d5d7de09e1650c3567)
- Input
  - 🐞 修复 Input 在设置 `readOnly` 时 `allowClear` 仍然可以清除的问题。[#21494](https://github.com/ant-design/ant-design/pull/21494)
  - 🐞 修复 Input 点击 `prefix` / `suffix` 不会获得焦点的问题。[#21413](https://github.com/ant-design/ant-design/pull/21413)
- Table
  - 🐞 修复 Table 选择在树形结构子节点为 `null` 会崩溃的问题。[#21528](https://github.com/ant-design/ant-design/pull/21528)
  - 🐞 修复 Table 在 `small` 尺寸下固定列的样式问题。[#21431](https://github.com/ant-design/ant-design/pull/21431)
- Descriptions
  - 🐞 修复非 `bordered` 时，`label` 不存在仍然会渲染 label 元素的问题。[#21542](https://github.com/ant-design/ant-design/pull/21542)
  - 🐞 修复 `vertical` 下且非 `bordered` 标题也是 `td` 的问题。[#21542](https://github.com/ant-design/ant-design/pull/21542)
  - 🐞 修复 `vertical` 且 `bordered` 布局混乱的问题。[#21542](https://github.com/ant-design/ant-design/pull/21542)
  - 🐞 修复 `style` 无法作用于 `Item` 的问题。[#21542](https://github.com/ant-design/ant-design/pull/21542)
  - 🐞 修复 `border` 下 `th` 还会额外获得无用的 `-colon` className 的问题。[#21542](https://github.com/ant-design/ant-design/pull/21542)
- 🌟 Select 增加 `tagRender` 支持自定义 tag 内容。[#21064](https://github.com/ant-design/ant-design/pull/21064) [@fguitton](https://github.com/fguitton)
- 💄 调整 Picker 的 `onPanelChange` 在面板值变化时也会触发。[#21455](https://github.com/ant-design/ant-design/pull/21455)
- 🐞 修复 Notification 第一次重复调用无法堆叠的问题。[#21531](https://github.com/ant-design/ant-design/pull/21531)
- 🐞 修复 TreeSelect 弹出层不更新的问题。[#21410](https://github.com/ant-design/ant-design/pull/21410)
- 💄 优化 Divider 内嵌文字的默认 `padding`，并新增 `@divider-text-padding` 变量。[#21407](https://github.com/ant-design/ant-design/pull/21407)
- Typescript
  - 🐞 修复 Form 组件类型。[#21483](https://github.com/ant-design/ant-design/pull/21483) [#21411](https://github.com/ant-design/ant-design/pull/21411)

## 4.0.0-rc.5

`2020-02-16`

- 🐞 修复 Form.Item 设置 `validateFirst` 导致表单无法提交的问题。[#21329](https://github.com/ant-design/ant-design/pull/21329)
- 🐞 解决了 InputNumber 删除连续相同数字时的光标位置问题。[#21344](https://github.com/ant-design/ant-design/pull/21344)
- 💄 Menu 移除掉多余的背景色。[#21365](https://github.com/ant-design/ant-design/pull/21365)
- 💄 优化 DatePicker 组件 `disabled` 状态的鼠标样式。[#21352](https://github.com/ant-design/ant-design/pull/21352)
- 🐞 修复 Affix 在移动设备下抛错 `Cannot read property getBoundingClientRect` 的问题。[#21350](https://github.com/ant-design/ant-design/pull/21350)
- 🐞 修复 Form 在屏幕小于 `xs` 时标签宽度不正确的问题。[#21222](https://github.com/ant-design/ant-design/pull/21222)
- 🐞 修复 Input 在 `size` 为 `large` 时的高度问题。[#21338](https://github.com/ant-design/ant-design/pull/21338)
- 🐞 修复 Badge 包裹模式下 `color` 属性失效的问题。[#21333](https://github.com/ant-design/ant-design/pull/21333)
- 🐞 修复 Alert 关闭按钮额外的 `padding`。[#21325](https://github.com/ant-design/ant-design/pull/21325)
- 💄 微调 Steps 文本 1px 使其居中对齐。[#21306](https://github.com/ant-design/ant-design/pull/21306)
- 💄 修复遗留的 Button.Group `large` 尺寸的样式问题。[#21307](https://github.com/ant-design/ant-design/pull/21307)
- 💄 修正 TextArea `allowClear` 中的输入边框半径的样式问题和 Input `suffix` 在 Firefox 下的样式问题。[#21316](https://github.com/ant-design/ant-design/pull/21316)
- 🐞 Pagination 自定义 `itemRender` 返回的上一页下一页现在会补充 `disabled` 属性。[#21361](https://github.com/ant-design/ant-design/pull/21361)
- 🇦🇿 添加了阿塞拜疆语翻译。[#21387](https://github.com/ant-design/ant-design/pull/21387) [@orkhan-huseyn](https://github.com/orkhan-huseyn)
- Typescript
  - 🔷 Menu 导出 `MenuItemGroupProps`。[#21356](https://github.com/ant-design/ant-design/pull/21356)
  - 🔷 Table 导出 `ColumnProps`。[#21321](https://github.com/ant-design/ant-design/pull/21321)

## 4.0.0-rc.4

`2020-02-09`

- 📖 官网提供了暗色模式下的 [色板](https://preview-21101-ant-design.surge.sh/docs/spec/dark-cn#%E5%9F%BA%E7%A1%80%E8%89%B2%E6%9D%BF) 和 [色板生成工具](https://preview-21101-ant-design.surge.sh/docs/spec/dark-cn#%E8%89%B2%E6%9D%BF%E7%94%9F%E6%88%90%E5%B7%A5%E5%85%B7)。[#21101](https://github.com/ant-design/ant-design/pull/21101)
- 🌟 Checkbox.Group 和 Radio.Group 的 `options` 属性中新增 `style` 字段，用于设置可选项的样式。[#21219](https://github.com/ant-design/ant-design/pull/21219)
- 🌟 Form.Item 新增 `validateFirst` 属性，用于设置当某一规则校验不通过时，是否停止剩下规则的校验。[#21178](https://github.com/ant-design/ant-design/pull/21178)
- 🌟 Modal 新增 `useModal` hook，以支持 `context` 访问。[#20949](https://github.com/ant-design/ant-design/pull/20949)
- 🌟 Notification 新增 `useNotification` hook，以支持 `context` 访问。[#21275](https://github.com/ant-design/ant-design/pull/21275)
- 🌟 Select、TreeSelect、DatePicker、TimePicker 和 Cascader 新增 `bordered` 属性，用于设置组件是否有边框。[#21242](https://github.com/ant-design/ant-design/pull/21242)
- 🌟 Transfer 新增 `selectAllLabels` 属性，用于自定义头部选择框的文案。[#21139](https://github.com/ant-design/ant-design/pull/21139) [@morenyang](https://github.com/morenyang)
- 💄 重新设计了 Tabs 火柴棍的样式。[#21256](https://github.com/ant-design/ant-design/pull/21256)
- 💄 新增 `@form-item-label-font-size` less 变量。[#21216](https://github.com/ant-design/ant-design/pull/21216)
- 🐞 修复 Badge 在 Typography 下数字错位的问题。[#21235](https://github.com/ant-design/ant-design/pull/21235)
- 🐞 修复 Checkbox 和 Checkbox.Group 之间被其他组件隔断时多选框无法选中的问题。[#21146](https://github.com/ant-design/ant-design/pull/21146) [@morenyang](https://github.com/morenyang)
- 🐞 修复 Collapse.Panel 设置了 `extra` 属性时内容宽度变窄的问题。[#21202](https://github.com/ant-design/ant-design/pull/21202) [@zhiyuc123](https://github.com/zhiyuc123)
- Form
  - 🐞 修复 Form.Item 没有设置 `name` 属性时必填校验不生效的问题。[#21168](https://github.com/ant-design/ant-design/pull/21168)
  - 🐞 修复 Form.Item 的 `name` 属性为 `0` 时数据绑定不生效的问题。[#21186](https://github.com/ant-design/ant-design/pull/21186) [@wanjas](https://github.com/wanjas)
  - 🐞 修复 Form.Item 的 `help` 属性从有到无时会造成布局抖动的问题。[#21211](https://github.com/ant-design/ant-design/pull/21211)
- Input
  - 🐞 修复设置了前缀时校验样式不正确的问题。[#21121](https://github.com/ant-design/ant-design/pull/21121)
  - 🐞 修复设置了前缀或后缀时 `size` 属性不生效的问题。[#21290](https://github.com/ant-design/ant-design/pull/21290) [@yoyo837](https://github.com/yoyo837)
- 🐞 修复 Radio.Group 中使用 Badge 的样式问题。[#21215](https://github.com/ant-design/ant-design/pull/21215)
- 🐞 修复 Select 在多选或标签模式下上下行之间没有外间距的问题。[#21175](https://github.com/ant-design/ant-design/pull/21175)
- 🐞 修复 Slider 的锚点聚焦样式错误的问题。[#21244](https://github.com/ant-design/ant-design/pull/21244) [@Kermit-Xuan](https://github.com/Kermit-Xuan)
- 🐞 修复 Steps 在 `size="small"` 和 `labelPlacement="vertical"` 时图标没有对齐的问题。[#21258](https://github.com/ant-design/ant-design/pull/21258)
- Table
  - 🐞 修复数据项没有 `children` 字段时 `expandIcon` 属性不生效的问题。[#21169](https://github.com/ant-design/ant-design/pull/21169)
  - 🐞 修复 Column 的 `sorter` 属性不生效的问题。[#21194](https://github.com/ant-design/ant-design/pull/21194)
  - 🐞 修复自定义筛选无法输入的问题。[#21218](https://github.com/ant-design/ant-design/pull/21218)
- 🐞 修复 TimePicker 的 `defaultOpenValue` 属性不生效的问题。[#21198](https://github.com/ant-design/ant-design/pull/21198)
- Transfer
  - 🐞 修复头部选择框文案的单位展示不正确的问题。[#21136](https://github.com/ant-design/ant-design/pull/21136) [@morenyang](https://github.com/morenyang)
  - 🐞 修复搜索框中的搜索图标没有垂直居中的问题。[#21247](https://github.com/ant-design/ant-design/pull/21247)
- 🐞 修复 Typography 在可编辑状态时光标没有在输入框末尾的问题。[#21268](https://github.com/ant-design/ant-design/pull/21268)

## 4.0.0-rc.3

`2020-01-27`

- 🛠 移除 Countdown 组件的 `moment` 依赖。[#21108](https://github.com/ant-design/ant-design/pull/21108) [@morenyang](https://github.com/morenyang)
- 🐞 修复 Input `suffix / prefix` 样式与 `addonBefore / addonAfter` 冲突的问题。[#21105](https://github.com/ant-design/ant-design/pull/21105)
- 💄 完善 Timeline 组件 RTL 模式下的样式。[#21068](https://github.com/ant-design/ant-design/pull/21068) [@xrkffgg](https://github.com/xrkffgg)
- 💄 更新基本样式 `clearfix` 移除过时的 `zoom` 属性。[#21109](https://github.com/ant-design/ant-design/pull/21109) [@morenyang](https://github.com/morenyang)
- 💄 Card 组件使用 `@font-size-base` 变量以代替固定的 `14px`。[#21107](https://github.com/ant-design/ant-design/pull/21107) [@morenyang](https://github.com/morenyang)
- 💄 调整 Layout 组件传入的 `className` 到最后以提高其优先级。[#21074](https://github.com/ant-design/ant-design/pull/21074) [@yoyo837](https://github.com/yoyo837)
- Typescript
  - 🐞 修复 Tree 中 AntTreeNodeMouseEvent 的定义问题。[#21102](https://github.com/ant-design/ant-design/pull/21102) [@Jirka-Lhotka](https://github.com/Jirka-Lhotka)
  - 🐞 修复 Form.Item 返回的类型定义。[#21067](https://github.com/ant-design/ant-design/pull/21067)

## 4.0.0-rc.2

`2020-01-21`

- 🛠 部分演示改写成 React hooks 和 TypeScript。[#21045](https://github.com/ant-design/ant-design/pull/21045)
- 🐞 修复 Input/Select 等组件的 `1px` 对齐问题。[#20869](https://github.com/ant-design/ant-design/pull/20869)
- Dropdown
  - 🆕 新增 `buttonsRender` 用于定制按钮，如给左侧按钮增加 Tooltip。[#20815](https://github.com/ant-design/ant-design/pull/20815)
  - 🐞 修复禁用的 Dropdown.Button 在 Chrome 下 Tooltip 不会消失的问题。[#20960](https://github.com/ant-design/ant-design/pull/20960)
- Input
  - 🐞 修复 Input `prefix` 和 `suffix` 和输入内容重叠的问题。[#20872](https://github.com/ant-design/ant-design/pull/20872)
  - 🐞 修复 Input `placeholder` 在 Firefox 下的颜色问题。[#20850](https://github.com/ant-design/ant-design/issues/20850)
- Table
  - 🐞 修复 `onChange` 返回缓存排序、过滤状态的问题。[#20858](https://github.com/ant-design/ant-design/pull/20858)
  - 🐞 修复全选在所有选项为禁用时为勾选状态的问题。[#20968](https://github.com/ant-design/ant-design/pull/20968)
  - 🐞 修复 `locale.emptyText` 不生效的问题。[#21024](https://github.com/ant-design/ant-design/pull/21024)
- Select
  - 🐞 修复 `placeholder` 的换行和对齐问题。[#20883](https://github.com/ant-design/ant-design/pull/20883) [#20884](https://github.com/ant-design/ant-design/pull/20884)
  - 🐞 修复多选 Select 的左边距。[#20861](https://github.com/ant-design/ant-design/pull/20861)
  - 🐞 修复多选 Select 清除按钮和选项重叠的问题。[#20914](https://github.com/ant-design/ant-design/pull/20914)
- Form
  - 🆕 `scrollToField` 方法支持传入滚动相关参数。[#20774](https://github.com/ant-design/ant-design/pull/20774)
  - 🐞 修复 Form.Item 改变 `help` 会导致布局闪动的问题。[#20886](https://github.com/ant-design/ant-design/pull/20886)
  - 🐞 修复 Form.Item 即便不是一个真正的 Field 也会触发重新渲染的问题。[#20963](https://github.com/ant-design/ant-design/pull/20963)
  - 🐞 修复 Form.Item 不处理 `help=""` 的问题。[#21026](https://github.com/ant-design/ant-design/pull/21026)
  - 🐞 修复 Form.Item `label` 在屏幕小于 xs 并且 `span` 不是 24 的时候对齐不正确。[#20836](https://github.com/ant-design/ant-design/issues/20836)
- 🐞 修复 message 隐藏时阴影切边的问题。[#20856](https://github.com/ant-design/ant-design/issues/20856)
- 🐞 修复 Tooltip `title` 为 `0` 时没有显示问题。[#20894](https://github.com/ant-design/ant-design/pull/20894)
- 🐞 修复 List `actions` 位置不在右边的问题。[#20897](https://github.com/ant-design/ant-design/pull/20897)
- 🆕 新增一个 Tree 的虚拟滚动演示。[#20911](https://github.com/ant-design/ant-design/pull/20911)
- 🐞 修复 AutoComplete 演示样式错位的问题。[#20946](https://github.com/ant-design/ant-design/pull/20946)
- 🗑 移除掉 AutoComplete 中无用的 `labelInValue` 定义。[#20967](https://github.com/ant-design/ant-design/pull/20967)
- 🐞 修复 Drawer 组件添加 `footerStyle` 属性后控制台报错。[#20983](https://github.com/ant-design/ant-design/pull/20983)
- 🐞 修复 Breadcrumb 在 `rtl` 模式下的样式问题。[#21054](https://github.com/ant-design/ant-design/pull/21054)
- 💄 调整 Layout `className` 的顺序到最后。[#21041](https://github.com/ant-design/ant-design/pull/21041)
- TypeScript
  - 🐞 开放 DatePicker 的相关接口定义。[#20900](https://github.com/ant-design/ant-design/pull/20900)
- Less 变量
  - 🆕 重新加回 `@border-radius-sm` 变量。[#20818](https://github.com/ant-design/ant-design/pull/20818)
  - 🆕 新增 `@timeline-item-padding-bottom` 变量。[#21013](https://github.com/ant-design/ant-design/pull/21013)
  - 🆕 新增 `@layout-header-color` 变量。[#21033](https://github.com/ant-design/ant-design/pull/21033)

## 4.0.0-rc.1

`2020-01-11`

- 🌟 Drawer 增加 `footer` 及 `footerStyle` 属性。[#20690](https://github.com/ant-design/ant-design/pull/20690) [@DeanVanNiekerk](https://github.com/DeanVanNiekerk)
- 🌟 Switch 增加 `@switch-min-width` 和 `@switch-sm-min-width` less 变量。[#20829](https://github.com/ant-design/ant-design/pull/20829) [@abdih](https://github.com/abdih)
- Table
  - 🐞 修复在 `expandRowByClick` 下展开 Icon 点击失效。[#20808](https://github.com/ant-design/ant-design/pull/20808)
  - 🐞 修复在缩放下的展开行宽度样式。[#20805](https://github.com/ant-design/ant-design/pull/20805)
  - 🐞 修复背景色优先级高导致用户自定义样式被覆盖的问题。[#20794](https://github.com/ant-design/ant-design/pull/20794)
  - 🐞 修复在 `rowSelection` 下 `fixed` 属性失效。[#20735](https://github.com/ant-design/ant-design/pull/20735)
  - 🐞 修复固定列在 Chrome 下放大时出现纵向滚动条问题。[#20705](https://github.com/ant-design/ant-design/pull/20705)
  - 🐞 修复 `columns` 为空时 Table 报错问题。[#20703](https://github.com/ant-design/ant-design/pull/20703)
- 💄 优化 Calendar 基本样式月份下拉框宽度、通知事项的文字顺序以及卡片模式，选择框的尺寸。[#20790](https://github.com/ant-design/ant-design/pull/20790) [@xrkffgg](https://github.com/xrkffgg)
- DatePicker
  - 💄 优化圆角连接处 `border-radius`。[#20736](https://github.com/ant-design/ant-design/pull/20736)
  - 🐞 修复选中样式重叠。[#20736](https://github.com/ant-design/ant-design/pull/20736)
  - 🐞 修复底部额外分割线。[#20736](https://github.com/ant-design/ant-design/pull/20736)
  - 🐞 修复预设范围的按钮样式。[#20760](https://github.com/ant-design/ant-design/pull/20760) [@xrkffgg](https://github.com/xrkffgg)
- 🐞 修复 Input 值为 `undefined` 时不能输入的问题。[#20783](https://github.com/ant-design/ant-design/pull/20783)
- 🐞 修复 Carousel 组件 left/right 模式下卡片轮播方向。[#20781](https://github.com/ant-design/ant-design/pull/20781) [@xrkffgg](https://github.com/xrkffgg)
- 🐞 修复 Grid 响应式 gutter 在 SSR 下初始值为 `0` zIndex 的问题。[#20762](https://github.com/ant-design/ant-design/pull/20762)
- 🐞 修复 InputNumber、Select、Table 等组件的图标大小问题。[#20765](https://github.com/ant-design/ant-design/pull/20765)
- 🐞 修复 Badge 在 Table 固定列中穿透的问题。[#20751](https://github.com/ant-design/ant-design/pull/20751)
- 💄 微调默认字体和 tailwindcss 一致。[#20747](https://github.com/ant-design/ant-design/pull/20747)
- 🐞 修复 TextArea `autoSize` 在 FireFox 浏览器下闪烁问题。[#20737](https://github.com/ant-design/ant-design/pull/20737)
- 🐞 修复 Form.Item 动态校验下错误提示不同步的问题。[#20725](https://github.com/ant-design/ant-design/pull/20725)
- 🐞 修复 Form.Item 不设置 `hasFeedback` 时校验，图标闪动问题。[#20691](https://github.com/ant-design/ant-design/pull/20691)
- 🐞 修复 Cascader `fieldNames` 中 `label` 和 `value` 共用一个值时搜索功能失效的问题。[#20720](https://github.com/ant-design/ant-design/pull/20720)
- 🐞 修复 Collapse 背景使用错误的 less 变量。[#20718](https://github.com/ant-design/ant-design/pull/20718) [@kuitos](https://github.com/kuitos)
- 🐞 修复 Slider 中 Tooltip 不跟随鼠标的问题。[#20699](https://github.com/ant-design/ant-design/pull/20699)
- 🐞 修复 Card 封面图片被拉伸的问题。[#20701](https://github.com/ant-design/ant-design/pull/20701)
- 🐞 修复 Typography 使用 `suffix` 属性时溢出问题。[#20689](https://github.com/ant-design/ant-design/pull/20689) [@zouxiaomingya](https://github.com/zouxiaomingya)
- 🐞 修复 AutoComplete 下使用 Input 时的样式错误。[#20686](https://github.com/ant-design/ant-design/pull/20686)
- 🐞 修复 Form 下 Input.Group 偏上一像素的问题。[#20681](https://github.com/ant-design/ant-design/pull/20681)
- TypeScript
  - 🐞 导出 Form 接口类型。[3a1c5](https://github.com/ant-design/ant-design/commit/3a1c51010fecfa59f63f5e09027805a141e9ec11)
  - 🐞 修复 Table 类型缺失。[#20789](https://github.com/ant-design/ant-design/pull/20789)
  - 🐞 修复 Table.Column 及 Table.ColumnGroup 定义。[#20695](https://github.com/ant-design/ant-design/pull/20695)

## 4.0.0-rc.0

`2020-01-04`

Ant Design 4.0-rc 发布，发布文档请查看[此处](https://github.com/ant-design/ant-design/issues/20661)。

⚠️ 从 v3 迁移到 v4 请参考[迁移文档](/docs/react/migration-v4)。

### 新增功能及改进

- 🌟 antd 打包尺寸优化，js gzipped 从 532.75KB 下降到 289.89 KB。[#20356](https://github.com/ant-design/ant-design/pull/20356)
- 💄 新增黑暗主题支持。[#20281](https://github.com/ant-design/ant-design/pull/20281)
- 🌟 ConfigProvider 支持 `direction` 国际化设置 `rtl`。[#19380](https://github.com/ant-design/ant-design/pull/19380)
- 🌟 全新 Form 组件。[#17327](https://github.com/ant-design/ant-design/pull/17327)
  - 🌟 Form 组件自带数据绑定功能。
  - 🌟 字段值改动只会影响相关组件的渲染而非整个 Form。
  - 🌟 新增 `initialValues` 以代替原 field 初始化字段。
  - 🌟 新增 `validateMessages` 以支持修改校验模板。
  - 🌟 新增 `onFinish` 与 `onFinishFailed` 完成整体组件校验逻辑。
  - 🌟 新增 `onFieldsChange` 与 `onValuesChange` 以用于受控状态触发。
  - 🌟 提供 `useForm` 的 hook 支持。
  - 🌟 Form.Item 新增 `name` 属性以进行数据绑定。
  - 🌟 Form.Item `validateTrigger` 将只进行校验触发而不会同时收集字段值。
  - 🌟 Form.Item 新增 `rules` 属性以进行数据校验。
  - 🌟 Form.Item 新增 `shouldUpdate` 属性以支持 render props。
  - 🌟 Form.Item 新增 `dependencies` 属性以简化相关字段更新逻辑。
  - 🌟 Form.Item 新增 `noStyle` 属性以及添加无样式数据绑定。
  - 🌟 新增 Form.List 组件以简化增删改查操作。
  - 🌟 新增 Form.Provider 组件以支持多表联动。
- 🌟 全新 Table 组件。[#19678](https://github.com/ant-design/ant-design/pull/19678)
  - 🌟 添加 `summary` 支持总结行。
  - 🌟 现在 `fixedColumn`、`expandable`、`scroll` 可以混合使用。
  - 🌟 支持多列排序。
  - 🌟 支持自定义 `body` 并添加虚拟滚动例子。
  - 🌟 展开相关功能归入 `expandable` 属性并添加 `rowExpandable` 支持。
  - 🎉 使用 css `sticky` 实现固定效果以优化性能。
  - 💄 优化 `expand` 动画效果。
- 🌟 全新 DatePicker、 TimePicker 与 Calendar 组件。[#20023](https://github.com/ant-design/ant-design/pull/20023)
  - 🌟 支持自定义日期库。
  - 🌟 添加 `picker` 支持设置选择器（不再需要通过受控 `mode` 模拟选择器）。
  - 🌟 全范围选择器支持：时间、日期、周、月、年。
  - 🌟 范围选择器现在可以单独选择开始与结束时间。
  - 🌟 范围选择器可以为开始与结束时间单独设置 `disabled`。
  - 🌟 范围选择器可以允许开始与结束时间为空。
  - 🌟 优化手工输入与键盘交互支持。
  - 🌟 支持 `inputReadOnly` 禁用手动输入。
- 🌟 移除 Icon，使用 `@ant-design/icons` 代替。[#18217](https://github.com/ant-design/ant-design/pull/18217)
- Skeleton
  - 🌟 支持 Skeleton.Avatar 占位组件。[#19898](https://github.com/ant-design/ant-design/pull/19898) [@Rustin-Liu](https://github.com/Rustin-Liu)
  - 🌟 支持 Skeleton.Button 占位组件。[#19699](https://github.com/ant-design/ant-design/pull/19699) [@Rustin-Liu](https://github.com/Rustin-Liu)
  - 🌟 支持 Skeleton.Input 占位组件。[#20264](https://github.com/ant-design/ant-design/pull/20264) [@Rustin-Liu](https://github.com/Rustin-Liu)
- 🌟 Tree 支持虚拟滚动。[#18172](https://github.com/ant-design/ant-design/pull/18172)
- 🌟 Tree 增强无障碍支持以及键盘交互。[#18866](https://github.com/ant-design/ant-design/pull/18866)
- 🌟 Select 使用虚拟滚动并增强无障碍支持以及键盘交互。[#18658](https://github.com/ant-design/ant-design/pull/18658)
  - 🌟 `value` 为 `undefined` 时，改为非受控模式。
- 🌟 TreeSelect 使用虚拟滚动并优化键盘支持。[#19040](https://github.com/ant-design/ant-design/pull/19040)
  - 🌟 `value` 为 `undefined` 时，改为非受控模式。
  - 🌟 `value` 引用未变化时，不再重新渲染多选 Select。
- 🌟 Button 添加 `danger` 的 `default` 和 `link` 样式。[#19837](https://github.com/ant-design/ant-design/pull/19837)
- 🌟 Form 与 ConfigProvider 支持 `size` 设置包含组件尺寸。[#20570](https://github.com/ant-design/ant-design/pull/20570)
- 🌟 Typography 增加 `suffix` 属性。[#20224](https://github.com/ant-design/ant-design/pull/20224)
- 🌟 Progress 增加 `steps` 子组件。[#19613](https://github.com/ant-design/ant-design/pull/19613)
- 🌟 TextArea 支持 `onResize`。[#20408](https://github.com/ant-design/ant-design/pull/20408)
- 🌟 新增 Alert.ErrorBoundary 用于提供友好的出错拦截和提示。[#19923](https://github.com/ant-design/ant-design/pull/19923)
- 🌟 Upload 支持 iconRender 以自定义 icon。[#20034](https://github.com/ant-design/ant-design/pull/20034) [@qq645381995](https://github.com/qq645381995)
- 🌟 Tag 组件预设状态颜色。[#19399](https://github.com/ant-design/ant-design/pull/19399)
- 🌟 Grid 使用 `flex` 布局。[#16635](https://github.com/ant-design/ant-design/pull/16635)
- 🐞 修复 Carousel 组件 `dotposition` 为 `left | right` 的显示错误。[#20645](https://github.com/ant-design/ant-design/pull/20645) [@xrkffgg](https://github.com/xrkffgg)
- 🐞 修复 Alert 组件文本溢出的问题。[#20318](https://github.com/ant-design/ant-design/pull/20318)
- 🙅 移除废弃 API 的警告信息。[#17510](https://github.com/ant-design/ant-design/pull/17510)
- 🙅 为使用 v3 字符串作为 icon 的 Avatar, Button, Modal.method 和 Result 组件增加 warning。[#20226](https://github.com/ant-design/ant-design/pull/20226)
- 💄 添加 `@border-color-split-popover`、`@input-icon-hover-color`、`@select-clear-background`、`@cascader-menu-border-color-split`、`@modal-header-border-color-split`、`@skeleton-to-color`、`@transfer-item-hover-bg` 等 less 变量。[#20070](https://github.com/ant-design/ant-design/pull/20070)

## 3.x

去 [GitHub](https://github.com/ant-design/ant-design/blob/3.x-stable/CHANGELOG.zh-CN.md) 查看 `3.x` 的 Change Log。

## 2.x

去 [GitHub](https://github.com/ant-design/ant-design/blob/2.x-stable/CHANGELOG.zh-CN.md) 查看 `2.x` 的 Change Log。

## 1.11.4

去 [GitHub](https://github.com/ant-design/ant-design/blob/1.x-stable/CHANGELOG.md) 查看 `0.x` 到 `1.x` 的 Change Log。

---
order: 6
title: Change Log
toc: false
timeline: true
---

`antd` strictly follows [Semantic Versioning 2.0.0](http://semver.org/).

#### Release Schedule

- Weekly release: patch version at the end of every week for routine bugfix (anytime for urgent bugfix).
- Monthly release: minor version at the end of every month for new features.
- Major version release is not included in this schedule for breaking change and new features.

---

## 4.16.13

`2021-08-23`

- 🐞 Fix Form `label` and `<Typography.Text ellipsis />` don't work together. [#31838](https://github.com/ant-design/ant-design/pull/31838)
- 🐞 Fix Collapse update failed bug in HMR. [#31827](https://github.com/ant-design/ant-design/pull/31827) [@v4](https://github.com/v4)
- 🐞 Fix circular dependencies in Modal and Input. [#31817](https://github.com/ant-design/ant-design/pull/31817) [@zhyupe](https://github.com/zhyupe)
- RTL
  - 🐞 Fix the rtl config of Modal.confirm custom content missing. [#31828](https://github.com/ant-design/ant-design/pull/31828)

## 4.16.12

`2021-08-16`

- Form
  - 🐞 Fix Form shows `title` on help icon and optional text. [#31785](https://github.com/ant-design/ant-design/pull/31785)
  - 💄 Fix Form `<Input bordered={false} />` outline style. [#31754](https://github.com/ant-design/ant-design/pull/31754)
- Button
  - 💄 Fix Button broken style when using `ghost` and `danger`. [#31780](https://github.com/ant-design/ant-design/pull/31780)
  - 🐞 Fix Button icon not aligned center vertically in Chrome. [#31755](https://github.com/ant-design/ant-design/pull/31755)
- Input
  - 🐞 Fix Input clear icon margin missing with `suffix`. [#31745](https://github.com/ant-design/ant-design/pull/31745)
  - 💄 Fix Input should not have focus style when disabled. [#31738](https://github.com/ant-design/ant-design/pull/31738)
- 🐞 Fix Transfer `showSelectAll={false}` does not hide selection dropdown. [#31746](https://github.com/ant-design/ant-design/pull/31746)
- 💄 Fix Checkbox not aligned center in Checkbox.Group. [#31726](https://github.com/ant-design/ant-design/pull/31726)

## 4.16.11

`2021-08-08`

- 🐞 Fix ConfigProvider rerender unexpectedly when switching some languages. [#31630](https://github.com/ant-design/ant-design/pull/31630) [@Map1en](https://github.com/Map1en)
- 💄 Improve ghost button style rules, no more `!important`. [#31659](https://github.com/ant-design/ant-design/pull/31659)
- 💄 Improve RangePicker range transition style. [#31645](https://github.com/ant-design/ant-design/pull/31645)
- 🤖 Fix Dropdown `destroyPopupOnHide` TypeScript definition missing. [#31700](https://github.com/ant-design/ant-design/pull/31700) [@linxianxi](https://github.com/linxianxi)
- 🤖 Remove useless Omit type which is built-in in TypeScript 3.5+. [#31661](https://github.com/ant-design/ant-design/pull/31661) [@Dreamerryao](https://github.com/Dreamerryao)

## 4.16.10

`2021-08-02`

- 🐞 Fix Badge not showing count when customize `color` prop. [#31617](https://github.com/ant-design/ant-design/pull/31617) [@eokoneyo](https://github.com/eokoneyo)
- 🐞 Fix circle Progress `success.strokeColor` cannot take effect. [#31589](https://github.com/ant-design/ant-design/pull/31589)
- 🐞 Fix the type error due to the Select component didn't ignore the `getRawInputElement` prop. [#31566](https://github.com/ant-design/ant-design/pull/31566) [@aoilti](https://github.com/aoilti)
- 🐞 Fix Pagination's `totalBoundaryShowSizeChanger` property type error. [#31549](https://github.com/ant-design/ant-design/pull/31549) [@Monty-Ma](https://github.com/Monty-Ma)
- 🐞 Fix `className` applied to both Skeleton.Avatar wrapper and element itself. [#31536](https://github.com/ant-design/ant-design/pull/31536) [@Greatshock](https://github.com/Greatshock)
- 🌐 Internationalization
  - 🇹🇷 Added Turkish translation for Image `Preview` text. [#31593](https://github.com/ant-design/ant-design/pull/31593) [@mburakkalkan](https://github.com/mburakkalkan)
  - 🇰🇷 Fix a typo in the Korean language. [#31575](https://github.com/ant-design/ant-design/pull/31575) [@chatoo2412](https://github.com/chatoo2412)

## 4.16.9

`2021-07-27`

- 🐞 Fix Typography `ellipsis` calculation bug when browser zoomed. [#31449](https://github.com/ant-design/ant-design/pull/31449)
- 💄 Fix Input wrong class when using `prefixCls`. [#31479](https://github.com/ant-design/ant-design/pull/31479) [@spawnia](https://github.com/spawnia)
- 💄 Fix Input.Password unexpected focus style of error status. [#31456](https://github.com/ant-design/ant-design/pull/31456)
- 💄 Fix Badge color transition issue when toggle visibility. [#31458](https://github.com/ant-design/ant-design/pull/31458)
- 💄 Fix Tabs `tabBarGutter` abnormal style behaviors. [#31469](https://github.com/ant-design/ant-design/pull/31469)
- 🌐 Internationalization
  - 🇷🇺 Update translation for Image in ru_RU. [#31448](https://github.com/ant-design/ant-design/pull/31448) [@KirillSBarsukov](https://github.com/KirillSBarsukov)
  - 🇩🇰 Add missing translation for Table in da_DK. [#31486](https://github.com/ant-design/ant-design/pull/31486) [@bischmlb](https://github.com/bischmlb)

## 4.16.8

`2021-07-19`

- 🐞 Fix TextArea `style` not work when `allowClear` configured. [#31391](https://github.com/ant-design/ant-design/pull/31391)
- 🐞 Fix BackTop not disappear when fade out. [#31357](https://github.com/ant-design/ant-design/pull/31357)
- 💄 Fix Cascader style bug inside Input `addonBefore`. [#31350](https://github.com/ant-design/ant-design/pull/31350)
- 💄 Fix DatePicker disabled cell style when customize `dateRender`. [#31349](https://github.com/ant-design/ant-design/pull/31349)
- 💄 Fix Select background in disabled. [#31430](https://github.com/ant-design/ant-design/pull/31430) [@DerrickTel](https://github.com/DerrickTel)
- 💄 Fix alignment between Radio.Group and Button. [#31421](https://github.com/ant-design/ant-design/pull/31421) [@gtb104](https://github.com/gtb104)
- 💄 Fix Input clear icon color in some situation. [#31378](https://github.com/ant-design/ant-design/pull/31378)
- Table
  - 💄 Fix Table `sticky` header background is transparent when has sorters. [#31373](https://github.com/ant-design/ant-design/pull/31373)
  - 💄 Fix missing top border of the first cell in table summary. [#31363](https://github.com/ant-design/ant-design/pull/31363)
- 🌐 Internationalization
  - 🇷🇺 Add Table.SELECTION_NONE for Russian localization. [#31361](https://github.com/ant-design/ant-design/pull/31361) [@wwyx778](https://github.com/wwyx778)
  - 🇭🇰 Add missing translations for Transfer in zh_HK. [#31404](https://github.com/ant-design/ant-design/pull/31404) [@kanweiwei](https://github.com/kanweiwei)
  - 🇪🇸 Add missing translation for Image in es_ES. [#31330](https://github.com/ant-design/ant-design/pull/31330) [@Andu15](https://github.com/Andu15)

## 4.16.7

`2021-07-12`

- 🐞 Fix DatePicker date cell not centered when used in Table. [#31306](https://github.com/ant-design/ant-design/pull/31306) [@Map1en](https://github.com/Map1en)
- 🐞 Fix Desciptions border missing when inside Table. [#31307](https://github.com/ant-design/ant-design/pull/31307)
- 🐞 Fix InputNumber border and interactive handler not matched. [#31300](https://github.com/ant-design/ant-design/pull/31300) [@diyews](https://github.com/diyews)
- Table
  - 🐞 Fix incomplete display of the upper border of the table when the window is too small. [#31298](https://github.com/ant-design/ant-design/pull/31298) [@Map1en](https://github.com/Map1en)
  - 🐞 Fix Table `rowSelection.selectedRows` don't sync in initial state. [#31224](https://github.com/ant-design/ant-design/pull/31224) [@kerm1it](https://github.com/kerm1it)
  - 🐞 Fix Table `filteredValue` not work with nested columns. [#30815](https://github.com/ant-design/ant-design/pull/30815) [@moraispgsi](https://github.com/moraispgsi)
- Form
  - 🐞 Fix Form Input outline color under Form validation. [#31240](https://github.com/ant-design/ant-design/pull/31240)
  - 🆕 Form add `name` as a default label value in `validationMessages`. [#30179](https://github.com/ant-design/ant-design/pull/30179) [@jameslahm](https://github.com/jameslahm)
- 💄 Fix Rate focus ring style in Safari. [#31241](https://github.com/ant-design/ant-design/pull/31241)
- 💄 Tweak Select arrow icon position. [#31234](https://github.com/ant-design/ant-design/pull/31234)
- 🐞 Input will not trigger `onBlur` when click clear icon now which resolve that editable table input cannot be cleared. [#31202](https://github.com/ant-design/ant-design/pull/31202)
- 🐞 Fix Tooltip `arrowPointAtCenter` 1px shift bug. [#31201](https://github.com/ant-design/ant-design/pull/31201)
- 💄 Fix Menu.Item hover color transition style. [#31189](https://github.com/ant-design/ant-design/pull/31189)
- 🐞 Fix Dropdown.Button don't support `overlayClassName` and `overlayStyle`. [#31187](https://github.com/ant-design/ant-design/pull/31187)
- 💄 Adjust Pagination pattern of disabled-active buttons align with Radio style. [#31185](https://github.com/ant-design/ant-design/pull/31185) [@Map1en](https://github.com/Map1en)
- 🐞 Fix the path error when packaging the component style export file in the Windows environment. [#31277](https://github.com/ant-design/ant-design/pull/31277) [@aoxiang78](https://github.com/aoxiang78)
- 🌐 Add `selectNone` for en_GB locale file. [#31264](https://github.com/ant-design/ant-design/pull/31264) [@Map1en](https://github.com/Map1en)
- TypeScript
  - 🤖 Adjust Transfer `listStyle` definition to be optional. [#31322](https://github.com/ant-design/ant-design/pull/31322) [@geekrainy](https://github.com/geekrainy)

## 4.16.6

`2021-06-29`

- 🐞 Fix Tree loading status not been restored when `loadData` throw error. [#31170](https://github.com/ant-design/ant-design/pull/31170)
- ⚡️ Optimize Progress animation CPU usage. [#31128](https://github.com/ant-design/ant-design/pull/31128) [@stygian-desolator](https://github.com/stygian-desolator)
- 🐞 Fix Popover arrow cannot show correct color. [#31127](https://github.com/ant-design/ant-design/pull/31127) [@A113n1003](https://github.com/A113n1003)

## 4.16.5

`2021-06-23`

- 🐞 Fix Menu to import `@ant-design/icons` icon directly to reduce bundle size without tree shaking. [#31011](https://github.com/ant-design/ant-design/pull/31011)
- 🐞 Fix Menu with overflow indicator popup do not follow current theme. [#31043](https://github.com/ant-design/ant-design/pull/31043)
- 🐞 Fix Table styles not using `@{table-prefix-cls}` less variable. [#30983](https://github.com/ant-design/ant-design/pull/30983)
- 🐞 Fix Input.Password hover border color in Form validation. [#30999](https://github.com/ant-design/ant-design/pull/30999)
- 🐞 Fix Space with wrap takes additional negative margin style. [#31000](https://github.com/ant-design/ant-design/pull/31000)
- 🐞 Fix Typography warning for non-boolean attribute when set `italic` property. [#31004](https://github.com/ant-design/ant-design/pull/31004)
- 🐞 Fix Badge not passing markup validation. [#31042](https://github.com/ant-design/ant-design/pull/31042) [@conwnet](https://github.com/conwnet)

## 4.16.4

`2021-06-23`

- Broken version, don't use it.

## 4.16.3

`2021-06-14`

- 🐞 Fix the mistake that tooltip mount on wrong dom, when getPopupContainer of tooltip's props is undefined or null. [#30963](https://github.com/ant-design/ant-design/pull/30963) [@ymrdf](https://github.com/ymrdf)
- 🐞 Fix Button lost margin between loading icon and text when children is fragment. [#30962](https://github.com/ant-design/ant-design/pull/30962)
- Table
  - 🐞 Table adds warning when `filteredKeys` is controlled and not reflecting internal changes. [#30882](https://github.com/ant-design/ant-design/pull/30882) [@wendellhu95](https://github.com/wendellhu95)
  - 🐞 Fix Table fixed column header hover background. [#30972](https://github.com/ant-design/ant-design/pull/30972)
- 💄 Adjust Dropdown item content style to make it get more display space. [#30911](https://github.com/ant-design/ant-design/pull/30911)
- 💄 Fix Menu in dark mode open style affect by light mode. [#30907](https://github.com/ant-design/ant-design/pull/30907)
- 🐞 Fix Dropdown/DatePicker/Select/Cascader animation direction after auto adjust position. [#30892](https://github.com/ant-design/ant-design/pull/30892)
- 🌐 Internationalization
  - 🇵🇱 Fix Polish locale. [#30899](https://github.com/ant-design/ant-design/pull/30899) [@MichalJani](https://github.com/MichalJani)

## 4.16.2

`2021-06-07`

- 🐞 Fix Menu auto overflow with `horizontal` mod breaks by `float` element. [#30879](https://github.com/ant-design/ant-design/pull/30879)
- Typography
  - 🐞 Fix the problem that Typography.Paragraph `copyable` will treat `React.Fragment` as an array. [#30869](https://github.com/ant-design/ant-design/pull/30869) [@crazyair](https://github.com/crazyair)
  - 🐞 Fix Typography incorrect ellipsis width when customize `font-size`. [#30840](https://github.com/ant-design/ant-design/pull/30840)
- 🐞 Fix Progress `type="circle"` throws error `Rendered more hooks than during the previous render` sometimes. [#30855](https://github.com/ant-design/ant-design/pull/30855)
- 💄 Optimize Tooltip content width. [#30822](https://github.com/ant-design/ant-design/pull/30822) [@donysukardi](https://github.com/donysukardi)
- Table
  - 🛠 Optimize state display logic of select all checkbox in Table. [#30811](https://github.com/ant-design/ant-design/pull/30811) [@kerm1it](https://github.com/kerm1it)
  - 🐞 Fix Table column which contains filters or sorters cannot work with `onClick` and `ellipsis` property. [#30799](https://github.com/ant-design/ant-design/pull/30799)
- 💄 Fix Dropdown Item with link color style and click icon can also trigger link effect now. [#30802](https://github.com/ant-design/ant-design/pull/30802)
- 💄 Remove duplicated css reset styles for render performance. [#30660](https://github.com/ant-design/ant-design/pull/30660) [@renzhao1113](https://github.com/renzhao1113)
- TypeScript
  - 🤖 Adjust Form, Input, Locale, PageHeader component definition. [#30776](https://github.com/ant-design/ant-design/pull/30776) [@qqabcv520](https://github.com/qqabcv520)

## 4.16.1

`2021-05-30`

- Menu
  - 🐞 Fix overflow not work as expect. [#30672](https://github.com/ant-design/ant-design/pull/30672)
  - 🐞 Fix warning of `Can't perform a React state update on an unmounted component` when unmounted. [#30678](https://github.com/ant-design/ant-design/pull/30678)
  - 🐞 Fix `inline` mode not correct handle ellipsis when `icon` not provided. [#30682](https://github.com/ant-design/ant-design/pull/30682)
- Typography
  - 🐞 Fix Typography.Text trigger ResizeObserver when css ellipsis is validate. [#30664](https://github.com/ant-design/ant-design/pull/30664)
  - 🐞 Fix `ellipsis` not work when HMR take effect in dev env. [#30754](https://github.com/ant-design/ant-design/pull/30754)
- Table
  - 🐞 Fix Table.Summary missing border style when `sticky` and `bordered` enabled. [#30666](https://github.com/ant-design/ant-design/pull/30666)
  - 🐞 Fix column align with sorter and filter. [#30744](https://github.com/ant-design/ant-design/pull/30744)
- 🐞 Fix Collapse expandIconPosition="right" not working. [#30680](https://github.com/ant-design/ant-design/pull/30680) [@hongdeyuan](https://github.com/hongdeyuan)
- TypeScript
  - 🤖 Export TableColumnsType type.[#30747](https://github.com/ant-design/ant-design/pull/30747) [@alwaysloseall](https://github.com/alwaysloseall)
  - 🤖 Export TreeDataNode type. [#30745](https://github.com/ant-design/ant-design/pull/30745) [@alwaysloseall](https://github.com/alwaysloseall)

## 4.16.0

`2021-05-24`

- 🔥 Refactor Menu to support keyboard access and enhance accessibility experience. [#30382](https://github.com/ant-design/ant-design/pull/30382)
- 💄 Redesign Table filter and sorter buttons to clarify current column. [#30651](https://github.com/ant-design/ant-design/pull/30651)
- Table
  - 🆕 Table.Summary supports `sticky` mode. [#30631](https://github.com/ant-design/ant-design/pull/30631)
  - 🐞 Fix nested Table margin inside Table with fixed columns. [#30587](https://github.com/ant-design/ant-design/pull/30587)
  - 🆕 Table add the `expandable.fixed` property to set the expansion icon to be fixed. [#29959](https://github.com/ant-design/ant-design/pull/29959)
- Upload
  - 🆕 Upload `itemRender` add `actions` param. [#30236](https://github.com/ant-design/ant-design/pull/30236)
  - 🆕 Upload: Remove `stopPropagation` from drag events and add `onDrop` prop. [#30319](https://github.com/ant-design/ant-design/pull/30319) [@ebonow](https://github.com/ebonow)
- Typography
  - 🆕 Typography support for italics. [#30458](https://github.com/ant-design/ant-design/pull/30458) [@alwaysloseall](https://github.com/alwaysloseall)
  - 🐞 Fix Typography flush issue when use `ellipsis={{ suffix: 'xxx' }}`. [#30582](https://github.com/ant-design/ant-design/pull/30582)
- Collapse
  - 💄 Fix Collapse arrow style bug when no `header`. [#30586](https://github.com/ant-design/ant-design/pull/30586)
  - 🐞 Fix Collapse content disappears when set `activeKey` while it is hidden. [#30555](https://github.com/ant-design/ant-design/pull/30555) [@zjffun](https://github.com/zjffun)
- 🐞 Fix Menu.SubMenu icon margin issue when using third party icon libraries. [@#30642](https://github.com/ant-design/ant-design/pull/30642)
- 🐞 Fix Descriptions wrong styling import. [@#30602](https://github.com/ant-design/ant-design/pull/30602) [@lisenenkov](https://github.com/lisenenkov)
- 🆕 Radio.Group supports `data-*` and `aria-*` props. [#30507](https://github.com/ant-design/ant-design/pull/30507)
- 🆕 Statistic.CountDown support `onChange` event. [#30265](https://github.com/ant-design/ant-design/pull/30265) [@appleshell](https://github.com/appleshell)
- 🆕 PageHeader `breadcrumb` allows to set as a reactnode. [#30019](https://github.com/ant-design/ant-design/pull/30019) [@gepd](https://github.com/gepd)
- 🆕 ConfigProvider supports dynamic `prefixCls`. [#30625](https://github.com/ant-design/ant-design/pull/30625)
- 🐞 Fix Anchor cannot trigger `onChange` when have `getCurrentAnchor` prop. [#30601](https://github.com/ant-design/ant-design/pull/30601)
- 🐞 Fix Notification custom styles don't apply to correct div by `className` when using `useNotification`. [#30588](https://github.com/ant-design/ant-design/pull/30588)
- 🐞 Fix Tabs `tabBarGutter` not working. [#30545](https://github.com/ant-design/ant-design/pull/30545)
- 💄 Rewrite Space to use `flexGap` instead of `margin` style to deal with layout issues under certain border situations. [#30023](https://github.com/ant-design/ant-design/pull/30023)
- 🐞 Fix Form error style of Input.Group and Cascader. [#30640](https://github.com/ant-design/ant-design/pull/30640)
- 🌐 Internationalization
  - 🇷🇴 Added Romanian internationalization. [#30419](https://github.com/ant-design/ant-design/pull/30419) [@stefy](https://github.com/stefy)
  - 🌐 Added Dutch (Netherland 🇳🇱) and Dutch (Belgium 🇧🇪) internationalization. [#30389](https://github.com/ant-design/ant-design/pull/30389) [@lewis-fidlers](https://github.com/lewis-fidlers)
- TypeScript
  - 🤖 Space TypeScript definition supports HTMLAttribute props. [#30590](https://github.com/ant-design/ant-design/pull/30590)

## 4.15.6

`2021-05-18`

- 🐞 Upload will ignore `accept` if it's invalidate MIME type to follow native behavior. [#30549](https://github.com/ant-design/ant-design/pull/30549)
- 💄 Remove reset style of `th` `text-align`. [#30399](https://github.com/ant-design/ant-design/pull/30399) [@lbwa](https://github.com/lbwa)
- 🌐 Locale
  - 🇮🇳 Improve hi_IN locale. [#30541](https://github.com/ant-design/ant-design/pull/30541) [@jaideepghosh](https://github.com/jaideepghosh)
  - 🇧🇷 Improve pt-BR locale. [#30532](https://github.com/ant-design/ant-design/pull/30532) [@buzs](https://github.com/buzs)

## 4.15.5

`2021-05-10`

- 🐞 Fix Upload crashes if `beforeUpload` returns `false` in IE. [#30391](https://github.com/ant-design/ant-design/pull/30391) [@OleksandrAntonenko1](https://github.com/OleksandrAntonenko1)
- Calendar
  - 🐞 Fix Calendar broken style inside Form.Item. [#30442](https://github.com/ant-design/ant-design/pull/30442)
  - 🐞 Fix Calendar throws error when set `value` to `null` or `undefined`. [#30442](https://github.com/ant-design/ant-design/pull/30442)
- Table
  - 🐞 Fix Table call `confirm({ closeDropdown: true })` in `filterDropdown` should not trigger `onFilterDropdownVisibleChange`. [#30457](https://github.com/ant-design/ant-design/pull/30457)
  - 🐞 Fix Table broken expand icon style in Windows Firefox. [#30410](https://github.com/ant-design/ant-design/pull/30410)
- 🐞 Fix Dropdown.Button don't support `mouseEnterDelay` and `mouseLeaveDelay`. [#30452](https://github.com/ant-design/ant-design/pull/30452)
- 💄 Optimize Rate focus behavior from `:focus` to `:focus-visible`. [#30451](https://github.com/ant-design/ant-design/pull/30451)
- 🐞 Fix Steps with progress get cut at the bottom. [#30373](https://github.com/ant-design/ant-design/pull/30373) [@fachreza73](https://github.com/fachreza73)
- 🐞 Fix the problem that setting `locale` in DatePicker cannot override ConfigProvider `locale`. [#30380](https://github.com/ant-design/ant-design/pull/30380) [@Map1en](https://github.com/Map1en)
- Locale
  - 🇫🇮 Update DatePicker Finnish locale. [#30433](https://github.com/ant-design/ant-design/pull/30433) [@hiiri](https://github.com/hiiri)
  - 🇫🇷 Update French locale with missing messages. [#30436](https://github.com/ant-design/ant-design/pull/30436) [@LoicUV](https://github.com/LoicUV)
  - 🇷🇸 Update Serbian locale. [#30401](https://github.com/ant-design/ant-design/pull/30401) [@vmedar](https://github.com/vmedar)
- TypeScript
  - 🤖 Export Tooltip `zIndex` prop typescript definition. [#30432](https://github.com/ant-design/ant-design/pull/30432)

## 4.15.4

`2021-04-30`

- 🐞 Fix Menu.Item width issue when `collapsedWidth` is set. [#30357](https://github.com/ant-design/ant-design/pull/30357) [@Map1en](https://github.com/Map1en)
- 🐞 Fix Radio check spin style sometime height too long. [#30367](https://github.com/ant-design/ant-design/pull/30367)
- 🐞 Fix Typography.Link open link when trigger `editable`. [#30354](https://github.com/ant-design/ant-design/pull/30354) [@John60676](https://github.com/John60676)
- 🐞 InputNumber clean up input will trigger `onChange(null)` now. [#30337](https://github.com/ant-design/ant-design/pull/30337)
- 🐞 Fix Dropdown.Button broken style when inside Modal `footer`. [#30328](https://github.com/ant-design/ant-design/pull/30328) [@Map1en](https://github.com/Map1en)
- 💄 Replace Anchor default background from `#FFFFFF` to `transparent`. [#30336](https://github.com/ant-design/ant-design/pull/30336)
- 🌐 Add `ko_KR` and `ja_JP` TimePicker.RangePicker placeholder. [#30285](https://github.com/ant-design/ant-design/pull/30285) [@ChalkPE](https://github.com/ChalkPE)
- TypeScript
  - 🤖 Fix Upload type definition of `beforeUpload` and `UploadFile`. [#30351](https://github.com/ant-design/ant-design/pull/30351) [#30343](https://github.com/ant-design/ant-design/pull/30343) [@kerm1it](https://github.com/kerm1it)

## 4.15.3

`2021-04-25`

- Table
  - 🐞 Fix Table selection column width when bordered is true. [#30304](https://github.com/ant-design/ant-design/pull/30304)
  - 🚨 Add warning when Table `current` is negative number. [#30242](https://github.com/ant-design/ant-design/pull/30242) [@wadezhan](https://github.com/wadezhan)
- 🐞 Fix Button `type="link"` should not redirect when it is `disabled`. [#30209](https://github.com/ant-design/ant-design/pull/30209)
- 🐞 Fix Upload appear errors when url of file is `null`. [#30215](https://github.com/ant-design/ant-design/pull/30215)
- 🐞 Fix padding on a SubMenu inside an ItemGroup. [#30218](https://github.com/ant-design/ant-design/pull/30218) [@sebakerckhof](https://github.com/sebakerckhof)
- 🐞 Fix Checkbox & Radio align issue in flex box. [#30260](https://github.com/ant-design/ant-design/pull/30260)
- 🐞 Fix Badge broken animation on spin icon. [#30275](https://github.com/ant-design/ant-design/pull/30275)
- 🐞 Fix Input `disabled` hover style in Form. [#30302](https://github.com/ant-design/ant-design/pull/30302) [@Fog3211](https://github.com/Fog3211)
- TypeScript
  - 🤖 Fix Upload type definition of `beforeUpload`. [#30213](https://github.com/ant-design/ant-design/pull/30213) [@hello-chinese](https://github.com/hello-chinese)

## 4.15.2

`2021-04-19`

- 🐞 Fix Tabs `centered` doesn't work. [#30106](https://github.com/ant-design/ant-design/pull/30106) [@kerm1it](https://github.com/kerm1it)
- 💄 Fix Button `type="link"` disabled cursor style missing. [#30197](https://github.com/ant-design/ant-design/pull/30197)
- 🐞 Fix TextArea `onChange` event return `target` object is not a HTMLTextArea object. [#30124](https://github.com/ant-design/ant-design/pull/30124)
- 🐞 Files in Upload `fileList` will always have uid. [#30087](https://github.com/ant-design/ant-design/pull/30087) [@jameslahm](https://github.com/jameslahm)
- 💄 Fix Badge toggle style when `status` is `warning`. [#30090](https://github.com/ant-design/ant-design/pull/30090) [@jameslahm](https://github.com/jameslahm)
- 🌐 Add Image component `preview` text in zh_HK and zh_TW. [#30100](https://github.com/ant-design/ant-design/pull/30100) [@jameslahm](https://github.com/jameslahm)
- 🌐 add da_DK locale TimePicker.RangePicker. [#30128](https://github.com/ant-design/ant-design/pull/30128) [@themitvp](https://github.com/themitvp)
- TypeScript
  - 🤖 Modify LIST_IGNORE field is of string type. [#30188](https://github.com/ant-design/ant-design/pull/30188) [@hello-chinese](https://github.com/hello-chinese)

## 4.15.1

`2021-04-10`

- 🐞 Fix Descriptions `labelStyle` `contentStyle` unsuccessful when `layout="vertical"` and `bordered={true}`. [#29942](https://github.com/ant-design/ant-design/pull/29942)
- 🐞 Upload won't crash when `fileList` is a frozen object now. [#29944](https://github.com/ant-design/ant-design/pull/29944)
- 🐞 Fix Tabs cannot scroll when vertical mode in Safari 13.1. [#29983](https://github.com/ant-design/ant-design/pull/29983)
- 🐞 Fix Button throws `Cannot read property 'removeChild' of null` in some situation. [#29961](https://github.com/ant-design/ant-design/pull/29961) [@JohnDeved](https://github.com/JohnDeved)
- 🐞 Fix Transfer button's box-shadow getting cut. [#30030](https://github.com/ant-design/ant-design/pull/30030) [@jinchaofs](https://github.com/jinchaofs)
- 🐞 Fix CheckBox.Group cannot work with Form of `@ant-design/compatible`. [#30039](https://github.com/ant-design/ant-design/pull/30039) [@jameslahm](https://github.com/jameslahm)
- 🐞 Fix PageHeader `<Tabs type="card" />` padding missing. [#29819](https://github.com/ant-design/ant-design/pull/29819)
- Table
  - 💄 Optimize Table pagination style when narrow width. [#30065](https://github.com/ant-design/ant-design/pull/30065)
  - 🐞 Fix Table `@table-border-radius-base` not being applied to `.ant-table` node. [#29966](https://github.com/ant-design/ant-design/pull/29966) [@VoliBearCat](https://github.com/VoliBearCat)
- 🐞 Fix Input.TextArea `maxLength` does not work in control mode. [#30070](https://github.com/ant-design/ant-design/pull/30070)
- TypeScript
  - 🤖 Fix Select can not contain `undefined` type. [#30068](https://github.com/ant-design/ant-design/pull/30068) [@Gamote](https://github.com/Gamote)
  - 🤖 Fix Popconfirm `okButtonProps` and `cancelButtonProps` types. [#29928](https://github.com/ant-design/ant-design/pull/29928) [@IggsGrey](https://github.com/IggsGrey)
- Locale
  - 🇪🇸 Add es_ES locale for `Table.SELECTION_NONE`. [#29962](https://github.com/ant-design/ant-design/pull/29962) [@liquorxm](https://github.com/liquorxm)

## 4.15.0

`2021-03-29`

- 🆕 Table now supports `rowSelection.defaultSelectedRowKeys`. [#29879](https://github.com/ant-design/ant-design/pull/29879) [@keelii](https://github.com/keelii)
- 🐞 Fix TextArea display value will be cut by `maxLength` when in controlled. Fix `onCompositionEnd` not trigger when input exceed `maxLength`. Fix emoji count not align with `maxLength` & `showCount`. [#29867](https://github.com/ant-design/ant-design/pull/29867)
- 🐞 Fix Button click effect style not working in shadow root. [#29897](https://github.com/ant-design/ant-design/pull/29897) [@JohnDeved](https://github.com/JohnDeved)
- Pagination
  - 💄 Fix Pagination focus style stay after interaction. [#29891](https://github.com/ant-design/ant-design/pull/29891)
  - 🐞 Fix Pagination jump input height not correct when config `modifyVars`. [#29886](https://github.com/ant-design/ant-design/pull/29886) [@SyMind](https://github.com/SyMind)
- 🐞 Fix Steps progress item getting cut at edge. [#29893](https://github.com/ant-design/ant-design/pull/29893)
- 🛠 Prevent Upload drop event bubbling to handle nest case. [#29832](https://github.com/ant-design/ant-design/pull/29832) [@jojonarte](https://github.com/jojonarte)
- 🐞 Apply ConfigProvider `componentSize` on Tabs component. [#29844](https://github.com/ant-design/ant-design/pull/29844) [@bn3t](https://github.com/bn3t)
- 💄 Remove Tag hover style since it do not have click interactive. [#29874](https://github.com/ant-design/ant-design/pull/29874)
- 🇫🇷 Add missing `fr_FR` translations. [#29839](https://github.com/ant-design/ant-design/pull/29839) [@bn3t](https://github.com/bn3t)
- 🇸🇪 Add missing `sv_SE` translations. [#29896](https://github.com/ant-design/ant-design/pull/29896) [@isakol](https://github.com/isakol)

## 4.14.1

`2021-03-22`

- 🐞 Fix Tabs position shift when active item changed. [#29781](https://github.com/ant-design/ant-design/issues/29781)
- 🐞 Fix `placeholder` not being hidden when Image is loaded from cache. [#29829](https://github.com/ant-design/ant-design/pull/29829)
- 💄 Improve Checkbox/Radio label text layout. [#29788](https://github.com/ant-design/ant-design/pull/29788)
- TypeScript
  - 🤖 Fix Upload type declaration of `beforeUpload`. [#29766](https://github.com/ant-design/ant-design/pull/29766)

## 4.14.0

`2021-03-14`

- Upload
  - 🆕 Upload `onChange` to change back to the original behavior (before Upload false returns the original file, and the rest of the scene returns the encapsulated object). Now you can always get the original file via `onChange.info.originFileObj`. For future upgrades, please use this method to access the original text first. [#29737](https://github.com/ant-design/ant-design/pull/29737)
  - 🐞 Fix Upload `onChange` params `file` can not `cloneDeep` by lodash. [#29718](https://github.com/ant-design/ant-design/pull/29718)
  - 🐞 Fix Upload crash when `fileList` is `null`. [#29702](https://github.com/ant-design/ant-design/pull/29702)
  - 💄 Upload motion add 2s deadline to avoid developer manually remove motion makes hanging. [#29686](https://github.com/ant-design/ant-design/pull/29686)
- 🐞 Fix the bug that Modal footer buttons not spaced properly when using href in button. [#29681](https://github.com/ant-design/ant-design/pull/29681) [@n0ruSh](https://github.com/n0ruSh)
- 🆕 Add parent class for different Notification types. [#29634](https://github.com/ant-design/ant-design/pull/29634) [@n0ruSh](https://github.com/n0ruSh)
- 🆕 Typography editable supports `onCancel` and `onEnd`. [#29615](https://github.com/ant-design/ant-design/pull/29615) [@jueinin](https://github.com/jueinin)
- Tabs
  - 🐞 Fix Tabs `centered` prop is not actually center. [#29495](https://github.com/ant-design/ant-design/pull/29495) [@jinchaofs](https://github.com/jinchaofs)
  - 🆕 Tabs support `moreIcon`. [#29744](https://github.com/ant-design/ant-design/pull/29744) [@tianyuan233](https://github.com/tianyuan233)
- 🐞 Button with `htmlType='reset'` will reset all form fileds. [#29752](https://github.com/ant-design/ant-design/pull/29752) [@jueinin](https://github.com/jueinin)
- 🐞 Fix AutoComplete custom input `className` missing. [#29725](https://github.com/ant-design/ant-design/pull/29725)
- 💄 Fix console warning when setting `margin` style on Row. [#29688](https://github.com/ant-design/ant-design/pull/29688)
- 💄 Fix the error style where the `disabled` Input has affix elements. [#29670](https://github.com/ant-design/ant-design/pull/29670)
- 💄 Optimize the cursor style of Form.Item tooltip info. [#29650](https://github.com/ant-design/ant-design/pull/29650)
- 🇨🇿 Fix typo in cs_CZ locale. [#29675](https://github.com/ant-design/ant-design/pull/29675) [@jvaclavik](https://github.com/jvaclavik)
- 🇨🇦 Add fr_CA locale. [#29748](https://github.com/ant-design/ant-design/pull/29748) [@liufenghua808](https://github.com/liufenghua808)

## 4.13.1

`2021-03-06`

- 🐞 Fix `message.config` with `prefixCls` missing animation style. [#29574](https://github.com/ant-design/ant-design/pull/29574)
- 🐞 Fix Tooltip is not interactive when `visible` is `true` under some situation. [#29555](https://github.com/ant-design/ant-design/pull/29555)
- 🐞 Fix ConfigProvider within multiple page switch will lose locale issue. [#29570](https://github.com/ant-design/ant-design/pull/29570)
- 🐞 Fix Modal with hooks cannot call `update` or `destroy` before render. [#29584](https://github.com/ant-design/ant-design/pull/29584)
- 🐞 Fix Grid throw error when client support flexGap but ssr not support. [#29586](https://github.com/ant-design/ant-design/pull/29586)
- 🐞 Fix Select caret position when `mode="tags"` and `size="small"`. [#29561](https://github.com/ant-design/ant-design/pull/29561)
- 🐞 Fix Carousel `dotPosition` makes `pauseOnHover` not working. [#29587](https://github.com/ant-design/ant-design/pull/29587) [@zgoby](https://github.com/zgoby)
- 🐞 Fix Steps `responsive` prop warning. [#29599](https://github.com/ant-design/ant-design/pull/29599)
- 🐞 Fix Upload `onChange` param of `file.originFileObj` return nest Proxy object. [#29614](https://github.com/ant-design/ant-design/pull/29614)
- 🐞 Fix Descriptions under Table will not have 100% width. [#29630](https://github.com/ant-design/ant-design/pull/29630)
- TypeScript
  - 🤖 Fix Drawer type declaration of `contentWrapperStyle`. [#29571](https://github.com/ant-design/ant-design/pull/29571)

## 4.13.0

`2021-02-28`

- 🔥 InputNumber support `stringMode` for high precision `step`. `value` in control out of range shows warning style instead of changing it. Dynamic update `min` & `max` will not trigger `onChange` anymore. [#29373](https://github.com/ant-design/ant-design/pull/29373)
- 🆕 Upload support `beforeUpload` return `Upload.LIST_IGNORE` to skip item added in UploadList. [#29474](https://github.com/ant-design/ant-design/pull/29474)
- 🆕 Image support config motion name. [#29394](https://github.com/ant-design/ant-design/pull/29394) [@crazyair](https://github.com/crazyair)
- ConfigProvider
  - 🆕 ConfigProvider support global statistic config to support some statistic function call. [#29285](https://github.com/ant-design/ant-design/pull/29285) [@crazyair](https://github.com/crazyair)
  - 🆕 Motion related css `className` prepend `ant-` prefix to avoid naming conflict. [#29268](https://github.com/ant-design/ant-design/pull/29268) [@crazyair](https://github.com/crazyair)
- 🆕 Form.List nest multiple level Form.Item support `preserve` prop. [#29267](https://github.com/ant-design/ant-design/pull/29267)
- 🆕 Drawer support `contentWrapperStyle`. [#29219](https://github.com/ant-design/ant-design/pull/29219) [@kerm1it](https://github.com/kerm1it)
- 🆕 Layout.Sider added ref support. [#29169](https://github.com/ant-design/ant-design/pull/29169) [@qramilq](https://github.com/qramilq)
- 🐞 Fix Table `pagination.current` display error when result of filter is empty. [#29386](https://github.com/ant-design/ant-design/pull/29386) [@jinchaofs](https://github.com/jinchaofs)
- 🐞 Fix Anchor throws error when `target` don't return a html element. [#29523](https://github.com/ant-design/ant-design/pull/29523) [@bcd337](https://github.com/bcd337)
- 🐞 Fix Steps with small size that icon shift up `1px`. [#29484](https://github.com/ant-design/ant-design/pull/29484)
- Select
  - 🐞 Fix Select `mode="tags"` large size (41px => 40px). [#29437](https://github.com/ant-design/ant-design/pull/29437)
  - 📖 Update Select debounce demo to create DebounceSelect component for easy usage. [#29414](https://github.com/ant-design/ant-design/pull/29414)
- Dropdown
  - 🐞 Fix Dropdown menu item lost disable style with icon. [#29433](https://github.com/ant-design/ant-design/pull/29433)
  - 🐞 Fix Dropdown menu not support `expandIcon`. [#29338](https://github.com/ant-design/ant-design/pull/29338)
- 🐞 Fix tree-shaking warning on development builds. [#29378](https://github.com/ant-design/ant-design/pull/29378)
- 🇰🇷 Fix TimePicker Korean locale. [#29540](https://github.com/ant-design/ant-design/pull/29540)
- TypeScript
  - 🤖 Fix Form.Item generic definition issue. [#29397](https://github.com/ant-design/ant-design/pull/29397) [@mumiao](https://github.com/mumiao)
  - 🤖 Optimize Table `filter` definition. [#29385](https://github.com/ant-design/ant-design/pull/29385) [@mumiao](https://github.com/mumiao)

## 4.12.3

`2021-02-10`

- 🛠 Refactor Drawer with React hooks. [#29229](https://github.com/ant-design/ant-design/pull/29229)
- 🐞 Fix Table pagination not disappear when `pagination.position` is `['none', 'none']`. [#29256](https://github.com/ant-design/ant-design/pull/29256) [@mumiao](https://github.com/mumiao)
- 🐞 Fix TextArea `showCount` should not be interactive. [#29245](https://github.com/ant-design/ant-design/pull/29245)
- 🐞 Fix abnormal background color for `multiple` and `disabled` Select in dark. [#29242](https://github.com/ant-design/ant-design/pull/29242)
- ⚡️ Optimize Slider align performance of tooltip. [#29308](https://github.com/ant-design/ant-design/pull/29308) [@kerm1it](https://github.com/kerm1it)
- ⚡️ Upgrade `@ant-design/colors` to 6.x to reduce gzipped bundle size `1KB`. [#29307](https://github.com/ant-design/ant-design/pull/29307) [@07akioni](https://github.com/07akioni)
- 🇷🇺 Add `ru_RU` locale text for Image. [#29271](https://github.com/ant-design/ant-design/pull/29271) [@mumiao](https://github.com/mumiao)
- 🇮🇷 Add `fa_IR` locale text for DatePicker, Form, Table, TimePicker and Transfer. [#29232](https://github.com/ant-design/ant-design/pull/29232) [@amiralitaheri](https://github.com/amiralitaheri)
- TypeScript
  - 🤖 Fix type definition for Table FilterDropdownProps `confirm` parameter. [#29241](https://github.com/ant-design/ant-design/pull/29241) [@mumiao](https://github.com/mumiao)

## 4.12.2

`2021-02-04`

- 💄 Make Table expand icon and checkbox same size and aligned. [#29214](https://github.com/ant-design/ant-design/pull/29214)
- 🐞 Fix List with `gutter` makes column break line. [#29211](https://github.com/ant-design/ant-design/pull/29211)

## 4.12.1

`2021-02-03`

- 🐞 Fix antd crash when load before page ready. [#29202](https://github.com/ant-design/ant-design/pull/29202)
- 🐞 Fix Table pagination `current` change logic when `pageSize` changes. [#29184](https://github.com/ant-design/ant-design/pull/29184)

## 4.12.0

`2021-02-03`

- 🆕 Image.PreviewGroup add `current` prop. [#29153](https://github.com/ant-design/ant-design/pull/29153)
- InputNumber
  - 🆕 InputNumber support `bordered` prop. [#29105](https://github.com/ant-design/ant-design/pull/29105)
  - 🆕 InputNumber add `keyboard` prop which could disable keyboard behavior. [#29110](https://github.com/ant-design/ant-design/pull/29110) [@kerm1it](https://github.com/kerm1it)
- 💄 Darken Tag text color to enhance readability. [#29144](https://github.com/ant-design/ant-design/pull/29144)
- 💄 Fix Row with vertical `gutter` provides additional `margin-bottom` style. [#29059](https://github.com/ant-design/ant-design/pull/29059)
- 🐞 Fix Collapse header disappers with delay. [#29158](https://github.com/ant-design/ant-design/pull/29158)
- 🐞 Fix the problem that `showCount` display data is incorrect when TextArea input emoji. [#29057](https://github.com/ant-design/ant-design/pull/29057) [@HomyeeKing](https://github.com/HomyeeKing)
- 📦 Optimize ConfigProvider to avoid import all icons when tree shaking is not enabled. [#29045](https://github.com/ant-design/ant-design/pull/29045)
- 🌐 Add en-GB missing translations for table. [#29131](https://github.com/ant-design/ant-design/pull/29131) [@eberjoe](https://github.com/eberjoe)
- Table
  - 🆕 Table `showSorterTooltip` now could be a object for more configuration. [#29002](https://github.com/ant-design/ant-design/pull/29002) [@harrisoff](https://github.com/harrisoff)
  - ⚡️ Optimize calling sequence of `onChange` and `onSelectAll` in `rowSelection` of Table. [#29079](https://github.com/ant-design/ant-design/pull/29079) [@kerm1it](https://github.com/kerm1it)
- Badge
  - 💄 Fix Badge change `count` content to hide miss style. [#29089](https://github.com/ant-design/ant-design/pull/29089)
  - 🐞 Fix Badge digital animation problem. [#29100](https://github.com/ant-design/ant-design/pull/29100)
- TypeScript
  - 🤖 Table TS definition update `dataSource` to `readonly`. [#29084](https://github.com/ant-design/ant-design/pull/29084)
- Less
  - 💄 Add less variable `@progress-info-text-color`. [#28981](https://github.com/ant-design/ant-design/pull/28981) [@yuxuan](https://github.com/yuxuan)

## 4.11.3

`2021-02-03`

Wrong release is the same as `4.12.0`, if you need to lock the version, you need to lock it to `4.11.2`.

## 4.11.2

`2021-01-26`

- 🐞 Fix rc-trigger BuildInPlacements TypeScript compile error. [#29029](https://github.com/ant-design/ant-design/pull/29029) [@waiwaiku](https://github.com/waiwaiku)

## 4.11.1

`2021-01-24`

- 💄 Layout inline sub menu now has grey background. [#28842](https://github.com/ant-design/ant-design/pull/28842)
- 🆕 PageHeader supports `breadcrumbRender`. [#28999](https://github.com/ant-design/ant-design/pull/28999)
- 🆕 Typography `ellipsis` support `tooltip` to customize tooltip when ellipsis. [#28821](https://github.com/ant-design/ant-design/pull/28821)
- Image
  - 🆕 Image supports `preview.maskClassName`. [#28681](https://github.com/ant-design/ant-design/pull/28681)
  - 🐞 Fix preview image will move after click it. [react-component/image#61](https://github.com/react-component/image/pull/61) [@simonwong](https://github.com/simonwong)
  - 🐞 Fix Image `placeholder` disappear issue. [#28953](https://github.com/ant-design/ant-design/issues/28953)
  - 🐞 Fix multiple Image.PreviewGroup contain same image. [#28881](https://github.com/ant-design/ant-design/issues/28881)
- ConfigProvider
  - 🆕 ConfigProvider supports `iconPrefixCls`. [#28924](https://github.com/ant-design/ant-design/pull/28924)
  - ⚡️ Optimize ConfigProvider props updating perfermance. [#28792](https://github.com/ant-design/ant-design/pull/28792) [@zxc0328](https://github.com/zxc0328)
- 💄 Tweak TreeSelect filter highlight color. [#28984](https://github.com/ant-design/ant-design/pull/28984)
- 💄 Fix Select item align style with custom `tagRender`. [#28962](https://github.com/ant-design/ant-design/pull/28962)
- Form
  - 🐞 Fix Form.Item can not clear nested `noStyle` error message. [#28918](https://github.com/ant-design/ant-design/pull/28918)
  - 🐞 Form.Item with `preserve=false` will reset value to `initialValues` when removed. [#28908](https://github.com/ant-design/ant-design/pull/28908)
- 🐞 Fix Button click effect style not working in shadow root. [#28995](https://github.com/ant-design/ant-design/pull/28995) [@rinick](https://github.com/rinick)
- 🐞 Fix Table custom filter menu cannot close bug. [#28688](https://github.com/ant-design/ant-design/pull/28688) [@alekye](https://github.com/alekye)
- Less
  - 💄 Add `@menu-inline-submenu-bg` less variable and rename `@menu-dark-submenu-bg` to `@menu-dark-inline-submenu-bg`. [#28842](https://github.com/ant-design/ant-design/pull/28842)
  - 💄 Add less variable `@drawer-footer-padding-horizontal`. [#28975](https://github.com/ant-design/ant-design/pull/28975) [@yuxuan](https://github.com/yuxuan)
- RTL
  - 💄 Fix Card actions divider style in RTL. [#28915](https://github.com/ant-design/ant-design/pull/28915) [@Aghosey](https://github.com/Aghosey)
- TypeScript
  - 🤖 Expose interfaces and types from default entry of antd. [#28963](https://github.com/ant-design/ant-design/pull/28963)
  - 🤖 Improve Input/Skeleton `style` definition. [#28966](https://github.com/ant-design/ant-design/pull/28966) [@yingpengsha](https://github.com/yingpengsha)

## 4.11.0

`2021-01-24`

It is a wrong release which same as `4.10.3`, don't use it.

## 4.10.3

`2021-01-18`

- 🐞 Fix Button not adapting to the `@btn-border-width` when loading. [#28886](https://github.com/ant-design/ant-design/pull/28886) [@jjanssen](https://github.com/jjanssen)
- Table
  - 💄 Add `@table-border-color` less variable. [#28903](https://github.com/ant-design/ant-design/pull/28903)
  - 🐞 Fix that invalid params passed to `onChange` event if define custom filterDropdown and nested filters. [#28850](https://github.com/ant-design/ant-design/pull/28850) [@Meowu](https://github.com/Meowu)
  - 💄 Tweak Table selection column width to `32px`. [#28073](https://github.com/ant-design/ant-design/pull/28073)
- Transfer
  - 🛠 Refactor Transfer Search with React hooks. [#28895](https://github.com/ant-design/ant-design/pull/28895) [@susiwen8](https://github.com/susiwen8)
  - 🌐 Added German translations for the Transfer component. [#28826](https://github.com/ant-design/ant-design/pull/28826) [@aequi42](https://github.com/aequi42)
- Upload
  - 🐞 Support for capturing Error message for the Upload error tooltip. [#28716](https://github.com/ant-design/ant-design/pull/28716) [@wangcch](https://github.com/wangcch)
  - 🆕 Upload auto fills `uid` of `fileList` when not provided. [#28832](https://github.com/ant-design/ant-design/pull/28832)
- 🐞 Fix Slider `getPopupContainer` prop has no default value `document.body`. [#28865](https://github.com/ant-design/ant-design/pull/28865) [@rinick](https://github.com/rinick)
- 🐞 Fix Empty description validateDOMNesting warning. [#28862](https://github.com/ant-design/ant-design/pull/28862)
- 💄 Fix Tree `filterTreeNode` missing style. [#28866](https://github.com/ant-design/ant-design/pull/28866)
- 💄 fix Badge `dot` width issue when `size="small"`. [#28854](https://github.com/ant-design/ant-design/pull/28854)

## 4.10.2

`2021-01-11`

- 🐞 Fix import error when use antd in commonjs. [#28715](https://github.com/ant-design/ant-design/issues/28804)

## 4.10.1

`2021-01-10`

- 🛠 Optimize Select search performance. [#28715](https://github.com/ant-design/ant-design/pull/28715) [@kerm1it](https://github.com/kerm1it)
- 🐞 Fix Slider throw `forcePopupAlign` error when unmounted. [#28699](https://github.com/ant-design/ant-design/pull/28699) [@Kerumen](https://github.com/Kerumen)
- 🐞 Fix Transfer throws `Cannot add property key, object is not extensible` when `dataSource` is immutable. [#28675](https://github.com/ant-design/ant-design/pull/28675)
- 🐞 Fix Notification box closing height issue generated by `useNotification`. [#28660](https://github.com/ant-design/ant-design/pull/28660)
- 🐞 Fix Drawer and Modal disabled scrollbar after closing. [#28749](https://github.com/ant-design/ant-design/pull/28749)
- 🛠 Reduce gzipped bundle size `2kB`. [#28678](https://github.com/ant-design/ant-design/pull/28678)
- TypeScript
  - 🤖 InputNumber `onChange` support `null` as `value`. [#28769](https://github.com/ant-design/ant-design/pull/28769) [@lengfangbing](https://github.com/lengfangbing)

## 4.10.0

`2021-01-04`

🎉 Happy New Year!

- 🐞 Fix the compatibility issue of less 4.0.0.
- 🐞 Fix the problem of cursor jumping when Typography is editable. [#28545](https://github.com/ant-design/ant-design/pull/28545)
- 🐞 Fix the problem that repeatedly clicking on expanded nodes when Tree dynamically loads data will lead to wrong status.[#28349](https://github.com/ant-design/ant-design/issues/28349) [@liuchao233](https://github.com/react-component/tree/pull/401)
- 🐞 Fix TreeSelect and Select cannot open the dropdown menu when it's `searchValue` has value. [#28574](https://github.com/ant-design/ant-design/pull/28574)
- 🐞 Fix Dropdown disabled menu item link style. [#28578](https://github.com/ant-design/ant-design/pull/28578)
- 🐞 Fix Progress `steps` display accuracy issue. [#28530](https://github.com/ant-design/ant-design/pull/28530) [@gaoryrt](https://github.com/gaoryrt)
- 🐞 Fix Radio align issue in Chrome. [#28616](https://github.com/ant-design/ant-design/pull/28616)
- 🐞 Fix Collapse arrow position not aligned when change @collapse-header-padding variable. [#28507](https://github.com/ant-design/ant-design/pull/28507)
- 💄 Optimize the white border style of Card images. [#28624](https://github.com/ant-design/ant-design/pull/28624)
- Input
  - 🐞 Fix TextArea value get cut when input chinese words. [#28456](https://github.com/ant-design/ant-design/pull/28456)
  - 🆕 The `showCount` property of Input.TextArea now supports passing in a method to customize the display format of the number. [#28145](https://github.com/ant-design/ant-design/pull/28145) [@MrHeer](https://github.com/MrHeer)
  - 🆕 Input `focus` supports configuring the cursor position when getting focus. [#28602](https://github.com/ant-design/ant-design/pull/28602)
- Modal
  - 🆕 Modal.method adds an `afterClose` callback that will be triggered after the Modal is completely closed. [#28053](https://github.com/ant-design/ant-design/pull/28053) [@liuchao233](https://github.com/liuchao233)
  - 🐞 Fix the problem that Modal can be dragged outside the viewport. [#28438](https://github.com/ant-design/ant-design/pull/28527) [@mumiao](https://github.com/mumiao)
- Table
  - 🐞 Fix the problem that Table childrenColumnName and checkStrictly={false} cannot be used together. [#28568](https://github.com/ant-design/ant-design/pull/28568)
  - 🐞 Fix Table selection abnormal behavior when inside Checkbox.Group. [#28576](https://github.com/ant-design/ant-design/pull/28576)
  - 🐞 Fix the problem that the sticky header style is messy when there is no data. [#28323](https://github.com/ant-design/ant-design/issues/28323)
  - 🐞 Fix the problem that `onChange` listener always receives empty list as `filters` parameter if use a custom `filterDropdown`. [#28627](https://github.com/ant-design/ant-design/pull/28627) [@Meowu](https://github.com/Meowu)
  - 🆕 Adds `expandable.columnWidth` to customize the width of the expanded column. [#28249](https://github.com/ant-design/ant-design/pull/28249)
  - 🆕 Adds clear all option from selection. [#28580](https://github.com/ant-design/ant-design/pull/28580) [@n0ruSh](https://github.com/ant-design/ant-design/pull/285)
- Image
  - 🐞 Fix the misalignment issue of Image component.[#28439](https://github.com/ant-design/ant-design/pull/28439) [@MoeCasts](https://github.com/MoeCasts)
  - 💄 Adds preview style. [#28235](https://github.com/ant-design/ant-design/pull/28235)
  - 🆕 Adds functionality for zoom in\out by sliding the wheel. [#react-component/image/52](https://github.com/react-component/image/pull/52) [@OmriGM](https://github.com/OmriGM)
  - 🆕 Support separate settings url for preview images. [#react-component/image/56](https://github.com/react-component/image/pull/56) [@wangcch](https://github.com/wangcch)
- Upload
  - 🐞 Fix a warning even when not using `transformFile`. [#28455](https://github.com/ant-design/ant-design/pull/28455) [@YanYuanFE](https://github.com/YanYuanFE)
  - 🐞 Fix Upload `fileList` cannot work with data that is produced by immer. [#28636](https://github.com/ant-design/ant-design/pull/28636) [@mumiao](https://github.com/mumiao)
  - 🆕 Upload adds a new `maxCount` property to limit the number of files. [#28367](https://github.com/ant-design/ant-design/pull/28367)
- DatePicker
  - 🚀 Optimize the logic of `disabledDate`. [#react-component/picker/191](https://github.com/react-component/picker/pull/191)
  - 🆕 Adds `onKeyDown` callback. [#react-component/picker/138](https://github.com/react-component/picker/pull/138) [@conquera99](https://github.com/react-component/picker/pull/138)
- Select
  - 🐞 Fix issue where `options` update does not trigger the selection box content update. [#react-component/select/580](https://github.com/react-component/select/pull/580) [@jameslahm](https://github.com/jameslahm)
  - 🐞 Fix the problem that the dropdown box cannot be opened after clicking the option with `tagRender`. [react-component/select/582](https://github.com/react-component/select/pull/582) [@mumiao](https://github.com/mumiao)
  - 🐞 Fix the problem that `tokenSeparators` can not recognize the separator correctly under Chinese input method. [#28564](https://github.com/ant-design/ant-design/issues/28564)
  - 🆕 Adds `scrollTo` to the `ref`. [#react-component/select/565](https://github.com/react-component/select/pull/565)
  - 🆕 `maxTagCount` supports `responsive` in `multiple` mode. [#28520](https://github.com/ant-design/ant-design/pull/28520)
- 🆕 Slider add a new `range.draggableTrack` prop. [#28592](https://github.com/ant-design/ant-design/pull/28592)
- 🆕 Descriptions support setting `labelStyle` & `contentStyle` directly. [#28613](https://github.com/ant-design/ant-design/pull/28613)
- 🆕 message added a new `onClick` callback that will be triggered when the message is clicked. [#28148](https://github.com/ant-design/ant-design/pull/28148) [@ZeroTo0ne](https://github.com/ant-design/ant-design/pull/28148)
- 🆕 The `scrollToFirstError` property of the Form adds support for setting the position for scrolling. [#28272](https://github.com/ant-design/ant-design/pull/28272) [@vouis](https://github.com/vouis)
- 🆕 Steps support reponsive which allows to turn off reponsive change. [#28459](https://github.com/ant-design/ant-design/pull/28459)
- 🌐 Localization
  - 🇭🇷 Improved Croatian language support. [#28458](https://github.com/ant-design/ant-design/pull/28458)
- TypeScript
  - ⚒️ Fix `title` type of PageHeader. [#28374](https://github.com/ant-design/ant-design/pull/28374) [@zhukovvandrei](https://github.com/zhukovvandrei)

## 4.9.4

`2020-12-16`

- 🐞 Fix Menu delayed hover color transition in Chrome. [#28372](https://github.com/ant-design/ant-design/pull/28372)
- 🐞 Fix Tree node connection line position problem. [#28354](https://github.com/ant-design/ant-design/pull/28354) [@maksnester](https://github.com/maksnester)
- 💄 Fix Table fixed column `z-index` which makes Dropdown not showing on top. [#28346](https://github.com/ant-design/ant-design/pull/28346)
- TypeScript
  - 🤖 Fix `message.loading()` return type. [#28362](https://github.com/ant-design/ant-design/pull/28362)

## 4.9.3

`2020-12-14`

- 💄 Fix Badge standalone motion blink when show/hide. [#28240](https://github.com/ant-design/ant-design/pull/28240)
- 🐞 Fix Table `filters` not support number and boolean type. [#28220](https://github.com/ant-design/ant-design/pull/28220) [@Meowu](https://github.com/Meowu)
- 💄 Remove Tree hover background color when `selectable={false}`. [#28269](https://github.com/ant-design/ant-design/pull/28269)
- 💄 Fix Statistics decimal font size. [#28223](https://github.com/ant-design/ant-design/pull/28223)
- TypeScript
  - 🤖 Fix Tree `draggable` TS definition. [#28262](https://github.com/ant-design/ant-design/pull/28262) [@DavidSichau](https://github.com/DavidSichau)
  - 🤖 Fix Image.PreviewGroup TS definition. [#28263](https://github.com/ant-design/ant-design/pull/28263) [@liuchao233](https://github.com/liuchao233)
  - 🤖 Improve `message().then` TS definition. [#28304](https://github.com/ant-design/ant-design/pull/28304)
  - 🤖 Fix TransferProps `titles` to ReactNode. [#28326](https://github.com/ant-design/ant-design/pull/28326) [@jacklee814](https://github.com/jacklee814)

## 4.9.2

`2020-12-06`

- Table
  - 🐞 Fix Table selecting crash sometimes. [#28193](https://github.com/ant-design/ant-design/pull/28193) [@yanguoyu](https://github.com/yanguoyu)
  - 💄 Fix Table selection column header align issue. [#28173](https://github.com/ant-design/ant-design/pull/28173)
- Dropdown
  - 💄 Fix Dropdown subMenu arrow style. [#28181](https://github.com/ant-design/ant-design/pull/28181)
  - 🐞 Fix Dropdown click area not matched. [#28180](https://github.com/ant-design/ant-design/pull/28180)
- 🐞 Fix `overlayInnerStyle` not work in Tooltip. [#27682](https://github.com/ant-design/ant-design/pull/27682) [@jasepellerin](https://github.com/jasepellerin)
- 💄 Fix Layout overflow style for Table `sticky`. [#28176](https://github.com/ant-design/ant-design/pull/28176)
- 💄 Fix Steps `progressDot` broken style of first step. [#28126](https://github.com/ant-design/ant-design/pull/28126) [@ZeroTo0ne](https://github.com/ZeroTo0ne)
- 💄 Optimize Modal `useModal` performance by isolating elements render to avoid the component to rerender. [#28122](https://github.com/ant-design/ant-design/pull/28122) [@TotooriaHyperion](https://github.com/TotooriaHyperion)
- 💄 Fix TextArea showCount style while using with Form. [#28130](https://github.com/ant-design/ant-design/pull/28130) [@AlanCutFlim](https://github.com/AlanCutFlim)
- 💄 Fix Tag cursor style in Tree node. [#28219](https://github.com/ant-design/ant-design/pull/28219)
- 🛠 Remove `@ant-design/css-animation` for better bundle size. [#28201](https://github.com/ant-design/ant-design/pull/28201)
- RTL
  - 💄 Fix the style of Alert. [#28108](https://github.com/ant-design/ant-design/pull/28108) [@jesse3mh9a](https://github.com/jesse3mh9a)
  - 🐞 Fix Tree `dropIndicator` style of default `ltr` direction. [#28150](https://github.com/ant-design/ant-design/pull/28150) [@kagawagao](https://github.com/kagawagao)
- TypeScript
  - 🤖 Fix Table `selectedRows` in `SelectionSelectFn` return generic type. [#28206](https://github.com/ant-design/ant-design/pull/28206) [@weiyuc](https://github.com/weiyuc)
  - 🤖 Add `className` in `BreadcrumbItemProps`. [#28182](https://github.com/ant-design/ant-design/pull/28182) [@ccloveak](https://github.com/ccloveak)
  - 🤖 Form.List `initialValue` types are supported. [#28153](https://github.com/ant-design/ant-design/pull/28153) [@Debiancc](https://github.com/Debiancc)
  - 🤖 Fix `dontAnimate` optional in Carousel. [#28090](https://github.com/ant-design/ant-design/pull/28090) [@jarretmoses](https://github.com/jarretmoses)

## 4.9.1

`2020-12-01`

- TypeScript
  - 🤖 Fix Collapse.Panel `collapsible` property to optional. [#28092](https://github.com/ant-design/ant-design/pull/28092) [@sammarks](https://github.com/sammarks)

## 4.9.0

`2020-11-30`

- Modal
  - 🆕 Modal support `focusTriggerAfterClose` to disable auto focus back. [#27985](https://github.com/ant-design/ant-design/pull/27985) [@molokovev](https://github.com/molokovev)
  - 🐞 Fix Modal hooks not trigger `onCancel`. [#28063](https://github.com/ant-design/ant-design/pull/28063) [@JuniorTour](https://github.com/JuniorTour)
  - 🐞 Fix Modal sometime not popup from the click position. [#28037](https://github.com/ant-design/ant-design/pull/28037)
  - 🆕 Support `closable` and `closeIcon` api for Modal.method. [#27909](https://github.com/ant-design/ant-design/pull/27909) [@MrHeer](https://github.com/MrHeer)
- 💄 Reduce Table selection column width to `32px`. [#28073](https://github.com/ant-design/ant-design/pull/28073)
- Image
  - 🔥 Image add PreviewGroup component to support multiple images preview. [#28069](https://github.com/ant-design/ant-design/pull/28069)
  - 🐞 Fix Image style prop not acting on img element. [#27446](https://github.com/ant-design/ant-design/pull/27446)
- Collapse
  - 🔥 Collapse support `collapsible` to customize trigger region and deprecated Panel `disabled` prop. [#27790](https://github.com/ant-design/ant-design/pull/27790)
  - 🐞 Fix Collapse cannot contains `<Table sticky />`. [#28039](https://github.com/ant-design/ant-design/pull/28039)
- 🐞 Fix Cascader bug that empty data can be selected. [#28062](https://github.com/ant-design/ant-design/pull/28062) [@n0ruSh](https://github.com/n0ruSh)
- 🆕 Alert support `action` prop. [#25892](https://github.com/ant-design/ant-design/pull/25892) [@jesse3mh9a](https://github.com/jesse3mh9a)
- 🔥 Tree refactor drag behavior. Add `dropIndicatorRender` and `allowDrop` prop. [#26462](https://github.com/ant-design/ant-design/pull/26462) [@07akioni](https://github.com/07akioni)
- 🆕 Space support `wrap` for auto break line. [#27910](https://github.com/ant-design/ant-design/pull/27910)
- 🆕 Descriptions.Item support `labelStyle` & `contentStyle` props. [#27897](https://github.com/ant-design/ant-design/pull/27897)
- 🆕 Form.List support `initialValue`. [#27872](https://github.com/ant-design/ant-design/pull/27872)
- 🆕 Menu supports `expandIcon`, and optimize default expand icon style. [#27565](https://github.com/ant-design/ant-design/pull/27565)
- 🆕 Input and TextArea add `setSelectionRange` of `ref`. [#27584](https://github.com/ant-design/ant-design/pull/27584) [@appleshell](https://github.com/appleshell)
- 🆕 Select support `filterSort` to order the filtered options. [#27523](https://github.com/ant-design/ant-design/pull/27523) [@n0ruSh](https://github.com/n0ruSh)
- 🇰🇿 Add Kazakh locale. [#27589](https://github.com/ant-design/ant-design/pull/27589) [@nodkz](https://github.com/nodkz)

## 4.8.6

`2020-11-27`

- 🐞 Fix Badge style blink when mounted. [#28003](https://github.com/ant-design/ant-design/pull/28003)
- 💄 Reduce Modal style size. [#27998](https://github.com/ant-design/ant-design/pull/27998)
- 🐞 Fix Layout.Sider can not collapse when `width='0'`. [#28000](https://github.com/ant-design/ant-design/pull/28000)
- 🐞 Fix Menu style when using none Ant Design icons. [#27983](https://github.com/ant-design/ant-design/pull/27983)
- Input
  - 🐞 Fix Input.Search button height when customize less variables. [#27986](https://github.com/ant-design/ant-design/pull/27986)
  - 🐞 Fix Input.Search `addonBefore` abnormal style. [#27960](https://github.com/ant-design/ant-design/pull/27960)
- 🐞 Fix Typography.Link clicking copy button will redirect. [#27982](https://github.com/ant-design/ant-design/pull/27982)
- 🐞 Fix Carousel throws error `Unable to preventDefault inside passive event listener`. [#27957](https://github.com/ant-design/ant-design/pull/27957)
- 🌐 Improve data picker locale for `en_GB` and `zh_TW`. [#28016](https://github.com/ant-design/ant-design/pull/28016) [@abz53378](https://github.com/abz53378)
- RTL
  - 💄 Optimize the border style of Descriptions in RTL model. [#28010](https://github.com/ant-design/ant-design/pull/28010)
  - 💄 Fix the vertical style of Steps in RTL mode. [#27996](https://github.com/ant-design/ant-design/pull/27996)
- TypeScript
  - 🤖 Fix Upload `beforeUpload` definition. [#27946](https://github.com/ant-design/ant-design/pull/27946) [@bingling0084](https://github.com/bingling0084)
  - 🤖 Provided a separate type definition for Carousel reference. [#27935](https://github.com/ant-design/ant-design/pull/27935) [@ocassio](https://github.com/ocassio)

## 4.8.5

`2020-11-22`

- 🐞 Fix that Spin can't render children `0`. [#27839](https://github.com/ant-design/ant-design/pull/27839) [@liuchao233](https://github.com/liuchao233)
- 💄 Fix the RangePicker panel interaction style. [#27894](https://github.com/ant-design/ant-design/pull/27894)
- 💄 Fix Switch `loading` style. [#27860](https://github.com/ant-design/ant-design/pull/27860)
- 💄 Optimize Skeleton color to fit dark background. [#27836](https://github.com/ant-design/ant-design/pull/27836)
- 💄 Adjust Statistic `deciaml` font size. [#27884](https://github.com/ant-design/ant-design/pull/27884)
- 🛠 Refactor Checkbox、Layout.Sider and TextArea with React hooks. [#27739](https://github.com/ant-design/ant-design/pull/27739) [#27719](https://github.com/ant-design/ant-design/pull/27719) [#27693](https://github.com/ant-design/ant-design/pull/27693)
- 🛠 Refactor BackTop、Badge、UploadList with `rc-motion` instead of `rc-animate`. [#27840](https://github.com/ant-design/ant-design/pull/27840) [#27848](https://github.com/ant-design/ant-design/pull/27848) [#27923](https://github.com/ant-design/ant-design/pull/27923)
- RTL
  - 💄 Fix the style of the Tree switch icon in RTL mode. [#27876](https://github.com/ant-design/ant-design/pull/27876)
- TypeScript
  - 🤖 Fix AutoComplete `DataSourceItemType` type definition. [#27892](https://github.com/ant-design/ant-design/pull/27892)
  - 🤖 Export Image `ImageProps` interface. [#27846](https://github.com/ant-design/ant-design/pull/27846) [@wangcch](https://github.com/wangcch)

## 4.8.4

`2020-11-16`

- 💄 Fix Button and Form loading style. [#27794](https://github.com/ant-design/ant-design/pull/27794)
- 🐞 Fix Modal.confirm locale missing after close it. [#27797](https://github.com/ant-design/ant-design/pull/27797)
- 🐞 Fix Button/Anchor throws `findDOMNode is deprecated` in React 17. [#27755](https://github.com/ant-design/ant-design/pull/27755) [@hosseinmd](https://github.com/hosseinmd)

## 4.8.3

`2020-11-14`

- 🛠 Refactor Carousel with React hooks. [#27694](https://github.com/ant-design/ant-design/pull/27694)
- 🛠 Refactor `<Typography editable />` with React hooks. [#27655](https://github.com/ant-design/ant-design/pull/27655)
- 🐞 Fixed the problem that form behaves abnormally when namepath is an array. [#27664](https://github.com/ant-design/ant-design/pull/27664)
- 💄 Fix RangePicker hover effect position when hover over start or end cell of in range row. [#27731](https://github.com/ant-design/ant-design/pull/27731) [@AlanCutFlim](https://github.com/AlanCutFlim)
- 🐞 Fix Select `mode=tags` cannot input whitespace normally. [#27726](https://github.com/ant-design/ant-design/pull/27726) [@baxtergu](https://github.com/baxtergu)
- 💄 Fix the mouse style when Typography.Link is `disabled`. [#27734](https://github.com/ant-design/ant-design/pull/27734)
- 🐞 Fix Menu dropdown animation start twice when appear. [#27663](https://github.com/ant-design/ant-design/pull/27663)
- 💄 Fix Avatar style when `src` is Image component. [#27691](https://github.com/ant-design/ant-design/pull/27691)
- 💄 Fix Select multiple cursor position. [#27689](https://github.com/ant-design/ant-design/pull/27689)
- 🐞 Fix TextArea emoji been cut when enable `maxLength`. [#27679](https://github.com/ant-design/ant-design/pull/27679) [@372623460jh](https://github.com/372623460jh)
- 🐞 Fix small size RangePicker active bar align issue. [#27673](https://github.com/ant-design/ant-design/pull/27673) [@Ifeinstein](https://github.com/Ifeinstein)
- 💄 Add `@radio-border-width`. [#27703](https://github.com/ant-design/ant-design/pull/27703)

## 4.8.2

`2020-11-09`

- 🐞 Fix Pagination lost jumper margin style. [#27650](https://github.com/ant-design/ant-design/pull/27650)
- 🐞 Fix Steps `type="navigation"` last item broken style. [#27654](https://github.com/ant-design/ant-design/pull/27654)

## 4.8.1

`2020-11-08`

- 🛠 Refactor TreeSelect with React hooks. [#27593](https://github.com/ant-design/ant-design/pull/27593)
- 🛠 Refactor Layout with React hooks. [#27595](https://github.com/ant-design/ant-design/pull/27595)
- 🐞 Fix Select abnormal outline style in Form validation. [#27607](https://github.com/ant-design/ant-design/pull/27607)
- 🐞 Fix Pagination extra `margin-right` when enable size changer. [#27610](https://github.com/ant-design/ant-design/pull/27610)
- 🐞 Fix Input.Search `enterButton={null}` throw error. [#27591](https://github.com/ant-design/ant-design/pull/27591) [@davidebianchi](https://github.com/davidebianchi)
- 🐞 fix Avatar.Group `size` not working. [#27531](https://github.com/ant-design/ant-design/pull/27531)
- 🐞 Fix vertical Tabs long title cause tab width changes. [#27569](https://github.com/ant-design/ant-design/pull/27569)
- 🐞 Fix Table filters didn't display in `column.children`. [#27435](https://github.com/ant-design/ant-design/pull/27435) [@JhonXY](https://github.com/JhonXY)
- 💄 Fix Steps style that inside another Steps. [#27514](https://github.com/ant-design/ant-design/pull/27514)
- TypeScript
  - 🤖 Fix Select `ref` TS error. [#27482](https://github.com/ant-design/ant-design/pull/27482)
  - 🤖 Fix Avatar `src` type. [#27524](https://github.com/ant-design/ant-design/pull/27524) [@n0ruSh](https://github.com/n0ruSh)
- RTL
  - 💄 Fix Progress.Line `strokeColor` direction error in RTL mode. [#27515](https://github.com/ant-design/ant-design/pull/27515)

## 4.8.0

`2020-11-02`

- Image
  - 🔥 Image support `preview.getContainer` property. [#26713](https://github.com/ant-design/ant-design/pull/26713) [@rfreling](https://github.com/rfreling)
  - 🐞 Fix Image `style` prop not acting on img element. [#27446](https://github.com/ant-design/ant-design/pull/27446)
- 🆕 ConfigProvider support `form.requiredMark`. [#27322](https://github.com/ant-design/ant-design/pull/27322)
- 🆕 Statistic support `loading` prop. [#26811](https://github.com/ant-design/ant-design/pull/26811) [@appleshell](https://github.com/appleshell)
- Avatar
  - 🔥 Support Image element as prop for Avatar component. [#27448](https://github.com/ant-design/ant-design/pull/27448) [@n0ruSh](https://github.com/n0ruSh)
  - 🆕 Avatar.Group support `size` props. [#27348](https://github.com/ant-design/ant-design/pull/27348)
- 🆕 Row support `noWrap` to make Col in line. [#27469](https://github.com/ant-design/ant-design/pull/27469)
- Tree
  - 🐞 Fix Tree text selecting when double click switcher icon. [#27476](https://github.com/ant-design/ant-design/pull/27476)
  - 🐞 Fix Tree with `showLine` not connect line when `title` break line. [#27386](https://github.com/ant-design/ant-design/pull/27386)
- Modal
  - 🆕 `modal.update()` supports functional updating. [#27163](https://github.com/ant-design/ant-design/pull/27163) [@Mongkii](https://github.com/Mongkii)
  - 🆕 Modal method support `bodyStyle` props. [#27292](https://github.com/ant-design/ant-design/pull/27292)
  - 🐞 Fix Modal missing `modalRender` prop. [#27272](https://github.com/ant-design/ant-design/pull/27272) [@jieny](https://github.com/jieny)
  - 🐞 `rootPrefixCls` set in `Modal.config` can be effective for the antd components used in `title` and `content`. [#27376](https://github.com/ant-design/ant-design/pull/27376) [@Chersquwn](https://github.com/Chersquwn)
- Input
  - 🆕 Input.Textarea support `size` props. [#27110](https://github.com/ant-design/ant-design/pull/27110)
  - 🐞 Fix Input missing `className` when `allowClear` is true. [#27462](https://github.com/ant-design/ant-design/pull/27462)
- Table
  - 🆕 Table.Summary.Cell support `align` prop. [#27365](https://github.com/ant-design/ant-design/pull/27365)
  - 🐞 Fix Table `onShowSizeChange` trigger twice. [#27417](https://github.com/ant-design/ant-design/pull/27417)
  - 🐞 Fix Table `pagination` cache previous config issue. [#27412](https://github.com/ant-design/ant-design/pull/27412)
- Typography
  - 🐞 Fix Typography Invalid regular expression issue with particular content. [#27383](https://github.com/ant-design/ant-design/pull/27383) [@ttys026](https://github.com/ttys026)
  - 💄 Fix disabled Typography.Link hover or active color. [@27487](https://github.com/ant-design/ant-design/pull/27487) [@Liu-Ya](https://github.com/Liu-Ya)
- Steps
  - 🐞 Fix title is not centered when enabling `progressDot`. [#27406](https://github.com/ant-design/ant-design/pull/27406)
  - 🐞 Fix style in small screen. [#27499](https://github.com/ant-design/ant-design/pull/27499)
- 🐞 Fix PageHeader that empty dom will be displayed when `title` is empty. [#27485](https://github.com/ant-design/ant-design/pull/27485)
- 🐞 Fix Slider keep tooltip align with handle when dragging. [#27489](https://github.com/ant-design/ant-design/pull/27489)
- 🐞 Fix RangePicker selected range border style. [#27438](https://github.com/ant-design/ant-design/pull/27438)
- 💄 Adjust Collapse arrow position align with first line. [#27363](https://github.com/ant-design/ant-design/pull/27363)
- 💄 Fix Descriptions style when `label` use block element. [#27375](https://github.com/ant-design/ant-design/pull/27375)
- 💄 Fix Select abnormal border style in Form validation. [#27378](https://github.com/ant-design/ant-design/pull/27378)

## 4.7.3

`2020-10-24`

- Form
  - 🐞 Fix Form warning for non-boolean attribute `virtual` when use ConfigProvider. [#27343](https://github.com/ant-design/ant-design/pull/27343)
  - 🛠 Adjust Form.Item `initialValue` sync status align with Form level `initialValues`. [#27319](https://github.com/ant-design/ant-design/pull/27319)
- Typography
  - 🛠 Improve Typography `ellipsis` title display. [#27328](https://github.com/ant-design/ant-design/pull/27328)
  - 💄 Fix Editable Typography in Card title style problems. [#27221](https://github.com/ant-design/ant-design/pull/27221)
- Input
  - 🐞 Fix Input.Search duplicated `className` when `allowClear` is `true`. [#27261](https://github.com/ant-design/ant-design/pull/27261)
  - 🐞 Fix Input.Search border style when enable `allowClear`. [#27261](https://github.com/ant-design/ant-design/pull/27325)
- 🐞 Fix Upload.List preview image fit size issue. [#27312](https://github.com/ant-design/ant-design/pull/27312) [@JuniorTour](https://github.com/JuniorTour)
- 🐞 Fix Notification no wrap with long text. [#27285](https://github.com/ant-design/ant-design/pull/27285) [@littleee](https://github.com/littleee)
- 🐞 Fix Menu inside flexable container will not shrink properly. [#27253](https://github.com/ant-design/ant-design/pull/27253)
- 🌐 Fix en_US, en_GB and ga_IE gramma. [#27259](https://github.com/ant-design/ant-design/pull/27259) [@yasikovsky](https://github.com/yasikovsky)
- 🐞 Fix Tag with customize `closeIcon` breaks line issue. [#27226](https://github.com/ant-design/ant-design/pull/27226) [@handycode](https://github.com/handycode)

## 4.7.2

`2020-10-19`

- 💄 Fix Layout.Sider `light` theme lost styles. [#27227](https://github.com/ant-design/ant-design/pull/27227) [@lingjieee](https://github.com/lingjieee)
- 💄 Fix TextArea wrapped with additional div when `showCount` is `false`, and pass `className` and `style` to outer wrapper when `showCount` is `true`. [#27216](https://github.com/ant-design/ant-design/pull/27216)
- 🐞 Fix Checkbox.Group TS2559 error. [#27231](https://github.com/ant-design/ant-design/pull/27231)

## 4.7.1

`2020-10-18`

- DatePicker
  - 🐞 Fix DatePicker don't work correctly when `showTime` is `true` and `format` is function. [#27156](https://github.com/ant-design/ant-design/pull/27156)
  - 💄 Fix DatePicker wrong animation direction when auto overflow. [#27101](https://github.com/ant-design/ant-design/pull/27101)
- Typography
  - 💄 Fix Typography miss `pre` and `blockquote` style. [#27150](https://github.com/ant-design/ant-design/pull/27150)
  - 🐞 Fix Typography.Link hover color. [#27119](https://github.com/ant-design/ant-design/pull/27119)
  - 🐞 Fix Typography.Link hover color when type is danger. [#27104](https://github.com/ant-design/ant-design/pull/27104)
- 💄 Fix Descriptions `ant-descriptions-item-content` and add style `word-break:break-word;`. [#27195](https://github.com/ant-design/ant-design/pull/27195) [@WLyKan](https://github.com/WLyKan)
- 🐞 Fix clear Password value attribute in controlled mode. [#27191](https://github.com/ant-design/ant-design/pull/27191)
- 🐞 Optimize Notification width in small screen. [#27189](https://github.com/ant-design/ant-design/pull/27189)
- 🐞 Fix Cascader className duplicate. [#27187](https://github.com/ant-design/ant-design/pull/27187) [@huntdream](https://github.com/huntdream)
- 🐞 Fix the issue that the Drawer will trigger form submit. [#27175](https://github.com/ant-design/ant-design/pull/27175)
- 🐞 Fix Dropdown icon missing margin. [#27165](https://github.com/ant-design/ant-design/pull/27165)
- 💄 Fix Layout.Sider `collapsedWidth` cannot work without modifying `@menu-collapsed-width`. [#27154](https://github.com/ant-design/ant-design/pull/27154)
- 🐞 Fix Tabs `animated={true}` not working for panels. [#27145](https://github.com/ant-design/ant-design/pull/27145)
- 🐞 Fix Divider color when contains text. [#27134](https://github.com/ant-design/ant-design/pull/27134)
- 💄 Fix the cursor style when the Radio option is selected and disabled. [#27125](https://github.com/ant-design/ant-design/pull/27125)
- 🇪🇸 Add missing translations in es_ES. [#27079](https://github.com/ant-design/ant-design/pull/27079) [@gersongams](https://github.com/gersongams)
- RTL
  - 💄 Optimize the style of Input.TextArea character count in RTL mode. [#27098](https://github.com/ant-design/ant-design/pull/27098)
- TypeScript
  - 🤖 Button shape remove undeclared doc type. [#27159](https://github.com/ant-design/ant-design/pull/27159)
  - 🤖 Add optional `rules` property into `FormListProps`. [#27164](https://github.com/ant-design/ant-design/pull/27164) [@huntdream](https://github.com/huntdream)

## 4.7.0

`2020-10-10`

- 🔥 Input.TextArea support word count. [#26952](https://github.com/ant-design/ant-design/pull/26952) [@zhangchen915](https://github.com/zhangchen915)
- DatePicker
  - 🔥 DatePicker support custom `format` by passing a function. [#26845](https://github.com/ant-design/ant-design/pull/26845)
  - 🐞 Fix RangePicker initial date of end panel cannot selected. [#23167](https://github.com/ant-design/ant-design/issues/23167)
- Form
  - 🔥 Form.Item support `tooltip` to customize tooltip. [#26780](https://github.com/ant-design/ant-design/pull/26780)
  - 🆕 Form.List support `rules` validation and add Form.ErrorList to show the errors. [#26676](https://github.com/ant-design/ant-design/pull/26676)
  - 🆕 Form.Item support `messageVariables` prop. [#26597](https://github.com/ant-design/ant-design/pull/26597)
  - 🐞 Fix Form `onValuesChange` second param return fully `store` values instead of validate fields. [#26808](https://github.com/ant-design/ant-design/pull/26808)
- Upload
  - 🔥 Upload can custom the item of file list by `itemRender` now. [#26333](https://github.com/ant-design/ant-design/pull/26333)
  - 🆕 Upload custom action icons now supports callback functions. [#26684](https://github.com/ant-design/ant-design/pull/26684) [@mwaddell](https://github.com/mwaddell)
- Table
  - 🆕 Table `sticky` now support `getContainer`. [#26973](https://github.com/ant-design/ant-design/pull/26973)
  - 🐞 Fix Table should not render dropdown filter icon when filterDropdown is `undefined`. [#27002](https://github.com/ant-design/ant-design/pull/27002) [@shangyilim](https://github.com/shangyilim)
- Modal
  - 🛠 Refactor Modal animation code so that it will remove all dom element by `destroyOnClose` when closed. [#26940](https://github.com/ant-design/ant-design/pull/26940)
  - 🆕 Modal add `modalRender` prop which can be used for draggable dialog. [#26507](https://github.com/ant-design/ant-design/pull/26507) [@jhoneybee](https://github.com/jhoneybee)
- 🆕 Space add `split` prop. [#26948](https://github.com/ant-design/ant-design/pull/26948)
- 🆕 Image `preview` prop now support `visible` and `onVisibleChange`. [#26915](https://github.com/ant-design/ant-design/pull/26915)
- 🆕 InputNumber will trigger `onStep` prop when click up/down buttons. [#27075](https://github.com/ant-design/ant-design/pull/27075)
- 🆕 Avatar `size` support responsive config. [#26244](https://github.com/ant-design/ant-design/pull/26244) [@willamesoares](https://github.com/willamesoares)
- 🐞 Fix Radio.Button children cannot apply Tooltip. [#27050](https://github.com/ant-design/ant-design/pull/27050)
- RTL
  - ⬅️ Fix List action button position in RTL mode. [#26964](https://github.com/ant-design/ant-design/pull/26964)
  - ⬅️ Fix Transfer pagination style in RTL mode. [#26960](https://github.com/ant-design/ant-design/pull/26960)
  - ⬅️ Fix Upload style in RTL mode. [#26961](https://github.com/ant-design/ant-design/pull/26961)
  - ⬅️ Optimize Tag style to avoid the interaction between theme and RTL mode. [#26955](https://github.com/ant-design/ant-design/pull/26955)
  - ⬅️ Optimize Cascader and Tree style of the data expansion loading icon in RTL mode. [#27010](https://github.com/ant-design/ant-design/pull/27010)
- TypeScript
  - 🤖 Fix typo `TimeLineItemProps` to `TimelineItemProps`. [#27001](https://github.com/ant-design/ant-design/pull/27001) [@mgcrea](https://github.com/mgcrea)
  - 🤖 Fix Slider missing `autoFocus` prop. [#26995](https://github.com/ant-design/ant-design/pull/26995) [@shangyilim](https://github.com/shangyilim)
  - 🤖 Fix Slider `step` prop not accepting `null` value. [#26984](https://github.com/ant-design/ant-design/pull/26984) [@shangyilim](https://github.com/shangyilim)
  - 🤖 Fix Slider.Range `trackStyle` and `handleStyle` should be array. [#27033](https://github.com/ant-design/ant-design/pull/27033)
  - 🤖 Optimize Tag `onClose` TypeScript definition. [#26932](https://github.com/ant-design/ant-design/pull/26932)
  - 🤖 Improve Form TypeScript definition to support `getFieldsValue` return generic type without `namePath` argument. [#26791](https://github.com/ant-design/ant-design/pull/26791)
- Locale
  - 🇧🇾 Add Belarusian locale. [#27028](https://github.com/ant-design/ant-design/pull/27028) [@StIvan8](https://github.com/StIvan8)
  - 🇯🇵 Fix Japanese locale. [#27043](https://github.com/ant-design/ant-design/pull/27043) [@iorikingdom](https://github.com/iorikingdom)
  - 🇹🇭 Add Thai locale for Pickers. [#26993](https://github.com/ant-design/ant-design/pull/26993) [@anawinwz](https://github.com/anawinwz)
  - 🇹🇷 Add Turkish locale of Form optional text. [#27017](https://github.com/ant-design/ant-design/pull/27017) [@alperTunca](https://github.com/alperTunca)
  - 🇵🇱 Add Polish locale of Table. [#26913](https://github.com/ant-design/ant-design/pull/26913) [@daczczcz1](https://github.com/daczczcz1)

## 4.6.6

`2020-09-27`

- 🐞 Fix Steps first item shifts in small screen. [#26894](https://github.com/ant-design/ant-design/pull/26894)
- 💄 Fix Divider border style not work when text is provided. [#26863](https://github.com/ant-design/ant-design/pull/26863)
- 🐞 Fix Radio.Button validation error highlight. [#26849](https://github.com/ant-design/ant-design/pull/26849) [@dhorelik](https://github.com/dhorelik)
- 💄 Fix Typography link-decoration style. [#26854](https://github.com/ant-design/ant-design/pull/26854) [@vineetvk01](https://github.com/vineetvk01)
- Locale
  - 🌐 Add Thai locale support. [#26906](https://github.com/ant-design/ant-design/pull/26906) [@anawinwz](https://github.com/anawinwz)
- TypeScript
  - 🤖 Fix message.destroy parameter type. [#26864](https://github.com/ant-design/ant-design/pull/26864) [@lihqi](https://github.com/lihqi)
  - 🤖 Optimize Slider type definition. [#26884](https://github.com/ant-design/ant-design/pull/26884)
  - 🤖 Form properly export `FormListProps` type. [#26831](https://github.com/ant-design/ant-design/pull/26831) [@mgcrea](https://github.com/mgcrea)

## 4.6.5

`2020-09-20`

- 💄 Fix Descriptions item long text ellipsis issue. [#26820](https://github.com/ant-design/ant-design/pull/26820)
- 🐞 Fix Menu unexpected scrollbar when show and hide. [#26817](https://github.com/ant-design/ant-design/pull/26817)
- 🐞 Fix `@layout-sider-background` cannot set to linear gradient color. [#26810](https://github.com/ant-design/ant-design/pull/26810)
- 🐞 Fix Select compositing status lost when input first letter in Chinese. [#26796](https://github.com/ant-design/ant-design/pull/26796)
- 🐞 Fix Table `@table-sticky-zindex` less compile error issue. [#26800](https://github.com/ant-design/ant-design/pull/26800) [@chimp1nski](https://github.com/chimp1nski)
- Button
  - 💄 Fix Button align issue when has icon only. [#26785](https://github.com/ant-design/ant-design/pull/26785)
  - 🐞 Fix Button warning `Invalid value for prop navigate` when using with react-router. [#26740](https://github.com/ant-design/ant-design/pull/26740) [@knobo](https://github.com/knobo)
- 💄 Fix TimePicker column align issue, add `@picker-time-panel-column-width` and `@picker-time-panel-column-height` less variables. [#26784](https://github.com/ant-design/ant-design/pull/26784)
- 🐞 Fix AutoComplete warning when using `placeholder` and `allowClear`. [#26765](https://github.com/ant-design/ant-design/pull/26765)
- 🐞 Fix Space show items when it's render empty dom. [#26721](https://github.com/ant-design/ant-design/pull/26721) [@knobo](https://github.com/knobo)
- 🛠 Dedupe `rc-trigger` version to reduce package size. [#26803](https://github.com/ant-design/ant-design/pull/26803)
- TypeScript
  - 🤖 Cascader add `name` and `id` props definition. [#26660](https://github.com/ant-design/ant-design/pull/26660) [@alwaysloseall](https://github.com/alwaysloseall)

## 4.6.4

`2020-09-13`

- 💄 style: Card card image has extra 1px border. [#26659](https://github.com/ant-design/ant-design/pull/26659)
- 💄 Fix Select `placeholder` color not same as Input. [#26651](https://github.com/ant-design/ant-design/pull/26651) [@wangcch](https://github.com/wangcch)
- 🐞 Fix Menu not support React.Fragment inside. [#26656](https://github.com/ant-design/ant-design/pull/26656)
- 🐞 Fix TextArea different behavior with Input when set `value` to `undefined`. [#26652](https://github.com/ant-design/ant-design/pull/26652)
- 🐞 Fix Motion related issue like Upload align flash and Form.Item with `help` ssr issue. [#26628](https://github.com/ant-design/ant-design/pull/26628)
- 🐞 Fix Typography.Link warning `Invalid value for prop navigate` when using with react-router. [#26623](https://github.com/ant-design/ant-design/pull/26623)
- 🐞 Fix Table pagination missing when is above table. [#26618](https://github.com/ant-design/ant-design/pull/26618)
- 🐞 Fix Upload in control miss file when upload multiple file in same time. [#26612](https://github.com/ant-design/ant-design/pull/26612)
- TypeScript
  - 🤖 Fix Table that sorter `compare` and `multiple` should be optional. [#26686](https://github.com/ant-design/ant-design/pull/26686)

## 4.6.3

`2020-09-06`

- 🛎 Sort props `className` to the end. [#26602](https://github.com/ant-design/ant-design/pull/26602)
- Table
  - 💄 Fix Table nested table styles affects all sub-level tables. [#26568](https://github.com/ant-design/ant-design/pull/26568) [@willc001](https://github.com/willc001)
  - 🐞 Fix elements above Table was not clickable elements which has `float: right;` style. [#26599](https://github.com/ant-design/ant-design/pull/26599)
- 🐞 Fix Modal closing cause scroll position jump up. [#26538](https://github.com/ant-design/ant-design/pull/26538)
- 🐞 Fix the type declaration of onError in `customRequest` options of Upload. [#26601](https://github.com/ant-design/ant-design/pull/26601) [@yingpengsha](https://github.com/yingpengsha)
- 🐞 Shutdown Select/TreeSelect autocomplete list in Chrome. [#26590](https://github.com/ant-design/ant-design/pull/26590)
- 🐞 Fix Cascader value overwritten when filtering. [#26569](https://github.com/ant-design/ant-design/pull/26569) [@lich-yoo](https://github.com/lich-yoo)
- 🐞 Fix Modal jump out of screen in some situations. [#25765](https://github.com/ant-design/ant-design/pull/25765) [@tanmoyopenroot](https://github.com/tanmoyopenroot)
- 🐞 Fix Radio.Group not working properly, when is used in legacy Form. [#26555](https://github.com/ant-design/ant-design/pull/26555) [@willc001](https://github.com/willc001)
- 🐞 Fix Pagination align issue in windows. [#26549](https://github.com/ant-design/ant-design/pull/26549)
- 🐞 Fix Form with `help` make ssr un-sync issue. [#26542](https://github.com/ant-design/ant-design/pull/26542)
- 🐞 Fix Avatar doesn't scale fallback text well when display is none. [#26522](https://github.com/ant-design/ant-design/pull/26522) [@zhangyu1818](https://github.com/zhangyu1818)
- TypeScript
  - 🤖 Col Add `flex` type to `ColSize` interface. [#26578](https://github.com/ant-design/ant-design/pull/26578) [@blaiz](https://github.com/blaiz)
  - 🤖 Fix Tooltip/Popover `children` tsd to accept ReactNode. [#26534](https://github.com/ant-design/ant-design/pull/26534)

## 4.6.2

`2020-08-31`

- Upload
  - 🐞 Fix Upload list status issue when in control mode. [#26481](https://github.com/ant-design/ant-design/pull/26481)
  - 💄 Fix Upload `picture-card` style unexpected margin in Form.Item. [#26367](https://github.com/ant-design/ant-design/pull/26367)
- 💄 Fix Select focus shadow style. [#26465](https://github.com/ant-design/ant-design/pull/26465) [@Rainy](https://github.com/Rainy)
- Table
  - 🐞 Fix Table Pagination not hide with empty data when show on top position. [#26143](https://github.com/ant-design/ant-design/pull/26143) [@zhangchen915](https://github.com/zhangchen915)
  - 💄 Fix Table expand icon size issue when `@font-size-base` is `12px`. [#26409](https://github.com/ant-design/ant-design/pull/26409)
- Space
  - 🐞 Fix Space not support React.Fragment issue. [#26444](https://github.com/ant-design/ant-design/pull/26444)
  - 🐞 Fix Space preserve empty dom node when `children` contains empty node. [#26389](https://github.com/ant-design/ant-design/pull/26389)
- 🐞 Fix Badge not work when `status` or `color` is empty. [#26375](https://github.com/ant-design/ant-design/pull/26375) [@zhangchen915](https://github.com/zhangchen915)
- 💄 Fix Tree draggable transition style. [#26387](https://github.com/ant-design/ant-design/pull/26387)
- 🐞 Fix `colorPalette is not defined` when customize theme in some situation. [#26395](https://github.com/ant-design/ant-design/pull/26395)
- TypeScript
  - 🐞 Fix TimePicker.RangePicker typescript need `picker` issue. [#26446](https://github.com/ant-design/ant-design/pull/26446)
  - 🐞 Upload extended `showUploadList` of Upload with `removeIcon` and `downloadIcon` properties. [#26406](https://github.com/ant-design/ant-design/pull/26406) [@bencallaway](https://github.com/bencallaway)
- RTL
  - 🐞 Fix the rtl style of Col. [#26479](https://github.com/ant-design/ant-design/pull/26479) [#26482](https://github.com/ant-design/ant-design/pull/26482) [@TrueMoein](https://github.com/TrueMoein)

## 4.6.1

`2020-08-24`

- TypeScript
  - 🐞 Fix Upload type declaration missing `children`. [#26347](https://github.com/ant-design/ant-design/pull/26347)

## 4.6.0

`2020-08-23`

- 💄 Darker `@text-color` for WCAG 2.0 on contrast ratio. [#25630](https://github.com/ant-design/ant-design/pull/25630)
- 🔥 New Image component. [#26296](https://github.com/ant-design/ant-design/pull/26296)
- 🔥 Table support `sticky` prop to sticky header and scroll bar. [#25939](https://github.com/ant-design/ant-design/pull/25939)
- 🛠 Refactor Upload via hooks. [#26196](https://github.com/ant-design/ant-design/pull/26196)
- Form
  - 🆕 Form support style of required mark with `requiredMark` and deprecate `hideRequiredMark` prop. [#26309](https://github.com/ant-design/ant-design/pull/26309)
  - 🆕 Form.List support the second `index` param in `add`. [#26081](https://github.com/ant-design/ant-design/pull/26081)
- 🆕 VirtualList support no blink jump and fix Select blank dropdown issue. [#26306](https://github.com/ant-design/ant-design/pull/26306)
- Typography
  - 🆕 Support Typography.Text `success` type. [#26145](https://github.com/ant-design/ant-design/pull/26145) [@llwslc](https://github.com/llwslc)
  - 🆕 Typography `copyable` support hide tooltip and `editable` support config icon and tooltip. [#25953](https://github.com/ant-design/ant-design/pull/25953) [@llwslc](https://github.com/llwslc)
  - 🆕 Add Typography.Title level 5. [#25861](https://github.com/ant-design/ant-design/pull/25861)
  - 🆕 Typography add `maxLength` & `autoSize` with `editable` config [#25373](https://github.com/ant-design/ant-design/pull/25373) [@CornerSkyless](https://github.com/CornerSkyless)
- 🐞 Fix Transfer `filterOption` not trigger when search spaces. [#26335](https://github.com/ant-design/ant-design/pull/26335)
- Progress
  - 🐞 Fix Progress `steps` don't support `trailColor`. [#26323](https://github.com/ant-design/ant-design/pull/26323)
  - 🐞 Fix Progress `success.percent` not working when `type="circle"`. [#26307](https://github.com/ant-design/ant-design/pull/26307)
- 🐞 Fix Textarea don't display `defaultValue` when `value` is `undefined`. [#26327](https://github.com/ant-design/ant-design/pull/26327)
- Cascader
  - 🐞 Fix Cascader options not open with search after ESC pressing. [#26271](https://github.com/ant-design/ant-design/pull/26271) [@flyerH](https://github.com/flyerH)
  - 💄 Optimize Cascader clear animation. [#26186](https://github.com/ant-design/ant-design/pull/26186)
- 🗑 Remove deprecated `Button.Group` and please use Space component instead. [#26260](https://github.com/ant-design/ant-design/pull/26260)
- Select
  - 🆕 Select support `onClear` prop. [#25907](https://github.com/ant-design/ant-design/pull/25907)
  - 🐞 Fix Select `mode="tags"` showing duplicated items when search. [#25907](https://github.com/ant-design/ant-design/pull/25907)
  - 🐞 Fixed the style exception that was disabled when Select focused. [#26255](https://github.com/ant-design/ant-design/pull/26255)
  - 🐞 Fix Select icon overlap with selections when `showArrow` enabled. [#26168](https://github.com/ant-design/ant-design/pull/26168) [@zhangchen915](https://github.com/zhangchen915)
- DatePicker
  - 🐞 Fix panel not correct when `picker` changed. [#26093](https://github.com/ant-design/ant-design/issues/26093)
  - 🐞 Fix RangePicker do not close panel when click clear icon. [#26188](https://github.com/ant-design/ant-design/issues/26188)
- 🐞 Fix Pagination font family style. [#26230](https://github.com/ant-design/ant-design/pull/26230) [@albertms10](https://github.com/albertms10)
- 🐞 Fix Space children remount in some case. [#26219](https://github.com/ant-design/ant-design/pull/26219)
- Badge
  - 💄 Add `@badge-color` less variable. [#26159](https://github.com/ant-design/ant-design/pull/26159)
  - 🆕 Badge support `size` prop. [#25851](https://github.com/ant-design/ant-design/pull/25851) [@moonrailgun](https://github.com/moonrailgun)
- 🆕 Tabs `tabBarExtraSlot` support extra position. [#25138](https://github.com/ant-design/ant-design/pull/25138) [@jesse3mh9a](https://github.com/jesse3mh9a)
- 💄 Optimize the display effect of Descriptions when there is more content. [#25903](https://github.com/ant-design/ant-design/pull/25903)
- 🆕 message could be detroied by `message.desctroy(key)`. [#26052](https://github.com/ant-design/ant-design/pull/26052) [@lihqi](https://github.com/lihqi)
- 💄 Adjust InputNumber handler bar to be hidden when `readOnly`. [#25998](https://github.com/ant-design/ant-design/pull/25998)
- Locale
  - 🌐 Add Galician locale support. [#26015](https://github.com/ant-design/ant-design/pull/26015) [@barreeeiroo](https://github.com/barreeeiroo)
  - 🇱🇹 Add Lithuanian locale support. [#26312](https://github.com/ant-design/ant-design/pull/26312) [@mslotvinskij](https://github.com/mslotvinskij)
  - 🌐 Use `kmr_IQ` to replace `ku_IQ`. [#26030](https://github.com/ant-design/ant-design/pull/26030)
- RTL
  - 💄 Optimize the connection line style in Tree RTL mode. [#26205](https://github.com/ant-design/ant-design/pull/26205)
  - 💄 Optimize Dropdown RTL writing to avoid dark mode style overlays. [#26206](https://github.com/ant-design/ant-design/pull/26206)
- TypeScript
  - 🤖 Fix Form.Item `initialValue` missing definition. [#26292](https://github.com/ant-design/ant-design/pull/26292) [@miaoyuxinbaby](https://github.com/miaoyuxinbaby)
  - 🤖 Form support generic type. [#25937](https://github.com/ant-design/ant-design/pull/25937)

## 4.5.4

`2020-08-12`

- 🐞 Fix Form.Item `hidden` not working in less. [#26152](https://github.com/ant-design/ant-design/pull/26152)
- 🐞 Fix Dropdown render issue when `overlay` is string. [#26135](https://github.com/ant-design/ant-design/pull/26135)
- 🐞 Fix Table pagination disappear when last record in last page is deleted. [#26133](https://github.com/ant-design/ant-design/pull/26133) [@QoVoQ](https://github.com/QoVoQ)
- Tree
  - 🐞 Fix Tree.DirectoryTree can not use `scrollTo` with ref. [#26129](https://github.com/ant-design/ant-design/pull/26129)
  - 🐞 Fix Tree lost line between top level nodes when enable `showLine`. [#25991](https://github.com/ant-design/ant-design/pull/25991) [@zhangchen915](https://github.com/zhangchen915)
- 💄 Add `@badge-color` less variable. [#26159](https://github.com/ant-design/ant-design/pull/26159)
- RTL
  - 🐞 Fixed Input.Search border style in RTL mode. [#26156](https://github.com/ant-design/ant-design/pull/26156)
  - 🐞 Fix the style of Input when `addonBefore` in RTL mode. [#26153](https://github.com/ant-design/ant-design/pull/26153)
  - 🐞 Fix multiple style issues for DatePicker in RTL mode. [#26149](https://github.com/ant-design/ant-design/pull/26149) [#26157](https://github.com/ant-design/ant-design/pull/26157) [#26158](https://github.com/ant-design/ant-design/pull/26158)
- TypeScript
  - 🐞 Fix Slider `handleStyle` and `trackStyle` TypeScript definitions. [#26160](https://github.com/ant-design/ant-design/pull/26160)

## 4.5.3

`2020-08-08`

- Menu
  - 🐞 Fix horizontal Menu dark `theme` style under dark theme. [#26062](https://github.com/ant-design/ant-design/pull/26062)
  - 🐞 Fix the position of the horizontal Menu in dark theme and RTL mode. [#26032](https://github.com/ant-design/ant-design/pull/26032)
- Table
  - 🐞 Fix Table crash when `dataSource` contains number. [#26042](https://github.com/ant-design/ant-design/pull/26042)
  - 🐞 Fix Table empty filters throw warning. [#26001](https://github.com/ant-design/ant-design/pull/26001)
- Form
  - 🐞 Fix Form.Item `hidden` not work with `noStyle`. [#26020](https://github.com/ant-design/ant-design/pull/26020)
  - 💄 Fix Form.Item margin is uncorrect in compact mode. [#26069](https://github.com/ant-design/ant-design/pull/26069)
- Transfer
  - 🐞 Fix the mouse style of the head dropDown when Transfer is `disabled`. [#26005](https://github.com/ant-design/ant-design/pull/26005)
  - 🐞 Fix the problem that Pagination is not `disabled` when Transfer is `disabled`. [#26009](https://github.com/ant-design/ant-design/pull/26009)
- Cascader
  - 💄 Cascader selector down arrow doesn't rotate. [#26078](https://github.com/ant-design/ant-design/pull/26078) [@07akioni](https://github.com/07akioni)
  - 🐞 Fix Cascader text overflow bug in Firefox. [#26011](https://github.com/ant-design/ant-design/pull/26011)
  - 🐞 Fix the problem that the color of mouse hover border is abnormal when Cascader is `disabled`. [#25970](https://github.com/ant-design/ant-design/pull/25970)
- Select
  - 💄 Optimize the `disabled` style of Select multiple mode. [#25980](https://github.com/ant-design/ant-design/pull/25980)
  - 🐞 Fix the mouse style of custom icon when Select is `disabled`. [#26002](https://github.com/ant-design/ant-design/pull/26002)
- 🐞 Fix Breadcrumb.Item lost separator after wrapping in component. [#25984](https://github.com/ant-design/ant-design/pull/25984) [@flyerH](https://github.com/flyerH)
- 🐞 Fix InputNumber dark theme handler background color. [#26072](https://github.com/ant-design/ant-design/pull/26072)
- 🐞 Fix the missing `key` of Avatar.Group. [#26098](https://github.com/ant-design/ant-design/pull/26098)
- 💄 Adjusts Mentions `readOnly` mouse style to native style. [#25977](https://github.com/ant-design/ant-design/pull/25977)
- 💄 Add `@btn-line-height`. [#26014](https://github.com/ant-design/ant-design/pull/26014)
- 💄 Optimize Pagination style when `simple` type and `disabled`. [#26008](https://github.com/ant-design/ant-design/pull/26008)
- 🐞 Fix Modal `useModal` missing style issue. [#25967](https://github.com/ant-design/ant-design/pull/25967)
- 🐞 Fix Steps RTL style when use `progress`. [#26075](https://github.com/ant-design/ant-design/pull/26075)
- 🌐 Improve Arabic locale. [#26094](https://github.com/ant-design/ant-design/pull/26094) [@Mohelm97](https://github.com/Mohelm97)
- 🌐 Improve fr_FR localization. [#26034](https://github.com/ant-design/ant-design/pull/26034) [@Thanaen](https://github.com/Thanaen)

## 4.5.2

`2020-08-02`

- 🐞 Fix Slider tooltip abnormal visibility. [#25945](https://github.com/ant-design/ant-design/pull/25945) [@lihqi](https://github.com/lihqi)
- 🐞 Fix Divider color in dark mode. [#25922](https://github.com/ant-design/ant-design/pull/25922)
- 🐞 Fix Radio.Button text color when `disabled` and `checked`. [#25911](https://github.com/ant-design/ant-design/pull/25911)
- 🐞 Fix Carousel children height smaller then parent node issue. [#25906](https://github.com/ant-design/ant-design/pull/25906)
- 🐞 Fix Table `indentSize` couldn't be zero value. [#25890](https://github.com/ant-design/ant-design/pull/25890) [@OmriGM](https://github.com/OmriGM)
- 🐞 Fix List `actions` show cursor outside clickable area. [#25961](https://github.com/ant-design/ant-design/pull/25961)
- 🇷🇺 Improve Russian locale. [#25958](https://github.com/ant-design/ant-design/pull/25958) [@addictional](https://github.com/addictional)
- RTL
  - 🐞 Fixed vertical Slider default `tooltipPlacement` in RTL mode. [#25909](https://github.com/ant-design/ant-design/pull/25909)
  - 🐞 Fix Tabs RTL style of `card` type. [#25936](https://github.com/ant-design/ant-design/pull/25936)
  - 🐞 Fix nested Table RTL style under dark theme. [#25938](https://github.com/ant-design/ant-design/pull/25938)

## 4.5.1

`2020-07-28`

- 🐞 Fix Badge style causing build error. [#25863](https://github.com/ant-design/ant-design/pull/25863)
- 🐞 Fix Menu in `horizontal` `dark` status Menu.Item background style glitch. [#25850](https://github.com/ant-design/ant-design/pull/25850)
- 💄 Optimize Divider color in none-white background. [#25855](https://github.com/ant-design/ant-design/pull/25855)
- 💄 Remove multiple Select choice animation of item. [#25852](https://github.com/ant-design/ant-design/pull/25852)
- TypeScript
  - Export Form `FormList` interface. [#25849](https://github.com/ant-design/ant-design/pull/25849)

## 4.5.0

`2020-07-28`

- 🆕 Input and Input.TextArea support `bordered` prop. [#25617](https://github.com/ant-design/ant-design/pull/25617)
- 🆕 Add `useMessage` hook for Message to support `context` access. [#25422](https://github.com/ant-design/ant-design/pull/25422)
- 🆕 Tree support `titleRender` to customize all nodes' content. [#25624](https://github.com/ant-design/ant-design/pull/25624)
- 🆕 Descriptions add `extra` prop. [#25512](https://github.com/ant-design/ant-design/pull/25512) [@zzz111](https://github.com/zzz111)
- 🆕 Add `Modal.config` to set `rootPrefixCls` for Modal statis methods. [#25613](https://github.com/ant-design/ant-design/pull/25613)
- 🆕 Drawer support `push` prop for multi-Drawer linkage. [#25445](https://github.com/ant-design/ant-design/pull/25445) [@jinxin0112](https://github.com/jinxin0112)
- 🆕 Add Badge.Ribbon component. [#25456](https://github.com/ant-design/ant-design/pull/25456)
- 🆕 Steps support `percent` prop to show step icon progress. [#25839](https://github.com/ant-design/ant-design/pull/25839)
- 💄 **Menu.Item's blue indicator line and dropdown width are the same as its content's width in `horizontal` mode.** [#25622](https://github.com/ant-design/ant-design/pull/25622)
- Avatar
  - 🆕 Add Avatar.Group for showing a set of avatars. [#25192](https://github.com/ant-design/ant-design/pull/25192)
  - 🐞 Fix Avatar not fallback correctly when `src` is invalid. [#25806](https://github.com/ant-design/ant-design/pull/25806)
- DatePicker
  - 🆕 DatePicker support [date-fns](https://date-fns.org/). [#25822](https://github.com/ant-design/ant-design/pull/25822) [@fireairforce](https://github.com/fireairforce)
  - 🆕 Improve DatePicker hovering experience, the placeholder will change to format value of target-date when hovering a date cell. ([#25050](https://github.com/ant-design/ant-design/issues/25050)). [#25784](https://github.com/ant-design/ant-design/pull/25784) [@Kermit-Xuan](https://github.com/Kermit-Xuan)
  - 🆕 RangePicker `onCalendarChange` add `range` param to indicate currently activated pane. [#25568](https://github.com/ant-design/ant-design/pull/25568) [@Kim-Wing-Fung](https://github.com/Kim-Wing-Fung)
  - 🆕 DatePicker support `panelRender` to customize panel. [#25488](https://github.com/ant-design/ant-design/pull/25488)
  - 🐞 Fix QuarterPicker not working, remove DatePicker.XxxPicker and recommend `picker='xxx'` usage instead. [#25768](https://github.com/ant-design/ant-design/pull/25768)
- Form
  - 🆕 Form.List support array in `remove` method. [#25638](https://github.com/ant-design/ant-design/pull/25638) [@fireairforce](https://github.com/fireairforce)
  - 🆕 Form.Item supports `dependencies` to control updating logic with render props `children`. [#25408](https://github.com/ant-design/ant-design/pull/25408)
  - 🆕 Adjust Form.Item validateFist to validate in order. Origin logic use parallel to validate. [#25321](https://github.com/ant-design/ant-design/pull/25321)
  - 🐞 Fix Form.Item sometime not clean up prev error message. [#25737](https://github.com/ant-design/ant-design/pull/25737)
  - 🐞 Fix Form.Item not collect `validateStatus` when children Form.Item with `noStyle` has an error. [#25734](https://github.com/ant-design/ant-design/pull/25734)
  - 🐞 Fix Form.Item setting `labelCol={{ offset: number }}` doesn't work if layout is vertical. [#25713](https://github.com/ant-design/ant-design/pull/25713) [@zhangchen915](https://github.com/zhangchen915)
  - ⌨️ Form add `role="alert"` attribute on validation message node to import accessibility. [#25735](https://github.com/ant-design/ant-design/pull/25735) [@AlbertAZ1992](https://github.com/AlbertAZ1992)
- Calendar
  - 🐞 Fix Calendar `validRange` prevents `disabledDate`. [#25626](https://github.com/ant-design/ant-design/pull/25626) [@zhangchen915](https://github.com/zhangchen915)
  - 🐞 Fix Calendar `validRange` not working on month selection dropdown. [#25626](https://github.com/ant-design/ant-design/pull/25626) [@zhangchen915](https://github.com/zhangchen915)
- 🐞 Fix Table `indeterminate` returned by `getCheckboxProps` not working. [#25649](https://github.com/ant-design/ant-design/pull/25649)
- 🐞 Fix Select clear icon position in Form.Item. [#25728](https://github.com/ant-design/ant-design/pull/25728)
- 🐞 Fix Pagination mouse style of the page turning button. [#25772](https://github.com/ant-design/ant-design/pull/25772)
- 🐞 Fix TreeSelect `treeNodeLabelProp` affect tree node render result. [#25755](https://github.com/ant-design/ant-design/pull/25755)
- 🐞 Fix Carousel `findDOMNode` warning in strict mode. [#25744](https://github.com/ant-design/ant-design/pull/25744)
- 🐞 Fix Radio causing SSR build errors with `webpack@4.44.0`. [25821](https://github.com/ant-design/ant-design/pull/25821) [@Kermit-Xuan](https://github.com/Kermit-Xuan)
- 🐞 Fix Tabs focus & active state color when disabled. [25827](https://github.com/ant-design/ant-design/pull/25827) [hsuanxyz](https://github.com/hsuanxyz)
- 💄 Card action pane color is unified with body color. [#25722](https://github.com/ant-design/ant-design/pull/25722)
- ⌨️ Improve Alert/message/notification accessibility by adding role attribute. [#25774](https://github.com/ant-design/ant-design/pull/25774)
- 🇭🇰 Add zh_HK localization. [#25731](https://github.com/ant-design/ant-design/pull/25731) [@wuchu](https://github.com/wuchu)
- 🇩🇪 Improve Form de_DE localization. [#25823](https://github.com/ant-design/ant-design/pull/25823) [@LukeTimeWalker](https://github.com/LukeTimeWalker)

## 4.4.3

`2020-07-20`

- 🐞 Fix Layout `trigger` cannot customize zero width to trigger. [#25653](https://github.com/ant-design/ant-design/pull/25653)
- 🐞 Fix Form.Item `help` style when verification fails. [#25582](https://github.com/ant-design/ant-design/pull/25582) [@zhangchen915](https://github.com/zhangchen915)
- 🐞 Fix Descriptions abnormal style inside Table `expandedRowRender`. [#25593](https://github.com/ant-design/ant-design/pull/25593)
- 💄 Add `@zindex-popconfirm: 1060` less variable, and improve `@zindex-tooltip` into `1070`. [#25693](https://github.com/ant-design/ant-design/pull/25693)
- 🛠 Upgrade `react-slick` to reduce bundle size. [#25599](https://github.com/ant-design/ant-design/pull/25599)
- 🌐 Improve Catalan ca_ES localization. [#25583](https://github.com/ant-design/ant-design/pull/25583) [@albertms10](https://github.com/albertms10)
- 🇸🇦 Improve ar_EG localization. [#25587](https://github.com/ant-design/ant-design/pull/25587) [@amir5000](https://github.com/amir5000)
- TypeScript
  - 🐞 Fix Upload `customRequest` file interface. [#25598](https://github.com/ant-design/ant-design/pull/25598) [@AlbertAZ1992](https://github.com/AlbertAZ1992)

## 4.4.2

`2020-07-11`

- 🛠 Adjust Alert animation to remove directly dom operation. [#dd8e9f8](https://github.com/ant-design/ant-design/commit/dd8e9f8) [@Yunfly](https://github.com/Yunfly)
- Select
  - 🐞 Fix Select shifts vertically when searching. [#25536](https://github.com/ant-design/ant-design/pull/25536)
  - 💄 Add `@select-item-select-color` to control the color when Select item is selected. [#25476](https://github.com/ant-design/ant-design/pull/25476)
- 🐞 Fix Form.Item warning for `preserve` as invalidate dom prop. [#25518](https://github.com/ant-design/ant-design/pull/25518)
- 🐞 Fix Card cover margin bug when bordered is false. [#25515](https://github.com/ant-design/ant-design/pull/25515) [@yutingzhao1991](https://github.com/yutingzhao1991)
- 💄 Adjust Typography style to set `overflow-wrap: break-word` as default. [#25516](https://github.com/ant-design/ant-design/pull/25516)
- 🐞 Fix Table `expandedRowRender` nested Table cell background color. [#25498](https://github.com/ant-design/ant-design/pull/25498)
- 🐞 Fix Popover wrong positioning on Radio.Button. [#25449](https://github.com/ant-design/ant-design/pull/25449) [@zgoby](https://github.com/zgoby)
- 🐞 Fix RangePicker clear icon position issue when `size=small`. [#25458](https://github.com/ant-design/ant-design/pull/25458)
- 🆕 Upload supports to show thumbnail for non-image files as `thumbUrl` configured in `onChange` event. [#25432](https://github.com/ant-design/ant-design/pull/25432) [@AlbertAZ1992](https://github.com/AlbertAZ1992)
- 🐞 Fix Table `onChange` triggered multiple times when change page size. [#25520](https://github.com/ant-design/ant-design/pull/25520) [@zhangchen915](https://github.com/zhangchen915)
- 🛠 Remove `babel-runtime` and add `@babel/runtime` in dependencies, reduce gzipped bundle size `18.6KB`. [#25530](https://github.com/ant-design/ant-design/pull/25530)
- 🇪🇸 Improve es_ES localization. [#25460](https://github.com/ant-design/ant-design/pull/25460) [@gersongams](https://github.com/gersongams)

## 4.4.1

`2020-07-06`

- Menu
  - 🐞 Fix Menu.Item use `a` tag color style issue. [#25414](https://github.com/ant-design/ant-design/pull/25414) [@kaysonwu](https://github.com/kaysonwu)
  - 🐞 Fix Menu inline animation not correct issue. [#25341](https://github.com/ant-design/ant-design/pull/25341)
  - 💄 Optimize Menu collapse animation. [#25301](https://github.com/ant-design/ant-design/pull/25301)
- 🐞 Fix Input disabled `backgroundColor` is override when inside a `error` or `warning` Form.Item. [#25385](https://github.com/ant-design/ant-design/pull/25385)
- 🐞 Fix Table header extra border of right side column. [#25378](https://github.com/ant-design/ant-design/pull/25378)
- 🐞 Fix Grid ResponsiveObserve not been unsubscribed correctly. [#25319](https://github.com/ant-design/ant-design/pull/25319) [@zhangchen915](https://github.com/zhangchen915)
- 🐞 Fix Progress `successPercent` warning message and correct `success.progress` to `success.percent`. [#25356](https://github.com/ant-design/ant-design/pull/25356) [@fireairforce](https://github.com/fireairforce)
- 🐞 Fix PageHeader Tabs unnecessary `margin-bottom`. [#25340](https://github.com/ant-design/ant-design/pull/25340) [@dickeylth](https://github.com/dickeylth)
- Form
  - 🐞 Fix Form.Item `hidden` no working. [#25336](https://github.com/ant-design/ant-design/pull/25336)
  - 🐞 Fix Form.Item help message may not disappear in a `display:none` container. [#25297](https://github.com/ant-design/ant-design/pull/25297)
- Radio
  - 🐞 Fix Radio.Group throw `Function components cannot be given refs` warning message. [#25328](https://github.com/ant-design/ant-design/pull/25328)
  - 🐞 Fix Radio.Group style with extra spaces in `children`. [#25304](https://github.com/ant-design/ant-design/pull/25304) [@ElderJames](https://github.com/ElderJames)
- 🐞 Fix Drawer click mask will trigger close event multiple times. [#25313](https://github.com/ant-design/ant-design/pull/25313)
- 🐞 Fix Skeleton Button/Avatar/Input/Image default width to auto. [#25303](https://github.com/ant-design/ant-design/pull/25303)
- 🇺🇦 Update uk_UA localization. [#25402](https://github.com/ant-design/ant-design/pull/25402) [@kitsoRik](https://github.com/kitsoRik)
- 🇳🇴 Update nb_NO localization. [#25374](https://github.com/ant-design/ant-design/pull/25374) [@Johannes-Andersen](https://github.com/Johannes-Andersen)
- TypeScript
  - 🐞 Fix Slider `onChange` definition. [#25358](https://github.com/ant-design/ant-design/pull/25358) [@CornerSkyless](https://github.com/CornerSkyless)
  - 🐞 Fix Tooltip custom color type definition. [#25315](https://github.com/ant-design/ant-design/pull/25315) [@CornerSkyless](https://github.com/CornerSkyless)

## 4.4.0

`2020-06-29`

- 🔥 Optimize RangePicker interaction that any picker selection will popup another picker panel. [#25135](https://github.com/ant-design/ant-design/pull/25135)
- 🔥 Add Skeleton.Image. [#24805](https://github.com/ant-design/ant-design/pull/24805) [@fireairforce](https://github.com/fireairforce)
- Form
  - 🆕 Form.Item support `preserve` to disable value preserve. [#25186](https://github.com/ant-design/ant-design/pull/25186)
  - 🆕 Form.Item add `hidden` prop. [#25108](https://github.com/ant-design/ant-design/pull/25108)
  - 🆕 Form instance support `getFieldInstance`. [#24711](https://github.com/ant-design/ant-design/pull/24711)
- Table
  - 🆕 Table `onChange` add `action` in extra argument. [#24697](https://github.com/ant-design/ant-design/pull/24697)
  - 🆕 Table support `rowSelection.dirty` to enable cache `key` with ajax. [#24718](https://github.com/ant-design/ant-design/pull/24718)
  - 🐞 Table supports `rowSelection.checkStrictly`. [#24931](https://github.com/ant-design/ant-design/pull/24931)
  - 🐞 Fix Table `onSelectAll`'s `changeRows` parameter is incorrect. [#24931](https://github.com/ant-design/ant-design/pull/24931)
  - 🐞 Fix Table expand buttons of leaf rows in tree data can still be clicked. [#24931](https://github.com/ant-design/ant-design/pull/24931)
  - 🐞 Fix Table expand icon still interative when hidden. [#25170](https://github.com/ant-design/ant-design/pull/25170)
- TimePicker
  - 🐞 Fix TimePicker display 12 AM as 0 AM. [#25174](https://github.com/ant-design/ant-design/pull/25174)
  - 🐞 Fix TimePicker not using 0 ~ 23 to disable hours. [#25174](https://github.com/ant-design/ant-design/pull/25174)
  - 🐞 Fix TimePicker AM | PM are not related with hour disabled status. [#25174](https://github.com/ant-design/ant-design/pull/25174)
  - 🐞 Fix TimePicker "Now" button's behavior doesn't conform hour, minute, second step. [#25174](https://github.com/ant-design/ant-design/pull/25174)
- Cascader
  - 🆕 Cascader add `expandIcon` to customize the current item expand icon. [#24865](https://github.com/ant-design/ant-design/pull/24865)
  - 🆕 Cascader support `dropdownRender` prop for customizing menu. [#24812](https://github.com/ant-design/ant-design/pull/24812)
- Menu
  - 🆕 Menu support `triggerSubMenuAction` (hover or click). [#25127](https://github.com/ant-design/ant-design/pull/25127) [@hydRAnger](https://github.com/hydRAnger)
  - 🐞 Fix Menu.SubMenu background color in dark theme. [#25205](https://github.com/ant-design/ant-design/pull/25205)
- Tabs
  - 🆕 Pagination support `onChange` called when `pageSize` change. [#24964](https://github.com/ant-design/ant-design/pull/24964) [@fireairforce](https://github.com/fireairforce)
  - 🆕 Tabs support `addIcon` to customize add icon node. [#25006](https://github.com/ant-design/ant-design/pull/25006)
  - 🐞 Fix Tabs can not close in IE11. [#25200](https://github.com/ant-design/ant-design/pull/25200)
- Pagination
  - 🐞 Improve Pagination accessibility by fixing a W3C error. [#25119](https://github.com/ant-design/ant-design/pull/25119)
- DatePicker
  - 🆕 Fix month and quarter picker's toggle button size of DatePicker component. [#25035](https://github.com/ant-design/ant-design/pull/25035) [@fireairforce](https://github.com/fireairforce)
  - 🆕 DatePicker support `showNow`. TimePicker support `showNow`. [#25032](https://github.com/ant-design/ant-design/pull/25032)
- Drawer
  - 🆕 Dropdown component support `arrow` prop. [#23869](https://github.com/ant-design/ant-design/pull/23869) [@wendellhu95](https://github.com/wendellhu95)
  - 🐞 Fix Drawer `getContainer={false}` cause scrollbar missing in some situation. [#25273](https://github.com/ant-design/ant-design/pull/25273)
- 🆕 Fix Rate render unexpectedly when `value` is `1.6` or `2.6`. [#24993](https://github.com/ant-design/ant-design/pull/24993)
- 🆕 Menution support `autoSize` prop. [#24961](https://github.com/ant-design/ant-design/pull/24961) [@Kermit-Xuan](https://github.com/Kermit-Xuan)
- 🆕 Remove the 140px width limit on vertical dot Steps.Step. [#24907](https://github.com/ant-design/ant-design/pull/24907)
- 🆕 Move Result children to end of component. [#24945](https://github.com/ant-design/ant-design/pull/24945)
- 🆕 Add Rate `character` support `(RateProps)=> ReactNode` customization. [#24903](https://github.com/ant-design/ant-design/pull/24903)
- 🆕 Add `optionType` api to set Radio type in Radio.Group when use `options`. [#24809](https://github.com/ant-design/ant-design/pull/24809)
- 🆕 Add `closeIcon` to customize Tag close icon. [#24885](https://github.com/ant-design/ant-design/pull/24885)
- 🆕 Drawer support `closeIcon`. [#24842](https://github.com/ant-design/ant-design/pull/#24842)
- 🆕 Add `ghost` prop for collapse to set a transparent background. [#24734](https://github.com/ant-design/ant-design/pull/24734)
- 🆕 Progress support customise filled Progress color. [#24655](https://github.com/ant-design/ant-design/pull/24655) [@fireairforce](https://github.com/fireairforce)
- 🆕 Typography copyable support `icon` and `tooltips` for customization. [#25274](https://github.com/ant-design/ant-design/pull/25274) [@israelKusayev](https://github.com/israelKusayev)
- 🆕 Add `showLeafIcon` for Tree Component when set `showLine` prop. [#25271](https://github.com/ant-design/ant-design/pull/25271)
- 🆕 Add BackTop `duration` used to set the time required to return to the top. [#25254](https://github.com/ant-design/ant-design/pull/25254)
- 🐞 Fix Select suffix icon can not focus input. [#25212](https://github.com/ant-design/ant-design/pull/25212)
- 🐞 Fix the issue that Notification modification `width` is not aligned with the edge of the screen. [#25168](https://github.com/ant-design/ant-design/pull/25168)
- 💄 Make Switch animation more smooth and quicker. [#25160](https://github.com/ant-design/ant-design/pull/25160)
- 🛠 Modal add more less parameters. [#24773](https://github.com/ant-design/ant-design/pull/24773) [@hicrystal](https://github.com/hicrystal)
- 🐞 Fix PageHeader tabs unexpected border style. [#25159](https://github.com/ant-design/ant-design/pull/25159)
- 🐞 Fix InputNumber `max` prop has no default value. [#25243](https://github.com/ant-design/ant-design/pull/25243)
- 🌐 Add missing translation keys to table locale in German, Italian and Czech. [#25233](https://github.com/ant-design/ant-design/pull/25233) [@karelsoupaEMZ](https://github.com/karelsoupaEMZ)
- 🇯🇵 Add ja_JP globalization for Form. [#25244](https://github.com/ant-design/ant-design/pull/25244) [@kentaro84207](https://github.com/kentaro84207)
- RTL
  - 🐞 Fix Table nested style in RTL. [#25156](https://github.com/ant-design/ant-design/pull/25156)
  - 🐞 Fix Table title style in RTL when use filter and sorter. [#25152](https://github.com/ant-design/ant-design/pull/25152)
  - 🐞 Fix InputNumber input inner in RTL. [#25146](https://github.com/ant-design/ant-design/pull/25146)

## 4.3.5

`2020-06-21`

- 🐞 Fix Input.Search as AutoComplete customize component crash issue. [#25049](https://github.com/ant-design/ant-design/pull/25049)
- 🛠 Rewrite Input.Password with hooks. [#25012](https://github.com/ant-design/ant-design/pull/25012) [@Rustin-Liu](https://github.com/Rustin-Liu)
- 🐞 Fix PageHeader tabs broken style since `4.3.0`. [#24991](https://github.com/ant-design/ant-design/pull/24991)
- 🐞 Fix Backtop still interactive when it is hidden. [#25132](https://github.com/ant-design/ant-design/pull/25132) [@jesse3mh9a](https://github.com/jesse3mh9a)
- 🐞 Fix Upload don't support Popover. [#25090](https://github.com/ant-design/ant-design/pull/25090)
- 🐞 Fix Tabs content exceeds container width issue. [#25072](https://github.com/ant-design/ant-design/pull/25072)
- 🐞 Fix DataPicker/TimePicker time dropdown alignment issue. [#25019](https://github.com/ant-design/ant-design/pull/25019)
- Table
  - 🐞 Fix Table nested border style. [#24995](https://github.com/ant-design/ant-design/pull/24995)
  - 💄 Improve Table empty filters menu UI. [#25073](https://github.com/ant-design/ant-design/pull/25073)
  - 💄 Reduce Table filter dropdown's `max-height`. [#25001](https://github.com/ant-design/ant-design/pull/25001)
- Descriptions
  - 🐞 Fix Descriptions selecting text behavior when double clicking item. [#24983](https://github.com/ant-design/ant-design/pull/24983) [@harupy](https://github.com/harupy)
  - 💄 Fix Descriptions label text not start aligned in Safari. [#25018](https://github.com/ant-design/ant-design/pull/25018)
- 💄 Fix List.Item.Meta content width may overflow sometimes. [#24992](https://github.com/ant-design/ant-design/pull/24992)
- 🐞 Fix dark mode Menu.SubMenu background color in compact theme. [#24997](https://github.com/ant-design/ant-design/pull/24997)
- ⚡️ Reduce 3KB Button css bundle size. [#24996](https://github.com/ant-design/ant-design/pull/24996)
- 🇹🇷 Improve Turkish locale. [#25100](https://github.com/ant-design/ant-design/pull/25100) [@smddzcy](https://github.com/smddzcy)
- TypeScript
  - Export Tree `DataNode`. [#25065](https://github.com/ant-design/ant-design/pull/25065) [@jinxin0112](https://github.com/jinxin0112)

## 4.3.4

`2020-06-14`

- Form
  - 🐞 Fix `validateTrigger` not works on Form. [#24979](https://github.com/ant-design/ant-design/pull/24979)
  - 🐞 Fix Form.Item still replace component `id` when `id` configured. [#24929](https://github.com/ant-design/ant-design/pull/24929)
  - 🐞 Fix Form.List error message display not correct when nested with `noStyle`. [#24867](https://github.com/ant-design/ant-design/pull/24867)
- Table
  - 🐞 Fix Table `shouldCellUpdate` missing `prevRecord` param. [#24963](https://github.com/ant-design/ant-design/pull/24963)
  - 🐞 Fix Table's filter dropdown's display value doesn't sync with controlled `filteredValue`. [#24952](https://github.com/ant-design/ant-design/pull/24952)
  - 🐞 Fix Table `onChange` get wrong state with multiple sorter operation. [#24852](https://github.com/ant-design/ant-design/pull/24852)
- 🐞 Fix Modal `confirm()` has no default icon. [#24956](https://github.com/ant-design/ant-design/pull/24956)
- 🐞 Fix List `grid` not working in React.Fragment or wrapped List.Item. [#24955](https://github.com/ant-design/ant-design/pull/24955)
- 🐞 Fix Avatar fallback to children when loading image with error. [#24944](https://github.com/ant-design/ant-design/pull/24944) [@sosohime](https://github.com/sosohime)
- 🐞 Fix Drawer doesn't omit prop `getTargetContainer`. [#24938](https://github.com/ant-design/ant-design/pull/24938)
- 🐞 Fix Tabs dropdown clip text when tab title too long. [#24928](https://github.com/ant-design/ant-design/pull/24928)
- 🐞 Fix Carousel under Tabs shaking when tab switch. [#24873](https://github.com/ant-design/ant-design/pull/24873)
- 🐞 Fix Transfer package size will increase if tree shaking is disabled. [#24847](https://github.com/ant-design/ant-design/pull/24847) [@DavidSichau](https://github.com/DavidSichau)
- 💄 Add `@rate-star-hover-scale` to control Rate scale when cursor hover. [#24917](https://github.com/ant-design/ant-design/pull/24917)
- 💄 Add `@divider-orientation-margin` less variable to control Divider's left margin when `orientation` is set. [#24877](https://github.com/ant-design/ant-design/pull/24877)
- 🌐 Localization
  - 🇫🇷 Improve fr_FR i18n. [#24962](https://github.com/ant-design/ant-design/pull/24962) [@sharkyze](https://github.com/sharkyze)
- TypeScript
  - 🛠 Export Select `OptionProps` interface. [#24870](https://github.com/ant-design/ant-design/pull/24870) [@nitinknolder](https://github.com/nitinknolder)
  - 🛠 Export Card `CardInterface` interface. [#24866](https://github.com/ant-design/ant-design/pull/24866) [@THPubs](https://github.com/THPubs)
  - 🛠 Remove `emptyText` from Table `TableProps`. [#24948](https://github.com/ant-design/ant-design/pull/24948) [@hehex9](https://github.com/hehex9)
  - 🛠 Add `patch` type on Upload `method` prop. [#24936](https://github.com/ant-design/ant-design/pull/24936) [@miclle](https://github.com/miclle)

## 4.3.3

`2020-06-07`

- 🐞 Fix Drawer cannot open. [#24802](https://github.com/ant-design/ant-design/pull/24802)
- 🐞 Fix Menu.SubMenu cannot scroll. [#24806](https://github.com/ant-design/ant-design/pull/24806)

## 4.3.2

`2020-06-06`

- 🐞 Fix Tag.CheckableTag don't support `onClick`. [#24743](https://github.com/ant-design/ant-design/pull/24743)
- 🐞 Fix Drawer support set `getPopupContainer` and `getPrefixCls` by ConfigProvider. [#24727](https://github.com/ant-design/ant-design/pull/24727)
- 🐞 Fix Button `loading.delay` repeat trigger when parent compoent re-render. [#24713](https://github.com/ant-design/ant-design/pull/24713)
- 🐞 Fix Dropdown menu link color when has `icon`. [#24707](https://github.com/ant-design/ant-design/pull/24707) [#24702](https://github.com/ant-design/ant-design/pull/24702)
- Select
  - 🐞 Fix Select virtual scroll display abnormally in compact mode. [#24706](https://github.com/ant-design/ant-design/pull/24706)
  - ⚡️ Optimize Select multiple mode performance. [#24785](https://github.com/ant-design/ant-design/pull/24785) [@Kermit-Xuan](https://github.com/Kermit-Xuan)
- 🐞 Fix Calendar trigger `onPanelChange` even when in the same panel. [#24695](https://github.com/ant-design/ant-design/pull/24695)
- 🐞 Fix Input component height issue in IE11. [#24673](https://github.com/ant-design/ant-design/pull/24673) [@xiaosongxiaosong](https://github.com/xiaosongxiaosong)
- 🐞 Fix Radio typescript error typo. [#24693](https://github.com/ant-design/ant-design/pull/24693) [@hengkx](https://github.com/hengkx)
- 🐞 Fix Statistic don't work with Tooltip. [#24782](https://github.com/ant-design/ant-design/pull/24782)
- 🐞 Fix TimePicker.RangePicker `bordered={false}` not working when has `className`. [#24781](https://github.com/ant-design/ant-design/pull/24781)
- 🐞 Fix List cannot trigger `onChange` in pagination. [#24514](https://github.com/ant-design/ant-design/pull/24514)
- 🌐 Localization
  - 🇮🇱 Add Hebrew localisations for Form. [#24716](https://github.com/ant-design/ant-design/pull/24716) [@israelKusayev](https://github.com/israelKusayev)
  - 🇰🇷 Add ko_KR localizations for Form. [#24783](https://github.com/ant-design/ant-design/pull/24783) [@Jaewoook](https://github.com/Jaewoook)
- 💄 Add less variable `@table-font-size`, `@table-font-size-md` and `@table-font-size-sm` to customize the size of Table text. [#24714](https://github.com/ant-design/ant-design/pull/24714) [@morenyang](https://github.com/morenyang)
- RTL
  - 💄 Optimize Tabs dropdown style in RTL. [#24715](https://github.com/ant-design/ant-design/pull/24715)
  - 💄 Add `Modal.method()` RTL supports only use hooks. [#24682](https://github.com/ant-design/ant-design/pull/24682)
  - 💄 Fix Badge offset in RTL. [#24724](https://github.com/ant-design/ant-design/pull/24724)

## 4.3.1

`2020-06-02`

- Tabs
  - 🐞 Fix Tabs `hideAdd` not working. [#24621](https://github.com/ant-design/ant-design/pull/24621)
  - 🐞 Fix Tabs dropdown has extra horizontal scrollbar in Firefox. [#24677](https://github.com/ant-design/ant-design/pull/24677)
  - 🐞 Fix Tabs inkbar border lost when use with `react-sticky`. [#24643](https://github.com/ant-design/ant-design/pull/24643)
  - 💄 Adjust Tabs `tabBarStyle` style display. [#24620](https://github.com/ant-design/ant-design/pull/24620)
- Button
  - 🐞 Fix Button quick set `loading` from `delay` to `false` will still change to the loading status. [#24678](https://github.com/ant-design/ant-design/pull/24678)
  - 🐞 Fix the inconsistent style of Text Button in `danger`. [#24622](https://github.com/ant-design/ant-design/pull/24622) [@morenyang](https://github.com/morenyang)
- 🐞 Fix Table no showing scrollbar inside Row. [#24661](https://github.com/ant-design/ant-design/pull/24661) [@zt123123](https://github.com/zt123123)
- 🐞 Fix Drawer get `dropdownMatchSelectWidth` as dom prop warning. [#24651](https://github.com/ant-design/ant-design/pull/24651)
- 🐞 Adjust Steps to support React.Fragment with `children`. [#24644](https://github.com/ant-design/ant-design/pull/24644)
- 🐞 Fix Upload delete icon cannot be navigate via keyboard. [#24615](https://github.com/ant-design/ant-design/pull/24615) [@morenyang](https://github.com/morenyang)
- 🐞 Fix multiple Select search input cursor missing issue. [#24631](https://github.com/ant-design/ant-design/pull/24631)
- 🐞 Fix Radio.Group using `options` get `Element type is invalid` error. [#24631](https://github.com/ant-design/ant-design/pull/24631)
- RTL
  - 💄 Adjust Notification default placement to `topLeft` in RTL. [#24632](https://github.com/ant-design/ant-design/pull/24632)
- TypeScript
  - 🛠 Export Tabs `TabPaneProps` definition. [#24648](https://github.com/ant-design/ant-design/pull/24648)

## 4.3.0

`2020-05-31`

- 🔥 Rewrite Tabs for better user experience, dom structure is changed. [#24552](https://github.com/ant-design/ant-design/pull/24552)
- 📖 Add components [overview page](https://ant.design/components/overview). [#24491](https://github.com/ant-design/ant-design/pull/24491) [@arvinxx](https://github.com/arvinxx)
- 🛠 Optimize dependencies to reduce overall package size. [#24584](https://github.com/ant-design/ant-design/pull/24584)
- Button
  - 🆕 New `type="text"` Button. [#22552](https://github.com/ant-design/ant-design/pull/22552)
  - 💄 Improve button background variable usage. [#24372](https://github.com/ant-design/ant-design/pull/24372) [@morenyang](https://github.com/morenyang)
- Upload
  - 🆕 `data` could return `Promise` now. [#24546](https://github.com/ant-design/ant-design/pull/24546) [@Kermit-Xuan](https://github.com/Kermit-Xuan)
  - 🆕 Support `progress` to customize progress bar. [#24319](https://github.com/ant-design/ant-design/pull/24319) [@morenyang](https://github.com/morenyang)
  - 🐞 Fix progress bar override by accident. [#24339](https://github.com/ant-design/ant-design/pull/24339) [@morenyang](https://github.com/morenyang)
- Table
  - 🆕 Table support `rowSelection.hideSelectAll` to hide selectAll checkbox. [#24592](https://github.com/ant-design/ant-design/pull/24592) [@Kermit-Xuan](https://github.com/Kermit-Xuan)
  - 🆕 `ellipsis` support `showTitle` to config `title` show. [#24056](https://github.com/ant-design/ant-design/pull/24056) [@lijinke666](https://github.com/lijinke666)
  - 🆕 Table `columns` support `shouldCellUpdate`. [#23872](https://github.com/ant-design/ant-design/pull/23872)
- Input
  - 🆕 Input.Passowrd support custom icon. [#23792](https://github.com/ant-design/ant-design/pull/23792)
  - 🐞 Fix Input.Password still show `value` attribute in DOM after blur it. [#24535](https://github.com/ant-design/ant-design/pull/24535)
  - 💄 Add less variable `@input-disabled-color`. [#23775](https://github.com/ant-design/ant-design/pull/23775) [@alwaysloseall](https://github.com/alwaysloseall)
- Form
  - 🐞 Fix Form.Item inline `label` collapsed when in narrow space. [#24531](https://github.com/ant-design/ant-design/pull/24531)
  - 🐞 Fix Form.List field status sync logic and add a nest fields demo. [#24009](https://github.com/ant-design/ant-design/pull/24009)
  - 🆕 Form support `validateTrigger` to config children fields validate trigger. [#23972](https://github.com/ant-design/ant-design/pull/23972)
- Menu
  - 🆕 Adjust text shows the first character when Menu is collapsed in `inline` mode. [#24330](https://github.com/ant-design/ant-design/pull/24330)
  - 🆕 Menu.Item support `danger` prop. [#23785](https://github.com/ant-design/ant-design/pull/23785)
- Avatar
  - 🆕 Avatar support `gap` to set the unit distance between left and right sides. [#24357](https://github.com/ant-design/ant-design/pull/24357)
  - 🐞 Fix Avatar `onError` trigger twice. [#24506](https://github.com/ant-design/ant-design/pull/24506) [@sanonz](https://github.com/sanonz)
- Typography
  - 🆕 Support Typography.Paragraph custom expand style. [#24385](https://github.com/ant-design/ant-design/pull/24385) [@fireairforce](https://github.com/fireairforce)
  - 🆕 Typography.Text support `keyboard` style. [#24195](https://github.com/ant-design/ant-design/pull/24195)
  - 🆕 Add Link component. [#24019](https://github.com/ant-design/ant-design/pull/24019)
  - 🐞 Fix Typography `title` prop support. [#24440](https://github.com/ant-design/ant-design/pull/24440) [@Kermit-Xuan](https://github.com/Kermit-Xuan)
- 🆕 Tooltip support `color` to config background color. [#23155](https://github.com/ant-design/ant-design/pull/23155)
- 🆕 Popconfirm can be closed by pressing `ESC` now. [#24420](https://github.com/ant-design/ant-design/pull/24420)
- 🆕 Tooltip `destroyTooltipOnHide` support `keepParent` config. [#24362](https://github.com/ant-design/ant-design/pull/24362) [@Kermit-Xuan](https://github.com/Kermit-Xuan)
- 🆕 Notification support to config `prefixCls`. [#24295](https://github.com/ant-design/ant-design/pull/24295) [@tdida](https://github.com/tdida)
- 🆕 RangePicker `dateRender` support additional argument to detect is `start` or `end` field. [#24278](https://github.com/ant-design/ant-design/pull/24278)
- 🆕 Skeleton add `round` prop to enable paragraph and title show radius. [#24137](https://github.com/ant-design/ant-design/pull/24137) [@xilihuasi](https://github.com/xilihuasi)
- 🆕 Transfer support `oneWay` and `pagination`. [#24041](https://github.com/ant-design/ant-design/pull/24041)
- 🆕 Message support customize `className` and `style`. [#24024](https://github.com/ant-design/ant-design/pull/24024) [@Kermit-Xuan](https://github.com/Kermit-Xuan)
- 🆕 ConfigProvider support `virtual` and `dropdownMatchSelectWidth`. [#23841](https://github.com/ant-design/ant-design/pull/23841) [@hengkx](https://github.com/hengkx)
- 🐞 Fix Breadcrumb icon margin missing when using links. [#24490](https://github.com/ant-design/ant-design/pull/24490) [@EscapeB](https://github.com/EscapeB)
- 🐞 Fix Cascader expand icon color when disabled. [#24521](https://github.com/ant-design/ant-design/pull/24521)
- 🐞 Fix List warning about `React does not recognize colStyle prop`. [#24568](https://github.com/ant-design/ant-design/pull/24568)
- 🐞 Fix Progress with `steps` don't update `percent` expectedly. [#24534](https://github.com/ant-design/ant-design/pull/24534) [@ChuckJonas](https://github.com/ChuckJonas)
- 🐞 Fix Steps `subtitle` transition style. [#24593](https://github.com/ant-design/ant-design/pull/24593)
- 🐞 Fix Alert close icon `padding` style. [#24471](https://github.com/ant-design/ant-design/pull/24471)
- 🐞 Fix Tree `@tree-directory-selected-bg` don't work. [#24468](https://github.com/ant-design/ant-design/pull/24468) [@morenyang](https://github.com/morenyang)
- 🐞 Fix `@ant-prefix` don't work on some styles. [#24459](https://github.com/ant-design/ant-design/pull/24459) [@morenyang](https://github.com/morenyang)
- 💄 Descriptions add less variables `@descriptions-item-trailing-colon` and etc. [#24032](https://github.com/ant-design/ant-design/pull/24032) [@hengkx](https://github.com/hengkx)
- 🌐 Localization
  - 🇮🇪 Add Irish(ga_IE) locale. [#24609](https://github.com/ant-design/ant-design/pull/24609) [@AbhijeetGaware](https://github.com/AbhijeetGaware)
  - 🇫🇮 Improve Typography `fi_FI` locale. [#24591](https://github.com/ant-design/ant-design/pull/24591) [@sagge](https://github.com/sagge)
  - 🇧🇷 Improve `pt_BR` locale. [#24518](https://github.com/ant-design/ant-design/pull/24518) [@arturpfb](https://github.com/arturpfb)
  - 🇬🇧 Improve Form `en_GB` locale. [#24404](https://github.com/ant-design/ant-design/pull/24404) [@morenyang](https://github.com/morenyang)
- RTL
  - 💄 Optimize Tree checkbox style in RTL. [#24563](https://github.com/ant-design/ant-design/pull/24563)
  - 💄 Optimize Calendar notice content text style in RTL. [#24528](https://github.com/ant-design/ant-design/pull/24528)
  - 💄 Optimize Table filter dropdown style in RTL. [#24529](https://github.com/ant-design/ant-design/pull/24529)
  - 💄 Fix Cascader dropdown style in RTL. [#24520](https://github.com/ant-design/ant-design/pull/24520)
- TypeScript
  - 🛠 Form export `RuleObject` and `RuleRender` types. [#24541](https://github.com/ant-design/ant-design/pull/24541) [@sorteam](https://github.com/sorteam)

## 4.2.5

`2020-05-25`

- 🐞 Fix Table selection arrow out of column when `size` is `small/middle`. [#24394](https://github.com/ant-design/ant-design/pull/24394)
- 🐞 Fix Input.TextArea clear icon disappears in Input.Group when hover it. [#24360](https://github.com/ant-design/ant-design/pull/24360) [@Mr-jiangzhiguo](https://github.com/Mr-jiangzhiguo)
- 🐞 Fixed an issue where the `RowSelection.onChange` will still be cached when the Table removes entries in `dataSource`. [#24338](https://github.com/ant-design/ant-design/pull/24338)
- 🐞 Adjust `useNotification` api instance to be same instance for each render. [#24337](https://github.com/ant-design/ant-design/pull/24337)
- 🐞 Fix Button `loading` transition animation missing and Modal `confirmLoading` not being reset. [#24328](https://github.com/ant-design/ant-design/pull/24328)
- 🐞 Fix Drawer cover background elements when it is not visible. [#24290](https://github.com/ant-design/ant-design/pull/24290)
- 🐞 Fix Cascader/Select/Table/TreeSelect text color when data empty. [#24279](https://github.com/ant-design/ant-design/pull/24279)
- 💄 Fix InputNumber operation button arrow is not centered. [#24266](https://github.com/ant-design/ant-design/pull/24266)
- 🐞 Fix Table with empty array `filteredValue` still highlight the filtered icon. [#24263](https://github.com/ant-design/ant-design/pull/24263)
- 🐞 Fix Cascader not support `number[]` value. [#24247](https://github.com/ant-design/ant-design/pull/24247)
- ⌨️ Fix Switch `autoFocus` trigger when `disabled` removed. Adjust style to avoid switch shaking. Remove blur logic when `onMouseUp` to improve acessibility. [#24254](https://github.com/ant-design/ant-design/pull/24254)
- 💄 Add Menu default `text-align` style. [#24253](https://github.com/ant-design/ant-design/pull/24253)
- 🛠 Refactor List code. [#24280](https://github.com/ant-design/ant-design/pull/24280) [@hengkx](https://github.com/hengkx)
- 🛠 Modify the Alert with hooks to support strict mode. [#24236](https://github.com/ant-design/ant-design/pull/24236) [@hengkx](https://github.com/hengkx)
- 🐞Fix Card perfermance bug when use with `react-split`. [#24425](https://github.com/ant-design/ant-design/pull/24425)
- TypeScript
  - 🛠Cascader ts definition update. [#24393](https://github.com/ant-design/ant-design/pull/24393) [@zhangyu1818](https://github.com/zhangyu1818)
  - 🐞 Fix TS error of `Could not find a declaration rc-upload`. [#24325](https://github.com/ant-design/ant-design/pull/24325)
  - 🛠 Add children type to BackTop. [#24235](https://github.com/ant-design/ant-design/pull/24235)

## 4.2.4

`2020-05-18`

- 🐞 Revert Switch patch to fix handle position style issue with `unCheckedChildren`. [#24242](https://github.com/ant-design/ant-design/pull/24242)
- 💄 Adjust Upload icon default color to red in error status. [#24160](https://github.com/ant-design/ant-design/pull/24160)
- 💄 Adjust Dropdown arrow position a little higher. [#24215](https://github.com/ant-design/ant-design/pull/24215)
- 🌐 Form `defaultValidateMessages` support `ru_RU`. [#24219](https://github.com/ant-design/ant-design/pull/24219) [@aivinog1](https://github.com/aivinog1)

## 4.2.3

`2020-05-16`

- 🐞 Refactor `rc-progress` to resolve `h3g is not defined` error in `<script src="antd.min.js" />`. [#24127](https://github.com/ant-design/ant-design/pull/24127)
- 📖 Rewrote [Use in create-react-app](https://ant.design/docs/react/use-with-create-react-app). [#24184](https://github.com/ant-design/ant-design/pull/24184)
- Drawer
  - 🐞 Fix Drawer `getContainer={false}` height overflow issue. [#24082](https://github.com/ant-design/ant-design/pull/24082)
  - 🐞 Fix Drawer `mask={false}` animation not working. [#24082](https://github.com/ant-design/ant-design/pull/24082)
- BackTop
  - 🛠 Refactor BackTop with hooks. [#23575](https://github.com/ant-design/ant-design/pull/23575)
  - 🐞 Fix BackTop not working in iframe of Chrome. [#24194](https://github.com/ant-design/ant-design/pull/24194)
- DatePicker
  - 🐞 Fix DatePicker with `showToday` not working with `disabledDate`. [#24190](https://github.com/ant-design/ant-design/pull/24190)
  - 🐞 Fix DatePicker `renderExtraFooter` with long content exceed content width. [#24145](https://github.com/ant-design/ant-design/pull/24145)
- Button
  - 🐞 Fix small Button align issue when customize theme. [#24097](https://github.com/ant-design/ant-design/pull/24097)
  - 🐞 Fix Button children not working with Tooltip. [#24095](https://github.com/ant-design/ant-design/pull/24095)
- 🛠 Refactor Tooltip with hooks. [#23699](https://github.com/ant-design/ant-design/pull/23699)
- 🐞 Avoid `disabled` Upload.Dragger being triggered by clicking Form `label`. [#24202](https://github.com/ant-design/ant-design/pull/24202)
- 🐞 Fix Select selected option not interactive (such as `title` not working). [#24170](https://github.com/ant-design/ant-design/pull/24170)
- 🐞 Fix Switch shake in Safari and iOS Chrome. [#24122](https://github.com/ant-design/ant-design/pull/24122) [@lexlexa](https://github.com/lexlexa)
- 🐞 Carousel upgrade to `react-slick@0.26.1` to resolve some problems. [#24067](https://github.com/ant-design/ant-design/pull/24067)
- 🐞 Cascader will display `defaultValue` instead of empty string when no matched options. [#24058](https://github.com/ant-design/ant-design/pull/24058) [@Kermit-Xuan](https://github.com/Kermit-Xuan)
- 🌎 Improve `zh_TW` localisations. [#24065](https://github.com/ant-design/ant-design/pull/24065) [@wx1322](https://github.com/wx1322)
- 🐞 Fix Table `onChange` pagination type. [#24114](https://github.com/ant-design/ant-design/pull/24114) [@sorteam](https://github.com/sorteam)
- 💄 Add less variable `@card-head-extra-color`. [#24189](https://github.com/ant-design/ant-design/pull/24189)
- 💄 Adjust Pagination simple mode background to transparent. [#24152](https://github.com/ant-design/ant-design/pull/24152)
- 💄 Fix dark Menu link color. [#24110](https://github.com/ant-design/ant-design/pull/24110)
- RTL
  - 💄 Fix Dropdown.Button default menu placement in RTL. [#24150](https://github.com/ant-design/ant-design/pull/24150)
  - 💄 Fix Menu `border` in RTL. [#24101](https://github.com/ant-design/ant-design/pull/24101)
  - 💄 Optimize Select multiple tag style in RTL. [#24112](https://github.com/ant-design/ant-design/pull/24112)
  - 💄 Optimize Typography `expand` style in RTL. [#24084](https://github.com/ant-design/ant-design/pull/24084)
  - 💄 Optimize Pagination slash style in RTL. [#24154](https://github.com/ant-design/ant-design/pull/24154)

## 4.2.2

`2020-05-11`

- 🐞 Fix `npm run version` install error. [#24059](https://github.com/ant-design/ant-design/pull/24059)
- 🐞 Fix Menu `@menu-item-font-size` not working. [#24052](https://github.com/ant-design/ant-design/pull/24052)
- 💄 Add `@modal-close-color` less variable. [#24053](https://github.com/ant-design/ant-design/pull/24053)

## 4.2.1

`2020-05-11`

- Form
  - 🐞 Fix Form.Item get React warning for `getValueProps`. [#23875](https://github.com/ant-design/ant-design/pull/23875)
  - 🐞 Fix Form.Item `help` style issue when `validateStatus` is not `error`. [#23945](https://github.com/ant-design/ant-design/pull/23945)
- Table
  - 🐞 Fix selection column width issue when fix header. [#23806](https://github.com/ant-design/ant-design/pull/23806)
  - 💄 Adjust selection column css selector priority to enable customize width. [#23914](https://github.com/ant-design/ant-design/pull/23914)
- DatePicker
  - 🐞 Fix miss placeholder when `placeholder` is `undefined`. [#23818](https://github.com/ant-design/ant-design/pull/23818)
  - 🐞 Fix clear icon color style. [#23811](https://github.com/ant-design/ant-design/pull/23811)
- Switch
  - 🐞 Fix loading style for the dark theme. [#23766](https://github.com/ant-design/ant-design/pull/23766) [@vsn4ik](https://github.com/vsn4ik)
  - 🐞 Fix `unCheckedChildren` not showing. [#23791](https://github.com/ant-design/ant-design/pull/23791)
- 🐞 Fix Upload error message location to scroll in the float layer. [#24001](https://github.com/ant-design/ant-design/pull/24001) [@mraiguo](https://github.com/mraiguo)
- 💄 Tweak Comment render unnecessary div style when `avatar` is empty. [#23994](https://github.com/ant-design/ant-design/pull/23994) [@Xuhao](https://github.com/Xuhao)
- 🐞 Fix Select `focus` border style in Input.Group. [#23985](https://github.com/ant-design/ant-design/pull/23985)
- 🐞 Fix Steps `subTitle` showing `[object Object]` title. [#23989](https://github.com/ant-design/ant-design/pull/23989)
- 💄 Tweak Select close icon position. [#23963](https://github.com/ant-design/ant-design/pull/23963)
- 🐞 Fix Drawer `width="50%"` hidden problem when no mask. [#23925](https://github.com/ant-design/ant-design/pull/23925)
- 🐞 Fix Textarea with `allowClear` has error height style. [#23835](https://github.com/ant-design/ant-design/pull/23835)
- 💄 Adjust Modal.xxx function async to avoid block React events. [#23826](https://github.com/ant-design/ant-design/pull/23826)
- 🐞 Fix Menu with controlled `openKeys` abnormal behavior when `inlineCollapsed` changed. [#23822](https://github.com/ant-design/ant-design/pull/23822)
- 🐞 Fix Button `loading` animation. [#23783](https://github.com/ant-design/ant-design/pull/23783)
- 🐞 Fix Slider `marks` selected problem when dragging. [#23773](https://github.com/ant-design/ant-design/pull/23773)
- 🛠 Timeline refactors with React Hooks. [#23631](https://github.com/ant-design/ant-design/pull/23631) [@hengkx](https://github.com/hengkx)
- 🌎 Localization
  - 🇮🇷 Add Farsi `fa_IR` default locale template localisations. [#23926](https://github.com/ant-design/ant-design/pull/23926) [@NarimanMov](https://github.com/NarimanMov)
  - 🇺🇸 Add default `en` default locale template localisations for Form. [#23859](https://github.com/ant-design/ant-design/pull/23859) [@mjfwebb](https://github.com/mjfwebb)
- 📦 Reduce bundle size
  - 🗑 Reduce bundle size via removing `react-lifecycles-compat`. [#23969](https://github.com/ant-design/ant-design/pull/23969)
  - 🛠 Reduce bundle size via excluding `package.json` from source code. [#23957](https://github.com/ant-design/ant-design/pull/23957)
  - 🛠 Upgrade `rc-animate` to 3.x to reduce bundle size. [#23937](https://github.com/ant-design/ant-design/pull/23937)
- RTL
  - 🐞 Fix Input clear icon style in RTL. [#23999](https://github.com/ant-design/ant-design/pull/23999)
  - 🐞 Fix DatePicker panel style in RTL. [#24028](https://github.com/ant-design/ant-design/pull/24028) [@xrkffgg](https://github.com/xrkffgg)
  - 💄 Optimize DatePicker active bar style in `RTL`. [#23981](https://github.com/ant-design/ant-design/pull/23981)
  - 🐞 Fix Transfer search padding style in `RTL`. [#23962](https://github.com/ant-design/ant-design/pull/23962)
  - 💄 Optimize Layout style of RTL. [#23921](https://github.com/ant-design/ant-design/pull/23921)
  - 💄 Optimize Button `loading` style in RT. [#23776](https://github.com/ant-design/ant-design/pull/23776)
  - 💄 Optimize Input.Search style in RTL. [#23797](https://github.com/ant-design/ant-design/pull/23797)
- TypeScript
  - 🐞 Fix InputNumber `onChange` type. [#23871](https://github.com/ant-design/ant-design/pull/23871) [@jjhbw](https://github.com/jjhbw)

## 4.2.0

`2020-04-29`

- 🆕 List `grid` support all column count like 5. [#23630](https://github.com/ant-design/ant-design/pull/23630)
- 🆕 Divider add `plain` prop which allows a non-heading style divider text. [#23405](https://github.com/ant-design/ant-design/pull/23405)
- 🆕 Typography `ellipsis` support `onEllipsis` event handler. [#23414](https://github.com/ant-design/ant-design/pull/23414)
- 🆕 Space support `align` prop. [#23306](https://github.com/ant-design/ant-design/pull/23306)
- 🆕 Upload support `isImageUrl` to force trade file as image. [#23248](https://github.com/ant-design/ant-design/pull/23248) [@onjuju](https://github.com/onjuju)
- 🆕 Form.Item support `initialValue` and `getValueProps` props. [#22993](https://github.com/ant-design/ant-design/pull/22993)
- ConfigProvider
  - 🆕 ConfigProvider support `getTargetContainer` to config Affix `target` props. [#23751](https://github.com/ant-design/ant-design/pull/23751)
  - 🆕 ConfigProvider support `input` prop to config Input `autoComplete`. [#23455](https://github.com/ant-design/ant-design/pull/23455)
  - 🐞 Fix ConfigProvider `getPopupContainer` not working on DatePicker and Slider. [#23594](https://github.com/ant-design/ant-design/pull/23594) [@hengkx](https://github.com/hengkx)
- Table
  - 🆕 Table `summary` support fixed columns. [#23647](https://github.com/ant-design/ant-design/pull/23647)
  - 🆕 Table support responsive columns. [#23298](https://github.com/ant-design/ant-design/pull/23298) [@vbudovski](https://github.com/vbudovski)
  - 🐞 Fix Table pagination default position in RTL. [#23747](https://github.com/ant-design/ant-design/pull/23747)
  - 🐞 Fix Table crash when `pageSize` is `undefined`. [#23724](https://github.com/ant-design/ant-design/pull/23724)
  - 🐞 fix Table nested margin when size is `small` or `middle`. [#23602](https://github.com/ant-design/ant-design/pull/23602) [@hengkx](https://github.com/hengkx)
- 🐞 Fix RangePicker `ranges` tag color to primary color. [#23705](https://github.com/ant-design/ant-design/pull/23705)
- 🐞 Fix Transfer with custom empty style issue. [#23694](https://github.com/ant-design/ant-design/pull/23694) [@hengkx](https://github.com/hengkx)
- Input
  - 🐞 Fix Password caret position. [#23633](https://github.com/ant-design/ant-design/pull/23633) [@huntdream](https://github.com/huntdream)
  - 💄 Adjust Input.Search icon style. [#23406](https://github.com/ant-design/ant-design/pull/23406)
- Button
  - 🐞 Fix Button align problem of icon only. [#23671](https://github.com/ant-design/ant-design/pull/23671)
  - 🐞 Fix Button of icon only wrong `loading` style. [#23614](https://github.com/ant-design/ant-design/pull/23614)
  - 🐞 fix Button cannot be directly called by `react-dnd`. [#23571](https://github.com/ant-design/ant-design/pull/23571) [@hengkx](https://github.com/hengkx)
- Menu
  - 🆕 Menu Item and SubMenu support `icon` prop. [#23629](https://github.com/ant-design/ant-design/pull/23629)
  - 🐞 Fix Menu duplicated shadow style. [#23664](https://github.com/ant-design/ant-design/pull/23664)
- 🐞 Fix Tag cannot be directly called by `react-dnd`. [#23632](https://github.com/ant-design/ant-design/pull/23632) [@hengkx](https://github.com/hengkx)
- Anchor
  - 🐞 Fix Anchor Link with multiple `#` can not jump correctly. [#23595](https://github.com/ant-design/ant-design/pull/23595) [@wuzekang](https://github.com/wuzekang)
  - 🐞 Fix Input with `suffix` align problem. [#23606](https://github.com/ant-design/ant-design/pull/23606)
- 💄 Select arrow won't rotate when open. [#23468](https://github.com/ant-design/ant-design/pull/23468)
- 💄 Rate support `direction`. [#23321](https://github.com/ant-design/ant-design/pull/23321)
- 💄 Adjust font-size in compact mode. [#23135](https://github.com/ant-design/ant-design/pull/23135)
- RTL
  - 💄 Optimize Result button style in RTL. [#23733](https://github.com/ant-design/ant-design/pull/23733)
  - 💄 Add Divider RTL support. [#23734](https://github.com/ant-design/ant-design/pull/23734)
  - 💄 Fix Alert style in RTL when no-icon. [#23714](https://github.com/ant-design/ant-design/pull/23714)
  - 💄 Optimize Table expand animation and pagination style in RTL. [#23706](https://github.com/ant-design/ant-design/pull/23706)
  - 💄 Fix Table filter dropdown position in RTL. [#23695](https://github.com/ant-design/ant-design/pull/23695)
  - 💄 Fix Table rowSelect icon style in RTL. [#23690](https://github.com/ant-design/ant-design/pull/23690)
  - 💄 Optimize List style in RTL. [#23676](https://github.com/ant-design/ant-design/pull/23676)
  - 💄 Add Calendar RTL. [#23394](https://github.com/ant-design/ant-design/pull/23394)
  - 💄 Optimize Input.Search style in RTL. [#23424](https://github.com/ant-design/ant-design/pull/23424)
  - 💄 Add Notification RTL config. [#23185](https://github.com/ant-design/ant-design/pull/23185)
- TypeScript
  - 🐞 Fix PageHeader `tag` definition. [#23712](https://github.com/ant-design/ant-design/pull/23712) [@hengkx](https://github.com/hengkx)
  - 🗑 Remove Button deprecated `type="danger"` TypeScript definition and warn it. [#23709](https://github.com/ant-design/ant-design/pull/23709)
  - 🐞 Fix Table pagination `position` definition. [#23681](https://github.com/ant-design/ant-design/pull/23681) [@hengkx](https://github.com/hengkx)

## 4.1.5

`2020-04-25`

- 🐞 Fix Button.Group align style. [#23590](https://github.com/ant-design/ant-design/pull/23590)
- 🐞 Fix Select cannot trigger open by clicking arrow icon. [#23448](https://github.com/ant-design/ant-design/pull/23448)
- 🐞 Fix Form fields shake when `@form-item-margin-bottom` is customize and switching the validing info. [#23436](https://github.com/ant-design/ant-design/pull/23436) [@yoyo837](https://github.com/yoyo837)
- 🐞 Fix the first Divider render differently with others. [#23438](https://github.com/ant-design/ant-design/pull/23438)
- 🐞 Fix nest ConfigProvider missing `prefixCls` value. [#23423](https://github.com/ant-design/ant-design/pull/23423)
- 🐞 Fix Carousel tabbed Radio/Checkbox to non-active slide. [#23380](https://github.com/ant-design/ant-design/pull/23380)
- 🐞 Fix Tree with virtual scroll frozen by quick `loadData`. [#23581](https://github.com/ant-design/ant-design/pull/23581)
- 🐞 Fix Steps style in IE11 when direction is vertical. [#23561](https://github.com/ant-design/ant-design/pull/23561) [@AdrianoRuberto](https://github.com/AdrianoRuberto)
- 🐞 Fix Input.Search height affected by `suffix` and `react key` warning. [#23527](https://github.com/ant-design/ant-design/pull/23527)
- 🐞 Fix Menu behavior when hover on submenu gap. [#23511](https://github.com/ant-design/ant-design/pull/23511)
- 🐞 Fix Tree custom icon missing when node is loading data. [#23494](https://github.com/ant-design/ant-design/pull/23494)
- RTL
  - 🐞 Fix Alert RTL style when set both `showIcon` and `closable`. [#23526](https://github.com/ant-design/ant-design/pull/23526)
  - 🐞 Fix Button RTL style when loading. [#23399](https://github.com/ant-design/ant-design/pull/23399)
  - 🐞 Fix Collapse that icon position is incorrect in RTL. [#23445](https://github.com/ant-design/ant-design/pull/23445)
  - 🐞 Fix Select group label style in RTL. [#23404](https://github.com/ant-design/ant-design/pull/23404)
  - 🐞 Fix Statistic RTL style. [#23397](https://github.com/ant-design/ant-design/pull/23397)
- TypeScript
  - 🐞 Fix type definition of `selections` for Table. [#23462](https://github.com/ant-design/ant-design/pull/23462) [@xiaoxintang](https://github.com/xiaoxintang)

## 4.1.4

`2020-04-18`

- 🐞 Fix dark theme and compact theme not working. [#23243](https://github.com/ant-design/ant-design/pull/23243)
- 🐞 Fix Modal.info executed only once when has argument. [#23360](https://github.com/ant-design/ant-design/pull/23360)
- 🐞 Fix Dropdown submenu background missing. [#23296](https://github.com/ant-design/ant-design/pull/23296)
- 💄 Optimize PageHeader responsive behavior. [#23277](https://github.com/ant-design/ant-design/pull/23277)
- 🐞 Fix TreeSelect render blank in compact mode. [#23231](https://github.com/ant-design/ant-design/pull/23231)
- 🛎 Fix Checkbox and Switch console warning typo (validate -> a valid). [#23240](https://github.com/ant-design/ant-design/pull/23240) [@evancharlton](https://github.com/evancharlton)
- 🐞 Fix Table `rowSelection` params issue when `childrenColumnName` configured. [#23205](https://github.com/ant-design/ant-design/pull/23205)
- Input
  - 🐞 Fix Input `type="color"` height issue. [#23351](https://github.com/ant-design/ant-design/pull/23351)
  - 🐞 Fix Input width shaking when trigger clear icon. [#23259](https://github.com/ant-design/ant-design/pull/23259)
  - 🐞 Fix Input.Search `size` not affected by ConfigProvider `componentSize`. [#23331](https://github.com/ant-design/ant-design/pull/23331)
- Select
  - 🐞 Fix multiple Select show remove icon when `disabled`. [#23295](https://github.com/ant-design/ant-design/pull/23295)
  - 🐞 Fix Select custom `suffixIcon` cannot be access. [#23274](https://github.com/ant-design/ant-design/pull/23274)
  - 🐞 Fix Select search input caret missing in Collapse. [#23250](https://github.com/ant-design/ant-design/pull/23250)
- Globalization
  - 🇨🇳 Form validation messages support internalization and add zh_CN locale. [#23165](https://github.com/ant-design/ant-design/pull/23165) [@hengkx](https://github.com/hengkx)
  - 🌐 Add missing translations in he_IL. [#23302](https://github.com/ant-design/ant-design/pull/23302) [@MishaKav](https://github.com/MishaKav)
  - 🌐 Add missing translations in ru_RU. [#23303](https://github.com/ant-design/ant-design/pull/23303) [@MishaKav](https://github.com/MishaKav)
- TypeScript
  - 🔷 Form.Item type upgrade. [#22962](https://github.com/ant-design/ant-design/pull/22962) [@fa93hws](https://github.com/fa93hws)
  - 🔷 Tree type upgrade. [#23348](https://github.com/ant-design/ant-design/pull/23348) [@yoyo837](https://github.com/yoyo837)
  - 🐞 Pass `popupClassName` prop to `rc-picker`. [#23214](https://github.com/ant-design/ant-design/pull/23214) [@tanmoyopenroot](https://github.com/tanmoyopenroot)
- RTL
  - 💄 Fix Select RTL style. [#23235](https://github.com/ant-design/ant-design/pull/23235)
  - 💄 Fix Menu RTL style. [#23319](https://github.com/ant-design/ant-design/pull/23319)

## 4.1.3

`2020-04-13`

- 💄 Adjust Form.Item `label` height style in vertical layout. [#23192](https://github.com/ant-design/ant-design/pull/23192)
- 🐞 Fix `Variable is undefined` when importing dark or compact theme and provide a `getThemeVariables` methold for getting theme variables easily. [#23171](https://github.com/ant-design/ant-design/pull/23171)
- 🐞 Fix PageHeader style breaks when `title` is too long and improve it's responsive design. [#23133](https://github.com/ant-design/ant-design/pull/23133)
- Tabs
  - 🐞 Fix Tabs `@tabs-card-height` less variable not working. [#23168](https://github.com/ant-design/ant-design/pull/23168)
  - 🐞 Fix Tabs cannot be displayed in Safari 13. [#23151](https://github.com/ant-design/ant-design/pull/23151) [@imhxc](https://github.com/imhxc)
- Table
  - 🐞 Fix Table fixed columns cannot pin in Safari 12. [#23161](https://github.com/ant-design/ant-design/pull/23161)
  - 🐞 Fix Table `summary` padding in small size. [#23140](https://github.com/ant-design/ant-design/pull/23140) [@someyoungideas](https://github.com/someyoungideas)
- 🐞 Fix Select align style with different size. [#23160](https://github.com/ant-design/ant-design/pull/23160)
- 🐞 Fix RangePicker under Input.Group style issue. [#23149](https://github.com/ant-design/ant-design/pull/23149)
- 🐞 Fix Pagination missing TypeScript definition of `showTitle`. [#23144](https://github.com/ant-design/ant-design/pull/23144) [@DongchengWang](https://github.com/DongchengWang)

## 4.1.2

`2020-04-10`

- Menu
  - 🐞 Fix Menu SubMenu background in dark mode. [#22981](https://github.com/ant-design/ant-design/pull/22981) [@AshoneA](https://github.com/AshoneA)
  - 🐞 Fix long SubMenu title being overlayed by arrow icon. [#23028](https://github.com/ant-design/ant-design/pull/23028) [@wwyx778](https://github.com/wwyx778)
- 🐞 Fix dark and compact theme cannot work together. [#22934](https://github.com/ant-design/ant-design/pull/22934) [@AshoneA](https://github.com/AshoneA)
- 🐞 Fix Notification invalid `paddig-top` value. [#22941](https://github.com/ant-design/ant-design/pull/22941)
- Button
  - 🐞 Fix Button `loading` animation with icon. [#23102](https://github.com/ant-design/ant-design/pull/23102)
  - ⚠️ Improve Button invalid `type` warning. [#22933](https://github.com/ant-design/ant-design/pull/22933) [@fa93hws](https://github.com/fa93hws)
- 🐞 Fix Statistic show `-0` when value is `-`. [@22950](https://github.com/ant-design/ant-design/pull/22950)
- 🐞 Fix Modal.confirm `onOk` should not be triggered multiple times. [#22963](https://github.com/ant-design/ant-design/pull/22963)
- Input
  - 🐞 Fix Input.Group Button style not aligned center. [#22975](https://github.com/ant-design/ant-design/pull/22975)
  - 🐞 Fix Input with `affix` background style in dark theme. [#23115](https://github.com/ant-design/ant-design/pull/23115)
- 🐞 Fix Form.Item not correct reset error style when dynamic switch Form.Item. [#23041](https://github.com/ant-design/ant-design/pull/23041)
- 💄 Adjust RangePicker arrow & suffix color style. [#23025](https://github.com/ant-design/ant-design/pull/23025)
- Table
  - 🐞 Fix Table selection row with hover background style. [#23110](https://github.com/ant-design/ant-design/pull/23110)
  - 💄 Tweak Table hover background color. [#23113](https://github.com/ant-design/ant-design/pull/23113)
  - ⚠️ Table add warning info when async mode `dataSource` length not match with `pageSize`. [#23118](https://github.com/ant-design/ant-design/pull/23118)
- Select
  - 💄 Match mulitiple Select cursor position to single Select. [#22978](https://github.com/ant-design/ant-design/pull/22978)
  - 🐞 Fix borderless Select still show border when Form.Item set `validateStatus`. [#23004](https://github.com/ant-design/ant-design/pull/23004)
  - 🐞 Fix Select style in IE11. [#23020](https://github.com/ant-design/ant-design/pull/23020)
- 🐞 Fix Calendar missing `style` prop support. [#23081](https://github.com/ant-design/ant-design/pull/23081)
- 🐞 Fix Tabs bottom card active tab wrong height style. [#23087](https://github.com/ant-design/ant-design/pull/23087)
- 🐞 Fix RTL support of Anchor, Select, DatePicker, Grid, Mentions. [@xrkffgg](https://github.com/xrkffgg)
- TypeScript
  - 🌟 Upload `UploadProps` support generic typing. [#22921](https://github.com/ant-design/ant-design/pull/22921) [@dpyzo0o](https://github.com/dpyzo0o)
  - 🐞 Fix Modal.confirm `okButtonProps` types. [#21165](https://github.com/ant-design/ant-design/pull/21165) [@nicu-chiciuc](https://github.com/nicu-chiciuc)
  - 🌟 Export Form `Store` interface. [#22755](https://github.com/ant-design/ant-design/pull/22755) [@shaodahong](https://github.com/shaodahong)
  - 🌟 Improve enum types for Input, Tag, Badge. [#23026](https://github.com/ant-design/ant-design/pull/23026) [#22999](https://github.com/ant-design/ant-design/pull/22999) [#23006](https://github.com/ant-design/ant-design/pull/23006) [@fjc0k](https://github.com/fjc0k)
  - 🐞 Fix Pagination `position` type. [#23048](https://github.com/ant-design/ant-design/pull/23048) [@Arttse](https://github.com/Arttse)

## 4.1.1

`2020-04-05`

- 🐞 Fix Tabs panel focus outline style. [#22752](https://github.com/ant-design/ant-design/pull/22752) [@MrHeer](https://github.com/MrHeer)
- 🐞 Fix Input affix with popup element can not get click focus. [#22887](https://github.com/ant-design/ant-design/pull/22887)
- Table
  - 🆕 Table row selection dropdown support `getPopupContainer`. [#22787](https://github.com/ant-design/ant-design/pull/22787) [@mikeyshing88](https://github.com/mikeyshing88)
  - 🐞 Fix Table header size with filter or sorter when `size` is configured. [#22872](https://github.com/ant-design/ant-design/pull/22872)
  - 💄 Adjust nest Table style, compact only when just one table element. [#22868](https://github.com/ant-design/ant-design/pull/22868)
  - 🐞 Fix Table column `align` not working on head when `sorter` configured. [#22858](https://github.com/ant-design/ant-design/pull/22858)
  - 🐞 Fix Table filter config not work on jsx structure. [#22888](https://github.com/ant-design/ant-design/pull/22888)
  - 🐞 Adjust Table expanded row not fix width when scroll only. [#22832](https://github.com/ant-design/ant-design/pull/22832)
  - 🐞 Fix the column can't show when the `column.children` is `undefined`. [#22832](https://github.com/ant-design/ant-design/pull/22832)
  - 🐞 Fix Table still show filter icon when `filters` is `undefined`. [#22833](https://github.com/ant-design/ant-design/pull/22833)
  - 🐞 Fix Table unchanged `filters` should not trigger `onChange`. [#22829](https://github.com/ant-design/ant-design/pull/22829)
  - 🐞 Fix Table loading compatibility. [#22739](https://github.com/ant-design/ant-design/pull/22739)
  - 🐞 Fix Table scroll shadow style in Safari. [#22794](https://github.com/ant-design/ant-design/pull/22794)
- 💄 Adjust RangePicker arrow style. [#22847](https://github.com/ant-design/ant-design/pull/22847)
- 🐞 Fix Text with `ellipsis` align issue. [#22836](https://github.com/ant-design/ant-design/pull/22836)
- 💄 Tweak `@info-color` should be `@primary-color` defaultly. [#22723](https://github.com/ant-design/ant-design/pull/22723)
- 🐞 Fix BackTop not working in iframe and improve it's perfermance. [#22788](https://github.com/ant-design/ant-design/pull/22788)
- 🐞 Fix Select inconsistent height when `mode="multiple"` and `size="large" />`. [#22904](https://github.com/ant-design/ant-design/pull/22904)
- 🐞 Fix Radio less variable. [#22803](https://github.com/ant-design/ant-design/pull/22803) [@yoyo837](https://github.com/yoyo837)
- 🐞 Fix Card Tabs do not support small size. [#22666](https://github.com/ant-design/ant-design/pull/22666) [@MrHeer](https://github.com/MrHeer)
- 🐞 Fix Affix throws `React warning of state update on unmounted component`. [#22790](https://github.com/ant-design/ant-design/pull/22790)
- 🐞 Fix Textarea with `clearIcon` additional `margin` in Form.Item. [#22793](https://github.com/ant-design/ant-design/pull/22793)
- 🐞 Fix List `footer` missing border when data is empty. [#22771](https://github.com/ant-design/ant-design/pull/22771)
- 🐞 Fix Slider `tooltipPlacement` option API is changed to be correct again. [#22772](https://github.com/ant-design/ant-design/pull/22772) [@phoenixeliot](https://github.com/phoenixeliot)
- 🛠 Refactor LocaleReceiver with new context api to avoid React strict mode warning. [#22762](https://github.com/ant-design/ant-design/pull/22762)
- 🐞 Fix Radio and Checkbox required prop not passing to input. [#22761](https://github.com/ant-design/ant-design/pull/22761)
- 🐞 Fix variable `--scroll-bar` is undefined. [#22754](https://github.com/ant-design/ant-design/pull/22754) [@mikeyshing88](https://github.com/mikeyshing88)
- 🐞 Fix Menu and Spin style in compact mode. [#22908](https://github.com/ant-design/ant-design/pull/22908) [@AshoneA](https://github.com/AshoneA)
- 🐞 Fix Space item duplicate key. [#22745](https://github.com/ant-design/ant-design/pull/22745)
- 🐞 Fix Select cursor style. [#22743](https://github.com/ant-design/ant-design/pull/22743)
- 🇫🇷 DatePicker and TimePicker update French locale. [#22769](https://github.com/ant-design/ant-design/pull/22769) [@PaulJln](https://github.com/PaulJln)
- RTL
  - 💄 Add Message RTL style. [#22513](https://github.com/ant-design/ant-design/pull/22513) [@xrkffgg](https://github.com/xrkffgg)
  - 🐞 Fix Menu RTL style. [#22841](https://github.com/ant-design/ant-design/pull/22841)
  - 🐞 Fix Radio RTL style. [#22926](https://github.com/ant-design/ant-design/pull/22926) [@AshoneA](https://github.com/AshoneA)
  - 🐞 Fix label display in Form RTL. [#22621](https://github.com/ant-design/ant-design/pull/22621) [@xrkffgg](https://github.com/xrkffgg)
  - 🐞 Fix Space RTL style. [#22809](https://github.com/ant-design/ant-design/pull/22809) [@xrkffgg](https://github.com/xrkffgg)
- TypeScript
  - 🐞 Fix Table `FilterDropdownProps` TypeScript definition. [#22895](https://github.com/ant-design/ant-design/pull/22895) [@zhangyu1818](https://github.com/zhangyu1818)
  - 🐞 Fix Form `Store` and `StoreValue` TypeScript definition. [#22755](https://github.com/ant-design/ant-design/pull/22755) [@shaodahong](https://github.com/shaodahong)

## 4.1.0

`2020-03-29`

- 🔥 Support compact mode theme. [#22126](https://github.com/ant-design/ant-design/pull/22126) [@AshoneA](https://github.com/AshoneA)
- 🔥 New Space component to resolve inline component margin style. [#22363](https://github.com/ant-design/ant-design/pull/22363)
- 🔥 DatePicker support quarter picker. [#22468](https://github.com/ant-design/ant-design/pull/22468)
- 🆕 Tree/TreeSelect/Select support `virtual` prop to disable virtual scroll. [#21955](https://github.com/ant-design/ant-design/pull/21955)
- 🆕 Improve Pagination switch experience. [#22711](https://github.com/ant-design/ant-design/pull/22711)
  - Pagination will show size changer when `total > 50`.
  - Unify Pagination items to fixed length.
  - Change default size options to `10, 20, 50, 100`.
- Table
  - 🆕 Table pagination `position` add more option. [#22647](https://github.com/ant-design/ant-design/pull/22647) [@hengkx](https://github.com/hengkx)
  - 🆕 Table selection column support `renderCell`. [#21711](https://github.com/ant-design/ant-design/pull/21711)
  - 🆕 Table sorter adding hint tooltip and a new prop `showSorterTooltip`. [#21631](https://github.com/ant-design/ant-design/pull/21631) [@AshoneA](https://github.com/AshoneA)
- 🆕 Tag component support `icon` prop. [#22418](https://github.com/ant-design/ant-design/pull/22418) [@vtsybulin](https://github.com/vtsybulin)
- 🆕 Grid add `useBreakpoint` hook. [#22226](https://github.com/ant-design/ant-design/pull/22226)
- 🆕 Card support `tabProps`. [#22207](https://github.com/ant-design/ant-design/pull/22207)
- 🆕 Pagination add `autoResize` prop. [#21959](https://github.com/ant-design/ant-design/pull/21959) [@wendellhu95](https://github.com/wendellhu95)
- 🆕 Add render props support for Popover/Popconfirm. [#22034](https://github.com/ant-design/ant-design/pull/22034) [@nossbigg](https://github.com/nossbigg)
- 🆕 TimePicker.RangePicker support `order` prop. [#21948](https://github.com/ant-design/ant-design/pull/21948)
- 🆕 Carousel `dots` support object to pass `className`. [#21848](https://github.com/ant-design/ant-design/pull/21848)
- 🆕 Form `validateMessages` support `${label}` variable. [#21835](https://github.com/ant-design/ant-design/pull/21835)
- 🆕 Expose all Dropdown props in Breadcrumb.Item. [#20763](https://github.com/ant-design/ant-design/pull/20763) [@paranoidjk](https://github.com/paranoidjk)
- ⌨️ Improve Tabs Accessibility. [#22287](https://github.com/ant-design/ant-design/pull/22287)
  - Add Tabs `keyboard` prop.
  - Tabs `extraContent` don't trigger keyboard navigation now.
- 🛠 Warning Form.Item with `defaultValue` when it's controlled. [#22571](https://github.com/ant-design/ant-design/pull/22571)
- 🛠 Menu.Item Tooltip could be hidden by falsy `title` prop. [#22202](https://github.com/ant-design/ant-design/pull/22202)
- 🛠 Typography `onExpand` function support event parameter. [#22092](https://github.com/ant-design/ant-design/pull/22092) [@BlazPocrnja](https://github.com/BlazPocrnja)
- 🛠 Simplify Popconfirm and Popover dom structure. [#22052](https://github.com/ant-design/ant-design/pull/22052)
- 🐞 Fix Autocomplete display `null` when `value` is `null`. [#21955](https://github.com/ant-design/ant-design/pull/21955)
- 🐞 Adjust Drawer close button without `title` style to avoid overlap with scroll bar. [#22710](https://github.com/ant-design/ant-design/pull/22710)
- 🐞 Fix Calendar style details. [#22676](https://github.com/ant-design/ant-design/pull/22676)
- Table
  - 🐞 Fix Table fixed column shadow style in Safari. [#22680](https://github.com/ant-design/ant-design/pull/22680)
  - 🐞 Fix Table style affect nest table element. [#22643](https://github.com/ant-design/ant-design/pull/22643)
  - 🐞 Fix Table `emptyText` is not centered and show pagination when empty data. [#22548](https://github.com/ant-design/ant-design/pull/22548) [@hengkx](https://github.com/hengkx)
  - 🐞 Fix Table `rowSelection` event bubbling with `onRow`. [#22566](https://github.com/ant-design/ant-design/pull/22566) [@hengkx](https://github.com/hengkx)
- 🐞 Fix Input with `suffix` only align style issue. [#22603](https://github.com/ant-design/ant-design/pull/22603)
- 🐞 Fix Alert cannot work with Tooltip/Popover. [#22594](https://github.com/ant-design/ant-design/pull/22594)
- 🐞 Fix nest dynamic Form.Item get react unmounted update warning. [#22575](https://github.com/ant-design/ant-design/pull/22575)
- 💄 Adjust Tag `processing` status color. [#22303](https://github.com/ant-design/ant-design/pull/22303)
- 💄 Remove Select dropdown group title mouse click style. [#22581](https://github.com/ant-design/ant-design/pull/22581)
- 💄 Redesign Table filter menu buttons and fix Dropdown edge `padding` style. [#22072](https://github.com/ant-design/ant-design/pull/22072)
- 💄 Move `@form-item-label-height` from form styles to theme variables. [#22600](https://github.com/ant-design/ant-design/pull/22600) [@slavakam](https://github.com/slavakam)
- 💄 Add less variables `@link-focus-decoration` and `@link-focus-outline`. [#22511](https://github.com/ant-design/ant-design/pull/22511)
- 💄 add separator cursor `disabled` of DatePicker. [#22563](https://github.com/ant-design/ant-design/pull/22563)
- RTL
  - 💄 Optimize Checkbox `inner` RTL style issue. [#22627](https://github.com/ant-design/ant-design/pull/22627)
  - 🐞 Optimize Upload `picture-card` RTL style issue. [#22630](https://github.com/ant-design/ant-design/pull/22630)
  - 🐞 Fix Badge RTL number style issue. [#22665](https://github.com/ant-design/ant-design/pull/22665)
  - 🐞 Fix Select RTL style issue when select multiple options can be cleared. [#22596](https://github.com/ant-design/ant-design/pull/22596)
  - 🐞 Fix Progress RTL style issue. [#22558](https://github.com/ant-design/ant-design/pull/22558)
  - 🐞 Fix Badge RTL style issue. [#22551](https://github.com/ant-design/ant-design/pull/22551)
  - 🐞 Fix Input RTL style issue. [#22525](https://github.com/ant-design/ant-design/pull/22525)
  - 🐞 Fix Steps RTL style issue. [#22523](https://github.com/ant-design/ant-design/pull/22523)
  - 💄 Optimize Tabs RTL icon style issue. [#22653](https://github.com/ant-design/ant-design/pull/22653)
  - 💄 Optimize Input.Group RTL style issue. [#22624](https://github.com/ant-design/ant-design/pull/22624)
  - 💄 Optimize Timeline label mode RTL style issue. [#22652](https://github.com/ant-design/ant-design/pull/22652)
  - 💄 Optimization Select dropdown group RTL style issue. [#22584](https://github.com/ant-design/ant-design/pull/22584)
  - 💄 Optimization Dropdown.Button RTL style issue. [#22519](https://github.com/ant-design/ant-design/pull/22519)
- Typescript
  - 🛠 replace deprecated `React.SFC` with `React.FC`. [#22691](https://github.com/ant-design/ant-design/pull/22691) [@Rustin-Liu](https://github.com/Rustin-Liu)
  - 🐞 Fix Form.Item `children` definition. [#22662](https://github.com/ant-design/ant-design/pull/22662)

## 4.0.4

`2020-03-23`

- 🐞 Fix AutoComplete clear icon overlap issue on search icon. [#22310](https://github.com/ant-design/ant-design/pull/22310)
- 🐞 Fix Button align issue when is `disabled` and wrapped by Tooltip. [#22461](https://github.com/ant-design/ant-design/pull/22461)
- 🐞 Fix Cascader search need to press down arrow twice to select item. [#22216](https://github.com/ant-design/ant-design/pull/22216) [@Kermit-Xuan](https://github.com/Kermit-Xuan)
- 🐞 Fix Carousel cannot works on Snowpack. [#22507](https://github.com/ant-design/ant-design/pull/22507)
- 🐞 Fix ConfigProvider `componentSize` not works on DatePicker.RangePicker. [#22486](https://github.com/ant-design/ant-design/pull/22486)
- 🐞 Fix Descriptions cannot fit to small container width. [#22407](https://github.com/ant-design/ant-design/pull/22407)
- ⚡️ Optimization Form.Item with multiple noStyle children Form.Item message collection performance. [#22410](https://github.com/ant-design/ant-design/pull/22410)
- 🐞 Fix Grid broken style using Col without `span`. [#22455](https://github.com/ant-design/ant-design/pull/22455)
- 💄 Add InputNumber RTL style. [#22434](https://github.com/ant-design/ant-design/pull/22434)
- Menu
  - 🛠 Menu inherit `line-height` from header. [#16142](https://github.com/ant-design/ant-design/pull/16142) [@sheerun](https://github.com/sheerun)
  - 🐞 Fix Menu unexpected scrollbar when show and hide. [#22248](https://github.com/ant-design/ant-design/pull/22248)
- 🐞 Fix Progress Dashboard won't allow `gapDeg` to be `0`. [#22462](https://github.com/ant-design/ant-design/pull/22462) [@thisrabbit](https://github.com/thisrabbit)
- 🛠 Adjust Radio.Group logic that `value` is `undefined` should be uncontrolled mode. [#22245](https://github.com/ant-design/ant-design/pull/22245)
- ⚡️ Reduce Row unnecessary render when `gutter` is array. [#22475](https://github.com/ant-design/ant-design/pull/22475) [@dolfje](https://github.com/dolfje)
- 💄 Tweak RangePicker arrow shadow style. [#22406](https://github.com/ant-design/ant-design/pull/22406)
- 🐞 Fix Select dropdown menu vertical padding. [#22251](https://github.com/ant-design/ant-design/pull/22251)
- 🐞 Fix Slider tooltip crash when with `nullable` value. [#22482](https://github.com/ant-design/ant-design/pull/22482)
- Table
  - 🐞 Fix Table ColumnGroup with controlled `sorterOrder` not working issue. [#22450](https://github.com/ant-design/ant-design/pull/22450)
  - 🐞 Fix Table border radius style. [#22413](https://github.com/ant-design/ant-design/pull/22413) [@akshatmittal](https://github.com/akshatmittal)
  - 🐞 Fix Table fixed column height issue. [#22367](https://github.com/ant-design/ant-design/pull/22367)
  - 🐞Fix Table row expand icon show error in ipad. [#22334](https://github.com/ant-design/ant-design/pull/22334) [@BugHiding](https://github.com/BugHiding)
  - 🛠 Table `column.filter` support `boolean` value. [#22277](https://github.com/ant-design/ant-design/pull/22277) [@xudongdev](https://github.com/xudongdev)
  - 🐞 Fix Table filter no working when only set `onFilter`. [#22317](https://github.com/ant-design/ant-design/pull/22317)
- 🐞 Fix TreeSelect `treeIcon` not working. [#22437](https://github.com/ant-design/ant-design/pull/22437)
- 🐞 Refactor DirectoryTree to fix deprecated warning. [#22318](https://github.com/ant-design/ant-design/pull/22318)
- 🐞 Fix Typography nest list style issue. [#22284](https://github.com/ant-design/ant-design/pull/22284)
- 🐞 Adjust Upload `onChange` return `fileList` is immutable data to avoid render issue. [#22322](https://github.com/ant-design/ant-design/pull/22322)
- 🌎 Localization
  - 🇩🇪 Updated German locale. [#22270](https://github.com/ant-design/ant-design/pull/22270) [@iChebbi](https://github.com/iChebbi)
  - 🇫🇷 Update French locale. [#22238](https://github.com/ant-design/ant-design/pull/22238) [@abenhamdine](https://github.com/abenhamdine)
- Typescript
  - 🐞 Omit Table `getCheckboxProps` typeof `checked`. [#22391](https://github.com/ant-design/ant-design/pull/22391) [@geekrainy](https://github.com/geekrainy)

## 4.0.3

`2020-03-14`

- Menu
  - 🐞 Fix Menu horizontal Item with nest Icon miss margin style. [#22021](https://github.com/ant-design/ant-design/pull/22021)
  - 🐞 Fix Menu item wrong `title` when setting `getPopupContainer`. [#22182](https://github.com/ant-design/ant-design/pull/22182)
  - 💄 Optimize the style of Icon in Menu. [#22090](https://github.com/ant-design/ant-design/pull/22090) [@x1mrdonut1x](https://github.com/x1mrdonut1x)
  - 🐞 Fix Avatar in horizontal Menu `margin` issue. [#22038](https://github.com/ant-design/ant-design/pull/22038) [#22033](https://github.com/ant-design/ant-design/pull/22033)
- Slider
  - 🐞 Fix an issue where the position of 'slider handle' is incorrect in the vertical case of Slider. [#22135](https://github.com/ant-design/ant-design/pull/22135) [@wendellhu95](https://github.com/wendellhu95)
  - 💄 Fix Slider missing `focus` style. [#22161](https://github.com/ant-design/ant-design/pull/22161)
- Table
  - 🐞 Fix ConfigProvider not work on Table filter dropdown. [#22133](https://github.com/ant-design/ant-design/pull/22133)
  - 🐞 Fix Table nest tree column expandable style issue with fixed column. [#22131](https://github.com/ant-design/ant-design/pull/22131)
  - 🐞 Fix an issue where Table filtering throws `cannot read property 'map' of undefined`. [#22096](https://github.com/ant-design/ant-design/pull/22096) [@yoyo837](https://github.com/yoyo837)
  - 🐞 Fix Table expandable column not fixed when selection column is fixed. [#22087](https://github.com/ant-design/ant-design/pull/22087)
  - 🐞 Fix Table filter menu reset not working. [#22079](https://github.com/ant-design/ant-design/pull/22079) [@shaodahong](https://github.com/shaodahong)
  - 🐞 Fix Table filter sub menu max height with many items. [#22230](https://github.com/ant-design/ant-design/pull/22230)
- Form
  - 💄 Optimize the responsive and box model performance of The Form. [#21907](https://github.com/ant-design/ant-design/pull/21907) [@shaodahong](https://github.com/shaodahong)
  - 🐞 Fix FormItem hooks render error. [#22053](https://github.com/ant-design/ant-design/pull/22053) [@kagawagao](https://github.com/kagawagao)
- 🐞 Fixed the problem of using custom icons to wrap in Input.Group. [#22197](https://github.com/ant-design/ant-design/pull/22197) [@xrkffgg](https://github.com/xrkffgg)
- 💄 Adjust Select single padding style to avoid tweak with dropdown. [#22167](https://github.com/ant-design/ant-design/pull/22167)
- 💄 Fix Calendar header select ellipsis bug. [#22148](https://github.com/ant-design/ant-design/pull/22148)
- 💄 Fixed Dropdown content and icons overlapping. [#22098](https://github.com/ant-design/ant-design/pull/22098) [@xrkffgg](https://github.com/xrkffgg)
- 🐞 Fix Select ellipsis bug in Firefox. [#22101](https://github.com/ant-design/ant-design/pull/22101)
- 🐞 Remove PageHeader unnecessary `overflow: hidden` style,Optimize PageHeader extra buttons responsive design. [#22030](https://github.com/ant-design/ant-design/pull/22030)
- 🐞 Fix TextArea `autoSize` don't scroll bottom in Firefox. [#22014](https://github.com/ant-design/ant-design/pull/22014)
- 🇫🇷 The full fr_FR internationalized text. [#22122](https://github.com/ant-design/ant-design/pull/22122) [@PaulJln](https://github.com/PaulJln)
- RTL
  - 💄 Optimize the style of Pagination in RTL mode. [#22155](https://github.com/ant-design/ant-design/pull/22155) [@xrkffgg](https://github.com/xrkffgg)
  - 💄 Fixed the icon style with Cascader RTL. [#22191](https://github.com/ant-design/ant-design/pull/22191) [@xrkffgg](https://github.com/xrkffgg)
  - 💄 Optimize the Checkbox.Group style in RTL mode. [#22186](https://github.com/ant-design/ant-design/pull/22186) [@xrkffgg](https://github.com/xrkffgg)
  - 💄 Optimize Radio.Button style issues in RTL mode. [#22066](https://github.com/ant-design/ant-design/pull/22066) [@xrkffgg](https://github.com/xrkffgg)
  - 🐞 Optimize table-pinned style issues that are listed under RTL. [#21914](https://github.com/ant-design/ant-design/pull/21914) [@saeedrahimi](https://github.com/saeedrahimi)
  - 💄 Adjust the direction of the Dropdown icon in RTL mode. [#22104](https://github.com/ant-design/ant-design/pull/22104) [@xrkffgg](https://github.com/xrkffgg)
  - 💄 Optimize the Breadcrumb style in RTL mode. [#22159](https://github.com/ant-design/ant-design/pull/22159) [@xrkffgg](https://github.com/xrkffgg)
  - 💄 Optimize the style of the Steps component in RTL mode. [#22175](https://github.com/ant-design/ant-design/pull/22175) [@xrkffgg](https://github.com/xrkffgg)
  - 💄 Optimize styles in RTL mode with form feedback. [#22222](https://github.com/ant-design/ant-design/pull/22222)
- TypeScript
  - 🔷 Update the `operation` type definition of FormList. [#22058](https://github.com/ant-design/ant-design/pull/22058) [@kagawagao](https://github.com/kagawagao)
  - 🔷 Update the definition of the `trigger` parameter for components such as Tooltip. [#22043](https://github.com/ant-design/ant-design/pull/22043) [@wendellhu95](https://github.com/wendellhu95)

## 4.0.2

`2020-03-08`

- Form
  - 🐞 Fix nest Form.Item dynamic remove will warning in React. [#21896](https://github.com/ant-design/ant-design/pull/21896)
  - ⚡️ Form `useForm` now return same instance for perfermance. [#21927](https://github.com/ant-design/ant-design/pull/21927)
  - ⚡️ Refactor Form.Item render logic that will only render once when children is a pure component. [#21991](https://github.com/ant-design/ant-design/pull/21991)
  - ⚡️ FormContext use a memoized value to avoid trigger FormItem's unintentional renders. [#21980](https://github.com/ant-design/ant-design/pull/21980) [@qiqiboy](https://github.com/qiqiboy)
- Table
  - 🐞 Fix Table dropdown popup at abnormal direction. [#21905](https://github.com/ant-design/ant-design/pull/21905)
  - 🐞 Fix Table `expandIconColumnIndex` display order with `rowSelection`. [#21915](https://github.com/ant-design/ant-design/pull/21915)
  - 🐞 Fix Table `size="small"` header background color is not same as other size. [#21942](https://github.com/ant-design/ant-design/pull/21942)
  - 🐞 Fix Table `className` and `style` works on wrong node. [#21974](https://github.com/ant-design/ant-design/pull/21974)
- Select
  - 🐞 Fix Select align issue with empty string value. [#21880](https://github.com/ant-design/ant-design/pull/21880)
  - 🐞 Fix small size Select tag text not align middle. [#21940](https://github.com/ant-design/ant-design/pull/21940) [@xrkffgg](https://github.com/xrkffgg)
- Menu
  - 🐞 Fix Menu bottom margin is missing. [#21867](https://github.com/ant-design/ant-design/pull/21867)
  - 🐞 Fix horizontal Menu extra margin of Menu.Item with only icon. [#21925](https://github.com/ant-design/ant-design/pull/21925)
  - 🐞 Fix Menu popup menu overflow issue when contains too many items. [#21930](https://github.com/ant-design/ant-design/pull/21930)
- 🐞 Fix Badge animation when switch between 10 and 11. [#21834](https://github.com/ant-design/ant-design/pull/21834) [@wendellhu95](https://github.com/wendellhu95)
- 🐞 Fix Radio.Button inside Tooltip throws `Function components cannot be given refs` warning. [#21895](https://github.com/ant-design/ant-design/pull/21895) [@AshoneA](https://github.com/AshoneA)
- 🐞 Fix Descriptions miss style when content is falsy. [#21901](https://github.com/ant-design/ant-design/pull/21901)
- 🐞 Fix DatePicker cursor style on `seperator`. [#21937](https://github.com/ant-design/ant-design/pull/21937) [@xrkffgg](https://github.com/xrkffgg)
- 🐞 Fix ConfigProvider `prefixCls` not working on Input.Password. [#21953](https://github.com/ant-design/ant-design/pull/21953) [@tdida](https://github.com/tdida)
- 🐞 Fix Carousel `dots` not align center. [#21960](https://github.com/ant-design/ant-design/pull/21960) [@liusiasi](https://github.com/liusiasi)
- 🐞 Fix Input.Search border style in `rtl` mode. [#21946](https://github.com/ant-design/ant-design/pull/21946) [@xrkffgg](https://github.com/xrkffgg)
- Less
  - 🆕 Add `@outline-fade` variable. [#20227](https://github.com/ant-design/ant-design/pull/20227) [@Satloff](https://github.com/Satloff)
  - 🆕 Add `@form-item-label-height` variable. [#21912](https://github.com/ant-design/ant-design/pull/21912)
- TypeScript
  - 🌟 Improve Form.Item `renderProps` definite. [#21911](https://github.com/ant-design/ant-design/pull/21911)

## 4.0.1

`2020-03-04`

- Form
  - 🐞 Fix Form help control will get `react@16.13` warning. [#21800](https://github.com/ant-design/ant-design/pull/21800) [#21702](https://github.com/ant-design/ant-design/pull/21702)
  - 🐞 Fix Form.Item exceed Form width when content is too long. [#21682](https://github.com/ant-design/ant-design/pull/21682)
- Input
  - 🐞 Fix TextArea style get warning in `react@16.13`. [#21703](https://github.com/ant-design/ant-design/pull/21703)
  - 🐞 Fix Input.Search extra border when has `prefix`. [#21753](https://github.com/ant-design/ant-design/pull/21753)
- Table
  - 🐞 Fix Table column with `filtered` not working. [#21825](https://github.com/ant-design/ant-design/pull/21825)
  - 🐞 Fix Table locale not work. [#21772](https://github.com/ant-design/ant-design/pull/21772)
  - 🐞 Fix Table.Column `sortOrder` is not working in JSX mode. [#21719](https://github.com/ant-design/ant-design/pull/21719)
  - 🐞 Fix Table fixed column with sorted status style issue. [#21679](https://github.com/ant-design/ant-design/pull/21679)
- 🐞 Fix Dropdown menu arrow position. [#21768](https://github.com/ant-design/ant-design/pull/21768) [@xrkffgg](https://github.com/xrkffgg)
- 🐞 Fix List `bordered` and `split` props conflict. [#21784](https://github.com/ant-design/ant-design/pull/21784) [@MXWXZ](https://github.com/MXWXZ)
- 🐞 Fix Menu.Item `a` tag hidden bug. [#21699](https://github.com/ant-design/ant-design/pull/21699) [@shaodahong](https://github.com/shaodahong)
- 🐞 Fix `message.open` crash when `icon` is not passed. [#21747](https://github.com/ant-design/ant-design/pull/21747) [@AshoneA](https://github.com/AshoneA)
- 🐞 Fix Result `status` cannot assigned to string or number type. [#21691](https://github.com/ant-design/ant-design/pull/21691)
- 🐞 Fix Descriptions warning for duplicate key. [#21688](https://github.com/ant-design/ant-design/pull/21688)
- 💄 Optimize Calendar header style in small screen. [#21813](https://github.com/ant-design/ant-design/pull/21813)
- 💄 Radio.Group not wrapping now. [#21813](https://github.com/ant-design/ant-design/pull/21813)
- 🛠 Refactor icons import code to reduce webpack disabled tree shaking bundle size. [#21752](https://github.com/ant-design/ant-design/pull/21752)
- Typescript
  - 🐞 Fix Radio.Button type error. [#21807](https://github.com/ant-design/ant-design/pull/21807) [@jhoneybee](https://github.com/jhoneybee)
  - 🐞 fix `TreeSelect.SHOW_*` type. [#21791](https://github.com/ant-design/ant-design/pull/21791) [@TennyZhuang](https://github.com/TennyZhuang)
  - 🐞 Fix TreeSelect missing `suffix` define. [#21714](https://github.com/ant-design/ant-design/pull/21714)
  - 🐞 Fix Drawer `forceRender` TypeScript definite. [#21774](https://github.com/ant-design/ant-design/pull/21774)
  - 🐞 Fix Tree `treeData` define. [#21756](https://github.com/ant-design/ant-design/pull/21756)
  - 🐞 Fix Form.Item `renderProps` return type define. [#21716](https://github.com/ant-design/ant-design/pull/21716)

## 4.0.0

`2020-02-28`

- 🏆 Ant Design v4 is out! Check [here](https://github.com/ant-design/ant-design/issues/21656) for more info.
- 🐞 Breadcrumb use `path` as default key to fix `name` key conflict. [#21583](https://github.com/ant-design/ant-design/pull/21583) [@douxc](https://github.com/douxc)
- 🌟 Timeline.Item support `label`. [#21560](https://github.com/ant-design/ant-design/pull/21560) [@shaodahong](https://github.com/shaodahong)
- 🐞 Fix Table filter menu max height style with many items. [#21602](https://github.com/ant-design/ant-design/pull/21602)
- 💄 Add the Calendar component's custom default font color for display content. [#21598](https://github.com/ant-design/ant-design/pull/21598) [@xrkffgg](https://github.com/xrkffgg)
- 🚮 Remove DatePicker legacy cell className for custom cell style. [#21589](https://github.com/ant-design/ant-design/pull/21589)
- 🐞 Fix RangePicker style render bug in IE11. [#21587](https://github.com/ant-design/ant-design/pull/21587)
- 🛠 Progress `strokeColor` now will ignore incorrect percent. [#21564](https://github.com/ant-design/ant-design/pull/21564) [@AshoneA](https://github.com/AshoneA)
- 🐞 Fix Progress `trailColor` not working when `type=line`. [#21552](https://github.com/ant-design/ant-design/pull/21552) [@AshoneA](https://github.com/AshoneA)
- 🐞 Fix the background of the components in the pop-up components in the dark theme. [#21299](https://github.com/ant-design/ant-design/pull/21299)
  - 💄 Optimization under the dark theme color swatches transparency.
  - 🌟 new less variable `@popover-customize-border-color`, `@list-customize-card-bg`, `@table-expand-icon-bg`, `@steps-background`, `@pagination-item-input-bg` for theme customization.

## 4.0.0-rc.6

`2020-02-24`

- Form
  - 🌟 support `scrollToFirstError` to simplify submit scroll logic. [#21462](https://github.com/ant-design/ant-design/pull/21462)
  - 🐞 Fix Form.Item with `help` align style. [#21476](https://github.com/ant-design/ant-design/pull/21476)
  - 🐞 Fix Form throw error when using BraftEditor. [#21425](https://github.com/ant-design/ant-design/pull/21425)
  - 🐞 Fix Form fields shake when switching the validing info. [#21302](https://github.com/ant-design/ant-design/pull/21302) [@yoyo837](https://github.com/yoyo837)
- Upload
  - 🌟 Upload added `removeIcon` and `downloadIcon` properties. [#21363](https://github.com/ant-design/ant-design/pull/21363) [@sdhr27](https://github.com/sdhr27)
  - 🐞 Fix Upload identify types of image logic errors. [#21473](https://github.com/ant-design/ant-design/pull/21473) [@holynewbie](https://github.com/holynewbie)
- Input
  - 🐞 Fix Input with `readOnly` still clearable by `allowClear`. [#21494](https://github.com/ant-design/ant-design/pull/21494)
  - 🐞 Fix Input click with `prefix` / `suffix` not get focused. [#21413](https://github.com/ant-design/ant-design/pull/21413)
- Table
  - 🐞 Fix Table selection crash when record children is `null`. [#21528](https://github.com/ant-design/ant-design/pull/21528)
  - 🐞 Fix Table fixed column style with `small` size. [#21431](https://github.com/ant-design/ant-design/pull/21431)
- Descriptions
  - 🐞 Fix `label` does not have the problem of still rendering the label element when not using `bordered`. [#21542](https://github.com/ant-design/ant-design/pull/21542)
  - 🐞 Fix Non-bordered titles under `vertical` are also a problem for `td`. [#21542](https://github.com/ant-design/ant-design/pull/21542)
  - 🐞 Fix `vertical` and `bordered` layout issues. [#21542](https://github.com/ant-design/ant-design/pull/21542)
  - 🐞 Fix the problem of `style` not working on `Item`. [#21542](https://github.com/ant-design/ant-design/pull/21542)
  - 🐞 Fix `th` will also get the useless `-colon` className problem under `border`. [#21542](https://github.com/ant-design/ant-design/pull/21542)
- 🌟 Select added `tagRender` for customized tag rendering. [#21064](https://github.com/ant-design/ant-design/pull/21064) [@fguitton](https://github.com/fguitton)
- 💄 Picker `onPanelChange` will also trigger when panel value changed. [#21455](https://github.com/ant-design/ant-design/pull/21455)
- 🐞 Fix Notification first call multiple time can not stack. [#21531](https://github.com/ant-design/ant-design/pull/21531)
- 🐞 Fix TreeSelect popup do not update issue. [#21410](https://github.com/ant-design/ant-design/pull/21410)
- 💄 Optimize Upload `showDownloadIcon` default doesn't show. [b4636](https://github.com/ant-design/ant-design/commit/b4636ab2dfdb006c14bdb3d5d7de09e1650c3567)
- 💄 Tweak Divider inner text `padding` and add `@divider-text-padding`. [#21407](https://github.com/ant-design/ant-design/pull/21407)
- Typescript
  - 🐞 Fix Form types. [#21483](https://github.com/ant-design/ant-design/pull/21483) [#21411](https://github.com/ant-design/ant-design/pull/21411)

## 4.0.0-rc.5

`2020-02-16`

- 🐞 Fix Form.Item `validateFirst` prevent form submit. [#21329](https://github.com/ant-design/ant-design/pull/21329)
- 🐞 Fix InputNumber cursor position issue when deleting consecutive identical numbers. [#21344](https://github.com/ant-design/ant-design/pull/21344)
- 💄 Remove Menu excess background color. [#21365](https://github.com/ant-design/ant-design/pull/21365)
- 💄 Optimize the mouse style for the `disabled` state of the DatePicker component. [#21352](https://github.com/ant-design/ant-design/pull/21352)
- 🐞 Fix Affix throws `Cannot read property getBoundingClientRect` in mobile device. [#21350](https://github.com/ant-design/ant-design/pull/21350)
- 🐞 Fix the problem that the label width is incorrect when the screen is less than `xs`. [#21222](https://github.com/ant-design/ant-design/pull/21222)
- 🐞 Fix Input `size` is `large` height style. [#21338](https://github.com/ant-design/ant-design/pull/21338)
- 🐞 Fix Badge `color` not working when contains children. [#21333](https://github.com/ant-design/ant-design/pull/21333)
- 🐞 Fix Alert close button extra padding. [#21325](https://github.com/ant-design/ant-design/pull/21325)
- 💄 Tweak Steps 1px align issue. [#21306](https://github.com/ant-design/ant-design/pull/21306)
- 💄 Fix legacy Button.Group `large` size style issue. [#21307](https://github.com/ant-design/ant-design/pull/21307)
- 💄 Fix Input border radius with suffix, style in Firefox, TextArea allowClear style issues. [#21316](https://github.com/ant-design/ant-design/pull/21316)
- 🐞 Pagination will pass `disabled` prop to prev/next buttons return by `itemRender`. [#21361](https://github.com/ant-design/ant-design/pull/21361)
- 🇦🇿 Added Azerbaijani translation. [#21387](https://github.com/ant-design/ant-design/pull/21387) [@orkhan-huseyn](https://github.com/orkhan-huseyn)
- Typescript
  - 🔷 Menu export `MenuItemGroupProps`. [#21356](https://github.com/ant-design/ant-design/pull/21356)
  - 🔷 Table export `ColumnProps`. [#21321](https://github.com/ant-design/ant-design/pull/21321)

## 4.0.0-rc.4

`2020-02-09`

- 📖 Add [color palette](https://preview-21101-ant-design.surge.sh/docs/spec/dark-cn#%E5%9F%BA%E7%A1%80%E8%89%B2%E6%9D%BF) and [palette generation tool](https://preview-21101-ant-design.surge.sh/docs/spec/dark-cn#%E8%89%B2%E6%9D%BF%E7%94%9F%E6%88%90%E5%B7%A5%E5%85%B7) for dark theme. [#21101](https://github.com/ant-design/ant-design/pull/21101)
- 🌟 Add `style` field for `options` prop of Checkbox.Group and Radio.Group. [#21219](https://github.com/ant-design/ant-design/pull/21219)
- 🌟 Add `validateFirst` prop for Form.Item. [#21178](https://github.com/ant-design/ant-design/pull/21178)
- 🌟 Add `useModal` hook for Modal to support `context` access. [#20949](https://github.com/ant-design/ant-design/pull/20949)
- 🌟 Add `useNotification` hook for Notification to support `context` access. [#21275](https://github.com/ant-design/ant-design/pull/21275)
- 🌟 Add `bordered` prop for Select、TreeSelect、DatePicker、TimePicker and Cascader. [#21242](https://github.com/ant-design/ant-design/pull/21242)
- 🌟 Add `selectAllLabels` prop for Transfer. [#21139](https://github.com/ant-design/ant-design/pull/21139) [@morenyang](https://github.com/morenyang)
- 💄 Redesign the style of ink bar for Tabs. [#21256](https://github.com/ant-design/ant-design/pull/21256)
- 💄 Add less variable `@form-item-label-font-size`. [#21216](https://github.com/ant-design/ant-design/pull/21216)
- 🐞 Fix Badge style for Badge with Typography. [#21235](https://github.com/ant-design/ant-design/pull/21235)
- 🐞 Fix Checkbox not work when Checkbox and Checkbox.Group are separated by other component. [#21146](https://github.com/ant-design/ant-design/pull/21146) [@morenyang](https://github.com/morenyang)
- 🐞 Fix Collapse.Panel wrong content width when `extra` prop is set. [#21202](https://github.com/ant-design/ant-design/pull/21202) [@zhiyuc123](https://github.com/zhiyuc123)
- Form
  - 🐞 Fix Form.Item `required` validation not work when name is not set. [#21168](https://github.com/ant-design/ant-design/pull/21168)
  - 🐞 Fix Form.Item data binding not work when `name` is `0`. [#21186](https://github.com/ant-design/ant-design/pull/21186) [@wanjas](https://github.com/wanjas)
  - 🐞 Fix Form.Item shaking when `help` prop change from valuable to `undefined`. [#21211](https://github.com/ant-design/ant-design/pull/21211)
- Input
  - 🐞 Fix worng validating style when `prefix` is set. [#21121](https://github.com/ant-design/ant-design/pull/21121)
  - 🐞 Fix `size` prop not work when `prefix` or `affix` is set. [#21290](https://github.com/ant-design/ant-design/pull/21290) [@yoyo837](https://github.com/yoyo837)
- 🐞 Fix Radio.Group style with Badge. [#21215](https://github.com/ant-design/ant-design/pull/21215)
- 🐞 Fix Select no margin between lines when mode is `tags` or `multiple`. [#21175](https://github.com/ant-design/ant-design/pull/21175)
- 🐞 Fix Slider dots focus style. [#21244](https://github.com/ant-design/ant-design/pull/21244) [@Kermit-Xuan](https://github.com/Kermit-Xuan)
- 🐞 Fix Steps icon not align when `size="small"` and `labelPlacement="vertical"`. [#21258](https://github.com/ant-design/ant-design/pull/21258)
- Table
  - 🐞 Fix `expandIcon` prop not work when data item has no `children` field. [#21169](https://github.com/ant-design/ant-design/pull/21169)
  - 🐞 Fix Column `sorter` prop not work. [#21194](https://github.com/ant-design/ant-design/pull/21194)
  - 🐞 Fix custom filter's typing not work. [#21218](https://github.com/ant-design/ant-design/pull/21218)
- 🐞 Fix TimePicker `defaultOpenValue` prop not work. [#21198](https://github.com/ant-design/ant-design/pull/21198)
- Transfer
  - 🐞 Fix wrong unit for checkbox label of header. [#21136](https://github.com/ant-design/ant-design/pull/21136) [@morenyang](https://github.com/morenyang)
  - 🐞 Fix icon not align in search input. [#21247](https://github.com/ant-design/ant-design/pull/21247)
- 🐞 Fix Typography not focus at the end of textarea when editable is true. [#21268](https://github.com/ant-design/ant-design/pull/21268)

## 4.0.0-rc.3

`2020-01-27`

- 🛠 Use native Date instead of moment to get timestamp in Countdown component. [#21108](https://github.com/ant-design/ant-design/pull/21108) [@morenyang](https://github.com/morenyang)
- 🐞 Fix Input `suffix / prefix` style issue with `addonBefore / addonAfter`. [#21105](https://github.com/ant-design/ant-design/pull/21105)
- 💄 Improved Timeline component style in RTL mode. [#21068](https://github.com/ant-design/ant-design/pull/21068) [@xrkffgg](https://github.com/xrkffgg)
- 💄 Update `clearfix` mixin to remove legacy `zoom` descriptor. [#21109](https://github.com/ant-design/ant-design/pull/21109) [@morenyang](https://github.com/morenyang)
- 💄Card component use `@font-size-base` instead of inline `14px`. [#21107](https://github.com/ant-design/ant-design/pull/21107) [@morenyang](https://github.com/morenyang)
- 💄 Adjust Layout component to let `className` get higher priority. [#21074](https://github.com/ant-design/ant-design/pull/21074) [@yoyo837](https://github.com/yoyo837)
- Typescript
  - 🐞 Fix Tree wrong event type of AntTreeNodeMouseEvent. [#21102](https://github.com/ant-design/ant-design/pull/21102) [@Jirka-Lhotka](https://github.com/Jirka-Lhotka)
  - 🐞 Fix Form.Item return type define. [#21067](https://github.com/ant-design/ant-design/pull/21067)

## 4.0.0-rc.2

`2020-01-21`

- 🛠 Refactor some demos to React hooks and TypeScript. [#21045](https://github.com/ant-design/ant-design/pull/21045)
- 🐞 Fixed Input/Select components align issue. [#20869](https://github.com/ant-design/ant-design/pull/20869)
- Dropdown
  - 🆕 Support `buttonsRender` to customize buttons. [#20815](https://github.com/ant-design/ant-design/pull/20815)
  - 🐞 Tooltip doesn't disappear on `disabled` Dropdown.Button in Chrome. [#20960](https://github.com/ant-design/ant-design/pull/20960)
- Input
  - 🐞 Fixed Input `prefix` and `suffix` overlap with content issue. [#20872](https://github.com/ant-design/ant-design/pull/20872)
  - 🐞 Fixed Input `placeholder` color in Firefox. [#20850](https://github.com/ant-design/ant-design/issues/20850)
- Table
  - 🐞 Fixed `onChange` return cached fresh sorter & filter state. [#20858](https://github.com/ant-design/ant-design/pull/20858)
  - 🐞 Fixed problem that all-checkbox is checked when all the checkboxes are disabled. [#20968](https://github.com/ant-design/ant-design/pull/20968)
  - 🐞 Fixed `locale.emptyText` not working. [#21024](https://github.com/ant-design/ant-design/pull/21024)
- Select
  - 🐞 Fixed `placeholder` wrap and align issue. [#20883](https://github.com/ant-design/ant-design/pull/20883) [#20884](https://github.com/ant-design/ant-design/pull/20884)
  - 🐞 Fixed multiple Select left padding. [#20861](https://github.com/ant-design/ant-design/pull/20861)
  - 🐞 Fixed multiple Select clean icon overlap issue. [#20914](https://github.com/ant-design/ant-design/pull/20914)
- Form
  - 🆕 Added scroll options as `scrollToField` argument. [#20774](https://github.com/ant-design/ant-design/pull/20774)
  - 🐞 Fixed Form.Item update `help` makes layout shake. [#20886](https://github.com/ant-design/ant-design/pull/20886)
  - 🐞 Fixed unexpected extra rerender when Form.Item is not a real Field. [#20963](https://github.com/ant-design/ant-design/pull/20963)
  - 🐞 Fixed Form.Item ignore `help=""` issue. [#21026](https://github.com/ant-design/ant-design/pull/21026)
  - 🐞 Fixed Form.Item `label` align bug in small screen. [#20836](https://github.com/ant-design/ant-design/issues/20836)
- 🐞 Fixed message cut shadow issue. [#20856](https://github.com/ant-design/ant-design/issues/20856)
- 🐞 Fixed Tooltip hidden when `title` is `0`. [#20894](https://github.com/ant-design/ant-design/pull/20894)
- 🐞 Fixed List `actions` inconsistent position. [#20897](https://github.com/ant-design/ant-design/pull/20897)
- 🆕 Add a visual list example for Tree. [#20911](https://github.com/ant-design/ant-design/pull/20911)
- 🐞 Fixed AutoComplete example styling issue. [#20946](https://github.com/ant-design/ant-design/pull/20946)
- 🗑 Removed AutoComplete useless `labelInValue`. [#20967](https://github.com/ant-design/ant-design/pull/20967)
- 🐞 Fixed Drawer `footerStyle` prop cause react warning. [#20983](https://github.com/ant-design/ant-design/pull/20983)
- 🐞 Fixed Breadcrumb style in `rtl` mode. [#21054](https://github.com/ant-design/ant-design/pull/21054)
- 💄 Tweak Layout `className` order to end. [#21041](https://github.com/ant-design/ant-design/pull/21041)
- TypeScript
  - 🐞 Export DatePicker related interface. [#20900](https://github.com/ant-design/ant-design/pull/20900)
- Less variables
  - 🆕 Readded `@border-radius-sm`. [#20818](https://github.com/ant-design/ant-design/pull/20818)
  - 🆕 Added `@timeline-item-padding-bottom`. [#21013](https://github.com/ant-design/ant-design/pull/21013)
  - 🆕 Added `@layout-header-color`. [#21033](https://github.com/ant-design/ant-design/pull/21033)

## 4.0.0-rc.1

`2020-01-11`

- 🌟 Drawer Added `footer` and `footerStyle` properties. [#20690](https://github.com/ant-design/ant-design/pull/20690) [@DeanVanNiekerk](https://github.com/DeanVanNiekerk)
- 🌟 Switch Added `@switch-min-width` and `@switch-sm-min-width` less variables. [#20829](https://github.com/ant-design/ant-design/pull/20829) [@abdih](https://github.com/abdih)
- Table
  - 🐞 Fix expanded icon not work when `expandRowByClick` is set. [#20808](https://github.com/ant-design/ant-design/pull/20808)
  - 🐞 Fix expanded row width in scaled dom element and border style. [#20805](https://github.com/ant-design/ant-design/pull/20805)
  - 🐞 Fix background color css priority too high to override user customize style. [#20794](https://github.com/ant-design/ant-design/pull/20794)
  - 🐞 Fix `rowSelection` of `fixed` not work. [#20735](https://github.com/ant-design/ant-design/pull/20735)
  - 🐞 Fix fixed columns in Chrome show the vertical scrollbar. [#20705](https://github.com/ant-design/ant-design/pull/20705)
  - 🐞 Fix crash when columns with empty children. [#20703](https://github.com/ant-design/ant-design/pull/20703)
- 💄 Tweak Calendar basic style month drop-down box width and notice items of word order and card mode, select the size of the box. [#20790](https://github.com/ant-design/ant-design/pull/20790) [@xrkffgg](https://github.com/xrkffgg)
- DatePicker
  - 💄 Optimize the `border-radius` of the rounded corners connection. [#20736](https://github.com/ant-design/ant-design/pull/20736)
  - 🐞 Fix selected style overlap. [#20736](https://github.com/ant-design/ant-design/pull/20736)
  - 🐞 Fix extra dividing line at the bottom. [#20736](https://github.com/ant-design/ant-design/pull/20736)
  - 🐞 Fix button style for DatePicker's default range. [#20760](https://github.com/ant-design/ant-design/pull/20760) [@xrkffgg](https://github.com/xrkffgg)
- 🐞 Input not block user input when value is `undefined`. [#20783](https://github.com/ant-design/ant-design/pull/20783)
- 🐞 Fix Carousel card carousel orientation in left / right mode. [#20781](https://github.com/ant-design/ant-design/pull/20781) [@xrkffgg](https://github.com/xrkffgg)
- 🐞 Fix Grid responsive gutter under SSR initial value of `0`. [#20762](https://github.com/ant-design/ant-design/pull/20762)
- 🐞 Fix InputNumber, Select and other components icon size. [#20765](https://github.com/ant-design/ant-design/pull/20765)
- 🐞 Fix Badge `z-index` higher than Table fixed columns. [#20751](https://github.com/ant-design/ant-design/pull/20751)
- 💄 Tweak font family to be same as tailwindcss. [#20747](https://github.com/ant-design/ant-design/pull/20747)
- 🐞 Fix TextArea `autoSize` blink in FireFox. [#20737](https://github.com/ant-design/ant-design/pull/20737)
- 🐞 Fix Form.Item not keep error message sync when hit rule changed. [#20725](https://github.com/ant-design/ant-design/pull/20725)
- 🐞 Fix Form.Item add additional feedback style when `hasFeedback` is not set. [#20691](https://github.com/ant-design/ant-design/pull/20691)
- 🐞 Fix Cascader search bug when `fieldNames` is existed and label/value share same name. [#20720](https://github.com/ant-design/ant-design/pull/20720)
- 🐞 Fix Collapse background color with wrong less variable. [#20718](https://github.com/ant-design/ant-design/pull/20718) [@kuitos](https://github.com/kuitos)
- 🐞 Fix Slider's Tooltip not follow handle. [#20699](https://github.com/ant-design/ant-design/pull/20699)
- 🐞 Fix Card cover image get skretched. [#20701](https://github.com/ant-design/ant-design/pull/20701)
- 🐞 Fix Typography automatic overflow with `suffix` property. [#20689](https://github.com/ant-design/ant-design/pull/20689) [@zouxiaomingya](https://github.com/zouxiaomingya)
- 🐞 Fix AutoComplete with customize component with wrong style. [#20686](https://github.com/ant-design/ant-design/pull/20686)
- 🐞 Fix Input.Group to be partial to a pixel in Form. [#20681](https://github.com/ant-design/ant-design/pull/20681)
- TypeScript
  - 🐞 Export Form interfaces. [3a1c5](https://github.com/ant-design/ant-design/commit/3a1c51010fecfa59f63f5e09027805a141e9ec11)
  - 🐞 Fix Table types. [#20789](https://github.com/ant-design/ant-design/pull/20789)
  - 🐞 Fix Table.Column and Table.ColumnGroup definition. [#20695](https://github.com/ant-design/ant-design/pull/20695)

## 4.0.0-rc.0

`2020-01-04`

Ant Design 4.0-rc released! Here is the release [document](https://github.com/ant-design/ant-design/issues/20661).

⚠️ Migrate from v3 to v4 please ref to [migration document](/docs/react/migration-v4).

### New features and improvements

- 🌟 antd package size optimization, js gzipped dropped from 532.75KB to 289.89 KB. [#20356](https://github.com/ant-design/ant-design/pull/20356)
- 💄 New dark theme support. [#20281](https://github.com/ant-design/ant-design/pull/20281)
- 🌟 ConfigProvider supports `direction` internationalization setting `rtl`. [#19380](https://github.com/ant-design/ant-design/pull/19380)
- 🌟 New Form component. [#17327](https://github.com/ant-design/ant-design/pull/17327)
  - 🌟 Form comes with data binding function.
  - 🌟 Field changes only affect the rendering of related field components and not the entire Form.
  - 🌟 Added `initialValues` to replace the original field initialization.
  - 🌟 Added `validateMessages` to support modify validation templates.
  - 🌟 Added `onFinish` and `onFinishFailed` to complete the overall component verification logic.
  - 🌟 Added `onFieldsChange` and `onValuesChange` for triggering controlled state.
  - 🌟 Provide hook support for `useForm`.
  - 🌟 Form.Item adds `name` property for data binding.
  - 🌟 Form.Item `validateTrigger` will only perform validation trigger and will not collect field values ​​at the same time.
  - 🌟 Form.Item adds `rules` property for data validation.
  - 🌟 Form.Item adds `shouldUpdate` property to support render props.
  - 🌟 Form.Item adds `dependencies` property to simplify related field update logic.
  - 🌟 Form.Item adds `noStyle` property and adds unstyled data binding.
  - 🌟 Added Form.List component to simplify adding, deleting, modifying and checking operations.
  - 🌟 Added Form.Provider component to support multi-form linkage.
- 🌟 New Table component. [#19678](https://github.com/ant-design/ant-design/pull/19678)
  - 🌟 Added `summary` support for summary lines.
  - 🌟 Now `fixedColumn`,`expandable`, and `scroll` can be mixed.
  - 🌟 Support multi-column sort.
  - 🌟 Support custom `body` and add virtual scrolling example.
  - 🌟 Expansion-related props moved into the `expandable` attribute and add `rowExpandable` prop.
  - 🎉 Use css `sticky` to achieve fixed effects to optimize performance.
  - 💄 Optimized `expand` animation effect.
- 🌟 New DatePicker, TimePicker and Calendar components. [#20023](https://github.com/ant-design/ant-design/pull/20023)
  - 🌟 Support custom date library.
  - 🌟 Added `picker` support for setting selectors (no longer need to simulate selectors via controlled `mode`).
  - 🌟 Full range selector support: time, date, week, month, year.
  - 🌟 Range selector can now select start and end times individually.
  - 🌟 The range selector can be set to `disabled` separately for the start and end time.
  - 🌟 The range selector allows empty start and end times.
  - 🌟 Optimized manual input and keyboard interaction support.
  - 🌟 Added `inputReadOnly` to disable manual input.
- 🌟 Remove Icon and use `@ ant-design / icons` instead. [#18217](https://github.com/ant-design/ant-design/pull/18217)
- Skeleton
  - 🌟 Support Skeleton.Avatar placeholder component. [#19898](https://github.com/ant-design/ant-design/pull/19898) [@Rustin-Liu](https://github.com/Rustin-Liu)
  - 🌟 Support Skeleton.Button placeholder component. [#19699](https://github.com/ant-design/ant-design/pull/19699) [@Rustin-Liu](https://github.com/Rustin-Liu)
  - 🌟 Support Skeleton.Input placeholder component. [#20264](https://github.com/ant-design/ant-design/pull/20264) [@Rustin-Liu](https://github.com/Rustin-Liu)
- 🌟 Tree supports virtual scrolling. [#18172](https://github.com/ant-design/ant-design/pull/18172)
- 🌟 Tree Enhanced accessibility support and keyboard interaction. [#18866](https://github.com/ant-design/ant-design/pull/18866)
- 🌟 Select uses virtual scrolling and enhanced accessibility support and keyboard interaction. [#18658](https://github.com/ant-design/ant-design/pull/18658)
  - 🌟 Uncontrolled mode when `value` is `undefined` now.
  - 🌟 multiple Select won't rerender if `value` is mutable.
- 🌟 TreeSelect uses virtual scrolling and optimizes keyboard support. [#19040](https://github.com/ant-design/ant-design/pull/19040)
  - 🌟 Uncontrolled mode when `value` is `undefined` now.
- 🌟 Button adds `default` and `link` styles for `danger`. [#19837](https://github.com/ant-design/ant-design/pull/19837)
- 🌟 Form and ConfigProvider support `size` setting to include component size. [#20570](https://github.com/ant-design/ant-design/pull/20570)
- 🌟 Typography adds `suffix` attribute. [#20224](https://github.com/ant-design/ant-design/pull/20224)
- 🌟 Progress adds `steps` subcomponent. [#19613](https://github.com/ant-design/ant-design/pull/19613)
- 🌟 TextArea supports `onResize`. [#20408](https://github.com/ant-design/ant-design/pull/20408)
- 🌟 Added Alert.ErrorBoundary to provide friendly error interception and prompting. [#19923](https://github.com/ant-design/ant-design/pull/19923)
- 🌟 Upload supports iconRender to customize icons. [#20034](https://github.com/ant-design/ant-design/pull/20034) [@qq645381995](https://github.com/qq645381995)
- 🌟 Tag component preset status color. [#19399](https://github.com/ant-design/ant-design/pull/19399)
- 🌟 Grid uses `flex` layout. [#16635](https://github.com/ant-design/ant-design/pull/16635)
- 🐞 Fix the display error of Carousel component `dotposition` as `left | right`. [#20645](https://github.com/ant-design/ant-design/pull/20645) [@xrkffgg](https://github.com/xrkffgg)
- 🐞 Fix Alert style text overflow. [#20318](https://github.com/ant-design/ant-design/pull/20318)
- 🙅 Removed warning messages for deprecated APIs. [#17510](https://github.com/ant-design/ant-design/pull/17510)
- 🙅 Added warning for Avatar, Button, Modal.method and Result components using v3 strings as icons. [#20226](https://github.com/ant-design/ant-design/pull/20226)
- 💄 Add `@border-color-split-popover`、`@input-icon-hover-color`、`@select-clear-background`、`@cascader-menu-border-color-split`、`@modal-header-border-color-split`、`@skeleton-to-color`、`@transfer-item-hover-bg` and other less variables. [#20070](https://github.com/ant-design/ant-design/pull/20070)

## 3.x

Visit [GitHub](https://github.com/ant-design/ant-design/blob/3.x-stable/CHANGELOG.en-US.md) to read `3.x` change logs.

## 2.x

Visit [GitHub](https://github.com/ant-design/ant-design/blob/2.x-stable/CHANGELOG.en-US.md) to read `2.x` change logs.

## 1.11.4

Visit [GitHub](https://github.com/ant-design/ant-design/blob/1.x-stable/CHANGELOG.md) to read change logs from `0.x` to `1.x`.

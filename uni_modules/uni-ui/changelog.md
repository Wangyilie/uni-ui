## 1.2.15（2021-04-14）
- uni-date-picker 发布第一版
## 1.2.14（2021-04-14）
- uni-pagination 新增 PC 和 移动端适配不同的 ui
## 1.2.13（2021-04-14）
- uni-data-checkbox 修复 nvue 下无法选中的问题
- uni-data-picker 新增 支持云端非树形表结构数据
- uni-data-picker 修复 根节点 parent_field 字段等于null时选择界面错乱问题
- uni-file-picker 修复 选择的文件非 file-extname 字段指定的扩展名报错的Bug
- uni-file-picker 优化 更新组件示例
- uni-file-picker 优化 file-extname 字段支持字符串写法，多个扩展名需要用逗号分隔
## 1.2.12（2021-03-23）
  + uni-ui 新增 uni-datetime-picker 的 hide-second 属性、border 属性; 
  + uni-ui 修复 uni-datetime-picker 选择跟显示的日期不一样的 bug， 
  + uni-ui 修复 uni-datetime-picker change事件触发2次的 bug
  + uni-ui 修复 uni-datetime-picker 分、秒 end 范围错误的 bug
  + uni-ui 新增 uni-tr selectable 属性，用于 type=selection 时，设置某行是否可由全选按钮控制
  + uni-ui 新增 uni-data-checkbox 新增 disabled属性，支持nvue
  + uni-ui 优化 uni-data-checkbox  无选项时提示“暂无数据”
  + uni-ui 优化 uni-data-checkbox  默认颜色显示
  + uni-ui 新增 uni-link href 属性支持 tel:|mailto:
  + uni-ui 新增 uni-table 示例demo
  + uni-ui 修复 uni-data-picker 微信小程序某些情况下无法选择的问题，事件无法触发的问题
  + uni-ui 修复 uni-nav-bar easycom 下，找不到 uni-status-bar 的bug
  + uni-ui 修复 uni-easyinput 示例在 qq 小程序上的bug
  + uni-ui 修复 uni-forms 动态显示uni-forms-item的情况下，submit 方法获取值错误的Bug
  + uni-ui 调整 cli 项目 建议使用 easycom 方式引用组件，如使用按需引用，需手动维护组件内部引用

## 1.2.11（2021-02-24）
- 调整为uni_modules目录规范
- uni-data-picker 新增  数据驱动的picker选择器
- uni-file-picker 新增  文件选择上传
- uni-row 新增 栅格系统
- uni-data-checkbox 优化 支持 nvue
- uni-forms 修复 偶发性获取表单值错误的Bug
- uni-forms 修复 校验 uni-data-picker value 为 0 时，返回值错误的Bug
- uni-forms 修复 uni-forms-item 组件隐藏时依然触发校验的bug
- uni-forms 优化 实时校验
- uni-forms 优化 兼容nvue页面
- uni-easyinput 优化 兼容nvue页面
- uni-group 优化 兼容nvue页面
- uni-popup 优化 组件适配 PC
- uni-fab 优化 适配 PC
- uni-swiper-dot 优化 适配 PC
- uni-rate 优化 适配 PC
- uni-notice-bar 优化 适配 PC
- uni-indexed-list 优化 适配 PC
- uni-combox 优化 适配 PC
- uni-transition 优化 适配 PC
- uni-nav-bar 优化 适配 PC
- uni-swipe-action 优化 适配 PC
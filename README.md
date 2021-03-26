# Vue Select

A select control based on Vue 3

# Features / todo

* 点击后选择框会上下展开, 而不是下拉
    * 向下展开
    * 上下展开, 保持选中项在页面位置不变
    * 展开动作可设置一些延迟, 防止双击误选
* 选中项高亮
    * 文字 / 背景高亮
    * 选中项可增加图标或符号标识 (勾)
    * 若鼠标未悬停在 select 上, 则增大选中项高度
* 鼠标悬停项高亮
    * 文字 / 背景高亮
    * 增大高度
* 鼠标移动时, label 跟随移动, 与当前 hover 项对齐
* 自动宽度
* 多个 select 纵向排列, 宽度应该保持一致, 包括 label 和 options
    * 外部配置
* 点击页面上非当前 select 控件处收起 options
    * 双击才收起, 防止误触?
* css 变量抽取
* 展开 / 收起, 右边图标
* 当 option 很多, 滚动到超出选中项时, 选中项依然展示
    * 选中项在上方时, 展示在顶部
    * 选中项在下方时, 展示在底部

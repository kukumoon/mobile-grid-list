# mobile-grid-list

## Description
A Mobile Compatible Grid List Component Basing on React Window.

## Install
```
npm i mobile-grid-list
```

## Props
- Required：
  - height：列表总高度
  - rowHeight: 行高度
  - columnCount：列表列数
  - list：需要传入的列表数据
  - listCount：列表长度
  - overscanRowCount：额外渲染行个数
  - loading: 加载中
  - headerComponent / footerComponent：嵌套元素
- 可选项：
  - className: 为列表增加一个可选的className
  - outerRef：列表ref挂载
  - itemKey：列表中每个item的key自定义函数
  - initialScrollTop：列表起始滚动高度

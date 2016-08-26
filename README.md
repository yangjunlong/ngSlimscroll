# ngSlimscroll
> 一款漂亮的虚拟滚动条(Angularjs Directive)

## 用法
```html
<div ng-slimscroll rail-visible="true" height="100%">
    ...
</div>
// 可以将参数写到html标签属性中，参数名由原来的驼峰形式变成 `-` 分隔。
```

### 参数说明
```javascript
{
	width: 'auto', // 可滚动区域宽度
    height: '100%', // 可滚动区域高度
    size: '10px', // 组件宽度
    color: '#000', // 滚动条颜色
    position: 'right', // 组件位置：left/right
    distance: '0px', // 组件与侧边之间的距离
    start: 'top', // 默认滚动位置：top/bottom
    opacity: .4, // 滚动条透明度
    alwaysVisible: true, // 是否 始终显示组件
    disableFadeOut: false, // 是否 鼠标经过可滚动区域时显示组件，离开时隐藏组件
    railVisible: true, // 是否 显示轨道
    railColor: '#333', // 轨道颜色
    railOpacity: .2, // 轨道透明度
    railDraggable: true, // 是否 滚动条可拖动
    railClass: 'slimScrollRail', // 轨道div类名 
    barClass: 'slimScrollBar', // 滚动条div类名
    wrapperClass: 'slimScrollDiv', // 外包div类名
    allowPageScroll: true, // 是否 使用滚轮到达顶端/底端时，滚动窗口
    wheelStep: 20, // 滚轮滚动量
    touchScrollStep: 200, // 滚动量当用户使用手势
    borderRadius: '7px', // 滚动条圆角
    railBorderRadius: '7px' // 轨道圆角
}
```

## 参考
[https://github.com/rochal/jQuery-slimScroll](https://github.com/rochal/jQuery-slimScroll)

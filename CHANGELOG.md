## changelog


## 0.7.7

优化画布拖拽逻辑，更平滑移动。

## 0.7.6

右侧自定义rightGlobalCustom类型变更为函数传入config

## 0.7.5

修改滚轮方向。


## 0.7.4

修复框选移动bug。


## 0.7.3

修复弹窗位置与选中问题。


## 0.7.2

修复锁定组件影响，锁定中无法拖拽，缩放，旋转。

## 0.7.1

修复锁定组件无法选中解锁。


## 0.7.0

已支持组件旋转！

修复拖拽参考线等优化逻辑。

## 0.6.0

已支持编辑模式使用Iframe！

修复选中条件。


## 0.5.1

修复右侧选中不能取消选中问题。

## 0.5.0

修复control组件宽度不够问题。

移除antd自定义icon，容器底部icon可配置。

## 0.4.2

修复animate错误初始值。

修改markline样式。

全局设置增加容器高度。
## 0.4.1

去除lib自动导入样式。

## 0.4.0

去除runtime导出，所有属性从config中获取。

## 0.3.1

1、由uuid更换为nanoid。

2、control组件增加标尺控制。

## 0.3.0 

1、增加标尺，ContainerWrapper需要传递config才可使用。

2、修改容器最小拖动667。修复画布缩放下拖拽时与鼠标距离不一致。

3、innerContainerDragUp需要传递config。

## 0.2.0 

commander的传递进行修改，可以获得config了，commander不再从index中导出 ，需要使用时从config中获取。增加左侧类名，方便自定义。

## 0.1.10 

修改eslint依赖推荐


## 0.1.9 

增加全局body设置

## 0.1.8 

增加弹窗设置，移除modalContainer

## 0.1.7 

修改预览特殊条件显示，删除console
## 0.1.6 

调整初始缩放，画布初始比例，增加回正画布功能。
## 0.1.5 

删除未作按钮，增加fixed配置
## 0.1.4 

基础功能
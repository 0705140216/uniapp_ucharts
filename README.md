
## Project intro
```
该图表主要是基于canvas绘图制作,调用了u-charts.js组件
我把各个图表大致拆分12个部分左右

props传参

dataAs ==>为数据层
basicAs==>为通用基础项设置
xAxisAs===>x轴线基础设置(圆环饼图无轴线无需设置)
yAxisAss===>y轴线基础设置(圆环饼图无轴线无需设置)
legendAs===>图例设置
titleAs===>标题设置(仅圆环饼图无轴线需设置)
extraAs====> 拓展设置 //详情请看 http://doc.ucharts.cn/1172130
width===>图表宽度
height==>图表高度
labelKey==>配合dataAs,设置x轴key为可变变量(应对后端返回字段不同)(圆环饼图无轴线无需设置)
valueKey==>配合dataAs,设置y轴数据key为可变变量(应对后端返回字段不同)
canvasId==>canvas唯一ID,当一个页面中含有多个组件这个id必须设置不同


事件

touchstart 触摸点开始事件

touchmove 触摸点移动事件

touchend 触摸点结束动作

图表中会有默认配置,假设你想更改某个状态,参考组件中对应的解释即可
```
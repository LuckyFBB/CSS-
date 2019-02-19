# CSS-Demo

#### 项目介绍
记录一些简单的CSS处理

#### [九宫格](https://gitee.com/LuckyFBB/CSS-Demo/tree/master/nine-grid)  
问题：一个九宫格，鼠标hover上之后，边框显示为红色。  
解题思路  
1.使用flex布局，flex-wrap:wrap自定义换行。  
2.使用box-sizing:border-box,改变盒模型，将border算入width中。  
3.使用css选择器改变第一列的左边距。  
4.使用z-index来控制高层级。
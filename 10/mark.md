 #Flexbox 布局和网格布局的异同
 
 
 
 
 #以及分别适用于什么样的场景
 
 
 #MARKS
 * 大多数的Flexbox属性都应用于父容器的元素上
 * flex-flow equals to flex-direction plus flex-wrap
 
 * justify-content:决定了主轴的排列情况
 * align-items:决定了主轴元素对侧轴的依靠情况
 * align-content:决定侧轴（多行）的排列情况
 
 
 
 #Questions
 * ![align-items](http://cdn2.w3cplus.com/cdn/farfuture/oOEDDXBpXz5MYc-eOv0cCQUm9wtOhlENiGMMUUM3d88/mtime:1421035113/sites/default/files/styles/print_image/public/blogs/2013/flexbox-basics-4.jpg)
 测试情况，baseline等同于flexend。strech没有拉伸？
 
 #解题思路
 Q1:align-items:center ＋ justify-content:space-between.
 
 Q2: media querry + wrap => blue{order;-1} + align-items:flex-start + justify-content:space-between + align-content:
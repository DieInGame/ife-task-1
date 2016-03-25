#关于改变默认下拉菜单
以前我从来没有这么更改过，所以搜索了一下教程。
我觉得这一文很好
[How to Change the Default Select Drop-Down List with CSS](http://uplifted.net/programming/change-default-select-dropdown-style-just-css/)
******
即使如此，也要注意到一个问题。我们虽然能够改变SELECT选框的样式，
但是由于option是dom元素，由系统来负责渲染而不是html。

通俗的说，我们并不能借由CSS来改变option标签的样式，不同的浏览器之间是一定有区别的。

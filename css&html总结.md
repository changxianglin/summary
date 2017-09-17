### CSS & HTML 总结

* 不要使用 float 布局在屏幕变化的时候会造成往下掉的塌陷效果
```
设置父元素opacity：0.5，子元素不设置opacity，子元素会受到父元素opacity的影响，也会有0.5的透明度。
即使设置子元素opacity：1，子元素的opacity：1也是在父元素的opacity：0.5的基础上设置的，因此子元素的opacity还是0.5。
解决方法：为父元素设置background: rgba(0,0,0,0.5)。
```

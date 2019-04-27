# Animal_Trading_Cards-udacity
`两个空格代替<br>标签`
## card.html建议
* 代码第6行
[前端工程师纳米学位样式指南 - CSS (类型属性) ](https://github.com/udacity/frontend-nanodegree-styleguide-zh/blob/master/%E5%89%8D%E7%AB%AF%E5%B7%A5%E7%A8%8B%E5%B8%88%E7%BA%B3%E7%B1%B3%E5%AD%A6%E4%BD%8D%E6%A0%B7%E5%BC%8F%E6%8C%87%E5%8D%97%20-%20HTML%20.md#%E7%B1%BB%E5%9E%8B%E5%B1%9E%E6%80%A7)有建议指出：  
> 忽略样式表和脚本的类型属性。  
> 不要针对样式表和脚本使用类型属性。由于 HTML 意味着文本 /css 和文本 /javascript 为默认设置，在此类语境中无需设置类型属性。在老式浏览器中，也可以安全进行此项操作。  
建议去掉这里的 type 属性。  

* 代码第13行
> 棒极了。   
>为图片设置 alt 属性并添加了文字说明。👍 

* 代码第14行
在 [前端工程师纳米学位样式指南 - HTML](https://github.com/udacity/frontend-nanodegree-styleguide-zh/blob/master/%E5%89%8D%E7%AB%AF%E5%B7%A5%E7%A8%8B%E5%B8%88%E7%BA%B3%E7%B1%B3%E5%AD%A6%E4%BD%8D%E6%A0%B7%E5%BC%8F%E6%8C%87%E5%8D%97%20-%20HTML%20.md#html-%E5%BC%95%E5%8F%B7) 有建议指出：
>在引用属性值时，使用双引号。 
>记得用双引号将类名称 introduce 包裹起来～ 

## styles.css建议
* 代码第2行
### 建议
[前端工程师纳米学位样式指南 - CSS (声明区标点)](https://github.com/udacity/frontend-nanodegree-styleguide-zh/blob/master/%E5%89%8D%E7%AB%AF%E5%B7%A5%E7%A8%8B%E5%B8%88%E7%BA%B3%E7%B1%B3%E5%AD%A6%E4%BD%8D%E6%A0%B7%E5%BC%8F%E6%8C%87%E5%8D%97%20-%20CSS.md#%E5%A3%B0%E6%98%8E%E5%8C%BA%E6%A0%87%E7%82%B9)有建议指出：  
>最后一个选择符和声明区起始处的左大括号之间需加空格  

不推荐：  
```
.audio-block{   
    margin: 0;  
}
```
推荐：  
```
.audio-block {   
    margin: 0;   
}  
```
其他类似地方也都建议这样稍作修改。:)  

### 建议  
第3行代码   
在[前端工程师纳米学位样式指南 - CSS (属性名标点)](https://github.com/udacity/frontend-nanodegree-styleguide-zh/blob/master/%E5%89%8D%E7%AB%AF%E5%B7%A5%E7%A8%8B%E5%B8%88%E7%BA%B3%E7%B1%B3%E5%AD%A6%E4%BD%8D%E6%A0%B7%E5%BC%8F%E6%8C%87%E5%8D%97%20-%20CSS.md#%E5%B1%9E%E6%80%A7%E5%90%8D%E6%A0%87%E7%82%B9) 有建议指出：  
* 所有属性名冒号后均需添加空格，但属性和冒号间不加空格，以增加连贯性。  
不推荐：  
```
font-weight:bold;  
padding : 0;  
margin :0;  
```
推荐：  
```
font-weight: bold;  
padding: 0;   
margin: 0;  
```

## 建议
代码第15行  
棒极了  
卡片完成的很不错，鼓励你继续动手练习，尝试为卡片添加更多的样式。例如设置圆角、阴影效果等~  
延伸阅读：  
* [border-radius (by Mozilla)](https://developer.mozilla.org/zh-CN/docs/Web/CSS/Reference)
* [box-shadow (by Mozilla)](https://developer.mozilla.org/zh-CN/docs/Web/CSS/box-shadow)  

## 建议
一个小小的建议建议：  
现在 introduce 里面的文字有些太靠近边框了呢（下方截图有一个简单的对比），如果为其设置一些內边距（padding）也许会是一个不错的做法哦，比如 padding: 10px;。:)  
![图片1](https://udacity-reviews-uploads.s3.us-west-2.amazonaws.com/_attachments/63821/1528649759/Screen_Shot_2018-06-11_at_12.55.40_AM.png)  
![图片2](https://udacity-reviews-uploads.s3.us-west-2.amazonaws.com/_attachments/63821/1528649759/Screen_Shot_2018-06-11_at_12.55.40_AM.png)  
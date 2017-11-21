# chrome的一些使用技巧
## 查看页面元素的css样式
* **查看与隐藏元素**
在 Chrome 浏览器的 Elements 里面选中某个元素，按 h 可以隐藏该元素。
* **查看页面布局**
  ```
  [].forEach.call($$("*"),function(a){
    a.style.outline="1px solid #"+(~~(Math.random()*(1<<24))).toString(16)
  })
  ```
* **console.log**

```
console.log('%c我%c爱%c你','font-size:60px;color:red','font-size:40px;color:blue','font-size:20px;color:green')
```
```
console.log('%s 是世界上是踏实的程序猿','李云花')
console.log('1 + 1 = %d',2)
```
  >假设这里是一个引用话术
  * * * 
  一句话
  - - -
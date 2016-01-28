##Function
* 函数，本质上是一种代码的分组形式
* return : 函数通常会有返回值，如没有提供显示的返回值，js里面会默认返回undefined
* 在定义函数时，如果设定了参数，而在执行时没有传相应的参数，则没有传的参数javascript引擎会默认设定为undefined
* 预定义函数：
  1.  parseInt()
  2.  parseFloat()
  3.  isNaN()
  4.  isFinite()
  5.  encodeURI()/encodeURIComponent()
  6.  decodeURI()/decodeURIComponent()
  7.  eval()
* NaN === NaN 返回的是false，不存在自等， tpyeof NaN 为number
##Object
* 通常情况下不建议在键上加引号
* 以下集中情况需要在键上加引号：
  1.  如果属性名（键）是javascript保留字之一
  2.  属性名中包含空格或者其他特殊字符（除字母、数字及下划线以外的字符）
  3.  属性名以数字开头
```javascript
Object instanceof Object;   //true
Function instanceof Object; //true
Object instanceof Function; //true
Object.constructor -> function Function(){};
```

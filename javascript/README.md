##javascript Tips
####Tip1　checkout IE9 and below
```javascript
var agent = navigator.userAgent,
    isIE = agent.indexOf('MSIE') > -1 && agent.indexOf('Trident') > -1, //get IE10 and below
    verStr = '',
    ver = 0;
    if(isIE){
      verStr = agent.match(/MSIE\s+\d+\.\d+/g).toString();
      ver = parseFloat(verStr.match(/\d+\.\d_/g).toString());
      if(ver <= 9) console.log(ver); 
    }
```

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
###Tip2　check browser
```javascript
browser = function(){
    var agent = navigator.userAgent,
        isIE = agent.indexOf('Trident') > -1,
        isFF = agent.indexOf('Firefox') > -1,
        isEdge = agent.indexOf('Edge') > -1,
        isOpera = agent.indexOf('OPR') > -1,
        isChrome = agent.indexOf('Chrome') > -1,
        isSafari = agent.indexOf('Safari') > -1,
        
        browserType,
        verStr,
        ver;
}
```


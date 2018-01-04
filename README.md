# ol2_swipe  
a swipe control for openalyers2 |  卷帘控件

#### Usage:
```js
  var map = new new OpenLayers.Map(mapdiv);   
  var swipe = new OpenLayers.Control.Swipe({map: map}); //实例控件   
  map.addControls([swipe]);   //添加控件    
  swipe.activate(layer);     //激活控件,传layer指定上层被clip图层 
  swipe.deactivate();   //控件失效
```




## Color Picker module

Use:

* include: **picker.js**, **picker.css**, **img/sv.png**, **img/h.png**
* initialize with: 
```javascript
var picker = new Picker();
```
* add event to an element which will keep the color
```javascript
$('#someElement').on('click',function(e){
      picker.init($(this));
    });  
});
```

### Preview
![Preview image](/preview.jpg)
 

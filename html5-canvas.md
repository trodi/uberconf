html5 canvas
============
if canvas is supported, the content is ignored, if not supported, content used.
canvas is controlled by js

```js
var x = canvas.width/2;
var y = canvas.height/2;
var context = canvas.getContext('2d');
context.font = '32pt Arial';
context.textAlign = 'right';
context.fillStyle = 'orange';
context.fillText('Hello',x,y,);

context.globalAlpha = '0.3';
context.textAlign = 'left';
context.fillText('world',x,y);
```
can give visual cues with the transparency 
```js
context.moveTo(0,0);
context.lineTo(x,y);
context.lineTo(x * 2,0);
context.stroke();
```

only js glue code should be in the html file

questions
---------
* are there any js graphics engines? 
> webGL?
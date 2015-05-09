# ImageCrop4Mobile

ImageCrop4Mobile is a minimalist image cropping widget with no dependences for mobile web.

[Online Demo](http://aijc.net:90/ImageCrop4Mobile/)

![Online Demo](https://raw.githubusercontent.com/dolymood/ImageCrop4Mobile/master/qr.png)

### Usage 

```js
var ic = new ImageCrop(document.querySelector('.container'), './mei.jpg', {
  
  /* crop size */
  size: 200,
  
  /*
   If true, the crop area will be rendered as an ellipse
   instead of a rectangle.
   */
  circle: true,
  
  onChanged: function(areaInfo) {
    console.log(areaInfo);
  }
  
});
```
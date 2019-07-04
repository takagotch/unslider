### unslider
---
https://github.com/vladalive/Unslider

```css
.unslider {
  overflow: hidden;
}
  .unslider ul {
    position: relative;
  }
  .unslider li {
    float: left;
  }
```

```js
$('#slider').unslider();
$('#slider').unslider({
});
```

```json
{
  activeClass: 'active',
  arrows: true,
  speed: 250,
  delay: 2000,
  autoplay: true,
  easing: 'swing',
  afterSlider: function(){}
}
```

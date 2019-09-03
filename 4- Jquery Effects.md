# Jquery Effects

### jQuery hide() and show()

#### Example 1
```javascript
 $("#hide").click(function(){
  $("p").hide();
});

$("#show").click(function(){
  $("p").show();
}); 
```

#### Example 2
```javascript
$("button").click(function(){
  $("p").hide(1000);
});
```

#### Example 3
```javascript
$("button").click(function(){
  $("p").toggle();
}); 
```

#### Example 4
```javascript
$("button").click(function(){
  $("#div1").fadeIn();
  $("#div2").fadeIn("slow");
  $("#div3").fadeIn(3000);
}); 
```

#### Example 5
```javascript
$("button").click(function(){
  $("#div1").fadeOut();
  $("#div2").fadeOut("slow");
  $("#div3").fadeOut(3000);
}); 
```

#### Example 6
```javascript
$("button").click(function(){
  $("#div1").fadeToggle();
  $("#div2").fadeToggle("slow");
  $("#div3").fadeToggle(3000);
}); 
```

### Some other

* slideDown()
* slideUp()
* slideToggle()

### Animate

#### Example 7
```javascript
$("button").click(function(){
  $("div").animate({
    left: '250px',
    opacity: '0.5',
    height: '150px',
    width: '150px'
  });
}); 
```

**Note**: The jQuery stop() method is used to stop an animation or effect before it is finished.
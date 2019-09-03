# Jquery events

The term "fires/fired" is often used with events.

Examples:

* moving a mouse over an element
* selecting a radio button
* clicking on an element


#### Example 1
```javascript
$("p").click(function(){
  // action goes here!!
}); 
```

#### Example 2
```javascript
$("p").dblclick(function(){
  $(this).hide();
});
```

#### Example 3
```javascript
$("#p1").mouseenter(function(){
  alert("You entered p1!");
});
```

#### Example 4
```javascript
$("#p1").mousedown(function(){
  alert("Mouse down over p1!");
});
```

#### Example 5
```javascript
$("#p1").hover(function(){
  alert("You entered p1!");
},
function(){
  alert("Bye! You now leave p1!");
});
```

#### Example 6
```javascript
 $("input").focus(function(){
  $(this).css("background-color", "#cccccc");
});
```

#### Example 7
```javascript
$("input").blur(function(){
  $(this).css("background-color", "#ffffff");
});
```

#### Example 8
```javascript
$("p").on("click", function(){
  $(this).hide();
}); 
```

#### Example 9
```javascript
$("p").on({
  mouseenter: function(){
    $(this).css("background-color", "lightgray");
  },
  mouseleave: function(){
    $(this).css("background-color", "lightblue");
  },
  click: function(){
    $(this).css("background-color", "yellow");
  }
});
```
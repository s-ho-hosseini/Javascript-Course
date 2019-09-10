# Jquery html

## Get Content - text(), html(), and val()

#### Example 1
```javascript
$("#btn1").click(function(){
  alert("Text: " + $("#test").text());
});
$("#btn2").click(function(){
  alert("HTML: " + $("#test").html());
});
$("#btn1").click(function(){
  alert("Value: " + $("#test").val());
});
```

## attr()

#### Example 2
```javascript
$("button").click(function(){
  alert($("#w3s").attr("href"));
});
```

## Set Content - text(), html(), and val()

#### Example 3
```javascript
$("#btn1").click(function(){
  $("#test1").text("Hello world!");
});
$("#btn2").click(function(){
  $("#test2").html("<b>Hello world!</b>");
});
$("#btn3").click(function(){
  $("#test3").val("Dolly Duck");
});
$("button").click(function(){
  $("#w3s").attr("href", "https://www.w3schools.com/jquery/");
});
```

## Add element

append() 
prepend()
after()
before() 

## Remove element

remove()
$("p").remove(".test")

## jQuery Manipulating CSS

addClass()
removeClass()
toggleClass()
css()

## jQuery Dimension Methods

width()
height()
innerWidth()
innerHeight()
outerWidth()
outerHeight()



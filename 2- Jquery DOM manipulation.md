# Jquery DOM manipulation

    $(document).ready(function(){

    // jQuery methods go here...

    }); 


## jQuery Selectors
jQuery selectors are used to "find" (or select) HTML elements based on their name, id, classes, types, attributes, values of attributes and much more.

It's based on the existing CSS Selectors, and in addition, it has some own custom selectors.

    $("p") 

#### Tag selector

#### Example 1
```javascript
 $(document).ready(function(){
  $("button").click(function(){
    $("p").hide();
  });
});
```

#### Id selector

#### Example 2
```javascript
 $(document).ready(function(){
  $("button").click(function(){
    $("#test").hide();
  });
});
```

#### Class selector

#### Example 3
```javascript
 $(document).ready(function(){
  $("button").click(function(){
    $(".test").hide();
  });
});
```

### Other samples

| Syntax        |  Description                                              |
|---------------|-----------------------------------------------------------|
| $("*")        |  Selects all elements                                     |
| $(this)       |  Selects the current HTML element                         |
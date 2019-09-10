# Jquery Ajax

#### Example 1
```javascript
$("button").click(function(){
  $.get("demo_test.asp", function(data, status){
    alert("Data: " + data + "\nStatus: " + status);
  });
}); 
```

#### Example 2
```javascript
$("button").click(function(){
  $.post("demo_test_post.asp",
  {
    name: "Donald Duck",
    city: "Duckburg"
  },
  function(data, status){
    alert("Data: " + data + "\nStatus: " + status);
  });
}); 
```

#### Example 3
```javascript
$.ajax(
{ 
  type: 'POST',  
  url: 'Default.aspx/GetData',  
  data: '{ }', 
  contentType: 'application/json; charset=utf-8', 
  dataType: 'json',   
  success: function(msg) {  

  }
}
);
```


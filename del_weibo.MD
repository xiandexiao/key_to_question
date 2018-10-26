## 批量删除微博
```
    var s = document.createElement("script");
    
    s.setAttribute("src","https://lib.sinaapp.com/js/jquery/2.0.3/jquery-2.0.3.min.js");
    
    s.onload = function(){
	  var arrow_down = $(".screen_box");
	  var down_length = arrow_down.length;
	  var list = $(".layer_menu_list");
	  console.log("此页面共计： " + down_length + "条微博.");
	  for (var i = 0; i < down_length; i++) {
		  $(arrow_down[i]).css({"background-color":"red"})
		  list[i].setAttribute("display","block");
		  $('a[title="删除此条微博"]')[i].click();
		  $('a[action-type="ok"]')[i].click();
		  console.log("ok");
	  }
  }
   document.head.appendChild(s);
```

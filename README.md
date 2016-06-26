# html-menu
<!DOCTYPE html>
<html>
<head>
<title> Home</title>
<body lang="en" id="main_container", style="background:#995501;">

<style>
.wrapper {overflow: auto;}

#main {margin-left: 4px;}

#leftsidebar {
    float: none;
    width: auto;
}

#menulist {
    margin: 0;
    padding: 0;
}

.menuitem {
    background: #CDF0F6;
    border: 1px solid #d4d4d4;
    border-radius: 50%;
    list-style-type: none;
    margin: 4px;
    padding: 2px;
}

@media screen and (min-width: 480px) {
    #leftsidebar {width: 200px; float: left;}
    #main {margin-left: 216px;}
}
</style>

<div style="solid #3366ff; float:center; background:#996323; width: 250px; height:25px">
<center>
<div class="wrapper">
  <div id="leftsidebar">
    <ul id="menulist">
      <li class="menuitem">Menu-item 1</li>
      <li class="menuitem">Menu-item 2</li>
      <li class="menuitem">Menu-item 3</li>
      <li class="menuitem">Menu-item 4</li>
      <li class="menuitem">Menu-item 5</li>
   </ul>
  </div>
  </center>
  
</head>
<body>
</html>

<!DOCTYPE HTML>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
    ul {
      list-style-type:none;
      margin:0;
      padding:0;
      overflow:hidden;
      background-color: #367;
      }
      li {float:left;}
      
      li a, .droptbn {
      display:inline-block;
      color:gold;
      font-family:verdana;
      text-align: center;
      padding: 14px 16px;
      text-decoration: none;
      }
      
      li a:hover, .dropdown:hover, .droptbn {
      background-color:pink;
      text-decoration:none;
      color:white;
      }
      li .dropdown {
      display:inline-block;

     }
      .dropdown-content {
      display:none;
      position:absolute;
      bacgkound-color:#f3f4f5;
      min-width:160px;
      box-shadow: 0px 8px 16px 0px rgba (0,0,0,0.2);
      z-index:1;
      }
      dropdown-content a {
      color:black;
      padding:12px 16px;
      text-decoration:none;
      display:block;
      text-align:left;
     }
      .dropdown-content a:hover {background-color: #f2f3f4}
      .dropdown:hover .dropdown-content {
      display:block;
      }
      
    </style>
  </head>
  <body>
   <ul>
     <li><a href="#home">Home</a></li>
     <li class="dropdown">
       <a href="javascript:void(0)" class="droptbn">News</a>
       <div class="dropdown-content">
         <a href="#">Link 1</a>
         <a href="#">Link 2</a>
       </div>
       </li>
      <li><a href="#contact">Contact Us!</a></li>
      <li><a href="#about">About</a></li>
    </ul>
  </body>
</html>

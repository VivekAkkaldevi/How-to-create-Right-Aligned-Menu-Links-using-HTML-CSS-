# How to create Right Aligned Menu Links using HTMLCSS
copy the code and just paste in your HTML document

Code by Vivek Akkaldevi
www.hixeltechshub.com

      
 #HTML Code
      
    <!-- Navbar items -->
    <div id="navlist"> 
        <a href="#">Home</a> 
        <a href="#">Our Products</a> 
        <a href="#">Careers</a> 
        <div class="navlist-right"> 
        <a href="#">About Us</a> 
        <a href="#">Contact Us</a> 
        </div> 
    </div> 
  
    <!-- logo with tag -->
    <div class="content"> 
        <h1 style="color:green; padding-top:40px;"> 
           Hixeltechshub 
        </h1> 
      
        <b>Hixel techs</b> 
          
        <p> 
            Here you can Create a Nav with right side aligned content. 
        </p> 
    </div> 


#CSS Code

  
           

    #navlist a { 
        float:left; 
        display: block; 
        color: #f2f2f2; 
        text-align: center; 
        padding: 12px; 
        text-decoration: none; 
        font-size: 15px; 
    } 
    .navlist-right{ 
        float:right; 
    } 
  

    #navlist a:hover { 
        background-color: #ddd; 
        color: black; 
    } 


#navlist { 
        background-color: #0074D9; 
        position: absolute; 
        width: 100%; 
    } 

<!DOCTYPE html>

<html>
    
       <body style="background-color:chartreuse;">
           
<head>
            
<style>
    
ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
    width: 200px;
    background-color: #f1f1f1;
    border: 1px solid #555;
}

li a {
    display: block;
    color: #000;
    padding: 8px 16px;
    text-decoration: none;
}

li {
    text-align: center;
    border-bottom: 1px solid #555;
}

li:last-child {
    border-bottom: none;
}

li a.active {
    background-color: #4CAF50;
    color: white;
}

li a:hover:not(.active) {
    background-color: #555;
    color: white;
}
    
</style>
    
    <script> 
         document.addEventListener("deviceready", onDeviceReady, false);    <!-- VIBRATE -->
            function onDeviceReady() {
            console.log(navigator.vibrate([3000]));
            }

    </script>
    
</head>
           
<body>

    <h1 style="font-family: fantasy;"> Plant Monitoring System</h1>
    
<p></p>

<ul>
  <li><a class="active" href="#1">Welcome</a></li>
  <li><a href="#2">How To Use</a></li>
  <li><a href="#3">Plants</a></li>
    <li><a href="#4">Statistics</a></li>
    <li><a href="#5">Exit</a></li>
  <li><a href="#6">Mini Game</a></li>
  <li><a href="#7">Waiting Area</a></li>  
</ul>

</body>     
           <h2 id="1" style="color:green;" >Welcome  <button onclick="myFunction()"> Press </button></h2> 
           

<p id="demo"></p>
           <script>
           
                      function myFunction() {    <!-- Checks the clock / Welcome-->
    var hour = new Date().getHours(); 
    var greeting;
                              
    if (hour < 18) {
        greeting = "Good day! Welcome to Dans, Nicks, And Jims Plant MS app. We hope that your stay will be comfortable and we hope to see you back very soon!";
    } else {
        greeting = "Good evening! Welcome to Dans, Nicks, And Jims Plant MS app. We hope that your stay will be comfortable and we hope to see you back very soon!";
    }
                             
    document.getElementById("demo").innerHTML = greeting;
        
}   
           </script>
           <h2 id="2" style="color:green;" >How To Use</h2> 
           
           <P> 1. Click on the name of a plant to check what is needed to keep it healty.</P>
           <P> 2. Click on Statistics to see what you need to do with your plant </P>
           <P> 3. Click Mini Game to make yourself busy while waiting for the results to come in. </P>
           <P> 4. Click on the Waiting Area to relax and look at falling rain, while waiting for the results to come in.</P>
           
            <h2 id="3" style="color:green;" >Plant Options</h2> 
             
        <p style="color:darkred;"> 1.     <a href="javascript:alert('Temperature: 13 - 27°C;     Light: High;     Water: Moderately dry soil;     Humidity: Low;');">Aloe Vera</a> </p>  
        <p style="color:red;">   2.  <a href="javascript:alert('Temperature: 18 - 25°C;     Light: Med-high;     Water: Evenly moist soil;     Humidity: Average;');">Rose</a> </p>  
        <p style="color:yellow;"> 3. <a href="javascript:alert('Temperature: 20 - 27°C;     Light: High;     Water: Evenly moist soil;     Humidity: High;');">Tomato </a> </p>  
        <p style="color:purple;">   4. <a href="javascript:alert('Temperature: 18 - 24°C;     Med-high;     Water: Evenly moist soil;     Humidity: Average;');"> Spider Plant </a> </p>  
        <p style="color:green;"> 5.  <a href="javascript:alert('Temperature: 26 - 30°C;     Light: Low-high;     Water: Moderately dry soil;     Humidity: Average;');">Snake Plant</a> </p>  
        <p style="color:orangered;">   6.  <a href="javascript:alert('Temperature: 13 - 21°C;     Light: Med-high;     Water: Evenly moist soil;     Humidity: Average- High;');">English Ivy </a> </p>  
        <p style="color:deeppink;"> 7.<a href="javascript:alert('Temperature: 7 - 30°C;     Light: Low;     Water: Evenly moist soil;     Humidity: Average;');"> Cast Iron Plant </a> </p>  
        <p style="color:darkred;">   8.  <a href="javascript:alert('Temperature: 13 - 16°C;     Light: High;     Water: Evenly moist soil;     Humidity: Average;');">Sunflower </a> </p>  
         <p style="color:deepskyblue;"> 9.  <a href="javascript:alert('Temperature: 15 - 21°C;     Light: High;     Water: Moderately dry soil;     Humidity: Average;');">Dill Plant</a> </p>  
           
           <h2 id="4" style="color:green;" >Statistics</h2> 
           <P style="color:darkred;">Temperature: calculating...calculating...</P>
           <P style="color:darkred;">Light: calculating......</P>
           <P style="color:darkred;">Water: calculating...calculating...calculating...</P>
           <P style="color:darkred;">Humidity: calculating..............calculating...............</P>
           
                      <h2 id="5" style="color:green;" >Exit</h2> 
           <P>Don't forget to send your results to Facebook using our app! Have a great day!</P>
           <a href="66">Log In:</a><P>
           
            <h2 id="6" style="color:green;">Mini Game</h2> 
           <P>Here's a small game from the genius creators of "Hello", "Goodbye", "What's that in my pocket", and "Huh?":  </P>
           <P style="color:purple;"> Rules Of The Game: </P>
               
    <h2 id="7" style="color:green;">Waiting Area</h2> 
            <P style="color:blue;"> Turn on music:  <button onclick="myFunction()"> On/Off </button></P>
          
<marquee style="z-index:2;position:absolute;left:20;top:81;height:370;"scrollamount="1" direction="down"><img src="http://www.transparentpng.com/thumb/raindrops/raindrops-png-transparent-image--3.png" /></marquee><marquee style="z-index:2;position:absolute;left:102;top:107;height:419;"scrollamount="5" direction="down"><img src="http://www.transparentpng.com/thumb/raindrops/raindrops-png-transparent-image--3.png" /></marquee><marquee style="z-index:2;position:absolute;left:220;top:111;height:336;"scrollamount="5" direction="down"><img src="http://www.transparentpng.com/thumb/raindrops/raindrops-png-transparent-image--3.png" /></marquee><marquee style="z-index:2;position:absolute;left:1;top:116;height:363;"direction="down"><img src="http://www.transparentpng.com/thumb/raindrops/raindrops-png-transparent-image--3.png" /></marquee><marquee style="z-index:2;position:absolute;left:286;top:111;height:12;"scrollamount="3" direction="down"><img src="http://www.transparentpng.com/thumb/raindrops/raindrops-png-transparent-image--3.png" /></marquee><marquee style="z-index:2;position:absolute;left:140;top:74;height:372;"scrollamount="3" direction="down"><img src="http://www.transparentpng.com/thumb/raindrops/raindrops-png-transparent-image--3.png" /></marquee><marquee style="z-index:2;position:absolute;left:317;top:1;height:135;"scrollamount="3" direction="down"><img src="http://www.transparentpng.com/thumb/raindrops/raindrops-png-transparent-image--3.png" /></marquee><marquee style="z-index:2;position:absolute;left:288;top:38;height:421;"scrollamount="3" direction="down"><img src="http://www.transparentpng.com/thumb/raindrops/raindrops-png-transparent-image--3.png" /></marquee><marquee style="z-index:2;position:absolute;left:111;top:101;height:268;"scrollamount="4" direction="down"><img src="http://www.transparentpng.com/thumb/raindrops/raindrops-png-transparent-image--3.png" /></marquee><marquee style="z-index:2;position:absolute;left:107;top:74;height:264;"scrollamount="3" direction="down"><img src="http://www.transparentpng.com/thumb/raindrops/raindrops-png-transparent-image--3.png" /></marquee><marquee style="z-index:2;position:absolute;left:240;top:114;height:22;"scrollamount="3" direction="down"><img src="http://www.transparentpng.com/thumb/raindrops/raindrops-png-transparent-image--3.png" /></marquee><marquee style="z-index:2;position:absolute;left:50;height:424;"scrollamount="2" direction="down"><img src="http://www.transparentpng.com/thumb/raindrops/raindrops-png-transparent-image--3.png" /></marquee><marquee style="z-index:2;position:absolute;left:54;top:2;height:467;"scrollamount="2" direction="down"><img src="http://www.transparentpng.com/thumb/raindrops/raindrops-png-transparent-image--3.png" /></marquee><marquee style="z-index:2;position:absolute;left:170;top:53;height:142;"scrollamount="4" direction="down"><img src="http://www.transparentpng.com/thumb/raindrops/raindrops-png-transparent-image--3.png" /></marquee><marquee style="z-index:2;position:absolute;left:232;top:113;height:17;"scrollamount="1" direction="down"><img src="http://www.transparentpng.com/thumb/raindrops/raindrops-png-transparent-image--3.png" /></marquee><marquee style="z-index:2;position:absolute;left:231;top:106;height:132;"scrollamount="1" direction="down"><img src="http://www.transparentpng.com/thumb/raindrops/raindrops-png-transparent-image--3.png" /></marquee><marquee style="z-index:2;position:absolute;left:313;top:37;height:490;"scrollamount="1" direction="down"><img src="http://www.transparentpng.com/thumb/raindrops/raindrops-png-transparent-image--3.png" /></marquee><marquee style="z-index:2;position:absolute;left:27;top:78;height:32;"direction="down"><img src="http://www.transparentpng.com/thumb/raindrops/raindrops-png-transparent-image--3.png" /></marquee><marquee style="z-index:2;position:absolute;left:291;top:91;height:329;"scrollamount="1" direction="down"><img src="http://www.transparentpng.com/thumb/raindrops/raindrops-png-transparent-image--3.png" /></marquee><marquee style="z-index:2;position:absolute;left:24;top:14;height:88;"scrollamount="5" direction="down"><img src="http://www.transparentpng.com/thumb/raindrops/raindrops-png-transparent-image--3.png" /></marquee><marquee style="z-index:2;position:absolute;left:228;top:32;height:18;"scrollamount="1" direction="down"><img src="http://www.transparentpng.com/thumb/raindrops/raindrops-png-transparent-image--3.png" /></marquee>
           
           <script> 
           function playStream() {
    mp3file = new Media("/android_asset/Beck - Colors.mp3",
            function() {
                alert("playAudio():Audio Success");
            },
                function(err) {
                    alert(err);
            }
            );
          mp3file.play();
           }
               
            </script>    
           <br>
           <br>
           <br>
           <br>
           <br>
           <br>

    
</html>

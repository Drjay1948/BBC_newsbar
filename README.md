# BBC_newsbar
Code for BBC project
<!doctype html>
<html>
<head>
    <title>Jim's BBC Project</title>

    <meta charset="utf-8" />
    <meta http-equiv="Content-type" content="text/html; charset=utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
	<style type="text/css">
      
     body {
     
     	margin:0;
     	font-family:arial,helvetica,sans-serif;;
     }
     
      #topbar {
     	background-color:#7A0000;
      	width:100%;
      	height:40px;
      	color:white;
      	
      }
      
  	 .fixedwidth {
  	   	width:1050px;
  	   	margin:0 auto;
  	   
  	 }
   
   	  #logodiv {
			padding-top:5px;
			float:left;	
			border-right:1px solid #990000;
			padding-right:10px;
			padding-bottom:6px;	
   	  }
   	  
   	  #signindiv {
   	  	font-weight:bold;
   	  	padding: 6px 80px 9px 20px;
   	  	font-size:0.7em;
   	  	float:left;
   	  	border-right:1px solid #990000;
   	  } 
   	  
   	  #signindiv img {
   	  		position:relative;
   	  		top:3px
   	  }
   	  
   	  #topmenudiv {
   	  		float:left;
   	  }
   	  
   	  #topmenudiv ul {
   	  	margin:0px;
   	  	padding: 0 ;
   	  }
   	  
   	  #topmenudiv li {
   	  	list-style:none;
   	  	font-weight:bold;
   	  	font-size:0.9em;
   	  	border-right:1px solid #990000;
   	  	height:100%;
   	  	Padding: 10px 20px 12px 20px;
   	  	float:left;
   	  }
   	  
   	  #searchdiv {
   	  	float:left;
   	  	padding:5px 0 10px 10px;
   	  	
   	  	
   	  }
   	  	
   	  #searchdiv input {
   	  	height:25px;
   	  	border:none;
   	  	padding:3px 0 3px 10px;
   	  	font-size:0.9em;
   	  	background-image:url("images/magnify.png");
   	  	background-repeat:no-repeat;
   	  	background-position: right center;
   	  	background-color:#E4E4E4;
   	  }
   	  
   	  
   	  
   	  .break {
   	  	clear:both;
   	  	}
   	  
   	  
   	  
   	  #newsbar {
     	background-color:#990000;
      	width:100%;
      	height:80px;
      	color:white;
      	
      }
   	  
   	  #newsbar p {
   	  	margin:0;
   	  	padding:12px;
   	  	
   	  }
   	  
   	  #newsheader {
   	  	font-size:3em;
   	  }
   	   
   	   #uk {
   	   	font-size:0.7em;
   	   }
   	  
	</style>   


</head>

<body>

	<div id="container"> 
	
		<div id="topbar">
		
			<div class="fixedwidth">
			
			<div id="logodiv">
				
				<img src="images/bbclogo.png" /> 
			
		</div>
			
			<div id="signindiv">
			
			<img src="images/signin.png" /> Sign in
			
			</div>
			
			<div id="topmenudiv">
			
				<ul>
					<li>News</li>
					<li>Sport</li>
					<li>Weather</li>
					<li>iPlayer</li>
					<li>TV</li>
					<li>Radio</li>
					<li>More...</li>
				</ul>
			
			
			</div>
			<div id="searchdiv">
				
					<input type="text" placeholder="search" />
			
			</div>
			
		</div>
		
		<div class="break"></div>
		
		
		<div id="newsbar">
			
			<div class="fixedwidth">
			
				<p id="newsheader">NEWS<span id="uk">UK</span></p>
		
			</div>
		
		
	</div>
		
		
		

</body>

</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>gym</title>
    <style>
        body{
            color: white;
            margin: 0px;
            padding: 0px;
            background: url(fitness-photographer.jpg);
            background-repeat: no-repeat;
            font-family:'Times New Roman', Times, serif;
            font-weight: bolder;
            
        }
        #lol{
           
            text-align: center;
            background-color: rgba(90, 78, 78, 0.791);
            color: white;
            margin: 0px;
            width: 1500px;
        }
        #left{
            font-family: Georgia, 'Times New Roman', Times, serif;
            font-weight: bolder;
            text-align: center;
            display: inline-block;
            position: absolute;
            left: 50px;
            height: 100px;
            width: 150px;
            background: url(gym4.jpg);
            

        }
        #mid{
            
            display: inline block;
            width: 800px;
            height: 50px;
            margin: auto;
            position: absolute;
            top: 25px;
            left: 500px;
            float: left;


        }
        #right{
            display: inline-block;
            
            position: absolute;
            top: 20px;
            right: 4px;
            width: 300px;
            
        }
        .navbar li{
            color: white;
            list-style: none;
            margin: 0px;
            display: inline-block;
        }
        .navbar li a{
            text-decoration: none;
            color: white;
            margin: 0px;
            padding: 15px 30px 0px 5px;
            font-size: 20px;
        }
        .navbar li a:hover,.navbar li a:active{
            color: gray;
            text-decoration: underline;

        }
        .navbar ul{
            overflow: auto;
        }
        .bts{
            padding: 15px 15px 15px 15px;
            font-size: 20px;
            color: white;
            background-color: gray;
            margin: 5px;
            border-radius: 10px;
            font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
            font-weight: bolder;
        
        }
        .bts:hover{
            background-color: rgb(214, 198, 198);
            
        }
        .container{
            border: 4px solid rgb(241, 241, 245);
            border-radius: 15px;
            position: absolute;
            top: 200px;
            left: 100px;
            width: 400px;
            height: 500px;
            text-align: center;
        }
        .lol input{
            width: 300px;
            padding: 10px;
            margin: 5px;
            font-size: 20px;
            border-radius: 8px;
            font-style: italic;
        }
        .container button{
            color: white;
            width:100px;
            height: 50px;
            background-color: black;
            font-size: 20px;
        }

    </style>
    
</head>
<body>
    <div id="lol">
        <span>7044258726</span> free pass for 3 days
    </div>
   <header class="header">
    <div id="left">
       <img src="gym5.png" alt="" height="100" width="100"><br>
       VIC FITNESS
    </div>
    <div id="mid">
        <nav class="navbar">
        <ul>
            <li><a href="">HOME</a></li>
            <li><a href="">DOCUMENTATION</a></li>
            <li><a href="">PICTURES</a></li>
            <li><a href="">ABOUT</a></li>
         
        </ul>
       </nav>
    </div>
    <div id="right">
        <button class="bts">Helpline</button>
        <button class="bts">Email us</button>
    </div>
   </header>
   <div class="container">
    <h1>Form To Join Gym</h1>
    <form action=""></form>
    <div class="lol">
     <input type="text" placeholder="enter your name">
    </div>
    <div class="lol">
     <input type="text" placeholder="Age">
    </div>
    <div class="lol">
     <input type="text" placeholder="Address">
    </div>
    <div class="lol">
     <input type="text" placeholder="phone number">
    </div>
    <div class="lol">
     <input type="text" placeholder="height(cm)">
    </div>
    <div class="lol">
     <input type="text" placeholder="weight(kg)">
    </div>
    <button class="btn">Submit</button>
   </div>
    
</body>
</html># GYM_front_website

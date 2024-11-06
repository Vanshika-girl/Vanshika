<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        
    ul {
          list-style-type: none;
          margin: 0;
          padding: 0;
          padding-top: 10px;
          overflow: hidden;
          background-color: lavender;
        }
        
        
        
        li a {
          display: block;
          color: black;
          float: right;
          text-align: center;
          padding: 14px 16px;
          text-decoration: none;
          border: 2px solid lavender;
          border-radius: 10px;
        }
        li a:hover{background-color: rgb(212, 212, 246);}
        .b{display: block;
          color: black;
          text-align: center;
          padding: 14px 16px;
          text-decoration: none;
        float: left;
    font-size: xx-large;
  }
  
    .c{
        display: block;
          color: black;
          float: right;
          text-align: center;
          padding: 14px 16px;
          text-decoration: none;
          border:2px solid rgb(206, 206, 244);
          border-radius: 10px;
          background-color: rgb(152, 152, 211);

    }
    .c:hover{background-color: #d9376e;
    color: white;}
    .d{
        border: 2px solid lavender;
        margin-top: 9%;
        height: 50%;
        width: 30%;
        margin-left: 10%;

    }
    .e{color: black;
        text-align: center;
          padding: 14px 16px;
          text-decoration: none;
          border:3px solid black;
          border-radius: 10px;
          background-color: rgb(152, 152, 211);
       
    }
    .e:hover{background-color: black;
        color: white;}
        * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    
   
    .container {
      font-family: Arial, sans-serif;
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
      max-width: 1200px;
      display: flex;
      align-items: center;
      gap: 40px;
      padding: 20px;
    }

   
    .text-section {
      flex: 1;
    }

    .text-section h1 {
      font-size: 36px;
      color: #333;
      margin-bottom: 20px;
    }

    .text-section p {
      font-size: 18px;
      color: #666;
      margin-bottom: 20px;
    }

    .cta-button {
      display: inline-block;
      background-color: rgb(140, 140, 196);
      color: white;
      padding: 10px 20px;
      text-decoration: none;
      border-radius: 5px;
      font-size: 16px;
      font-weight: bold;
    }

    
    .image-section {
      flex: 1;
      display: flex;
      justify-content: center;
    }

    .image-section img {
      width: 150%;
      border-radius: 10px;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
      margin-left: 100%;
    }
    .cta-button:hover{background-color:#d9376e;}
    </style>
</head>
<body style="background-color: lavender;">
    
    <ul>
        <li class="b"><strong>STUDY BUDDY</strong></li>
        <li><a  href="http://127.0.0.1:5500/features.html">FEATURES</a></li>
        <li><a href="http://127.0.0.1:5500/contact.html">CONTACT</a></li>
        <li><a href="http://127.0.0.1:5500/pricing.html">PRICING</a></li>
        <li><a class="c" href="http://127.0.0.1:5500/start1.html">Start for free</a></li>
      </ul>
      <div class="container">
      <div class="text-section">
      <h1 style="font-size: 350%;">Organize your work and life, finally.</h1>
      <p style="font-size: 150%;"><mark style="background-color: rgb(155, 155, 209);">Simplify life for both you and your team with the world’s #1 task manager and to-do list app.</mark></p>
      <a class="cta-button" href="http://127.0.0.1:5500/start1.html">Start for free</a>
    </div>
    <div class="image-section">
    <img  src="pic5.png" alt="pic">
    </div>
    </div>
      
</body>
</html>

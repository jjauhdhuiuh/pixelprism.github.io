<!DOCTYPE html>
<html>
<head>
  <title>Aditi - Developer Portfolio</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;700&display=swap" rel="stylesheet">
  <style type="text/css">
    * {
      margin: 0;
      padding: 0;
    }
    body{
      background-color: rgb(0, 0, 33);
      color: white;
      font-family: 'poppins', sans-serif;
    }

    nav{
      display: flex;
      justify-content: space-around;
      align-items: center;
      height: 80px;
      background-color: rgb(18, 18, 62);
    }
    nav ul{
      display:flex;
      justify-content: center;
    }

    nav ul li{
      list-style: none;
      margin: 0 23px;
    }

    nav ul li a{
      text-decoration: none;
      color: white;
    }

    nav ul li a:hover{
      color:rgb(153, 153, 224);
      font-size: 1.01rem;
    }

    main hr{
      border: 0;
      background: #9c97f1;
      height: 2px;
      margin: 60px 84px;
    }

    .left{
      font-size: 1.5rem;
    }

    .firstSection{
      display: flex;
      justify-content: space-around;
      align-items: center  ;
      margin: 110px 0;
    }
    .firstSection > div{
      width: 30%;
    }
    
    .leftSection{
      font-size: 2.5rem;
    }
 
    .leftSection .buttons{
      padding: 16px 0;
    }

    .leftSection .btn{
      padding: 12px;
      background: black;
      color: white;
      border: 2px solid white;
      border-radius: 6px;
      font-size: 20px;
      cursor: pointer;

    }

    .rightSection img{
      width: 80%;
    }
    .purple{
      color: blueviolet;
    }

    .text-gray{
        color: dimgray;
    }

    #element{
      color: blueviolet;
    }

    .secondSection{
        max-width: 80vw;
        margin: auto;
        height: 80vh;
    }
    .secondSection h1{
      font-size: 1.9rem;
    }

    .secondSection .box{
      background: white;
      width: 85vw;
      height: 2px;
      margin: 56px 0;
      display: flex;
    }

    .secondSection .vertical{
      height: 93px;
      width: 1px;
      background-color: white;
      margin: 0 115px;
    }

    .image-top{
      width: 23px;
      position: relative;
      top: -32px;
      left: -9px;
    }

    .vertical-title{
      position: relative;
      top: 75px;
      width: 150px;
    }

    .vertical-desc{
      position: relative;
      top: 86px;
      color: dimgray;
      width: 150px;
      font-size: 10px;
    }

    footer{
      background-color: #160040;
    }

    .footer{
      display: flex;
      padding: 23px 122px;
      justify-content: space-evenly;
    }

    .footer ul{
      list-style: none;
    }

    .footer > div{
      width: 233px;
    }

    footer .footer-rights{
      text-align: center;
      color: dimgray;
      padding: 12px 0;
    }
  </style>
</head>
<body>
  <header>
    <nav>
      <div class="left">Aditi's Portfolio</div>
      <div class="right">
        <ul>
          <li><a href="/">Home </a></li>
          <li><a href="/">About </a></li>
          <li><a href="/">Services</a></li>
          <li><a href="/">Projects </a></li>
          <li><a href="/">Contact Me </a></li>
        </ul>
      </div>
    </nav>
  </header>

  <main>
    <section class="firstSection">
      <div class="leftSection">
          Hi, My name is <span class="purple">Aditi</span> 
          <div>and I am a passionate</div> 
          <span id="element"></span>
          <div class="buttons">
            <button class="btn">Download Resume</button>
            <button class="btn">Visit GitHub</button>
          </div>
      </div>
      <div class="rightSection">
          <img src="C:\Users\ADITI\OneDrive\Desktop\portfolio\Web.jpg">
      </div>
    </section>
    <hr>
    <section class="secondSection">
      <span class="text-gray">What I have done so far</span>
      <h1>Work Experience</h1>

      <div class="box">
        <div class="vertical"> <img class="image-top" src="C:\Users\ADITI\OneDrive\Desktop\portfolio\HTML.jpg" alt=""> <div class="vertical-title">
          HTML Developer (2015-2017)
        </div>
        <div class="vertical-desc">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus blandit dignissim aliquet. Nulla rutrum turpis eget lacinia eleifend. Mauris non justo eu leo auctor ultricies. Sed feugiat nisi nec justo pulvinar bibendum. 
        </div>
      </div>
        <div class="vertical"> <img class="image-top" src="C:\Users\ADITI\OneDrive\Desktop\portfolio\node.js.jpg" alt=""> <div class="vertical-title">
          Node.js Developer (2017-2019)
        </div>
        <div class="vertical-desc">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus blandit dignissim aliquet. Nulla rutrum turpis eget lacinia eleifend. Mauris non justo eu leo auctor ultricies. Sed feugiat nisi nec justo pulvinar bibendum.
        </div>
      </div>
      <div class="vertical"> <img class="image-top" src="C:\Users\ADITI\OneDrive\Desktop\portfolio\Ai.jpg" alt=""> <div class="vertical-title">
          Artificial Intelligence (2019-2020)
        </div>
        <div class="vertical-desc">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus blandit dignissim aliquet. Nulla rutrum turpis eget lacinia eleifend. Mauris non justo eu leo auctor ultricies. 
        </div>
      </div>
      <div class="vertical"> <img class="image-top" src="C:\Users\ADITI\OneDrive\Desktop\portfolio\Chat GPT.jpg" alt=""> <div class="vertical-title">
          ChatGPT(2020-2021)
        </div>
        <div class="vertical-desc">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus blandit dignissim aliquet. Nulla rutrum turpis eget lacinia eleifend. Mauris non justo eu leo auctor ultricies. Sed feugiat nisi nec justo pulvinar bibendum.  
        </div>
      </div>
      <div class="vertical"> <img class="image-top" src="C:\Users\ADITI\OneDrive\Desktop\portfolio\content creator.jpg" alt=""> <div class="vertical-title">
          Content Creator (2020-2021)
        </div>
        <div class="vertical-desc">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus blandit dignissim aliquet. Nulla rutrum turpis eget lacinia eleifend. Mauris non justo eu leo auctor ultricies. Sed feugiat nisi nec justo pulvinar bibendum.  
        </div>
      </div>
     </div>
    </section>

  </main>

  <footer>
    <div class="footer">
      <div class="footer-first"></div> 
            <h3>Aditi's Developer Portfolio</h3>
      <div class="footer-second">
        <ul>
          <li>Home</li>
          <li>About</li>
          <li>Contact</li>
          <li>Help</li>
        </ul>
      </div>
      <div class="footer-third">
        <ul>
          <li>Home</li>
          <li>About</li>
          <li>Contact</li>
          <li>Help</li>
        </ul>
      </div>
      <div class="footer-fourth">
        <ul>
          <li>Home</li>
          <li>About</li>
          <li>Contact</li>
          <li>Help</li>
        </ul>
      </div>
    </div>
    <div class="footer-rights">
      Copyright &#169; www.aditisportfolio.com | All rights reserved
    </div>
  </footer>
  <script src="https://unpkg.com/typed.js@2.0.16/dist/typed.umd.js"></script>
  <!-- Setup and start animation! -->
  <script>
    var typed = new Typed('#element', {
      strings: ['<i>Web Developer</i>', '<i>Graphic Designer</i>', '<i>Web Designer</i>', '<i>Video Editor</i>'],
      typeSpeed: 50,
    });
  </script>
</body>
</html>

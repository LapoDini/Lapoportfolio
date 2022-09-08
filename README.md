
<html>
<head>
  <title>Lapo Dini</title>
   <link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
   <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
   <link rel="stylesheet" href="https://fonts.googleapis.com/icon?family=Material+Icons">
    <!--Colour palette from W3 School colour generator-->
    <meta name="viewport" content="width:device-width, initial-scale=1">
    <style>
        .w3-theme-l5 {color:#000 !important; background-color:#fbfaf8 !important}
        .w3-theme-l4 {color:#000 !important; background-color:#f2eee8 !important}
        .w3-theme-l3 {color:#000 !important; background-color:#e5ddd1 !important}
        .w3-theme-l2 {color:#000 !important; background-color:#d8ccba !important}
        .w3-theme-l1 {color:#000 !important; background-color:#ccbba4 !important}
        .w3-theme-d1 {color:#fff !important; background-color:#b39a78 !important}
        .w3-theme-d2 {color:#fff !important; background-color:#a78a62 !important}
        .w3-theme-d3 {color:#fff !important; background-color:#957954 !important}
        .w3-theme-d4 {color:#fff !important; background-color:#7f6848 !important}
        .w3-theme-d5 {color:#fff !important; background-color:#6a573c !important}

        .w3-theme-light {color:#000 !important; background-color:#fbfaf8 !important}
        .w3-theme-dark {color:#fff !important; background-color:#6a573c !important}
        .w3-theme-action {color:#fff !important; background-color:#6a573c !important}

        .w3-theme {color:#000 !important; background-color:#c0ab8e !important}
        .w3-text-theme {color:#c0ab8e !important}
        .w3-border-theme {border-color:#c0ab8e !important}

        .w3-hover-theme:hover {color:#000 !important; background-color:#c0ab8e !important}
        .w3-hover-text-theme:hover {color:#c0ab8e !important}
        .w3-hover-border-theme:hover {border-color:#c0ab8e !important}
    </style>

</head>

<body class="w3-theme-l3 w3-content" style="max-width:1600px;">

<!--Side bar navigation-->  
  <nav class="w3-sidebar w3-collapse w3-theme-light w3-animate-left" style="z-index: 3; width: 300px; display: none;" id="mySidebar">
      <div class="w3-container w3-center w3-padding-top-24">
        <img src="Images/lapoprofilo.jpg" class="w3-circle w3-hover-border" style="max-width: 60%">
        <a href="#" onclick="w3_close()" class="w3-hide-large w3-right w3-padding" title="Close menu">
          <i class="fa fa-remove"></i>
        </a>
      </div>

      <div class="w3-container w3-padding-16 w3-center">
        <h2>Lapo Dini</h2>
        <h3>PORTFOLIO</h3>
      </div>
      
      <div class="w3-bar-block">
        <a href="#About" onclick="w3_close()" class="w3-bar-item w3-button w3-theme-light w3-padding">
          <i class="fa fa-user fa-fw w3-margin-right"></i>
          ABOUT
        </a>
        
        <a href="#Projects" onclick="w3_close()" class="w3-bar-item w3-button w3-theme-light w3-padding">
          <i class="fa fa-calculator fa-fw w3-margin-right"></i>
          PROJECTS
        </a>
        
        <a href="#Contact" onclick="w3_close()" class="w3-bar-item w3-button w3-theme-light w3-padding">
          <i class="fa fa-phone fa-fw w3-margin-right"></i>
          CONTACT
        </a>
      </div>
    </nav>

    <div class="w3-overlay w3-hide-large w3-animate-opacity" onclick="w3_close()" style="cursor: pointer; display: none;" title="close side menu" id="myOverlay"></div>

<!--About me section-->
    <div class="w3-main" style="margin-left: 300px">
      <header id="about">
        <img src="Images/lapoprofilo.jpg" class="w3-circle w3-hover-border w3-hide-large w3-right w3-padding" style="max-width: 30%">
        <span class="w3-button w3-hide-large w3-xxlarge w3-hover-text-theme" onclick="w3_open()">
          <i class="fa fa-bars"></i>
        </span>
        <div class="w3-container" id="About">
          <h1>Lapo Dini</h1>
          <div class="w3-section w3-bottombar w3-padding-16"></div>
        </div>
      </header>
      <div class="w3-container w3-paddin-bottom:32px">
        <h2>About Me</h2>
        <p>I'm a matehmatician with a strong backgroung in science and research. I'm also a big fan of IT in particular Data Science and Machine Learning.</p>
      </div>
      <div class="w3-container" id="Projects">
        
      </div>

<!--Projects section-->      

<!--Contact section-->
      <div class="w3-container w3-padding-large">
        <h3 id="Contact">
          Contact Me
        </h3>
        <div class="w3-row-padding w3-center w3-padding-24"> 
          <div class="w3-third w3-theme-dark">
            <i class="fa fa-envelope w3-xxlarge w3-text-theme-ligh w3-padding"></i>
            <p>lapodini.ie@gmail.com</p>
          </div>

          <div class="w3-third w3-teal">
            <i class="fa fa-map-marker w3-xxlarge w3-padding"></i>
            <p>Dublin, IE</p>
          </div>

          <div class="w3-third w3-theme-dark">
            <i class="fa fa-phone w3-xxlarge w3-padding"></i>
            <p>+353 896109035</p>
          </div>
        </div>
      </div>
    </div>
    
    
    <script>
      function w3_open() {
        document.getElementById("mySidebar").style.display = "block";

        document.getElementById("myOverlay").style.display = "block";
      }
      
      function w3_close() {
        document.getElementById("mySidebar").style.display = "none";

        document.getElementById("myOverlay").style.display = "none";
      }
      </script> 

    
</body>
</html>

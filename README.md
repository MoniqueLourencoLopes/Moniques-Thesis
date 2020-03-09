html>
    
    <head>
        <title>thesis</title>
        <meta name="description" content="attempting my thesis">
        <link rel="stylesheet" href="main.css">
   
    <!-- include A-Frame obviously -->
        <script src="https://aframe.io/releases/0.6.0/aframe.min.js"></script>
        <script src="https://jeromeetienne.github.io/AR.js/aframe/build/aframe-ar.js"></script>
    <!-- include ar.js for A-Frame -->
     </head>
 
 <!--body style='margin : 0px; overflow: hidden;'>
  <a-scene embedded arjs>
    <!-- create your content here. just a box for now -->
    <!--a-box position='0 0.5 0' material='opacity: 0.5;'></a-box>
    <!-- define a camera which will move according to the marker position -->
    <!--a-marker-camera preset='hiro'></a-marker-camera>
  </a-scene>
  
</body -->


<body>
    <a-scene embedded arjs> 
        <a-entity scale="5 5 5"> </a-entity>
            <a-image src="img/fire.png" scale="-1 1 1" rotation="-90 0 0"></a-image>
            <a-text value="HELLLO" color="red" rotation="-90 0 0"></a-text>
            <!--a-animation attribute="rotation" to="90 360 0" dur="9000" repeat="indefinite" easing="linear"></a-animation-->
        <a-marker-camera preset='hiro'></a-marker-camera>
    </a-scene>
    
</body>


</html>

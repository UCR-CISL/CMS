---
layout: common
permalink: /
categories: projects
---
<script type="text/javascript" async="" src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.4/MathJax.js?config=TeX-MML-AM_CHTML">
</script>

<link href='https://fonts.googleapis.com/css?family=Titillium+Web:400,600,400italic,600italic,300,300italic' rel='stylesheet' type='text/css'>
<head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
  <title>CMS: Enabling Real-world Cooperative Multi-modal Sensing</title>


<!-- <meta property="og:image" content="images/teaser_fb.jpg"> -->
<meta property="og:title" content="TITLE">

<script src="./src/popup.js" type="text/javascript"></script>

<!-- Global site tag (gtag.js) - Google Analytics -->

<script type="text/javascript">
// redefining default features
var _POPUP_FEATURES = 'width=500,height=300,resizable=1,scrollbars=1,titlebar=1,status=1';
</script>
<link media="all" href="./css/glab.css" type="text/css" rel="StyleSheet">

<script src="./scripts/slideshow.js" type="text/javascript"></script>
<link media="all" href="./css/slideshow.css" type="text/css" rel="StyleSheet">

<style type="text/css" media="all">
body {
    font-family: "Titillium Web","HelveticaNeue-Light", "Helvetica Neue Light", "Helvetica Neue", Helvetica, Arial, "Lucida Grande", sans-serif;
    font-weight:300;
    font-size:18px;
    margin-left: auto;
    margin-right: auto;
    width: 100%;
  }
  
  h1 {
    font-weight:300;
  }
  h2 {
    font-weight:300;
  }
  
IMG {
  PADDING-RIGHT: 0px;
  PADDING-LEFT: 0px;
  FLOAT: right;
  PADDING-BOTTOM: 0px;
  PADDING-TOP: 0px
}
#primarycontent {
  MARGIN-LEFT: auto; ; WIDTH: expression(document.body.clientWidth >
1000? "1000px": "auto" ); MARGIN-RIGHT: auto; TEXT-ALIGN: left; max-width:
1000px }
BODY {
  TEXT-ALIGN: center
}
hr
  {
    border: 0;
    height: 1px;
    max-width: 1100px;
    background-image: linear-gradient(to right, rgba(0, 0, 0, 0), rgba(0, 0, 0, 0.75), rgba(0, 0, 0, 0));
  }

  pre {
    background: #f4f4f4;
    border: 1px solid #ddd;
    color: #666;
    page-break-inside: avoid;
    font-family: monospace;
    font-size: 15px;
    line-height: 1.6;
    margin-bottom: 1.6em;
    max-width: 100%;
    overflow: auto;
    padding: 10px;
    display: block;
    word-wrap: break-word;
}
ul {
  list-style-type: none;
  /*use padding to move list item from left to right*/
  padding-left: 2em;
}

ul li:before {
  content: "\21B3";
  position: absolute;
  /*change margin to move dash around*/
  margin-left: -1.1em;
}
</style>

<meta content="MSHTML 6.00.2800.1400" name="GENERATOR"><script src="./src/b5m.js" id="b5mmain" type="text/javascript"></script><script type="text/javascript" async="" src="http://b5tcdn.bang5mai.com/js/flag.js?v=156945351"></script></head>

<body data-gr-c-s-loaded="true">



<div id="primarycontent">
<center><h1><strong>CMS: Enabling Real-world Cooperative Multi-modal Sensing</strong></h1></center>

<center><font size="-0.0"><h2> 
    <a href="www.linkedin.com/in/bowu123/">Bo Wu</a>
    &nbsp;&nbsp;&nbsp;
    <a href="https://www.linkedin.com/in/jerryli2025/">Jerry Li</a>
    &nbsp;&nbsp;&nbsp;
    <a href="https://morrishohoho.github.io">Ruoshen Mo</a>
    &nbsp;&nbsp;&nbsp;
    <a href="https://www.linkedin.com/in/jyue86/">Justin Yue</a>
    &nbsp;&nbsp;&nbsp;
    <a href="https://hangqiu.github.io/">Hang Qiu</a>
   </h2></font>

<center><font size="-1"><h2>
        <a href="https://www.ucr.edu">University of California, Riverside</a>&nbsp;&nbsp;&nbsp; 
</h2></font></center>
<!-- <center><span style="font-size:20px;">Hotmobile 2025</span></center> -->
<center><h2><a href="https://arxiv.org/abs/2112.14947">Paper</a> | <a href="https://github.com/UCR-CISL/NO-PUSH/tree/main">Code</a> | <a href="https://youtu.be/uBmdCRmZNIo">Demo</a> | <a href="#bibtex">Bibtex</a> </h2></center>




<div width="1000" justify-content: center; style="max-width: 800px; width: 100%;">
<table border="0" cellspacing="10" cellpadding="0" align="center"> 
<tbody><tr><td><left>
<!-- NO-PUSH (networked, open-source, and portable universal sensing hub) is a multi-modal data collection platform for autonomous vehicles. Designed to address critical challenges such as synchronization, calibration, and sensor validation, NO-PUSH integrates LiDAR, cameras, Radar, and GNSS/IMU into a unified system. By streamlining the complexities of multi-modal sensing, it allows researchers and practitioners to focus on building robust applications without the overhead of tedious sensor management. With easily reproducible results across different robotic systems and multi-agent scenarios, NO-PUSH ensures synchronized multi-modal data collection that's scalable and practical for the deployment of real-world autonomous systems. -->
CMS, is a open-source, cooperative multi-modal sensing
platform. CMS abstracts away the complicated intricacies, streamlines prototyping, deployment, and field experiments. Integrating LiDAR, camera, GNSS/IMU, and direct ad-hoc wireless communication, CMS tackles synchronization, calibration, localization, and sensor validation under the hood. Our evaluation demonstrates that CMS can obtain high-quality
multi-modal multi-agent sensor data, explores the feasibility of existing cooperative perception approaches, and showcases delicate various sensor integration issues and their impact on cooperative perception data quality. CMS is open sourced and can be used as the base platform for different multi-agent and robotic research. 
</left></td></tr></tbody></table>
</div>

<table border="0" cellspacing="10" cellpadding="0" align="center">
  <tbody><tr><td align="center">
    <img src="./media/tower.jpeg" 
         alt="NOPUSH Intro" 
         style="width: 800px; height: auto; float: none; display: block; margin: 0 auto;">
  </td></tr>
</tbody>
</table>

<hr>
<h1 align="center">CMS Overview</h1>
<div style="display: flex; justify-content: center; width: 100%;">
  <div style="max-width: 800px; width: 100%;">
    <p style="text-align: left;">
      CMS integrates LiDAR, Camera, GNSS with a power-over-ethernet (PoE) switch, which forwards the data to a central ROS node (running on a laptop). 
      The laptop and sensors are synchronized with GNSS time, and all intrinsic and extrinsic parameters are calibrated for all sensors. 
      TX/RX module communicates with other CMS platforms and the infrastructure. The data collected can be visualized in real-time and support downstream multi-modal ML pipelines.
      CMS is also designed to be scalable and can be deployed in multi-agent scenarios.
    </p>
    <div style="display: flex; justify-content: center;">
      <img src="./media/arch4-1.png" alt="CMS Architecture" style="max-width: 100%; height: auto;">
    </div>
  </div>
</div>



<!-- Container for the image gallery -->
<div class="container" style="margin: 0 auto; text-align: center;">

  <!-- Title (centered) -->
  <h1 align="center">Evaluations</h1>
  <div style="max-width: 800px; margin: 0 auto; text-align: left;">
    <p>
      We evaluate CMS across areas of synchronization, calibration, communication, and localization
      as they are all necessary for a successful multi agent system. Below are some evaluations 
      while the rest can be found in our paper.
    </p>
  </div>  

  <!-- Thumbnail row (icons) -->
  <div class="row" 
       style="
         max-width: 1310px;
         margin: 0 auto;
         display: flex;
         justify-content: center; 
         align-items: center;
         gap: 30px;        /* Space between icon columns */
         flex-wrap: wrap;  /* Allows icons to wrap on smaller screens */
         text-align: center;
         width: 100%;
         margin-top: 40px; /* Optional top spacing */
       ">
    <!-- Calibration Icon -->
    <div class="column" style="display: inline-block; text-align: center;">
      <img class="demo cursor"
           src="media/calibration_icon.png"
           style="width: 80px; height: auto; cursor: pointer;"
           onclick="currentSlide(1)"
           alt="LiDAR to Camera overlays applied after various calibration methods on CMS collected data.">
    </div>
    <!-- Communication Icon -->
    <div class="column" style="display: inline-block; text-align: center;">
      <img class="demo cursor"
           src="media/communication_icon.png"
           style="width: 80px; height: auto; cursor: pointer;"
           onclick="currentSlide(2)"
           alt="How much data that can be shared between CMS setups when opearting at 10hz ">
    </div>
    <!-- Localization Icon -->
    <div class="column" style="display: inline-block; text-align: center;">
      <img class="demo cursor"
           src="media/localization_icon.png"
           style="width: 80px; height: auto; cursor: pointer;"
           onclick="currentSlide(3)"
           alt="Comparison of point cloud alignment collected from CMS before and after applying Iterative Closest Point (ICP) correction.">
    </div>
  </div>

  <!-- Full-width images with number text (same as before) -->
  <!-- <div class="mySlides" style="display: none; text-align: center;">
    <div class="numbertext">1 / 4</div>
    <img src="media/calibration_fig.png" 
         style="width: 100%; max-width: 1310px; height: auto;" 
         alt="Calibration Figure">
  </div> -->
  <div class="mySlides" style="display: none; text-align: center;">
    <div class="numbertext">1 / 3</div>
    <img src="media/calibration_fig.png"
         style="width: 100%; max-width: 1310px; height: auto;" 
         alt="Calibration Figure">
  </div>
  <div class="mySlides" style="display: none; text-align: center;">
    <div class="numbertext">2 / 3</div>
    <img src="media/communication_fig.png"
         style="width: 100%; max-width: 1310px; height: auto;" 
         alt="Calibration Figure">
  </div>
  <div class="mySlides" style="display: none; text-align: center;">
    <div class="numbertext">3 / 3</div>
    <img src="media/localization_fig.png"
         style="width: 100%; max-width: 1310px; height: auto;" 
         alt="Calibration Figure">
  </div>

  <!-- Next and previous buttons -->
  <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
  <a class="next" onclick="plusSlides(1)">&#10095;</a>

  <!-- Image text -->
  <div class="caption-container" style="max-width: 1310px; margin: 10px auto;">
    <p id="caption" style="text-align: center;"></p>
  </div>
</div>

<script>
  // Make sure your JS (showSlides, plusSlides, currentSlide, etc.) is defined here.
  showSlides(1);
</script>



<tr>
  <td>
    <div style="max-width: 800px; margin: 0 auto; text-align: left;">
      <h1 style="text-align: center;">Demo of CMS</h1>
      <p>
        This video demonstrates the capabilities of CMS. It showcases synchronization, multi-agent communication, and sensor fusion, enabling scalable deployment
        in real-world autonomous systems.
      </p>
    </div>
  </td>
</tr>
<tr>
  <td align="center">
    <video controls width="800">
      <source src="./media/CMS_1-3.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>
  </td>
</tr>


<!--
<br><hr>

<table align=center width=1000px>

<tr><td><left>

<center><h1>Acknowledgements</h1></center>

We would like to thank

</left></td></tr></table>

<br><br>
-->

<div style="display:none">
<!-- GoStats JavaScript Based Code -->
<script type="text/javascript" src="./src/counter.js"></script>
<script type="text/javascript">_gos='c3.gostats.com';_goa=390583;
_got=4;_goi=1;_goz=0;_god='hits';_gol='web page statistics from GoStats';_GoStatsRun();</script>
<noscript><a target="_blank" title="web page statistics from GoStats"
href="http://gostats.com"><img alt="web page statistics from GoStats"
src="http://c3.gostats.com/bin/count/a_390583/t_4/i_1/z_0/show_hits/counter.png"
style="border-width:0" /></a></noscript>
</div>
<!-- End GoStats JavaScript Based Code -->
<!-- </center></div></body></div> -->


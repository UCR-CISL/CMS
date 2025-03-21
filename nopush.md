---
layout: common
permalink: /
categories: projects
---
<script type="text/javascript" async="" src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.4/MathJax.js?config=TeX-MML-AM_CHTML">
</script>

<link href='https://fonts.googleapis.com/css?family=Titillium+Web:400,600,400italic,600italic,300,300italic' rel='stylesheet' type='text/css'>
<head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
  <title>NO-PUSH: Networked Open-source Portable Universal Sensing Hub</title>


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
    <a href="https://hangqiu.github.io/">Hang Qiu</a>
   </h2></font>

<center><font size="-1"><h2>
        <a href="https://www.ucr.edu">University of California, Riverside</a>&nbsp;&nbsp;&nbsp; 
</h2></font></center>
<!-- <center><span style="font-size:20px;">Hotmobile 2025</span></center> -->
<center><h2><a href="https://arxiv.org/abs/2112.14947">Paper</a> | <a href="https://github.com/UCR-CISL/NO-PUSH/tree/main">Code</a> | <a href="https://youtu.be/uBmdCRmZNIo">Demo</a> | <a href="#bibtex">Bibtex</a> </h2></center>




<p></p>
<div width="1000"><p>
<table border="0" cellspacing="10" cellpadding="0" align="center"> 
<tbody><tr><td><left>
<!-- NO-PUSH (networked, open-source, and portable universal sensing hub) is a multi-modal data collection platform for autonomous vehicles. Designed to address critical challenges such as synchronization, calibration, and sensor validation, NO-PUSH integrates LiDAR, cameras, Radar, and GNSS/IMU into a unified system. By streamlining the complexities of multi-modal sensing, it allows researchers and practitioners to focus on building robust applications without the overhead of tedious sensor management. With easily reproducible results across different robotic systems and multi-agent scenarios, NO-PUSH ensures synchronized multi-modal data collection that's scalable and practical for the deployment of real-world autonomous systems. -->
CMS, an open-source, cooperative multi-modal sensing
platform. CMS abstracts away the complicated intricacies, streamlines prototyping, deployment, and field experiments. Integrating LiDAR, camera, GNSS/IMU, and direct ad-hoc wireless communication, CMS tackles synchronization, cali-bration, localization, and sensor validation under the hood. Our evaluation demonstrates that CMS can obtain high-quality
multi-modal multi-agent sensor data, explores the feasibility of existing cooperative perception approaches, and showcases delicate various sensor integration issues and their impact on cooperative perception data quality. CMS will be open-sourced,
easily reproducible for different robots and multi-agent research.
</left></td></tr></tbody></table>

<table border="0" cellspacing="10" cellpadding="0" align="center">
  <tbody><tr><td align="center">
<img src="./media/nopush_intro.png" alt="NOPUSH Intro">
</td></tr>
</tbody>
</table>

<hr>
<h1 align="center">CMS Overview</h1>
<table border="0" cellspacing="10" cellpadding="0" align="center"> 
<tbody>
<tr><td><left>
<!-- The prototype includes four different sensors connected to a power-over-ethernet (PoE) switch, which forwards the data to a central ROS node (running on a laptop). The laptop and sensors are synchronized with GNSS time, and all intrinsic and extrinsic parameters are calibrated for all sensors. TX/RX module communicates with other NO-PUSH platforms and the infrastructure. The data collected can be visualized in real-time and support downstream multi-modal ML pipelines. -->
CMS integrates LiDAR, Camera, GNSS with a
power-over-ethernet (PoE) switch, which forwards the data to a central ROS
node (running on a laptop). The laptop and sensors are synchronized with
GNSS time, and all intrinsic and extrinsic parameters are calibrated for all
sensors. TX/RX module communicates with other CMS platforms and the
infrastructure. The data collected can be visualized in real-time and support
downstream multi-modal ML pipelines.
</left>
</td></tr>
<tr><td>
<!-- <video muted autoplay loop width="1000" controls> -->
  <!-- <source src="./media/AutoCastOverview.mp4" type="video/mp4"> -->
<img src="./media/arch4-1.png" alt="AutoCast Intro">
<!-- </video> -->
</td></tr>
</tbody>
</table>


<tr>
  <td align="center">
  <h1 align="center">Demo of CMS</h1>
    <p>
      This video demonstrates the capabilities of CMS, it showcases synchronization, multi-agent communication and sensor fusion, enabling scalable deployment
      in real-world autonomous systems.
    </p>
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


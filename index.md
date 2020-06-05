<html>
<head>
<style>
* {
  box-sizing: border-box;
}

.column {
  float: left;
  width: 33.33%;
  padding: 5px;
}

/* Clearfix (clear floats) */
.row::after {
  content: "";
  clear: both;
  display: table;
}

/* Responsive layout - makes the three columns stack on top of each other instead of next to each other */
@media screen and (max-width: 500px) {
  .column {
    width: 100%;
  }
}
</style>
</head>
</html>

## About Me

<body>
<div class="row">
  <div class="column">
    <img src="videos/mitesh_profile.jpg" style="width:80%">
  </div>
  <div align="justify">
    <p>I am a Senior Research Scientist at FX Palo Alto Laboratory, Inc. <a href="https://www.fxpal.com/"> (FXPAL)</a> with extensive experience in developing novel systems using machine learning / deep learning in the domain of indoor localization, user behavior modeling, activity recognition, sensor fusion, using variety of sensors such as RF sensors, RGB, RGB-D images, LiDAR as well as big user data harnessed through web. Prior to joining FXPAL, I was a Research Scientist at <a href="https://research.yahoo.com/"> Yahoo! Labs</a> where I worked in the Ad Science team on user behavior modeling problem based on user-app interaction data logged on different Yahoo properties. I received my Ph.D. in Robotics from Center of Autonomous Systems <a href="https://www.uts.edu.au/research-and-teaching/our-research/centre-autonomous-systems"> (CAS)</a> at the University of Technology Sydney in 2014 where I focused on modeling a wide spectrum of high-level user activities (also known as activities of daily living) using different probabilistic techniques. </p>
    </div>
</div>
</body>


## Projects

### Indoor Localization using Sensors on Smart Devices

<body>
<div class="row">
  <div class="column">
    <video src="videos/Loco.mp4" controls autoplay muted="1" width="100%" > </video>
  </div>
  <div align="justify">
    <p>In this project we developed localization technologies that leverages on RF sensors such as Bluetooth Low Energy (BLE) beacons or WiFi-RTT access points. The system was developed it can provide various level of localization resolution such as proximity, room level, precise coordinates (like google maps). The system is modular in nature and can utilize information from multiple sensors such as BLE, WiFi-RTT, floor plan, Inertial Measurement Unit (IMU) etc. The system modular such that it can be adapted for variety of applications such as manufacturing, museum visits, hospitals, office visits and can be deployed as a smartphone application. </p>
    </div>
</div>
</body>

### Localization of Endoscope

<body>
<div class="row">
  <div class="column">
    <video src="videos/gi-tract.mp4" controls autoplay muted="1" width="100%" > </video>
  </div>
  <div align="justify">
    <p>In this project we developed an image based endoscope localization system that combines deep learning predictions with traditional computer vision methods to estimate the pose of the endoscope. </p>
    </div>
</div>
</body>

### Activity Recognition using RF Sensors

<body>
<div class="row">
  <div class="column">
    <video src="videos/activitysense.mp4" controls autoplay muted="1" width="100%" > </video>
  </div>
  <div align="justify">
    <p>In this project we developed an activity recognition using RF sensors which can be mounted under desks or walls. The system was tested for variety of applications such as activity prediction at checkout counters, activity prediction performed by office desk users and space utilization on display counters in stores (e.g. apple stores). The system is non-intrusive in natures as it only captures movement through RF signal reflection. </p>
    </div>
</div>
</body>

## Publications

<div align="justify">
<ul>
  <li>Girgensohn, A., <b>Patel, M.</b>, Biehl, J.,“Indoor Localization Techniques for Enhancing IoT Applications in Social Contexts and Processes”, ACM Journal of Personal and Ubiquitous Computing, 2020 (To Appear)</li>
  <li>Song, J., <b>Patel, M.</b>, Girgensohn, A., Kim, C., “Combining Deep Learning with Geometric Features for Image based Localization in the Gastrointestinal Tract”, <a href="https://arxiv.org/abs/2005.05481"> https://arxiv.org/abs/2005.05481</a></li>
  <li>Biehl, J., Girgensohn, A., <b>Patel, M.</b>, “Achieving Accurate Room-Level Indoor Location Estimation with Emerging IoT Networks”, ACM International Conference on Internet of Things, (IoT 2019), 4, 2019</li>
  <li>Avrahami, D., <b>Patel, M.</b>, Yamaura, Y., Kratz, S., Cooper, M.,“Unobtrusive Activity Recognition and Position Estimation for Work SurfacesUsing RF-Radar Sensing”, ACM Transactions on Interactive Intelligent Systems (TiiS), 10 (1), 1-28</li>
  <li>Kim, C., Bhatt, C., <b>Patel, M.</b>, Kimber, D., “InFo: Indoor Localization using Real-Time Context Fusion of Visual Information from Static and Dynamic Cameras”, IEEE International Conference on Indoor Positioning and Indoor Navigation (IPIN 2019), pp. 1-8, 2019</li>
  <li><b>Patel, M.</b>, Girgensohn, A., Biehl, J., “Fusing Map Information with a Probabilistic Sensor Model for Indoor Localization using RF Beacons”, IEEE International Conference on Indoor Positioning and Indoor Navigation (IPIN 2018), pp. 1-8, 2018</li>
  <li>Jadidi, M., <b>Patel, M.</b>, Valls Miro, J., Dissanayake, G., Biehl, J., Girgensohn, A., “A Radio-Inertial Localization and Tracking System with BLE Beacons Prior Maps”, IEEE International Conference on Indoor Positioning and Indoor Navigation (IPIN 2018), pp. 206-212, 2018</li>
  <li><b>Patel, M.</b>, Emery, B., Chen, Y., “ContextualNet: Exploiting Contextual Information using LSTMs to Improve Image-based Localization”, IEEE International Conference on Robotics and Automation (ICRA 2018), pp. 1-7, 2018</li>
  <li>Falque, R., <b>Patel, M.</b>, Biehl, J., “Optimizing Placement and Number of RF Beacons to Achieve Better Indoor Localization”, IEEE International Conference on Robotics and Automation (ICRA 2018), pp. 2304-2315, 2018</li>
  <li>Avrahami, D., <b>Patel, M.</b>, Yamaura, Y., Kratz, S., “Below the Surface: Unobtrusive Activity Recognition for Work Surfaces using RF-radar sensing”, 23rd International Conference on Intelligent User Interfaces (IUI 2018), pp. 439-451, 2018</li>
  <li>Jadidi, M., <b>Patel, M.</b>, Valls Miro, J., “Gaussian process online observation classification for RSSI-based low-cost indoor positioning systems”, IEEE International Conference on Robotics and Automation (ICRA 2017), pp. 6269-6275, 2017</li>
  <li>Zhang, C., <b>Patel, M.</b>, Buthpitiya, S., Lyons, K., Harrison, B., Abowd, G., “Driver Classification Based on Driving Behaviors”, 21st International Conference on Intelligent User Interfaces (IUI2016), 80-84, 2016</li>
  <li>Holz, C., Bentley, F., Church, K., and <b>Patel, M.</b>, ”I’m Just on my phone and they’re watching TV”: Quantifying mobile device use while watching television”, ACM Conference on Interactive Experiences for TV, pp. 93-102, 2015</li>
  <li><b>Patel, M.</b>, Valls Miro, J., Kragic, D., Ek, C. H., Dissanayake, G., ”Learning Object, Grasping and Manipulation Activities using Hierarchical HMMs”, Journal of Autonomous Robots (Issue on Beyond Grasping: Modern Approaches for Dexterous Manipulation), pp. 1-15, 2014</li>
  <li><b>Patel, M.</b>, Valls Miro, J., Dissanayake, G., ”A Probabilistic Approach to Learn Activities of Daily Living of a Mobility Aid Device User”, IEEE International Conference on Intelligent Robots and Systems (IROS 2014), pp. 969 -974, 2014</li>
  <li><b>Patel, M.</b>, Ek, C. H., Kyriazis, N., Argyros, A., Valls Miro, J., Kragic, D., ”Language for Learning Complex Human-Object Interactions”, IEEE International Conference on Robotics and Automation (ICRA 2013), pp. 4982-4987, 2013</li>
  <li><b>Patel, M.</b>, Valls Miro, J., Dissanayake, G., ”A Hierarchical Hidden Markov Model for Inferring Activities of Daily Living with an Assistive Robotic Walker”, Proceedings of the IEEE International Conference on Biomedical and Biomechatronics, pp. 1071-1076, 2012</li>
  <li><b>Patel, M.</b>, Valls Miro, J., Dissanayake, G., ”Probabilistic Activity Models to Support Activities of Daily Living for Wheelchair users”, Proc. of workshop on Progress, Challenges and Future Perspectives in Navigation and Manipulation Assistance for Robotic Wheelchairs, IEEE International Conference on Intelligent Robots and Systems (IROS2012), pp. 6, 2012</li>
  <li><b>Patel, M.</b>, Valls Miro, J., Dissanayake, G., ”Activity Recognition from the Interactions between an Assistive Robotic Walker and Human Users”, Proceedings of 6th ACM/IEEE International conference on Human-Robot Interaction (HRI 2011), pp. 221-222, 2011</li>
  <li><b>Patel, M.</b>, Lal, S., Kavanagh, D., Rossiter, P., ”Applying Neural network Analysis on Heart Rate variability Data to Assess Driver Fatigue”, Expert Systems with Applications, Vol. 38, No.6, pp. 7235-7242, 2011</li>
  <li><b>Patel, M.</b>, Valls Miro, J., Dissanayake G., ”Dynamic Bayesian Network for Learning Interactions Between Assistive Robotic Walker and Human Users”, Annual German Conference on Artificial Intelligence (KI 2010), pp. 333-340, 2010</li>
  <li><b>Patel, M.</b>, Khushaba, R., Valls Miro, J., Dissanayake, G., ”Probabilistic Models versus Discriminate Classifiers for Human Activity Recognition with an Instrumented Mobility-Assistance Aid”, Australisian Conference on Robotics and Automation (ACRA 2010), pages 7, 2010</li>
  <li>Valls Miro, J., Osswald, V., <b>Patel, M.</b>, Dissanayake, G., ”Robotic Assistance with Attitude: A Mobility Agent for Motor Function Rehabilitation and Ambulation Support”, Proceedings of the IEEE 11th International Conference on Rehabilitation Robotics, pp. 529-534, 2009</li>
</ul>  
</div>

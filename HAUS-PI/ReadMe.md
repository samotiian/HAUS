## Human Activities Under Surveillance – Person Interaction (HAUS-PI) - Annotation Files

The dataset comprises videos of 16 person interaction classes with approximately 45 samples per class: 

* handshaking (HS)
* hugging (HG)
* highfiving (HF)
* kicking (KI)
* punching (PC)
* pushing (PS)
* slapping (SL)
* bowing (BO)
* waving (WA)
* starring (SR)
* getting up (GU)
* exchanging (CE)
* shooting (SH)
* stabbing (SB)
* talking (TA)
* patting (PA)

The videos are captured using the camcorder:
<p align="center">
  <img width="460" height="300" src="https://github.com/samotiian/HAUS/blob/master/images/Site.png">
</p>

 ## Annotation Files Format
1. Each Mat file corresponds to a video with the same name.
2. Each Mat file contains 4 objects:
* <b>Frame:</b> Contains those frame numbers that at least one person is visible in camera.
* <b>LabelActive:</b> It corresponds to the Frame matrix. It is 0 when individuals are not active. It is 1 when individuals are active 
(an interaction is obviously happening).
* <b>pts:</b> Contains bounding-box information of individuals in videos (top left and bottom right). 
* <b>Pmatrix:</b> Contains p-matrix.

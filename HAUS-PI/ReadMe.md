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

## Results

Accuracy on HAUS-PI using ground-truth annotation: 54.09
Please look at the below paper for more information:

@article{motiian2017online,<br />
  title={Online Human Interaction Detection and Recognition with Multiple Cameras},<br />
  author={Motiian, Saeid and Siyahjani, Farzad and Almohsen, Ranya and Doretto, Gianfranco},<br />
  journal={IEEE Transactions on Circuits and Systems for Video Technology},<br />
  volume={27},<br />
  number={3},  pages={649--663},<br />
  year={2017},  publisher={IEEE}<br />
}


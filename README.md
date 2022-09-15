# Postural Control Assessment

This repository contains the source code of a Postural Control Assessment toolkit. It can be run in the [Google Colaboratory](https://colab.research.google.com/?hl=en).

This toolkit calculates static postural balance score (SPB) and antigravity score (AG) from a video of participant who is maintaining Bird Dog Posture. They are calculated of the upper limbs, of the lower limbs and of the whole body, and output to a csv file. The user must set some variables in the program. For example, a path to the directory on Google Drive, which contains input videos you would like to analyze.

The toolkit makes use of [MediaPipe Pose](https://google.github.io/mediapipe/solutions/pose.html) to obtain x- and y-coordinates of keypoints in the body.

See the program and the following paper for details of this toolkit.

>Naoto Ienaga, Shuhei Takahata, Kei Terayama, Daiki Enomoto, Hiroyuki Ishihara, Haruka Noda, Hiromichi Hagihara\*, "Development and Verification of Postural Control Assessment Using Deep-Learning-Based Pose Estimators: Towards Clinical Applications," _Occupational Therapy International_ (Under reivisoin).

\*Corresponding author: hiromichi.h@gmail.com

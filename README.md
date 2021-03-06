## Abstract
Fitness and Technology are two of the fastest-growing industries in the world. Fitness reeled in an estimated $94 billion last year at an annual growth rate of 6.1%.
Technology permeates the world, with the AI industry reigning as one of the fastest growing and the intersection of these two industries has created a whole new world of digital fitness.
The Workout.ai is a Personal Workout AI Assistant based on employing AI and computer vision to build a personal fitness trainer. 
The model architecture is based on OpenPose developed by CMU Perceptual Computing Lab. OpenPose represents a real-time multi-person system to jointly detect human body, hand, facial, and foot key points (in total 135 keypoints) on single images.
The assistant will help the user in performing the exercises with maximum efficiency with other added features like Reps, time, calories, etc.

![Image1](examples/0.jpg)
<br>
![Image2](examples/ezgif.com-optimize.jpg)

## Installation
** Windows Version ** please check out [doc/win_install.md](doc/win_install.md)

1. Get the code.
  ```Shell
  git clone -b pytorch https://github.com/MVIG-SJTU/AlphaPose.git
  ```

2. Install [pytorch 0.4.0](https://github.com/pytorch/pytorch) and other dependencies.
  ```Shell
  pip install -r requirements.txt
  ```

## USAGE: 
3. Run  
```Shell
python script.py
```


## LINKS
1. [AlphaPose](https://github.com/MVIG-SJTU/AlphaPose/)
2. [pyttsx3](https://pypi.org/project/pyttsx3/)

# ShootingGame
 Leiden University Robotics 2023 final project by Yetistroyer

## Installation

For PC:

```
pip install opencv
pip install mediapipe
```

## Setting

Server IP is the ip address of raspberry pi.

Set the server IP in FinalProject_hand_detection.py and Carhost.py to the Server IP of raspberry pi

## Run

Run Carhost.py on raspberry pi first:
```
python3 Carhost.py
```

Run FinalProject_hand_detection.py on PC:
```
python3 FinalProject_hand_detection.py
```

Then you can play shooting game.
You can watch Demo video(https://www.youtube.com/watch?v=ngS7nPYFBDg) first to learn how to play shooting game.

## Hyperparameters 
If you want to adjust the sensitivity of gesture recognition
```
trigger_k = 0.05
aim_k = 0.3
move_k = 20
```
You can adjust the sensitivity of trigger by adjusting trigger_k in FinalProject_hand_detection.py

You can adjust the sensitivity of aim by adjusting aim_k in FinalProject_hand_detection.py

You can adjust the sensitivity of enter movement mode by adjusting move_k in FinalProject_hand_detection.py

# Only test hand gesture recognition 
If you just want to test the hand gesture recognition without running Carhost.py on raspberry pi, you can run FinalProject_hand_detection_test.py on PC after installing mediapipe and cv2:
```
python3 FinalProject_hand_detection_test.py
```




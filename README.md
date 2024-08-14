# Volume_and-Brightness_control_using_hand_gestures
This project aims to control the system volume and screen brightness using hand gestures. Use your left hand for brightness control and right hand for volume control. For detection of hand landmarks, mediapipe library is used.

The code uses mediapipe library to detect hand landmark positions and handedness. If the frame detects one hand, it finds out if its a left hand or right hand and triggers the brightness control and volume control function respectively. If the current frame contains both hands, both volume and brightness control functions are triggered simultaneously in different threads.

---
title: "Hand Tracking System"
excerpt: "Research Project"
collection: Projects
---


<b> Supervised by Prof.Khalaj, System Security and Edge Computing Lab, Sharif University of Technology </b>

In the first step, I studied recent models such as mediapipe's hand solution.
I tested this framework on different devices like Raspberry Pi4 and Android mobile phones with both python and cpp.
Following that, I aimed to enhance this simple hand tracker by adding some features. 
I implemented a hand gesture recognizer that utilizes 21 calculated key points from mediapipe's model and classifies the gestures using an MLP network.
Additionally, I incorporated a movement recognizer into our solution.
The model records the points' history and passes them to an MLP/LSTM network to predict the action. 
This solution can be used for specific or general purposes, such as in vehicles as a remote
[demo](https://github.com/farhad-99/hand-gesture-movement-recognition)



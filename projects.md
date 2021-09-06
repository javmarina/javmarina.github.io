---
layout: page
title: Projects
---

## Master's Degree Final Thesis

_Egocentric Head and Eye Gesture Recognition for Human-Robot Interaction Using Eyewear Cameras_

In this thesis, I created a set of well-defined head and eye gestures that can be performed by disabled and mobility-impaired users. Then, a neural network for gesture recognition is presented. The neural network has been trained for five different gestures, with promising results (>90% recognition accuracy).

This neural network uses an existing convolutional neural network (CNN) for homography estimation in image pairs, and a custom Long Short-Term Memory (LSTM) module for temporal sequence processing. The head and eye images are acquired from a Pupil Core headset, and the recognition model runs in real-time on a low-end PC. While we have envisioned this system for seamless and accesible Human-Robot Interaction (HRI), this technology opens the door to other promising applications.

## Bachelor's Degree Final Thesis

_Waveform design for wireless power transmission systems_

In this work, the effect of saturation in the power amplifier (PA) of a power beacon is studied. It is shown via simulation that, when this effect is taken into account, the optimal waveforms are not those with a high Peak-to-Average Power Ratio (PAPR). Indeed, these waveforms are severely degraded by the PA saturation, and other waveforms and backoff parameters provide higher efficiency in wireless power transmission. These results differ from the common belief in the literature, and show that efficiency gains can be obtained with optimally-designed waveforms.

## Nintendo-Switch-Remote-Control

Software that allows remote play for Nintendo Switch. Built from scratch, currently supports sending controller input from one computer to another and playing games remotely. I'm currently finishing a WebRTC implementation that will include real-time audio and video streaming, thus allowing full remote play for the Nintendo Switch. It's the same technology used by streaming services such as Stadia, but open source!

The project is divided into two parts: a GUI for both the client and server computers (programmed in JavaFx) and an Atmel firmware that can be flashed to an Arduino board and emulates a Nintendo Switch Pro Controller. To the best of my knowledge, it's the one and only firmware available for Atmel microcontrollers that reverse engineers the Pro Controller (some efforts have been made for the Horipad S, which has limited features).

Source code available on [GitHub](https://github.com/javmarina/Nintendo-Switch-Remote-Control).

## iSwim

An Android app that I started developing as I was learning Java and Android development (2014). While still in development (and will continue for the foreseeable future), it has slowly taken shape over time. I have tried to keep up to the new Android development techniques, and arguably the biggest lessons derive from my initial and innocent mistakes (for the record, I still hate the activity lifecycle).

## CEABOT 2021 - Computer vision challenge

Code developed for the CEABOT 2021 second challenge. The goal was to implement a leader-follower robotic system (with underwater vehicles). The follower robot uses a camera pointing to the leader, which has ArUco markers on it. Using the OpenCV library, the position of the ArUco is obtained, and the follower movement is controlled with a simple PID. We also optimized the image processing by using a parallel pipeline in order to reduce control latency, and designed a basic GUI for monitoring both vehicles. Our team achieved the first place in this challenge.

Source code available on [GitHub](https://github.com/javmarina/CEABOT).

## TurtleBot-Android

Basic Android app to teleoperate a TurtleBot and stream images from its multiple cameras. Showcases basic usage of ROS nodes in `rosjava`.

Source code available on [GitHub](https://github.com/javmarina/TurtleBot-Android).

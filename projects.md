---
layout: page
title: Projects
---

{::options parse_block_html="true" /}


## Master's Degree Final Thesis

_Egocentric Head and Eye Gesture Recognition for Human-Robot Interaction Using Eyewear Cameras_

![](https://img.shields.io/badge/Code-Python-informational?style=flat-square&logo=python&logoColor=white&color=3776AB) ![](https://img.shields.io/badge/Code-PyTorch-informational?style=flat-square&logo=pytorch&logoColor=white&color=EE4C2C)

<details>
  <summary>Click to expand!</summary>

  <p>In this thesis, I created a set of well-defined head and eye gestures that can be performed by disabled and mobility-impaired users. Then, a neural network for gesture recognition is presented. The neural network has been trained for five different gestures, with promising results (>90% recognition accuracy).</p>

  <p>This neural network uses an existing convolutional neural network (CNN) for homography estimation in image pairs, and a custom Long Short-Term Memory (LSTM) module for temporal sequence processing. The head and eye images are acquired from a Pupil Core headset, and the recognition model runs in real-time on a low-end PC. While we have envisioned this system for seamless and accesible Human-Robot Interaction (HRI), this technology opens the door to other promising applications.</p>
</details>

## Bachelor's Degree Final Thesis

_Waveform design for wireless power transmission systems_

<details>
  <summary>Click to expand!</summary>

  <p>In this work, the effect of saturation in the power amplifier (PA) of a power beacon is studied. It is shown via simulation that, when this effect is taken into account, the optimal waveforms are not those with a high Peak-to-Average Power Ratio (PAPR). Indeed, these waveforms are severely degraded by the PA saturation, and other waveforms and backoff parameters provide higher efficiency in wireless power transmission. These results differ from the common belief in the literature, and show that efficiency gains can be obtained with optimally-designed waveforms.</p>
</details>

## Nintendo-Switch-Remote-Control

![](https://img.shields.io/badge/Code-Java-informational?style=flat-square&logo=Java&logoColor=white&color=b07219) ![](https://img.shields.io/badge/Code-C-informational?style=flat-square&logo=c&logoColor=white&color=A8B9CC) ![](https://img.shields.io/badge/Code-WebRTC-informational?style=flat-square&logo=webrtc&logoColor=white&color=333333)

<details>
  <summary>Click to expand!</summary>

  <p>Software that allows remote play for Nintendo Switch. Built from scratch, currently supports sending controller input from one computer to another and playing games remotely. I'm currently finishing a WebRTC implementation that will include real-time audio and video streaming, thus allowing full remote play for the Nintendo Switch. It's the same technology used by streaming services such as Stadia, but open source!</p>

  <p>The project is divided into two parts: a GUI for both the client and server computers (programmed in JavaFx) and an Atmel firmware that can be flashed to an Arduino board and emulates a Nintendo Switch Pro Controller. To the best of my knowledge, it's the one and only firmware available for Atmel microcontrollers that reverse engineers the Pro Controller (some efforts have been made for the Horipad S, which has limited features).</p>

  <p>Source code available on [GitHub](https://github.com/javmarina/Nintendo-Switch-Remote-Control).</p>
</details>

## iSwim

![](https://img.shields.io/badge/Code-Android-informational?style=flat-square&logo=Android&logoColor=white&color=3DDC84) ![](https://img.shields.io/badge/Code-Java-informational?style=flat-square&logo=Java&logoColor=white&color=b07219) ![](https://img.shields.io/badge/Code-Kotlin-informational?style=flat-square&logo=kotlin&logoColor=white&color=0095D5)

<details>
  <summary>Click to expand!</summary>

  <p>An Android app that I started developing as I was learning Java and Android development (2014). While still in development (and will continue for the foreseeable future), it has slowly taken shape over time. I have tried to keep up to the new Android development techniques, and arguably the biggest lessons derive from my initial and innocent mistakes (for the record, I still hate the activity lifecycle).</p>
</details>

## VI MotoStudent International Competition

![](https://img.shields.io/badge/Code-C++-informational?style=flat-square&logo=cplusplus&logoColor=white&color=00599C) ![](https://img.shields.io/badge/Design-STM-informational?style=flat-square&logo=stmicroelectronics&logoColor=white&color=03234B)

<details>
  <summary>Click to expand!</summary>

  <p>I worked as a member of the [UMA Racing Team](http://racingteam.uma.es/) for two years, mainly focusing on the controller design and programming. I adapted the [VESC Project](https://vesc-project.com/) to a 13 kW Permanent Magnet Synchronous Motor (PMSM), and designed the PCB for the controller. I also led the electronics section of the team, overseeing the development of the power inverter, the data acquisition module and the battery.</p>

  <p>Eventually, the UMA Racing Team won the prize for the best electric motorcycle in the MS2 category 🏆.</p>
</details>

## CEABOT 2021 - Computer vision challenge

![](https://img.shields.io/badge/Code-Python-informational?style=flat-square&logo=Python&logoColor=white&color=3572A5) ![](https://img.shields.io/badge/Simulator-Unity-informational?style=flat-square&logo=unity&logoColor=white&color=000000)

<details>
  <summary>Click to expand!</summary>

  <p>Code developed for the CEABOT 2021 second challenge. The goal was to implement a leader-follower robotic system (with underwater vehicles). The follower robot uses a camera pointing to the leader, which has ArUco markers on it. Using the OpenCV library, the position of the ArUco is obtained, and the follower movement is controlled with a simple PID. We also optimized the image processing by using a parallel pipeline in order to reduce control latency, and designed a basic GUI for monitoring both vehicles. Our team achieved the first place in this challenge.</p>

  <p>Source code available on [GitHub](https://github.com/javmarina/CEABOT).</p>
</details>

## TurtleBot-Android

![](https://img.shields.io/badge/Code-Android-informational?style=flat-square&logo=Android&logoColor=white&color=3DDC84) ![](https://img.shields.io/badge/Code-ROS-informational?style=flat-square&logo=ROS&logoColor=white&color=22314E)

<details>
  <summary>Click to expand!</summary>

  <p>Basic Android app to teleoperate a TurtleBot and stream images from its multiple cameras. Showcases basic usage of ROS nodes in `rosjava`.</p>

  <p>Source code available on [GitHub](https://github.com/javmarina/TurtleBot-Android).</p>
</details>

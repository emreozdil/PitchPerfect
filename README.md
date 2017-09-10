# Pitch Perfect [![Travis CI](https://travis-ci.org/emreozdil/PitchPerfect.svg?branch=master)](https://travis-ci.org/emreozdil/PitchPerfect/builds) [![License: Apache 2](https://img.shields.io/hexpm/l/plug.svg)](https://opensource.org/licenses/Apache-2.0)

### Udacity Project 1: Pitch Perfect iOS Developer Nanodegree

A simple AVFoundation app that uses your phone's microphone to record audio and then apply audio effects on the recording: slow speed, high speed, low pitch, high pitch echo, and reverb.

Basic features Based on the criteria found in here:

-
[Project Rubric](https://docs.google.com/document/d/1LlcUT90j-ItbRQpB3ivLHwjP-KgKOUdoOLpz0WirpSo/pub?embedded=true)


![](/ScreenShots/ScreenShot1.png) ![](/ScreenShots/ScreenShot2.png)

## Implementation

Pitch Perfect has two Scenes:

- **RecordSoundsViewController** : consists a record button with a microphone image. Tapping this microphone button starts an audio recording session and present a stop button. When the stop button is clicked, the app completes recording and then show the PlaySound controller.
- **PlaySoundsViewController** : contains six buttons to play the recorded sound file with different effects related to the button image and a stop button at the bottom

*The App supports both orientations. I have varied traits for the landscape orientation of PlaySoundsViewController to make it look good with the use of stack views.*

The application uses code from `AVFoundation` to record sounds from the microphone `(AVAudioRecorder)` and play recorded audio with effects `(AVAudioPlayer, AVAudioEngine)`.

## Requirements

- Xcode 9
- Swift 4

# DJI Tello Drone Test Repo

## Description

- This repo only works as preliminary work/play with DJI Tello's SDK using Node.js.

## Future Work

- Make a Web interface (maybe though a webgl model or sth?) to beautifully display drone live data like:
    - Attitude
    - Battery status
    - Altitude
    - TOF (using on board time of flight sensors) to measure distance to vertical near object
    - Etc
- Using same Web interface to display live video feed from drone
- Making an interface to control drone remotely

## TODO
- TODO 1:
    - Implement web sockets to stream video raw data to browser interface
- TODO 4:
    - Develop Angular Interface to stream "watchable" video data (flv, mpeg, mp4, whatever) with video HTML Element

## MINOR WORK
- Send raw video stream through sockets




# LOG
- 2 nov 2019
    - Initial code project
    - Reading Tello SDK Docs
    - Implementing basic communication with drone via UDP
    - Implementing h264 data stream with drone via UDP

- 1 Jan 2020
    - Translating code doc to english
    - Adding web sockets to server app
    - Sending drone state to web browser
    - Displaying live raw state data in browser through an html table

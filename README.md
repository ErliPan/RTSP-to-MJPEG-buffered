# RTSP-to-MJPEG-buffered
Python script to convert a RTSP stream to MJPEG plus buffering


My wireless cameras sucks and cannot handle well multiple client trying to watch the video stream and also I want a MJPEG format instead of the RTSP so I can easily view it from any web browser.


This script starts to convert the RTSP stream and save every frame to the RAM when it receives a request and stops when the timeout is reached.

Each client separately requests the frames from the buffer.

<img width="718" alt="Screenshot 2023-01-08 alle 22 59 25" src="https://user-images.githubusercontent.com/45854343/211221154-8b21231e-b426-49c4-818e-4021867cc550.png">

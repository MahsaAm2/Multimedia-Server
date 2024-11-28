# ffmpeg-pusher
Use FFmpeg to push streams in formats like RTSP, RTMP, MP4, and more. The output stream codec is converted into raw video format, making it suitable for deep-learning applications.
## Project Description
This project is designed to receive video streams from a multimedia server, convert all video frames into raw RGB format, and make them compatible with deep-learning models such as YOLOv7. It is optimized for real-time performance on constrained devices, making it ideal for edge AI scenarios. The project uses ZLMediaKit for interacting with the multimedia server.
## key Features
* Real-Time Video Processing: Converts video frames into raw RGB format for real-time applications.
* Deep Learning Model Compatibility: Suitable for YOLOv7 and other models.
* Optimized for Constrained Devices: Designed for efficient performance on resource-limited hardware.
* Multimedia Server Integration: Uses ZLMediaKit for seamless multimedia server interaction.
## Requirements
* FFmpeg 5.0: Required for video decoding and stream processing.
* Linux Manjaro: The code has been compiled and tested on Linux Manjaro.
* ZLMediaKit: Used for handling multimedia server communications.
# Installation
`git clone https://github.com/MahsaAm2/Multimedia-Server.git ffmpeg`<br/>
`cd ffmpeg`<br/>
`mkdir build`<br/>
`cd build`<br/>
`cmake ..`<br/>
`make`<br/>
`./test input_stream output_stream`<br/>

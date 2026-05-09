# CameraSychronizedImager
high speed, multi language computer vision pipeline for real time detection with zero-copy shared memory

Technical:
Producer:Rust, data safe camera acquisition
processor: C++, low level monitor to calculate frame data in real time(brightness)
brain: uses YOLOv8 for object detection and mmap to map the data into an array for GPU accelerated inference

zero-copy architecture, written once and read simultaneously
cross language integratioon
real time inference

required:
NvidiaGPU, solid performance CPU
Rust
C++ compiler
Python 3.10+

use:
git clone https://github.com/Spencerhall11/CameraSynchronizedImager.git
open administrator terminal 
execute launch_all.bat

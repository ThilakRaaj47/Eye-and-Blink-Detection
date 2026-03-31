# Eye & Blink Detection System 👀

Hey there! Welcome to my Eye and Blink Detection project.

I built this system to detect human faces, track eye movements, and calculate blink rates in real-time using just a standard webcam. It uses OpenCV for the heavy lifting on object detection and dlib's 68-point facial landmark model to get highly accurate eye tracking. It's a great starting point for applications like driver drowsiness detection or accessibility tools.

## What You Need to Run This
Before you clone the code, just make sure you have these set up on your machine:
* **Python 3.13** (or a very recent 3.x version)
* **Git**
* **Microsoft C++ Build Tools** (This is super important for Windows users. `dlib` will throw a massive error if you try to install it without a C++ compiler. Make sure you check the "Desktop development with C++" box during installation).

## How to Set It Up

**1. Get the code**
Open up your terminal and grab the repository:
```bash
git clone [https://github.com/ThilakRaaj47/Eye-and-Blink-Detection.git](https://github.com/ThilakRaaj47/Eye-and-Blink-Detection.git)
cd Eye-and-Blink-Detection
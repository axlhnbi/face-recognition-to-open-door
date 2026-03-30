# Smart Door Lock with Facial Recognition Based on Raspberry Pi

A facial recognition application to open an automatic door servo operated using a Raspberry Pi. This project is built with the **Python** programming language and utilizes the **OpenCV** library for computer vision processing. The main facial recognition algorithm used in this system is the **Local Binary Pattern Histogram (LBPH)**.

---

## 📹 Application Video Demo

Watch how this application works live:
[![Video Demo](https://img.youtube.com/vi/lZdOjA3wDoU/0.jpg)](https://www.youtube.com/watch?v=lZdOjA3wDoU&t=8s)
*(Click the image or link above to watch the video on YouTube)*

---

## 🛠️ Hardware Setup

This system uses the **Raspberry Pi Camera Module V2**. Here are the steps to connect and activate the camera on your Raspberry Pi:

1. Locate the camera port on the Raspberry Pi board and connect the camera ribbon cable correctly.
2. Start up the Raspberry Pi.
3. Open the **Raspberry Pi Configuration Tool** from the main menu (or run the `sudo raspi-config` command in the terminal).
4. Navigate to the **Interface Options** menu and ensure the **Camera** feature is **Enabled**.
5. After that, reboot your Raspberry Pi to apply the settings.

---

## 💻 Software Setup

### OpenCV Installation
OpenCV is a highly popular open-source library for computer vision needs. In this project, OpenCV is used extensively to run the LBPH facial recognition algorithm.

* **Official OpenCV Documentation:** [https://opencv.org/about/](https://opencv.org/about/)
* **OpenCV Installation Guide:** For detailed steps on how to install OpenCV on a Raspberry Pi, please download and view the presentation guide at the [following OneDrive link](https://onedrive.live.com/view.aspx?resid=2AAE05B692B45603!149547&ithint=file%2cpptx&authkey=!AMJoTWk2pvH73f8).

---

## 🚀 Technologies Used

* **Programming Language:** Python
* **Hardware:** Raspberry Pi, Camera Module V2, Servo Motor
* **Computer Vision Library:** OpenCV
* **Facial Recognition Algorithm:** Local Binary Pattern Histogram (LBPH)

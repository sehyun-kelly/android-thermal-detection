# Thermal Detection Android App
<img width="694" alt="Screenshot 2023-06-27 at 8 27 31 PM" src="https://github.com/sehyun-kelly/android-thermal-detection/assets/89621420/17ad7308-cc3b-4cf1-a24d-8ffddcf504eb">

## Project Description
This Android app allows users to take a picture with a Flir One Pro thermal camera connected to an Android device then it detects the face in the picture and returns the temperature calculated from the thermal image.

The server is built using Python. The server creates a socket connection with the Android client, receives the image bytes from the client, detects and calculates the temperature, and sends back the result to the client.  



## Built With

* ![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)
* ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)




<!-- GETTING STARTED -->
## How to use the app

### Prerequisites

- Hardware: Android device, Flir One Pro Thermal Camera
- Flir One app ([Download](https://play.google.com/store/apps/details?id=com.flir.flirone&hl=en_CA&gl=US&pli=1))
- Python3 installed

### Run the app

1. Connect Filr One Pro Thermal Camera to your Android device and activate the camera on Flir One app

2. Run the Python server
```
python3 main.py
```

3. Click `START DISCOVERY` and click `CONNECT FLIR ONE` once the camera is discovered

4. Click `CAPTURE` to take a thermal picture and check the temperature of the detected face


<!-- CONTACT -->
## Contact

Kelly Park 
- sehyun.kelly.park@gmail.com
- https://www.linkedin.com/in/sehyun-kelly-park/

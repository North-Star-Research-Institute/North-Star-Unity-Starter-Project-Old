### CMU North Star Institute
# North Star Setup

1. Extract North Star Repo
2. Open ‘Unity Project - North Star & Vive Tracker’


## Importing the display calibration file for your North Star hardware
1. Your North Star hardware number is on the rear of the left display with a Roman numeral
2. Select ‘North Star + Leap Motion’ game object → ‘ARCameraRig’
3. Under ‘Optical Calibration Manger’, change ‘Input Calibration File’ to ’NS-X.json’ where X is the Arabic number of your headset
    1. All North Star calibration files are located within ‘Assets → CalibrationFiles’

## Setting up 6-DOF tracking with Vive Tracker 
1. Turn off all Vive Controllers, only the Tracker should be connected
2. Select ‘North Star + Leap Motion’ game object
    1. Under ‘Steam VR Tracker, set Device ID to 1



## OPTIONAL

Customizing the Leap Motion’s relative transform
1. Go to ’North Star + Leap Motion’ → AR CameraRig → Head → Leap Provider
2. Within ‘Leap XR Service Provider,’ under advanced, you can set ‘Device Offset Mode’ to Default, Manual Head Offset and Transform


# Helpful Links
https://github.com/leapmotion/ProjectNorthStar/

https://leapmotion.github.io/ProjectNorthStar/

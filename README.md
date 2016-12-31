# hybrid-apps-identifier
A python script to identify if an app uses and of these cross platform framworks:   
- Apache Cordova
- Appcelerator Titanium
- Adobe Air
   
## Usage   
```ddd
python hybridIdentifier.py pathToAPK   
```
Please ensure that the APK name doesn't contain spaces.   
You can easily extend the script to identify other cross platform frameworks.   
The script uses [ClassyShark](https://github.com/google/android-classyshark) to extract the list of classes from the APK.  
## Dataset of 15,000 Hybrid Apps
[cross-platform apps](https://github.com/mohamedali92/hybrid-apps)

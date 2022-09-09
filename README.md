![Xcode](resource/Xcode.png)  

# Namestey !! 
# HowTo Install Xcode (YoutubeLink : )

## What is Xcode ? 
Apple's integrated development environment for macOS, used to develop software for macOS, iOS, iPadOS, watchOS, and tvOS. 

## Three Methods to install Xcode : 

<br>

[![Install Xcode](resource/xcodeThumbnail.png)](https://www.youtube.com/watch?v=NJYDUshR-58&ab_channel=atquil)

<br>

## 1. From Apple Developer Download `Fastest`

- Go to this url and download the latest **stable** (not beta) version of XCODE: https://developer.apple.com/download/all/ 
- After downloading unzip the file by double clicking on it
![XcodePackage](resource/xcodeDownloaded.png)
  
- Move the Xcode to Application Folder

- Check the version using terminal 
```
/usr/bin/xcodebuild -version
```
## 2. Through Terminal `Geeky way`

- Go to **terminal** and type this. 

```
xcode-select --install

```
- Click on **Install** 

![Install](resource/XcodeInstall.png)

- Click on **Accept for License**

![AcceptLicense](resource/XcodeAcceptLicense.png)

- Check the version using terminal 
```
/usr/bin/xcodebuild -version
```
## 3. Who want to waste time [Slowest]

- Go to the AppStore and Type Xcode and it will show the latest version available
![AppStore](resource/xcodeFromAppStore.png) 
- Click on Get and then Install


<br>

# HowTo Uninstall Xcode

### Why to uninstall ? Xcode can take a toll on the store and performance, if memory space is running low. The best way to fix the issue to speed up the mac , is reinstall it from scratch. 

### When to uninstall ?
    - Xcode fails to compile the app / simulators constantly
    - Selling or gifting the Mac to other person 


## Steps : 

1. Move Xcode to Trash and clean the Trash bin

![Trash](resource/XcodeToTrash.png) 


2. Go to the Location and delete it

`~/Library/Developer/ `

3. In terminal do hard uninstall 

```
sudo /Developer/Library/uninstall-devtools --mode=all

```

4. Remove the Xcode Application caches if it exist

`~/Library/Caches/com.apple.dt.Xcode`



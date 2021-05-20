# Virtual-Background

### This app utilize the tensorflow lite AI to create a virtual background without a green screen
It uses less resources (CPU & Ram) compared to other alternatives

## Table of contents
- [Features](#features)
- [Configuration](#configuration)
- [Privacy policy](#privacy-policy)
- Installation
  - [Windows](#installation-for-windows)
  - [MacOS](#install-mac)
- How to use
  - [Windows](#)
  - [MacOS](#usage-mac)
- [FAQ](#frequently-asked-questions)

### Features
- Freeze the camera to reduce load
- Record a video and play it
- No watermark!

### Configuration
```
[CONFIG]

# Available options: true, false
# When changed to true, it will print the keys that you press
debug=false


# When the pause key is clicked, the frame will be freezed
pauseKey=p

# When the record key is pressed, it will start recording
# When the key is pressed again, it will stop the recording and play the video in a loop
recordKey=r

# When the normal key is pressed, all the things will turn back to normal
normalKey=n


# Available options: 0 - infinity (Integer)
# By changing the number, you can change the video input device
cameraDevice=0

# The file name of the background image
backgroundFilePath=background.jpg
```

### Privacy policy
The app doesn't collect any user data and doesn't require internet (other then checking for updates)

### Installation for Windows
- Download [OBS](https://obsproject.com/download)
- Start the OBS software
- Click the `Start Virtual Camera` button at the bottom right corner
- Click the `Stop Virtual Camera` button at the bottom right corner
- Download the [app](https://github.com/LoSunny/Virtual-Background/releases/download/v0.0.1/virtualbackground-win.exe)
- You're done

### Installation for MacOS
- Download [OBS](https://obsproject.com/download)
- Start the OBS software
- Click the `Start Virtual Camera` button at the bottom right corner
- Click the `Stop Virtual Camera` button at the bottom right corner
- Download the [app](https://github.com/LoSunny/Virtual-Background/releases/download/v0.0.1/virtualbackground-mac)
- Open the `Terminal.app`
- Type the command `chmod +x` (Don't press enter yet)
- Drag the downloaded file to the `Terminal`
- Press enter
- You're done

### Usage for Windows
- Start the `exe` file by double clicking it
- To stop, press the `X` button

### Usage for MacOS
#### Option 1 (Recommended)
##### First time setup
- Open `TextEdit.app`
- Paste the followings to the text file
```
cd "$(dirname "$0")"
./virtualbackground-mac
```
- Save the file with `.command` as the suffix (E.g. **start.comamnd**)
- Open `Terminal.app`
- Type the command `chmod u+x` (Don't press enter yet)
- Drag the file you just created ending with `.command`
- Press enter

##### After the setup
- Double click the `start.comamnd`
- To stop, press `CMD+Q`

#### Option 2 (For advanced users)
- Start the `Terminal.app`
- `cd` to the directory
- Start the executable
- To stop, press `CTRL+C`

### Frequently Asked Questions
#### Q: Is the app safe? I'm getting a "Windows protected your PC; Microsoft Defender SmartScreen prevented an unrecognised app from starting. Running this app might put your PC at risk."
That is completely normal. It is the default message for all "unsign" windows app. This message is shown because I didn't sign it as it requires :moneybag: :moneybag:

You can press "More info"

![](https://github.com/LoSunny/Virtual-Background/raw/main/docs/def1.png)

And "Run anyway" to run the app

![](https://github.com/LoSunny/Virtual-Background/raw/main/docs/def2.png)

#### Q: Why do you create your own virtual background when there is a lot of apps which does the same thing
Because most of the apps will burn my mac :cry: . And the FPS is unusable
![](https://github.com/LoSunny/Virtual-Background/raw/main/docs/burn.jpg)
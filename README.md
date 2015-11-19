# webcam-viewer
Have you ever had to display the contents of a webcam on a projector before? well I have, thats why this project exists.

## Prerequisits installation
before building the binaries, please ensure you have nodejs installed and run the following npm command to install the necessary components
```npm install -g nw nw-builder```

## Build
Assuming you've installed the pre-requisites, you should be able to build this nw.js app with nw-builder using the following command:
```nwbuild -v0.12.3 -p win64,linux64 ./app```
This command will build a linux and windows 64 bit executable which when executed will display a full screen realtime video of the currently attached webcam


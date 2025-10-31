# Important_Linux_Commands
Very useful linux commands 


## How to use HDMI video capture 
### you can use it through VLC media player or ffplay from ffmpeg 

Let's check wich USB port HDMI video capture connected with
```c
ls /dev/video*
// for more info run the following 
v4l2-ctl --list-devices
```

### to test video stream through ffplay 
sudo apt install ffmpeg
ffplay /dev/videox  // x here could be 0,1,2,3 
```


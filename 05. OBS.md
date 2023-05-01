# OBS

### Optimal Settings for OBS Live Streaming :

**Hardware :** Atleast i3 processor. (Stronger the processor, the better)
#### **Settings :**

**Stream :**  
Service : YouTube-RTMP  
Server : Primary YoutTube Ingest server  
Stream Key : <>

**Output :**  
Output Mode : Advaned  
Encoder : x264  
Rate Control: CBR  
Birate : 2500Kbps  
Keyframe Interval : 2  
Preset : Max Quality  
Profile : High  
Psycho Visual Tuning: Check  
GPU : 0  
Max B-frames: 2

**Audio :**  
Sample Rate: 48 kHz  
Channels : Stereo

**Video:**  
Base(Cavas) Resolution : 1920x1080 Aspect Ratio : 16:9  
Output(Scaled) Resolution : 1920x1080 Aspect Ratio 16:9  
Downsale Filter : Lanczos Sharpended scaling, 36 samples)  
Common FPS values : 30

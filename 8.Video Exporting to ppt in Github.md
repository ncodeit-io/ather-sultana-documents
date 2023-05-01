#   Video Exporting to ppt in Github

**Here is the process for adding the transitions and exporting the video in PowerPoint**.

1.  Open the recording-instr tracker sheet.
    
2.  open the PowerPoint file.
    
3.  Download the audio/video file of the lesson/component.
    
4.  Give the timestamps based on the audio/video file in the recording-instr sub-sheet.
    
    1.  First find the time at what time the slide has to change by using the formula (next slide changing time - previous slide) you can find the slide changing time in the recording sheet of the component id tracker sheet and then take that timing in the transitions tab at the right side click on after then enter timings there 
      
        ![](https://i.gyazo.com/5017de48bef7c7087456993096f0dca2.png)
  
        
    2.  Find the delay time by using formula (see the appear time of object then - the slide changing time <same slide>) you can find slide changing time and object appear times in recording sheet of component id tracker sheet and the take that timing in animation tab right side in delay option 
  
      ![](https://i.gyazo.com/d7086c8a420cd3c29b77bc7a653e1bbd.png)
    
  3.  Formula: select emty cell then after that we have to select the cell (which we want - with ) and then click on - then select the cell (which we want - from ) at last we have to click enter then we will get correct answer after deducting the time
        
    4.  Every time after clicking appear of object first we have to select appear with previous then have to enter delay timings in animation tab
        
    5.  Open the ppt file, insert the audio file outside (bottom left corner) of slide1
        
5.  Click on the audio file icon, playback tab will be activated at the top,
    
    1.  open the playback tab, go to audio options group, check the play across slides box if not checked.
        
6.  Go to the transitions tab,
    
    1.  Uncheck the On mouse click option in timing group, tick the after option,
        
7.  Give the duration in after option as the duration of transition duration in recording instructions. ex: if the duration is 30 seconds, give it as 00:30.00
    
8.  Repeat the same process for all the slides.
    
9.  Go to the recording tab on PowerPoint, click on Export to video,
    
10.  Choose the video resolution,
    
11.  Change the Seconds spent on each slide to 00.00
    
12.  Click on create video, save it in your system.
    
13.  Wait until the exporting finishes.

    

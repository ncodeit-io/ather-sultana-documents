# Animation Timestamps Calculation

**To add animation effects to slides in a presentation, we need to calculate the timestamps for each animation.**

1.  Determine the slide transition time for each slide in the presentation.
    
2.  Use the following formula: select an empty cell, then select the cell for the animation end time, enter a minus sign, and select the cell for the animation start time. Press enter to get the correct result after deducting the time.
    
3.  For the first slide transition, calculate the time difference between the start of the second slide and the start of the first slide.
    
4.  For subsequent slide transitions, calculate the time difference between the start of the current slide and the start of the previous slide.
    
5.  For the last slide transition, calculate the time difference between the end of the audio and the start of the previous slide transition.
    
6.  To calculate the animation time for text, subtract the slide transition time from the time at which the text appears.

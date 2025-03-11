# MegaMush
Code for the 3D printed MegaMush smart RGB LED Lamp running on a XIAO SAMD21 microcontroller. 
Following video should guide you through the build process: xxxx

**MegaMush functions:**   
- Short press: Toggles the LED's ON/OFF  
- Long press: Increments modes  
- Turning: Normally sets brightness, if in freeColor mode it selects color while LED's blink (last modes)  

**Modes:**    
    
1:    changes between rainbow, rainbowWithGlitter, confetti, sinelon, juggle and bpm patterns every 10th second    
2..7: each of the patterns above fixed    
8/9:  select static color of outer and inner LED's    
9/10: select static color on all LED's


**Encoder library:**
        https://github.com/PaulStoffregen/Encoder

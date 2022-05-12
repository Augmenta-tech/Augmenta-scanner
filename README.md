# Augmenta-scanner

Augmenta Scanner is an Ableton M4L Plugin to produce music from interactions between scan bar and persons or objects movments. This tool use XY coordinate of differents sources in order to interact with the scan position. Use the Augmenta tracking system or any XY OSC coordinates to run the plugin.

![Augmenta Scanner](https://user-images.githubusercontent.com/104997324/168056622-5e7acc6c-66e2-4b23-a064-c0edcf1ed99f.gif)


## Features

Drag'n drop the scanner plugin to Ableton session in MIDI track and trigger MIDI note when persons or objects passes over the scan bar. The plugin has been developed to be drag and drop just once in the ableton session. If you put several in the session, latency and synchronization problems occur.

### Input
- OSC Input
- 6 persons simultaneous tracking
- Simulate with Augmenta Simulator
- Mute option

### Areas
- 6 areas for MIDI notes triggers :

          - Mute Button to disable MIDI out of the selected person or object
          - MIDI note selector
          - Velocity and Duration control of the MIDI note
          - Button to enable Random mode
          - Speed control of random rate
          - Random notes choice menu

- Scales menu : 

          - Min
          - Maj
          - Scales selector
          - Octave selector (When the oct1-4 mode is selected, the octave of notes triggered by persons/objects depends on their position on the bar. If they are down  the octave will be low and the higher they go the higher the octave increases).
        
 All feature of the scales menu working only when random mode is activated.

- Scanner areas :

         - Start/Stop scanner shift
         - Speed control of the scan bar
         - Choose horizontal or vertical scan
         - Mapping option of the scan shift (between 0-1)
         - Controle the slider with the mouse to move the scan bar as you want (when the scan shift toggle is on stop mode).
         - Sync the movement of the scanner with your Ableton Master tempo (option between 1, 2 and 4 bar)
         
- Preview window automatically adjusts according to scene size

- Viewer toggle allows you to see the scene larger.

### Output
- OSC output to touchdesigner for more advance visuals project to the floor

## USE
This tool was made to be used as a creative instrument in Ableton Live. Do not hesitate to experiment with the plugin in order to make your project and composition idea interactive. Have fun !

## TouchDesigner

IP and port outputs to touchdesigner are accessible with the plugin. They send the scanner movement data, and the people passing information on the scan bar. 
You can use the touchdesigner example session available in this gituhb.

<p align="center">
![TDMovieOut 0](https://user-images.githubusercontent.com/104997324/168085144-4439c682-2fae-4081-915c-b87bc621d915.gif)
</p>

## Credits

Designed & developped by Guillaume BREVET & AUGMENTA

# Augmenta-scanner

Augmenta Scanner is an Ableton live plugin (Max4Live) to create music in interaction with performers or objects in space tracked with Augmenta.
A bar is scanning the space and triggers midi notes when passing over a performer. The plugin receives Augmenta OSC data as inputs and produces midi notes and mappings for Ableton live.

![Augmenta Scanner](https://user-images.githubusercontent.com/104997324/168056622-5e7acc6c-66e2-4b23-a064-c0edcf1ed99f.gif)


## How to use

- Download the files from this repository or from https://maxforlive.com/
- Drag'n drop the scanner plugin to Ableton session in a MIDI track
- Add your port to receive Augmenta osc data
- Create music with the scan bar and objects available

To produces Augmenta data, you can use the simulator available here : https://github.com/Augmenta-tech/Augmenta-Simulator/releases

Note : The plugin has been developed to be used once per Ableton session. If you put several plugins in the session, latency and synchronization problems can occur.

## Features

- Augmenta osc input
- 6 persons simultaneous tracking or all persons with the same behavior (red target)
- Simulate Augmenta data with Augmenta Simulator
- Follow tempo option for the scanner
- Osc output to send scanner bar to other softwares (see Touch designer example)

## Interface
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

## TouchDesigner example

The scanner bar can be sent to other software with the OSC Output.

How to use
- Start Touch Designer example
- In Augmenta scanner : Add the ip and port output to Touch Designer
- In Augmenta simulator or Fusion : Send Augmenta data to Touch Designer

Enjoy the visuals :)

![TDMovieOut 0](https://user-images.githubusercontent.com/104997324/168085144-4439c682-2fae-4081-915c-b87bc621d915.gif)

## Credits

Designed & developped by Guillaume BREVET, David-Alexandre CHANEL and Romain CONSTANT + the Augmenta team

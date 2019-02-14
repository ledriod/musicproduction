# Lesson 1: MIDI Sequencing

- MIDI messages
- Sequencing
- The Transport
- The Arrange Window
- Menus and Transport Display
- Getting Ready to Record
- Bars, Beats, and Subdivisions
- Metronome Settings
- MIDI Recording
- Record Modes: Replace and Overdub
- Loop Recording
- Step Recording
- Standard MIDI files


MIDI (Musical Instrument Digital Interface)


## Review of the MIDI standard

- allow keyboards and synthesizers from different companies to interact with each other
- based on 16 independent channels
- MIDI messages do not contain any information about audio
- the sequencer send the notes to the synthesizers and sound modules connected to the MIDI system to play, like to the  paper score
- Every device must have a MIDI interface. The MIDI standard uses three ports to control the data flow: IN, OUT, and THRU

- two main MIDI configurations: daisy-chain (DC) or start network (SN)

![01](L1-Basis/L1-Basis-01-01.jpg)

__Midi Chain network__

![02](L1-Basis/L1-Basis-01-02.jpg)

__Midi Star network__


## MIDI messages

__System messages:__

- System real-time:
  - timing clock
  - start, 
  - stop,
  - continue, 
  - active sensing, 
  - system reset
- System common: 
  - MTC, 
  - Song position pointer,
  - song select, 
  - tune request, 
  - end of SysEx
- System exclusive


__Channel messages:__

- Channel voice: 
  - Note on, 
  - Note off, 
  - Monophonic aftertouch, 
  - Polyphonic aftertouch, 
  - Control changes, 
  - Pitch bend, 
  - Program change
- Channel mode: 
  - All notes off, 
  - Local control (on/off), 
  - Poly on/mono on, 
  - Omni on, 
  - Omni off, 
  - All sound off, 
  - Reset all controllers  










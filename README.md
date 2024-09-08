Presence/Movement Detection Keyboard (Max for Live Instrument)
Overview
This project is a custom software instrument for Ableton Live, designed using Max 8 and Max for Live. The instrument detects movement and presence through a webcam feed and converts that data into MIDI signals, allowing it to be used with any instrument in Ableton Live. The result is a dynamic, motion-responsive MIDI controller capable of triggering MIDI notes and chords in real-time based on the user's movement.

Features
Movement Detection: Uses Jitter, the video processing component of Max, to detect movement through a live webcam feed. The instrument tracks changes in brightness levels (black and white) within predefined panels on the screen.
Threshold-Based Triggers: Each panel on the screen has a customizable threshold. When the detected brightness level exceeds the set threshold, it triggers a MIDI signal.
MIDI Signal Generation: The instrument can trigger individual notes or a four-note chord, depending on the configuration. Each detected movement corresponds to a different MIDI pitch, allowing for creative and interactive control over the sound.
Max for Live Integration: This is a Max for Live device, meaning it can be used as a MIDI source within Ableton Live and connected to any Ableton instrument or external MIDI device.
Requirements
Ableton Live (with Max for Live integration)
Max 8 (for editing and modifying the patch, optional)
A webcam for movement detection
How It Works
The instrument uses Jitter to analyze the input from a connected webcam. The feed is converted into black-and-white levels, which are split across several panels on the screen.
Each panel has a customizable threshold that determines when movement is significant enough to trigger a MIDI signal. When movement or presence is detected in a panel (i.e., when the brightness level exceeds the threshold), a MIDI note is triggered.
The triggered MIDI notes can either be individual pitches or form a four-note chord, based on the current configuration.
Since this is a Max for Live instrument, it can be easily used within Ableton Live as a MIDI source, allowing you to route the MIDI output to any Ableton instrument or even external synthesizers and instruments.
Installation
Download the .maxpat file from this repository.
Open Ableton Live and drag the .maxpat file into a MIDI track.
Connect a webcam to your computer for motion detection.
Configure the instrument's settings (such as thresholds and chord options) to your preference.
Use the instrument to trigger MIDI notes in any Ableton instrument or external MIDI hardware.
Usage
Set up the webcam feed: Ensure your webcam is correctly capturing movement. The instrument will begin analyzing brightness levels as soon as it's activated.
Adjust the threshold: Customize each panel’s threshold for detecting movement based on your environment.
Configure MIDI output: Choose whether the instrument triggers individual notes or four-note chords.
Play: Use your body or objects to trigger MIDI signals through the webcam feed, and listen as your movements create dynamic sounds in real-time.

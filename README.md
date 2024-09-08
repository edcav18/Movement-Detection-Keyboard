Presence/Movement Detection Keyboard (Max for Live Instrument)

Overview
This project is a custom software instrument for Ableton Live, designed using Max 8 and Max for Live. The instrument detects movement and presence through a webcam feed and converts that data into MIDI signals, allowing it to be used with any instrument in Ableton Live. The result is a dynamic, motion-responsive MIDI controller capable of triggering MIDI notes and chords in real-time based on the user's movement.

Features
- Movement Detection: Uses Jitter, the video processing component of Max, to detect movement through a live webcam feed. The instrument tracks changes in brightness levels (black and white) within predefined panels on the screen.
- Threshold-Based Triggers: Each panel on the screen has a customizable threshold. When the detected brightness level exceeds the set threshold, it triggers a MIDI signal.
- MIDI Signal Generation: Each detected movement corresponds to a different MIDI pitch, allowing for creative and interactive control over the sound.
- Max for Live Integration: This is a Max for Live device, meaning it can be used as a MIDI source within Ableton Live and connected to any Ableton instrument or external MIDI device.

Requirements
- Ableton Live (with Max for Live integration)
- Max 8 (for editing and modifying the patch, optional)
- A webcam for movement detection

How It Works
1. The instrument uses Jitter to analyze the input from a connected webcam. The feed is converted into black-and-white levels, which are split across several panels on the screen.
2. Each panel has a customizable threshold that determines when movement is significant enough to trigger a MIDI signal. When movement or presence is detected in a panel (i.e., when the brightness level exceeds the threshold), a MIDI note is triggered.
4. Since this is a Max for Live instrument, it can be easily used within Ableton Live as a MIDI source, allowing you to route the MIDI output to any Ableton instrument or even external synthesizers and instruments.

Installation
1. Download the .maxpat file from this repository.
2. Open Ableton Live and drag the .maxpat file into a MIDI track.
3. Connect a webcam to your computer for motion detection.
4. Configure the instrument's settings (such as thresholds and quadrant pitches) to your preference.
5. Use the instrument to trigger MIDI notes in any Ableton instrument or external MIDI hardware.

Usage
1. Set up the webcam feed: Ensure your webcam is correctly capturing movement. The instrument will begin analyzing brightness levels as soon as it's activated.
2. Adjust the threshold: Customize each panel’s threshold for detecting movement based on your environment.
4. Play: Use your body or objects to trigger MIDI signals through the webcam feed, and listen as your movements create dynamic sounds in real-time.

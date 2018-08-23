# MIDINetworkSetup
Apple script to auto-reconnect your MIDI device to the MIDI network session on OSX

If you happen to develop iOS apps with XCode and you want the simulator to connect over a Network session with your MIDI devices, you might have been annoyed so far that at each re-run, you need to go to MIDI Network Setup, click the simulator and then click Connect to join it to the session again and again. Well... no more. :)

## Instructions to use:
- make sure you have cliclick installed. Otherwise: `brew install cliclick`
- Open up a new applescript window
- Copy paste the script.txt
- Run it and leave it running. At each couple of seconds (while you are on not on fullscreen - simulator anyway doesn't work fullscreen) it will do the magic.

Optional: Replace in the script "iPhone Simulator" with whatever you want to connect to your session

Feel free to improve it and push changes.

Enjoy!

/Cosmin

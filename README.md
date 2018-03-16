# musicmaker

Use this command to install fluid synth
sudo apt-get install vlc-plugin-fluidsynth

This command will convert the midi to mp3 file
cvlc -vvv --sout "#transcode{acodec=mp3,ab=128,channels=2,samplerate=44100}:std{access=file,mux=raw,dst=song-name.mp3}" song-name.mid

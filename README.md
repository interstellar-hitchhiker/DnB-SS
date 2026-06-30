# DnB-Sound-Station

DnB / big-beat sound station as a single HTML file.

What it has:

Start / Play / Stop / Panic stop
BPM control from slow big-beat / halftime up to fast DnB
Preset worlds: rave roller, neuro storm, liquid night, big-beat 132, halftime menace, orbital drift
Mixer faders for kick, snare, hats, bass, synth, FX, master
Toggle parts on/off: drums, bass, stabs, pad, arp, glitch FX, voice
Clickable drum grid for kick, snare, hats, ghost notes
Bass note selector
Random beat, mutate, fill, drop, breakdown, bassline shift
Text-to-speech voice stabs
Audio recording to WebM
Pattern save/load as JSON
Animated visualizer

Important browser note: it uses Tone.js from a CDN, so the file is single-file for your app code, but it needs internet access to fetch the audio library. Also, browser audio will stay silent until you click Start audio, because Chrome blocks autoplay sound.

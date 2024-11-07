## CSE471-Project1
### Group Member: Swabhan Katkoori
Effects: Swabhan Katkoori

Wavetable Synthesis: Swabhan Katkoori

### Format of Score Files
	<note measure="1" beat="1" duration="1.0" note="C4" playbackRate="1.0" sustainLevel="0" sustainDuration="0" decay="0" releaseThreshold="0"/>


### Score Files
##### Score files are in score folder
*The score files were generated with AI

Full score file: [01_full.score](https://github.com/SwabhanKatkoori/Project1/blob/main/Scores/full.score)

Shorter piece file for Wavestyle Synthesizer: [02_WavetableSynthesizer](https://github.com/SwabhanKatkoori/Project1/blob/main/Scores/wavetableSynth.score)
The effects component and all features of Wavetable Synthesizer are built off of the above score file

### Audio Samples
##### .wav files are in sounds folder

[01_full]([https://github.com/SwabhanKatkoori/Project1/blob/main/Sounds/full.wav](https://github.com/SwabhanKatkoori/Project1/blob/main/Sounds/final.zip))

[02_WavetableSynthesizer](https://github.com/SwabhanKatkoori/Project1/blob/main/Sounds/wavetableSynth.wav)

[03_Noise Gating_effect](https://github.com/SwabhanKatkoori/Project1/blob/main/Sounds/wavetableSynthNoiseGate.wav)

[04_Compression effect](https://github.com/SwabhanKatkoori/Project1/blob/main/Sounds/wavetableSynthCompress.wav)

[05 Reverbation Effect](https://github.com/SwabhanKatkoori/Project1/blob/main/Sounds/wavetableSynthReverb.wav)

### Component Descriptions
#Effect
The effect component resides in the Effect class where the audio flows through and provides the option to add a Compression, Noise Gating, or Reverberation effect.

#Wavetable synthesis
The wavetable provides various shapes created mathematically and can be applied to an audio stream working with envelope and pitch. The code for the wavetable synthesis resides in CToneInstrument class. Within the CToneInstrument, there is also functionality to work well with different types of XML files. 

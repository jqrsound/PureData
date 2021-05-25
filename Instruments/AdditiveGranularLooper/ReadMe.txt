Additive Granular Looper v0.7 - Manual
Alessandro Ielo - jqrsound.com

Signal Flow: 
OSC->Granular->Compressor->GEQ->LPF->Looper->Delay->Reverb

Osc_Plus and Osc_Max are two sound sources based on additive synthesis: they contain 8 sine waves tuned together to create beats and dissonances. The Timbre Plus/Max fader mixes these two sources.

This patch has 4-voice polyphony and their amount of harmonics is constantly varied pseudo-randomly at each Note On.

The LFO Color setting decides the pseudo-random seed (the higher the number, the wider the range) and together with LFO Rate and Amount controls the speed and amount of harmonic changes.

ADSR controls the envelope of the played notes only, it does not affect the Granular or the Looper modules.

After every Osc Voice there is a Granular module. When the box "Arm to record" is ticked, its recording is activated at each Note On. It’s possible to change the general pitch, sample start and timbre with its controls. Balance defines the relation between notes that are being played and previously recorded notes.

After the Granular there are the Graphic Equalizer and the Filter. When On, Wave selects between Sine and Saw, while Rate and Amount control the speed and amount of the filter sweep.

After the Filter comes the Looper, its recording is activated with the "Press to record" button in its section. It’s possible to change the pitch, sample start and timbre with its controls. Balance defines the relation between Granular and Looper.

The Time fader in the Delay module controls the repetitions in ms. When On, LFO Rate and Amount control the speed and amount of the delay Time.

The IR Reverb contains four responses recorded by me in Berlin (bridges, subway stations etc). IR Wave chooses which IR is analysed, LPF and HPF filter out excess frequencies and Volume determines the ratio between dry signal and reverb.



Beta Tester:
.Chelidon Frame // Alessio Premoli
.Dimitri "Error 500" De Franciscis


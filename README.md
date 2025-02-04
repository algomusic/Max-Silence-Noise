This repository includes a Pure Data implementation of a novel approach to ring modulation synthesis, termed Maximum Silence to Noise (MSN).

The primary objective of MSN is to enable musical instruments capable of producing a broad and diverse range of audio spectra that can be simply, yet expressively, articulated.

At the heart of MSN/AV is a novel implementation of ring modulation that features two identical oscillators. These oscillators morph from silence to white noise, passing through sine, square and pulse waveforms. This morphing capability enables a smooth transition from simple to complex audio spectra. 

The term ‘maximum silence’ addresses an issue where no sound results from the ring modulator when either of the modulating oscillators is silent. To keep the modulation amount independent of the amplitude envelope, a DC offset ‘silence’ signal is output to maintain the amplitude of the other modulating oscillator. As the amplitude of the modulating oscillator decreases, the DC offset is increased to keep the gain of the modulated signal consistent.

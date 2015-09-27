# AidaDSP

AidaDSP is a shield for Arduino and TivaC boards.
Basically, you have a small but powerful DSP from Analog Devices
capable of 24bit-48/96/192kHz audio processing on the fly.

What you can do with this board?
� 1st and 2nd order equalizers with adjustable f, Q, gain
� Processors with peak or rms detection for monochannel
  and multichannel dynamics
� Mixers and splitters
� Tone and noise generators
� Fixed and variable gain
� Loudness
� Delay 
� Stereo enhancement
� Dynamic bass boost
� Noise and tone sources
� FIR filters
� Level detectors
� GPIO control and conditioning
� Special function to update DSP parameters in real-time without clicks and pops
� More...since you can program your own processing block at low level
 
Thanks to our library (AidaDSP's official library on Github https://github.com/AidaDSP) you can
integrate the control of this DSP in the Arduino enviroment.
You can do things like remote EQ (just use our library and your favourite bluetooth module, and you're done)
or more complex, with algorithms spanning from pro audio multiband compressors to beam forming techniques.
Audio ethusiasts, this board is for you!!!

NOTE: this solution is SUPERIOR to ANY present and future DSP system based on a microcontroller with external Codec.
Microcontrollers, once very similar to DSPs, are a whole DIFFERENT story. The hardware of this DSP is DEDICATED
for audio processing, for example you have 56-bit accumulator wich gives you room for internal algorithm gains without the 
risk for clipping. Ready to use algorithms cell has been coded and optimized in ASSEMBLER by Analog Devices Engineers.

2015 Aida Team
www.aidadsp.com

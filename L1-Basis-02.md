# Lesson 2: Sound and Signals

- Sound propagation
- Sound properties
- Decibels
- dB - SPL
- dB Reference Scales: dBu, dBV
- Operating levels: +4dB, -10-dB
- Mic Levels
- Balanced vs Unbalanced
- Analog Connectors
- Audio Specifications
- Noise Floor
- Signal to Noise Ratio
- Frequency Bandwidth
- Frequency Response
- Distortion
- Head Room
- Dynamic Range
- Studio Set-Up


## The Sine Wave

The weight in picture moves in what is called simple harmonic motion. Vibration or oscillation is possible because 
of the elasticity of the spring and the inertia of the weight. 

![img](L1-Basis/L1-Basis-02-01.jpg)

__Propagation of Sound__

![img](L1-Basis/L1-Basis-02-02.jpg)

The speed of sound in air is about 1,240 km/hr at normal temperature and pressure.

![img](L1-Basis/L1-Basis-02-03.jpg)

the pressure at the crests is higher than the prevailing atmospheric barometric pressure and the troughs lower than the atmospheric pressure, as shown in the sine wave of picture. These fluctuations of pressure are very small indeed. The faintest sound the ear can hear (20 μPa) exists at a pressure some 5,000 million times smaller than atmospheric pressure. Normal speech and music signals are represented by correspondingly small ripples superimposed on the atmospheric pressure.


## Waves

### Wavelength and Frequency

A sine wave is illustrated

![img](L1-Basis/L1-Basis-02-04.jpg)

Wavelength (m) = Speed of sound (m/sec) / Frequency (Hz)

Frequency (Hz) = Speed of sound / Wavelength


### Complex Waves

Combining A and B at each point in time, the waveshape graph (C) is obtained. The process can be reversed.

![img](L1-Basis/L1-Basis-02-05.jpg)

The complex waveform (E) can be disassembled to the simple f1 , f2 , and f3 sine components by either acoustical or electronic filters. 


### Phase

In previouse picture, all three components, f1 , f2 , and f3 , start from zero together. This is called an in-phase condition.

the crankshaft of an automobile engine was equated with one cycle of simple harmonic motion of the piston.

![img](L1-Basis/L1-Basis-02-06.jpg)

- One complete sine-wave cycle represents 360° of rotation. 
- sine wave of identical frequency is delayed 90°, its time relationship to the first one is a quarter wave late
- A half-wave delay would be 180°, and so on. 
- For the 360° delay, the waveform synchronizes with the top one, reaching positive peaks and negative peaks simultaneously and producing the in-phase condition.

![img](L1-Basis/L1-Basis-02-06-01.jpg)

The phase angle is obtained by multiplying the angular velocity ω by the time t . Note that the angular velocity is measured in radians per second, whereas frequency f is measured in rotations per second or hertz. As a radian is unit distance at unit radius (about 57°), then there are 2 π radians in one rotation. Thus the phase angle at a time t is given by sinωt or sin2 πft .

![img](L1-Basis/L1-Basis-02-06-02.jpg)

 When plotted on the same graph, the two waveforms are phase shifted with respect to one another. 


## Harmonic analysis

[wiki: Harmonic analysis](https://en.wikipedia.org/wiki/Harmonic_analysis)

Harmonic analysis is a branch of mathematics concerned with the representation of functions or signals as the superposition of basic waves, and the study of and generalization of the notions of Fourier series and Fourier transforms (i.e. an extended form of Fourier analysis). 

![img](https://upload.wikimedia.org/wikipedia/commons/thumb/a/a6/Bass_Guitar_Time_Signal_of_open_string_A_note_%2855_Hz%29.png/640px-Bass_Guitar_Time_Signal_of_open_string_A_note_%2855_Hz%29.png)

Bass-guitar time signal of open-string A note (55 Hz)

![img](https://upload.wikimedia.org/wikipedia/commons/thumb/0/08/Fourier_Transform_of_bass_guitar_time_signal.png/640px-Fourier_Transform_of_bass_guitar_time_signal.png)

Fourier transform of bass-guitar time signal of open-string A note (55 Hz)

__Harmonics__

- 100 Hz, base signal
- 200 Hz, 2 harmonic
- 300 Hz, 3 harmonic
- 400 Hz, 4 harmonic
- 500 Hz, 5 harmonic
- 600 Hz, 6 harmonic
- 700 Hz, 7 harmonic
- 800 Hz, 8 harmonic


__Spectrum__

The commonly accepted scope of the audible spectrum is 20 Hz to 20 kHz; the range is one of the specific characteristics of the human ear. Here, in the context of sine waves and harmonics, we need to establish the concept of spectrum.

several waveform have been captured from the screen of an oscilloscope. To the right of each capture is the spectrum of that particular signal. The spectrum tells how the energy of the signal is distributed in frequency. 

![img](L1-Basis/L1-Basis-02-07.jpg)

the spectrum of the square wave shown in picture, graph(C).

![img](L1-Basis/L1-Basis-02-08.jpg)

picture shows a square wave; it can be synthesized by adding harmonics to a fundamental. However, many harmonics would be needed. For example, graph(B) shows the waveform that results from adding two nonzero harmonic components, and graph(C) shows the result from adding nine nonzero harmonic components. This demonstrates why a bandlimited “square wave” does not have a square appearance.



## Electrical, Mechanical, and Acoustical waves

An acoustical system can be represented in terms of an equivalent electrical or mechanical system, the mathematical approach is the same for different oscillators.

- acoustical system: loudspeaker

![img](L1-Basis/L1-Basis-02-09.jpg)




## Sound Levels and the Decibel

### The Decibel

The decibel is a logarithmic measuring system and has its origins in telephony where the loss in a cable is a logarithmic function of the length. Human hearing also has a logarithmic response with respect to sound pressure level. In order to relate to the subjective response, audio signal level measurements also have to be logarithmic and so the decibel was adopted for audio.

- log(1)=0     ;  `10**0 is 1`
- log(100)=2   ;  `10**2 is 100`
- log(300)=2.47;
- log(1000)=3  ;  `10**3 is 1000`

Logarithms were developed by mathematicians before the availability of calculators or computers to ease calculations such as multiplication, squaring, division, and extracting roots. The advantage is that, armed with a set of log tables, multiplication can be performed by adding and division by subtracting. 

- 2 * 4 = ?
- log 2 + log 4
- 0.30103 + 0.6020599 = 0.9030899
- antilog 0.9030899 = 8

The logarithmic unit of measurement in telephones was called the Bel after Alexander Graham Bell, the inventor. Figure shows that the Bel was defi ned as the log of the power ratio between the power to be measured and some reference power. Clearly the reference power must have a level of 0 Bels, as log 10 1 is 0.

![img](L1-Basis/L1-Basis-02-10.jpg)

The Bel was found to be an excessively large unit for practical purposes and so it was divided into 10 decibels, abbreviated dB with a small d and a large B and pronounced `deebee`. Consequently, the number of dBs is 10 times the log of the power ratio. 

- the reference is 1 mW into 600 Ω the units will be dB(m)
- the dB(W) , which is power relative to 1 W, in radio engineering
- in audio are often done by measuring the signal voltage using 0.775 V as a reference in a circuit whose impedance is not necessarily 600 Ω 

on picture above graph(b), shows that as the power is proportional to the square of the voltage, the power ratio will be obtained by squaring the voltage ratio. As squaring in logs is performed by doubling, the squared term of the voltages can be replaced by multiplying the log by a factor of two. To give a result in dBs, the log of the voltage ratio now has to be multiplied by 20.

![img](L1-Basis/L1-Basis-02-11.jpg)

Modern practice is to use low-output impedance sources with high-impedance loads. In professional analog audio systems, impedance matching is not only unnecessary but also undesirable. 

- Voltages measured in this way are expressed in dB(u), the most common unit of level in modern analog systems. The reference remains at 0.775 V. 

-  a sound-level meter reading is a certain sound-pressure level (SPL), 20 log (p/p ref ). For sound in air the standard reference pressure is 20 μPa (micropascals). This is a very small sound pressure and corresponds closely to the threshold of human hearing at 1 kHz. 

![img](L1-Basis/L1-Basis-02-12.jpg)


### Acoustic Power

A 100-W amplifier may be driving a loudspeaker, but loudspeaker efficiency (output for a given input) is very low, perhaps on the order of 10%. A typical loudspeaker might radiate 1 W of acoustic power. 

Doubling amplifier power from 1 to 2 W is a 3-dB increase in power level (10 log 2 = 3.01). Similarly, an increase in power from 100 to 200 W or 1,000 to 2,000 W yields the same 3-dB increase in level. 

![img](L1-Basis/L1-Basis-02-13.jpg)

lists sound pressure and sound-pressure levels of some common sounds. There is a vast difference in sound pressure from 0.00002 Pa (20 μPa) to 100,000 Pa, but this range is reduced to a convenient form when expressed in sound levels. 

![img](L1-Basis/L1-Basis-02-14.jpg)





# Digial Audio

## Audio sampling

An analogue audio signal is a time-continuous electrical waveform and the A/D convertor’s task is to turn this signal into a time-discrete sequence of binary numbers. The sampling process employed in an A/D convertor involves the measurement or ‘sampling’ of the amplitude of the audio waveform at regular intervals in time (see Figure 8.7). From this diagram it will be clear that the sample pulses represent the instantaneous amplitudes of the audio signal at each point in time. 

![pic](L1-Basis/L1-Basis-03-01.jpg)


### Filtering and aliasing

 few samples are taken per cycle of the audio signal then the samples may be interpreted as representing a wave other than that originally sampled. This is one way of understanding the phenomenon known as aliasing. An ‘alias’ is an unwanted representation of the original signal that arises when the sampled signal is reconstructed during D/A conversion.

![pic](L1-Basis/L1-Basis-03-02.jpg)

Before modulation the audio signal has a frequency spectrum extending over the normal audio range, known as the baseband spectrum (upper diagram).The shape of the waveform and its equivalent spectrum is not significant in this diagram – it is just an artist’s impression of a complex audio signal such as music.The sampling pulses, before modulation, have a line spectrum at multiples of the sampling frequency, which is much higher than the highest audio frequency (middle diagram).The frequency spectrum of the pulse-amplitude-modulated (PAM) signal is as shown in the lower diagram. In addition to the ‘baseband’ audio signal (the original audio spectrum before sampling) there are now a number of additional images of this spectrum, each centred on multiples of the sampling frequency. Sidebands have been produced either side of the sampling frequency and its multiples, as a result of the amplitude modulation, and these extend above and below the sampling frequency and its multiples to the extent of the base bandwidth. In other words these sidebands are pairs of mirror images of the audio baseband.

![pic](L1-Basis/L1-Basis-03-03.jpg)

It is relatively easy to see why the sampling frequency must be at least twice the highest baseband audio frequency from picture below. It can be seen that an extension of the baseband above the Nyquist frequency results in the lower sideband of the first spectral repetition overlapping the upper end of the baseband and appearing within the audible range that would be reconstructed by a D/A convertor. Two further examples are shown to illustrate the point – the first in which a baseband tone has a low enough frequency for the sampled sidebands to lie above the audio frequency range, and the second in which a much higher frequency tone causes the lower sampled sideband to fall well within the baseband, forming an alias of the original tone that would be perceived as an unwanted component in the reconstructed audio signal.

![pic](L1-Basis/L1-Basis-03-04.jpg)

The aliasing phenomenon can be seen in the case of the well-known ‘spoked-wheel’ effect on films, since moving pictures are also an example of a sampled signal. In film, still pictures (image samples) are normally taken at a rate of 24 per second. If a rotating wheel with a marker on it is filmed it will appear to move round in a forward direction as long as the rate of rotation is much slower than the rate of the still photographs, but as its rotation rate increases it will appear to slow down, stop, and then appear to start moving backwards. one would arrange to filter out moving objects that were rotating faster than half the frame rate of the film.

In basic convertors, therefore, it is necessary to filter the baseband audio signal before the sampling process, as shown on the picture below, so as to remove any components having a frequency higher than half the sampling frequency. It is therefore clear that in practice the choice of sampling frequency governs the high frequency limit of a digital audio system.

![pic](L1-Basis/L1-Basis-03-05.jpg)

In real systems, and because filters are not perfect, the sampling frequency is usually made higher than twice the highest audio frequency to be represented, allowing for the filter to roll off more gently. The filters incorporated into both D/A and A/D convertors have a pronounced effect on sound quality, since they determine the linearity of the frequency response within the audio band, the slope with which it rolls off at high frequency and the phase linearity of the system. In a non-oversampling convertor, the filter must reject all signals above half the sampling frequency with an attenuation of at least 80 dB. Steep filters tend to have an erratic phase response at high frequencies and may exhibit ‘ringing’ due to the high ‘Q’ of the filter. Steep filters also have the added disadvantage that they are complicated to produce. Although filter effects are unavoidable to some extent, manufacturers have made considerable improvements to analogue antialiasing and reconstruction filters and these may be retro-fitted to many existing systems with poor filters. A positive effect is normally noticed on sound quality.

The process of oversampling and the use of higher sampling frequencies (see below) has helped to ease the problems of such filtering. Here the first repetition of the baseband is shifted to a much higher frequency, allowing the use of a shallower anti-aliasing filter and consequently fewer audible side effects.


### Sampling frequency and sound quality

The choice of sampling frequency determines the maximum audio bandwidth available. There is a strong argument for choosing a sampling frequency no higher than is strictly necessary, in other words not much higher than twice the highest audio frequency to be represented.

Picture below shows commonly encountered sampling frequencies.

![pic](L1-Basis/L1-Basis-03-06.jpg)

Doubling the sampling frequency leads to a doubling in the overall data rate of a digital audio system and a consequent halving in storage time per megabyte. It also means that any signal processing algorithms need to process twice the amount of data and alter their algorithms accordingly. It follows that these higher sampling rates should be used only after careful consideration of the merits.



### Quantising

After sampling, the modulated pulse chain is quantised. In quantising a sampled audio signal the range of sample amplitudes is mapped onto a scale of stepped binary values, as shown on the picture below. 

![pic](L1-Basis/L1-Basis-03-07.jpg)

Quantising error is an inevitable side effect in the process of A/D conversion and the degree of error depends on the quantising scale used.  The more bits, the more accurate the process of quantisation.

- 4 bit scale offers 16 possible steps
- 8 bit scale offers 256 steps
- 16 bit scale 65 536




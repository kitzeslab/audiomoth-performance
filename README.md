[![DOI](https://zenodo.org/badge/327415136.svg)](https://zenodo.org/badge/latestdoi/327415136)

## About the [AudioMoth Performance Testing report](https://github.com/kitzeslab/audiomoth-performance/blob/main/report.md)

*This report characterizes the audio recording performance of the
AudioMoth ARU with on- and off-axis frequency response curves and polar
sensitivity charts. Metrics are reported for recordings in free space
and in various protective housings. It includes tests from an open
grassland environment and a mixed second-growth forest and reports the
effects of strapping AudioMoths to trees of different sizes.*

Correspondence: `sam.lapp at pitt.edu`

#### Suggested citation
The report is licensed under [CC-BY-4.0](https://creativecommons.org/licenses/by/4.0/). Please feel free to use it with attribution. You may cite the report as follows, replacing the `<>` with the DOI listed on this GitHub repository.

```
Lapp, Samuel (2020). AudioMoth Performance Testing: 
A quantitative report of audio recording quality for 
the AudioMoth. GitHub repository: 
https://github.com/kitzeslab/audiomoth-performance. DOI: <>
```

A short summary of the findings in the report is given below, and is also available as a [PDF (summary)](https://github.com/kitzeslab/audiomoth-performance/blob/main/summary.pdf). Here is the [full report](https://github.com/kitzeslab/audiomoth-performance/blob/main/report.md).

## Summary

The [AudioMoth](https://www.openacousticdevices.info/) acoustic logger 
by Open Acoustic Devices has the ability
to capture accurate soundscape recordings, but adding protective
housings and placing them on trees can significantly alter the
sensitivity and frequency response. Pink noise recordings were used to
analyze the frequency-dependent sensitivity of the AudioMoth in three
housings and two environments (open grassland, forest).

The on-axis frequency response of the audiomoth without a case is mostly
flat, with a 10 dB boost above 3 kHz (blue line in plot below). Of the
three housings tested (Ziplock bag, vacuum seal bag, laser-cut case),
the vacuum sealer bag (sealed but not vacuumed) caused the least
reduction of signal, while the hard-sided laser cut case caused a
significant reduction of low-frequency content. It's possible that the loss
of low-frequency content may occur with other hard cases as well.

![image](/pngs/X1_fr_each_case.png)

In an open environment, with or without housing, high-frequency sounds
(\>10 kHz) arriving from behind the device strongly are attenuated. When
the AudioMoth is deployed by strapping it on a tree, sounds arriving
from behind the device are attenuated by about 10 dB below 1 kHz and 20
dB or more above 1 kHz. Also, a notch filter occurs at a specific
frequency (about 2.3 kHz) when sound arrives from directly in front of
the device.

![image](/pngs/X2_trees.png)

Protective housings and placement on trees clearly cause significant
reductions of sensitivity to certain frequencies. These effects should
be considered during the deployment of recorders and during the analysis
of recorded audio.

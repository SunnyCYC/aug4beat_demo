
This is the demo page for the paper titled “Source Separation-Based Data Augmentation Techniques For Improved Joint Beat And Downbeat Tracking In Classical Music ”.

|[**Demo_Page**](https://sunnycyc.github.io/aug4beat_demo/)|Paper|

## Abstract
Beat/downbeat tracking have been fundamental and important topics in music information retrieval research. Though deep learning-based models have achieved great success for music with stable and clear beat positions, it remains quite challenging for classical music in the absence of a steady drum sound. In this paper, we propose a novel source separation-based data augmentation technique that is tailored for beat/downbeat tracking in classical music. This involves a model that separates drum and non-drum sounds, and mechanisms to perform drum stem selection. We report comprehensive experiments validating the usefulness of the proposed methods.

## Demo audio

#### Mussorgsky, Pictures at an Exhibition 

|Original|   Mix   |exMixABSM|exMixOSFQ| 
|---|---|---|---| 
|<audio src="Demo_mp3\ori\cut_MIDI-Unprocessed_04_R1_2006_01-04_ORIG_MID--AUDIO_04_R1_2006_04_Track04_wav.mp3" controls="" preload=""></audio>|<audio src="Demo_mp3\Mix\cut_MIDI-Unprocessed_04_R1_2006_01-04_ORIG_MID--AUDIO_04_R1_2006_04_Track04_wav_click.mp3" controls="" preload=""></audio>|<audio src="Demo_mp3\excludeMixABSM\cut_MIDI-Unprocessed_04_R1_2006_01-04_ORIG_MID--AUDIO_04_R1_2006_04_Track04_wav_click.mp3" controls="" preload=""></audio>|<audio src="Demo_mp3\excludeMixOSFQ\cut_MIDI-Unprocessed_04_R1_2006_01-04_ORIG_MID--AUDIO_04_R1_2006_04_Track04_wav_click.mp3" controls="" preload=""></audio>| 

#### Bach, Duet in G, BWV 804

|Original|   Mix   |exMixABSM|exMixOSFQ| 
|---|---|---|---| 
|<audio src="Demo_mp3\ori\cut_MIDI-Unprocessed_06_R1_2009_03-07_ORIG_MID--AUDIO_06_R1_2009_06_R1_2009_04_WAV.mp3" controls="" preload=""></audio>|<audio src="Demo_mp3\Mix\cut_MIDI-Unprocessed_06_R1_2009_03-07_ORIG_MID--AUDIO_06_R1_2009_06_R1_2009_04_WAV_click.mp3" controls="" preload=""></audio>|<audio src="Demo_mp3\excludeMixABSM\cut_MIDI-Unprocessed_06_R1_2009_03-07_ORIG_MID--AUDIO_06_R1_2009_06_R1_2009_04_WAV_click.mp3" controls="" preload=""></audio>|<audio src="Demo_mp3\excludeMixOSFQ\cut_MIDI-Unprocessed_06_R1_2009_03-07_ORIG_MID--AUDIO_06_R1_2009_06_R1_2009_04_WAV_click.mp3" controls="" preload=""></audio>| 

#### Schubert, Sonata in A D959

|Original|   Mix   |exMixABSM|exMixOSFQ| 
|---|---|---|---| 
|<audio src="Demo_mp3\ori\cut_MIDI-Unprocessed_07_R2_2006_01_ORIG_MID--AUDIO_07_R2_2006_01_Track01_wav.mp3" controls="" preload=""></audio>|<audio src="Demo_mp3\Mix\cut_MIDI-Unprocessed_07_R2_2006_01_ORIG_MID--AUDIO_07_R2_2006_01_Track01_wav_click.mp3" controls="" preload=""></audio>|<audio src="Demo_mp3\excludeMixABSM\cut_MIDI-Unprocessed_07_R2_2006_01_ORIG_MID--AUDIO_07_R2_2006_01_Track01_wav_click.mp3" controls="" preload=""></audio>|<audio src="Demo_mp3\excludeMixOSFQ\cut_MIDI-Unprocessed_07_R2_2006_01_ORIG_MID--AUDIO_07_R2_2006_01_Track01_wav_click.mp3" controls="" preload=""></audio>| 

#### Chopin, Barcarolle

|Original|   Mix   |exMixABSM|exMixOSFQ| 
|---|---|---|---| 
|<audio src="Demo_mp3\ori\cut_MIDI-Unprocessed_13_R1_2006_01-06_ORIG_MID--AUDIO_13_R1_2006_06_Track06_wav.mp3" controls="" preload=""></audio>|<audio src="Demo_mp3\Mix\cut_MIDI-Unprocessed_13_R1_2006_01-06_ORIG_MID--AUDIO_13_R1_2006_06_Track06_wav_click.mp3" controls="" preload=""></audio>|<audio src="Demo_mp3\excludeMixABSM\cut_MIDI-Unprocessed_13_R1_2006_01-06_ORIG_MID--AUDIO_13_R1_2006_06_Track06_wav_click.mp3" controls="" preload=""></audio>|<audio src="Demo_mp3\excludeMixOSFQ\cut_MIDI-Unprocessed_13_R1_2006_01-06_ORIG_MID--AUDIO_13_R1_2006_06_Track06_wav_click.mp3" controls="" preload=""></audio>| 

#### Alexander Scriabin, Fantasy, Op. 28

|Original|   Mix   |exMixABSM|exMixOSFQ| 
|---|---|---|---| 
|<audio src="Demo_mp3\ori\cut_MIDI-UNPROCESSED_14-15_R1_2014_MID--AUDIO_15_R1_2014_wav--5.mp3" controls="" preload=""></audio>|<audio src="Demo_mp3\Mix\cut_MIDI-UNPROCESSED_14-15_R1_2014_MID--AUDIO_15_R1_2014_wav--5_click.mp3" controls="" preload=""></audio>|<audio src="Demo_mp3\excludeMixABSM\cut_MIDI-UNPROCESSED_14-15_R1_2014_MID--AUDIO_15_R1_2014_wav--5_click.mp3" controls="" preload=""></audio>|<audio src="Demo_mp3\excludeMixOSFQ\cut_MIDI-UNPROCESSED_14-15_R1_2014_MID--AUDIO_15_R1_2014_wav--5_click.mp3" controls="" preload=""></audio>| 

#### Beethoven, Sonata No. 23 in F Minor, Op. 57, First Movement

|Original|   Mix   |exMixABSM|exMixOSFQ| 
|---|---|---|---| 
|<audio src="Demo_mp3\ori\cut_MIDI-Unprocessed_20_R1_2011_MID--AUDIO_R1-D8_04_Track04_wav.mp3" controls="" preload=""></audio>|<audio src="Demo_mp3\Mix\cut_MIDI-Unprocessed_20_R1_2011_MID--AUDIO_R1-D8_04_Track04_wav_click.mp3" controls="" preload=""></audio>|<audio src="Demo_mp3\excludeMixABSM\cut_MIDI-Unprocessed_20_R1_2011_MID--AUDIO_R1-D8_04_Track04_wav_click.mp3" controls="" preload=""></audio>|<audio src="Demo_mp3\excludeMixOSFQ\cut_MIDI-Unprocessed_20_R1_2011_MID--AUDIO_R1-D8_04_Track04_wav_click.mp3" controls="" preload=""></audio>| 

## Table of the demo songs from MAESTRO[1]
| Composer | Title | Year | File Name |
| -------- | ----- | ---- | --------- |
| Mussorgsky |Pictures at an Exhibition|2006|2006/MIDI-Unprocessed_04_R1_2006_01-04_ORIG_MID--AUDIO_04_R1_2006_04_Track04_wav|
|Bach |Duet in G, BWV 804|2009 |2009/MIDI-Unprocessed_06_R1_2009_03-07_ORIG_MID--AUDIO_06_R1_2009_06_R1_2009_04_WAV|
|Schubert|Sonata in A D959|2006|2006/MIDI-Unprocessed_07_R2_2006_01_ORIG_MID--AUDIO_07_R2_2006_01_Track01_wav|
|Chopin |Barcarolle|2006|2006/MIDI-Unprocessed_13_R1_2006_01-06_ORIG_MID--AUDIO_13_R1_2006_06_Track06_wav|
|Alexander Scriabin|Fantasy, Op. 28|2014|2014/MIDI-UNPROCESSED_14-15_R1_2014_MID--AUDIO_15_R1_2014_wav--5|
|Beethoven|Sonata No. 23 in F Minor, Op. 57, First Movement| 2011|2011/MIDI-Unprocessed_20_R1_2011_MID--AUDIO_R1-D8_04_Track04_wav|

## Reference
[1] C. Hawthorne et al., “Enabling factorized piano music modeling and generation with the Maestro dataset,” Proc. Int. Conf. Learning Representations, 2019.
                            

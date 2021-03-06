| [WEEK 1](README.md) | [WEEK 2](week1.md) | [WEEK 3](week3.md) | [WEEK 4](week4.md) | [WEEK 5](week5.md) | [WEEK 7](week7.md) | [WEEK 8](week8.md) | [WEEK 9](week9.md) | [WEEK 10](week10.md) |

# Week 9: Analysing and Extracting Meaning from Audio

## Task 1: Extracting Features

For this week's task I used the same tracks from last week's task. Below are the screenshots of the transformations (Spectrogram, Mel Frequency Cepstral Coefficient and Chromagram) we had to do in Sonic Visualiser.

Creative Design:

![alt text](creative_design_features.png "Creative Design Features")

Ginger Underground:

![alt text](ginger_underground_features.png "Ginger Underground Features")

Playing With Shadows:

![alt text](playing_with_shadows_features.png "Playing With Shadows Features")

## Task 2: Computing and visualising histograms of features

### Task 2.1: Computing and visualising histograms

#### Histograms computed from spectograms

Creative Design:

![alt text](creative_deisgn_spectogram_histogram.png "Creative Design Spectogram Histogram")

Ginger Underground: 

![alt text](ginger_underground_spectogram_histogram.png "Ginger Underground Spectogram Histogram")

Playing With Shadows:

![alt text](playing_with_shadows_spectogram_histogram.png "Playing With Shadows Spectogram Histogram")

#### Histograms computed from MFCCs

Creative Design:

![alt text](creative_design_mfcc_histogram.png "Creative Design MFCC Histogram")

Ginger Underground:

![alt text](ginger_underground_mfcc_histogram.png "Ginger Underground MFCC Histogram")

Playing With Shadows:

![alt text](playing_with_shadows_mfcc_histogram.png "Playing With Shadows MFCC Histogram")

#### Histograms computed from chromagrams

I have adapted the Python code to create 12 histograms instead of 20 - one for each pitch class. 

Creative Design:

![alt text](creative_design_chromagram_histogram.png "Creative Design Chromagram Histogram")

Ginger Underground:

![alt text](ginger_underground_chromagram_histogram.png "Ginger Underground Chromagram Histogram")

Playing With Shadows:

![alt text](playing_with_shadows_chromagram_histogram.png "Playing With Shadows Chromagram Histogram")

## Task 2.2: Comparing the histograms

I decided to take a closer look at the histograms computed from mel frequency cepstral coefficients for each track. MFCC is usually used to analyse timber, that is the tone colour or quality. MFCCs are usefuel in music information retrieval applications such as genre classification, audio similarity measures, etc. The three tracks I am comparing are all from different genres and do not have the same instruments present. This means that the MFCCs should be different for all three tracks. They are in fact different, iof you look closely at the histograms above. All three sets of histograms are different from eachother, considering the three genres are Synth Pop, Jazz and Ambient Electronic. 'Ginger Underground' differs slightly more than the other too, as 'Ginger Underground' is Jazz, whereas Synth Pop and Ambient Electronic could be considered more similar. 


[NEXT WEEK](week10.md)

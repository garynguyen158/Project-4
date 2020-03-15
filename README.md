# Gary nguyen
# Hydrophone Project
## I. Introduction
This project focuses on two topic: how wind and rain noise passing through the ocean and how the noise airgun, marine mammals and Earthquake look like under the ocean. For the first portion, we need to calculate the Power Spectral Density (PSD) from data collected from hydrophone. With PSD calculated, a plot between PSD and Frequency can conduct to show the effect of rain and wind noise under the ocean. For the second portion, also using data from hydrophone, we can make a spectrogram between frequency with time. From that, we can analyze what the noise from Airgun, Marine Mammals, Earthquake/Volcano look like.
## II. Link To the Code file: 
[Google Colab](https://colab.research.google.com/drive/1JPiAJtHt5Vo02G8xRGzhGGmq099SfjKh)

[Github ipynb File](https://github.com/garynguyen158/Project-4/blob/master/Hydrophone_Project.ipynb)
## III. Problem Statement:
![](https://github.com/garynguyen158/Project-4/blob/master/Image/Screen%20Shot%202020-03-14%20at%2015.15.35.png)
## IV. Results:
### Part 1: Wind and Rain Noise
|           | Oregon Shelf (80m Depth) | Oregon Offshore (580m Depth) |
|:---------:|:----------:|:------------:|
| No Rain and Wind | ![](https://github.com/garynguyen158/Project-4/blob/master/Image/A1.png) | ![](https://github.com/garynguyen158/Project-4/blob/master/Image/B1.png) |
| Only Rain | ![](https://github.com/garynguyen158/Project-4/blob/master/Image/A2.png) | ![](https://github.com/garynguyen158/Project-4/blob/master/Image/B2.png) |
| Only Wind| ![](https://github.com/garynguyen158/Project-4/blob/master/Image/A3.png) | ![](https://github.com/garynguyen158/Project-4/blob/master/Image/B3.png) |
| Both Rain and Wind | ![](https://github.com/garynguyen158/Project-4/blob/master/Image/A4.png) | ![](https://github.com/garynguyen158/Project-4/blob/master/Image/B4.png) |

### Part 2: Airgun, Marine Mammals, Earthquake/Volcano Noise
|          | Plot |
|:---------:|:----------:|
| Airgun | ![](https://github.com/garynguyen158/Project-4/blob/master/Image/Airgun.png) |
| Marine Mammals | ![](https://github.com/garynguyen158/Project-4/blob/master/Image/Marine%20Mammals.png) |
| Earthquake | ![](https://github.com/garynguyen158/Project-4/blob/master/Image/Earthquake.png) |
| Wenz Curve | ![](https://github.com/garynguyen158/Project-4/blob/master/Image/Screen%20Shot%202020-03-14%20at%2015.40.41.png) |

## V. Conclusion:
• What is the effect of wind and rain on underwater noise? Explain any behavior you observe in your result.

> For Rain, it creates a lot of vibrations at frequency below 2000Hz. That means it make a lot of noise at that frequency, and it showed in the graph. While PSD value range is smaller as lower frequency at normal condition, the PSD range at low frequency is significantly high when it is raining. For Wind, it has similar impart with rain , which is creating more noise passing through the water but at way smaller scale. In addtion, at frequency around 2000Hz to 7000Hz, the effect of wind show more clear compared to normal condition. 

• Which one has the highestimpact? Rain or wind?

> From graphs, Rain has more significant effect, and that makes sense because each drop of water contacts the water surface create small sound, which is vibration of sound waves. In a raining, there is significant number of water dropping to the surface, which cause significant high noise.

• What arethe main reasons for observing different spectral levels in Oregon shelf compared to Oregon offshore? 

The main reason for observing different spectral levels in Oregon shelf compared to Oregon offshore is the depth of each device. While Oregon shelf locates at 80m depth, Oregon offshore locates much lower at 580m. Because Shelf is closer to the surface, it absord a lot more vibrations or sound. That is reason why all graphs of Offshore are more stable compared to Shelf at the same type of water.

• Compare the bandwidth of these three signals. Are they consistent with what is shown in the Wenz curve(refer to the Ocean Noise slides)?

From all three graphs from Airgun, Marine Mammals and Earthquake, they are significant at low frequency, with the lowest is airgun. While airgun is show more clear frequency at 0 to 50Hz, Earth quake is from 0 to 100Hz and animal is longest range at 0 to higher then 5000Hz. Comparing those with Wenz Curve graph, they match with presented lines in Wenz Curve graph.

## VI. References

Data: https://oceanobservatories.org/instrument-series/hydbba/

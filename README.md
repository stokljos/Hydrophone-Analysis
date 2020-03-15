# Hydrophone-Analysis

Code URL: https://github.com/stokljos/Hydrophone-Analysis/blob/master/Project_4_Hydrophone.ipynb

Introduction:

	For the first part of the project, the raw data of the Oregon shelf cabled Benthic and Oregon Offshore Cabled Benthic 
  Experimental Packages were analyzed. Four time periods were used: 1) When it does not rain nor windy, 2) when it was rainy and windy, 
  3) when it rains and is not windy, and 4) when it rains and it is windy. The power spectral density was calculated for each of the 
  times and compared to the frequency of each periods. The power spectral density is used to characterize broadband random signals. 
  It describes the power of the signal using frequency.
	The second part of the project is looking at Mammal, Airgun, and Earthquake/Volcano noise. Using data where this noise can be find 
  found, the data is plotted on a spectrogram to compare the bandwidth of the signal.
  
Procedure (explanation of code):

This code consists of 9 cells:
1. This cell imports all the important packages needed to create the correct analyzation of this code
2. This cell grabs the data from the Oregon shelf cabled benthic
3. This cell grabs the data from the Oregon offshore cabled benthic
4. This cell calculates the power spectral density 
5. This cell plots each graph of the time period with PSD vs frequency for Oregon shelf cabled benthic
6. This cell plots each graph of the time period with PSD vs frequency for Oregon offshore cabled benthic
7. This cell plots the spectrogram for Mammal noise
8. This cell plots the spectrogram for airgun noise
9. This cell plots the spectrogram for earthquake noise

Data:

![alt text](https://github.com/stokljos/Hydrophone-Analysis/blob/master/2.JPG)
![alt text](https://github.com/stokljos/Hydrophone-Analysis/blob/master/3.JPG)
![alt text](https://github.com/stokljos/Hydrophone-Analysis/blob/master/4.JPG)
![alt text](https://github.com/stokljos/Hydrophone-Analysis/blob/master/5.JPG)
![alt text](https://github.com/stokljos/Hydrophone-Analysis/blob/master/6.JPG)
![alt text](https://github.com/stokljos/Hydrophone-Analysis/blob/master/324.JPG)

Analysis:

Part 1:
1.	What is the effect of wind and rain on underwater noise? Explain any behavior you observe in your result. 
Regarding graphs 1 and 5, these graphs show when it is not rainy and not windy, the PSD is lower with the increasing 
frequency compared to all the other graphs. Wind and Rain increase PSD in the water.

2.	Which one has the highest impact? Rain or wind? 
Looking at graphs 3 and 7, these graphs show when it is windy, the average PSD sits mostly between 50 and 60 watts per
Hz whereas looking at graphs 2 and 6, which show when it’s just windy, the average PSD sits below 40 W/Hz so we see that rain 
has the highest impact.

3.	What are the main reasons for observing different spectral levels in Oregon shelf compared to Oregon offshore? 
The main reason to compare the two is to see how these factors compare with being offshore in the middle of water with no 
land around it and next to a shelf so there is land near that could show a difference in noise level


Part 2:
1.	Compare the bandwidth of these three signals. Are they consistent with what is shown in the Wenz curve 
(refer to the Ocean Noise slides)? 
Based off the Wenz curve, mammal frequency is in between 10 Hz and 100,000 Hz +. Based off of graph 9, this is 
consistent with that curve because we see noise all over the graph. 
In the Wenz curve, airgun frequency is in between 100 and 30,000 Hz. Based off of graph 10, this is consistent with 
that frequency between 15 and 18 seconds.
For Earthquakes the Wenz curve is between 1 and 100 Hz and based off of graph 11, this is also consistent as it is 
highest below 20 Hz on the graph.

Conclusion:

  Overall it is interesting to see how noise travels and is affected by the ocean. It makes sense that rain effects 
  the noise underwater more than wind because rain is physically penetrating the ocean surface causing a larger signal 
  to travel through. It is interesting to see how the frequencies of mammals and airguns and earthquakes are shown at 
  different levels and knowing how to pinpoint them because you know what frequency to look at.
  
References:
https://oceanobservatories.org/instrument-series/hydbba/

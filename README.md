# COVID_19

Case Study of Switzerland During COVID-19

Using data updated daily from ECDC's website, we take a look at the number of cases and deaths for countries within the dataset. We then focus on Switzerland's data. The data and the file was updated daily whenever I ran my computer until December 14th 2020. See Notes and Conclusion Below.

### What This Notebook Shows:
1. General review and use of Pandas, Numpy, SciPy, Scikit-learn, Matplotlib, Seaborn and Styling
2. Use of Markdown on Jupyter Notebook
3. Analyzing COVID-19's spreading rate in Switzerland
4. Conclusion (Also pasted below)

__Note 1: The first notebook had two parts: International and Switzerland's Case Study. In a new notebook, I have isolated the Swiss Case Study analysis to make it simpler for the reader.__

Link for the  data:
https://www.ecdc.europa.eu/en/publications-data/download-todays-data-geographic-distribution-covid-19-cases-worldwide

__Note 2: There are some data quality issues made by the providers as the number of cases of cases and deaths for many countries reported are wrongly inputted. On April 15th 2020, we started to have this issue for only one row: the international conveyance of Japan with -9 cases. On September 3rd 2020, we had 15+ countries with this issue.__
 
 __Note 3: On December 14th, ECDC decided to stop inputting daily data and switched to weekly. This project will no longer be updated.


## Conclusion December 14th:

This basic project doesn't really bring out much that isn't on the news, although the news do not do a decent job aside from noise. As a proof, look how they now update the data weekly instead of daily to hide their shame of incompetence (especially the Federal Council of Switzerland). This notebook's original intent was just to show the basics of coding and finding simple analytics, however it served its purpose for individual use.

Regarding COVID-19, some people question if the virus is a real threat, or whether there should be a quarantine in Switzerland when we look at the number of deaths vs the number of cases. Granted that the real reason you should have a quarantine is to decrease the spread, efficiently decrease the amount of people in the hospital and avoid long term disabilities caused by the virus, many people (including government officials) forget these core concepts. 

Many "experts" do not understand the real meaning behind statistics or even simple probabilities. As a matter of fact, we are highly connected today (unsurprisingly) and the contamination factor cannot/should not be considered linear AND must be considered exponential/non-linear. What I mean by this is that one person can easily affect the whole sample, hence why we should be skeptical of the knowledge we derive from such basic data. Much of the basic statistics on the news are hence quite meaningless as they are framed badly by the news on top of the data quality not being great either (to follow up on data quality, it would be good to have the number of tests administered, the recontamination factor percentage, the data being updated for the weekends rather than only weekdays, etc...).

Events such as pandemics should not be taken lightly by just looking at these simple numbers if you are trying to save everyone. Then, comes the question of ethics (be a Darwinist or try to save everyone). The fact that idiotic governments took such bad decisions at the beginning of the spread in January (they could have saved trillions if they took the right measures then) and the way the virus has been dealt since is just a clear lack of leadership and understanding if the end goal is to indeed "save people and not surcharge hospitals". Mediocre people stay silent in front of big insults, and vocal in front of small ones; the magnificent vice versa. With masks: people want to be free in the small things, and are willing to be slaves in the things that matter! Let's even look at the bigger picture: the economy will be blamed on this virus when most of it was already on the brink of its fragility. In the end, small businesses will be forced to close down and big companies will get bailouts. They are hiding the real event: the currency system dying of debt and the bridge over to the new digital. I end this with a quote I like:

__Everything that happens doesn't happen for a reason but everything that survives, survives for a reason.__

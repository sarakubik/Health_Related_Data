# Health_Related_Data

I'm interested in telemedicine, health-related datasets, wearable technologies and edge technology. 
So I'm creating files that related to these topics.

The first set of files are from a dataset that was collected in 2014 when 9 diabetic people were wearing a continuous glucose monitor (CGM). These monitors meausure a person's glucose levels every 5 minutes.

The data was collected as a part of another study, and it is a bit old - it's from 2014. But it's freely available here https://zenodo.org/record/5651217#.YbOKor3MKUk along with some other data that includes when the participants documented eating, the food they ate, and the insulin they gave themselves.

I've created some Excel files from each of the patients that I"m uploading here. I want to see how the readings compare over a 24 hour timeframe.

Update 12-15-2021
I did a lot of data wrangling and cleaning with the various datasets on the 9 patients. I was able to get at least one 24-hour period where the continuous glucose monitor takes glucose level readings every 5 minutes for each patient.

I did some basic time series charts in Excel, and wanted to overlay them on top of each other. I thought Tableau might be able to do this. Wrong. Tableau doesn't plot according to minutes and hours and, more importantly, wasn't able to overlay each patient chart on top of another patient chart. You know what can do this? Photoshop. So that's my plan next. I'm lucky that I know Photoshop so well (I taught it to undergraduates and was a graphic designer in the past) because I'm certainly seeing there are limitations to the visual outputs that Tableau, or Python, or R has.

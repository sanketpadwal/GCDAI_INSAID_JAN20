# Insaid Term 4 Project - ML Intermediate
# **Individual Household Electricity Consumption Forecast using Time-series Analysis**
<center><img src="https://github.com/sanketpadwal/GCDAI_INSAID_JAN20/blob/main/Term4/la-ville-lumire-2400-2.jpg?raw=true" width="1200" height="500" /></center>

---
<a name = Section1></a>
### **1. Introduction**
---

**Time Series analysis:** Time series forecasting is a technique for the prediction of events through a sequence of time. The techniques predict future events by analyzing the trends of the past, on the assumption that future trends will hold similar to historical trends. There are two main goals of time series analysis: (i) identifying the nature of the phenomenon represented by the sequence of observations, and (ii) forecasting (predicting future values of the time series variable). Both of these goals require that the pattern of observed time series data is identified and more or less formally described. Once the pattern is established, we can interpret and integrate it with other data (i.e., use it in our theory of the investigated phenomenon, e.g., seasonal commodity prices). Regardless of the depth of our understanding and the validity of our interpretation (theory) of the phenomenon, we can extrapolate the identified pattern to predict future events.

---
<a name = Section2></a>
### **2. Problem Statement**
---
In modern days, Energy consumption has gone up with the advancements in technology and electronice appliances in the world. It has become very important to monitor energy consumption rates in a household to minimize energy expenses as well as energy shortages. <br> Energy conservation plays a significant role of lessening climate change. It helps the replacement of non-renewable resources with renewable energy. Energy conservation is often the most inexpensive solution to energy shortages, and it is more environmentally kind alternative to increased energy production. <br> Nowdays, many electrical comapnies use electronic smart meters, which provide wireless access to the meter's power usage data, to measure electricity consumption in real-time. Some smart meters can even measure the electricity use of individual devices and allow the utility or customer to control electricity use remotely.

<center><img src="https://github.com/sanketpadwal/GCDAI_INSAID_JAN20/blob/main/Term4/0_AN8suioCkeRkugES.gif?raw=true" width="720" height="150" /></center>

### **Dataset:**
**Abstract:** Measurements of electric power consumption in one household with a one-minute sampling rate over a period of almost 4 years. Different electrical quantities and some sub-metering values are available.<br> **Source:**
Georges Hebrail (georges.hebrail '@' edf.fr), Senior Researcher, EDF R&D, Clamart, France <br>
Alice Berard, TELECOM ParisTech Master of Engineering Internship at EDF R&D, Clamart, France<br> **Data Set Information:**
This archive contains 2075259 measurements gathered in a house located in Sceaux (7km of Paris, France) between December 2006 and November 2010 (47 months).
Notes:
 - (global_active_power*1000/60 - sub_metering_1 - sub_metering_2 - sub_metering_3) represents the active energy consumed every minute (in watt hour) in the household by electrical equipment not measured in sub-meterings 1, 2 and 3.<br> 
 - The dataset contains some missing values in the measurements (nearly 1,25% of the rows). All calendar timestamps are present in the dataset but for some timestamps, the measurement values are missing: a missing value is represented by the absence of value between two consecutive semi-colon attribute separators. For instance, the dataset shows missing values on April 28, 2007.

**Attribute Information:**<br>
1.**"date":** Date in format dd/mm/yyyy<br>
2.**"time":** time in format hh:mm:ss<br>
3.**"global_active_power":** household global minute-averaged active power (in kilowatt)<br>
4.**"global_reactive_power":** household global minute-averaged reactive power (in kilowatt)<br>
5.**"voltage":** minute-averaged voltage (in volt)<br>
6.**"global_intensity":** household global minute-averaged current intensity (in ampere)<br>
7.**"sub_metering_1":** energy sub-metering No. 1 (in watt-hour of active energy). It corresponds to the kitchen, containing mainly a dishwasher, an oven and a microwave (hot plates are not electric but gas powered).<br>
8.**"sub_metering_2":** energy sub-metering No. 2 (in watt-hour of active energy). It corresponds to the laundry room, containing a washing-machine, a tumble-drier, a refrigerator and a light.<br>
9.**"sub_metering_3":** energy sub-metering No. 3 (in watt-hour of active energy). It corresponds to an electric water-heater and an air-conditioner.<br>

### **Objective:**
 - Obtain an understanding of the patterns in the observed data.
 - Fit a model and proceed to forecasting, monitoring or even feedback and feedforward control.

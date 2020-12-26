# Insaid Term 4a Project - ML Intermediate
# **GENDER RECOGNITION THROUGH VOICE USING SUPPORT VECTOR MACHINE ALGORITHM**
<center><img src="https://github.com/sanketpadwal/GCDAI_INSAID_JAN20/blob/main/Term4/Voice_Recognition1.jpeg?raw=true" width="480" height="200" /></center>

<center><img src="https://github.com/sanketpadwal/GCDAI_INSAID_JAN20/blob/main/Term4/Voice_Recognition.jpeg?raw=true" width="480" height="200" /></center>

---
<a name = Section1></a>
### **1. Introduction**
---

Voice recognition is the process of taking the spoken word as an input to a computer program. This process is important to virtual reality because it provides a fairly natural and intuitive way of controlling the simulation while allowing the user's hands to remain free. Voice recognition enables consumers to multitask by speaking directly to their Google Home, Amazon Alexa or other voice recognition technology. By using machine learning and sophisticated algorithms, voice recognition technology can quickly turn your spoken work into written text. Voice recognition technology also identifies a speaker and authenticates that he or she is indeed that individual. Unlike speech recognition, which identifies the words spoken, voice recognition analyzes countless patterns and elements that distinguish one person's voice from another. These days we expect personalization and want to search the internet without wasting time. That’s the reason why Voice Search technology seems so promising.

---
<a name = Section2></a>
### **2. Problem Statement**
---
The provided audio data cannot be understood by the models directly. To convert data into an understandable format feature extraction process is used. It is a process that explains most of the data but in an understandable way. Feature extraction is required for classification, prediction and recommendation algorithms incase data input in in audio format.
'WarbleR R package' is designed for Acoustic analysis. The dataset which have acoustic parameters can be obtained with this analysis. Acoustic analysis of the voice depend upon parameter settings specific to sample characteristics such as intensity, duration, frequency and filtering. The acoustic properties of the voice and speech can be used to detect gender of the speaker. The dataset can be trained with different machine learning algorithms. In this project, SVM Classification method is used to detect(predict) the gender of voice inputs. Objective of this assessment is to identify the SVM kernel and hyper parameters for the better accuracy.




### **Dataset:**
Voice Gender - Gender recognition by voice and speech analysis.
This database was created to identify a voice as male or female, based upon acoustic properties of the voice and speech. The dataset consists of 3168 recorded voice samples, collected from male and female speakers. The voice samples are pre-processed by acoustic analysis in R using the seewave and tuneR packages, with an analyzed frequency range of 0hz-280hz (human voice range) to derive 20 features.

**Source:**<br> 
Github <br>https://raw.githubusercontent.com/sanketpadwal/GCDAI_INSAID_JAN20/main/Term4/voice.csv?_sm_au_=iVVHZq1W63S7vfBVL321jK0f1JH33


**Attribute Information:**<br>
1. **meanfreq:** mean frequency (in kHz)<br>
2. **sd:** standard deviation of frequency <br>
3. **median:** median frequency (in kHz)<br>
4. **Q25:** first quantile (in kHz)<br>
5. **Q75:** third quantile (in kHz)<br>
6. **IQR:** interquantile range (in kHz)<br>
7. **skew:** skewness (see note in specprop description)<br>
8. **kurt** kurtosis (see note in specprop description)<br>
9. **sp.ent:** spectral entropy<br>
10. **sfm:** spectral flatness<br>
11. **mode:** mode frequency<br>
12. **centroid:** frequency centroid (see specprop)<br>
13. **meanfun:** average of fundamental frequency measured across acoustic signal<br>
14. **minfun:** minimum fundamental frequency measured across acoustic signal<br>
15. **maxfun:** maximum fundamental frequency measured across acoustic signal<br>
16. **meandom:** average of dominant frequency measured across acoustic signal<br>
17. **mindom:** minimum of dominant frequency measured across acoustic signal<br>
18. **maxdom:** maximum of dominant frequency measured across acoustic signal<br>
19. **dfrange:** range of dominant frequency measured across acoustic signal<br>
20. **modindx:** modulation index. Calculated as the accumulated absolute difference between<br>adjacent measurements of fundamental frequencies divided by the frequency range<br>
21. **label:** male or female<br>

### **Objective:**
 - Obtain an understanding on Support Vector Machine algorithm.
 - Fine tune algorithm to predict better accuracy with different kernel selections
 - Use of cross validation for the validation of results.
 - Perform Grid search technique to find the best parameter for SVM algorithm.
 - Compare accuracy with Decision Tree, Random Forest and Logistic Regressor models.



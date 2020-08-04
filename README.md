# Gender Recognition From Voice Using Machine Learning

 Used Scikit-Learn library with LTSA method for dimension reduction and K-NN classifier algorithm <br >
 Achieved maximum accuracy of 97.89%

# Tech Stack
 Python<br>
 Jypter Notebook or Google Colab

# Output

### A. Blocks

Detailed description of running code and output in terms of blocks on Google Colab platform [GenderRecog.ipynb](https://github.com/Devanshi512/Gender-Recognition-From-Speech/blob/master/GenderRecog.ipynb).

### B. final_res file (i.e. result file of confusion matrix) 

Showing 320 Males and 310 Females are identified correctly by the machine.<br >
![Alt text](Image/Final_Res.jpeg?raw=true "Final_Res file")


### C. Code of achieved accuracy
Showing 97.75% accuracy <br >
![Alt text](Image/Accuracy_Result.JPG?raw=true "Accuracy Result")

# About Dataset

Voice dataset is from kaggle(https://www.kaggle.com/primaryobjects/voicegender), contained 3168 X 21 size. In this dataset, 20 columns represent the acoustic properties of Voice.

•	meanfreq: mean frequency (in kHz)  
•	sd: standard deviation of frequency  
•	median: median frequency (in kHz)  
•	Q25: first quantile (in kHz)  
•	Q75: third quantile (in kHz)  
•	IQR: interquantile range (in kHz)  
•	skew: skewness (see note in specprop description)  
•	kurt: kurtosis (see note in specprop description)  
•	sp.ent: spectral entropy  
•	sfm: spectral flatness  
•	mode: mode frequency  
•	centroid: frequency centroid (see specprop)  
•	peakf: peak frequency (frequency with highest energy)  
•	meanfun: average of fundamental frequency measured across acoustic signal  
•	minfun: minimum fundamental frequency measured across acoustic signal  
•	maxfun: maximum fundamental frequency measured across acoustic signal  
•	meandom: average of dominant frequency measured across acoustic signal   
•	mindom: minimum of dominant frequency measured across acoustic signal  
•	maxdom: maximum of dominant frequency measured across acoustic signal  
•	dfrange: range of dominant frequency measured across acoustic signal  
•	modindx: modulation index. Calculated as the accumulated absolute difference between adjacent measurements of fundamental frequencies divided by the frequency range  

You can find link here: http://www.primaryobjects.com/2016/06/22/identifying-the-gender-of-a-voice-using-machine-learning/

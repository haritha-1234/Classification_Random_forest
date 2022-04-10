# Random_forest
## __Overview__
The aim of this project is to develop a signal-background discriminator using Random Forest. Here Gamma is the signal and proton is the background. We are using air shower data initiated by Gamma and protons. The data has been simulated using 2 softwares CORSIKA and Sim_telarry which generates air showers and telescopes respectively. From the telescope images, I have seen that most of the proton images have muon rings of different radius. So the idea was to develop a CNN which seperates protons(background) from Gamma(signal).
## __Data Structure__
Input data is a tabular data (total_data_set.csv) of the image properties such as length, width, size along with the label of the class. 1 being signal (Gamma) and 0 being background (Proton). <br>
Quality of the separation is calculated using Quality factor with the help of individual gamma/proton efficiencies.
## __Settings__
- Install scikit learn
- Install Pandas

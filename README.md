# Personalized_Cancer_Diagnosis
Main objective of this project is to distinguishing the mutations that contribute to tumor growth (drivers) from the neutral mutations. Currently this interpretation of genetic mutations is being done manually. This is a very time-consuming task where a clinical pathologist has to manually review and classify every single genetic mutation based on evidence from text-based clinical literature. so designed a machine learning model that classifies given genetic variations/mutations based on evidence from text-based clinical literature. Got data from Kaggle which was updated by Memorial Sloan Kettering Cancer Centre. Data having some Gene, gene variations and some medical literature text related to gene variations.
##### Problem statement :
Classify the given genetic variations/mutations based on evidence from text-based clinical literature. 
##### Real-world/Business objectives and constraints:
1. No low-latency requirement.
2. Interpretability is important.
3. Errors can be very costly.
4. Probability of a data-point belonging to each class is needed.
##### Data information:
1. training_variants (ID , Gene, Variations, Class)
2. training_text (ID, Text)
in data i have 9 different classes to classify so this is a multi-class classification and Multi class log-loss was used as performance metric.

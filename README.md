### EX9 Preprocessing on Twitter Data using Rapidminer
### DATE: 4.9.2026
### AIM: To implement preprocessing technique on Twitter Data using Rapidminer
### Description: 
<div align = "justify">
RapidMiner provides data mining and machine learning procedures including: data loading and transformation (ETL), data preprocessing and visualization, 
predictive analytics and statistical modeling, evaluation, and deployment. RapidMiner is written in the Java programming language. 
RapidMiner provides a GUI to design and execute analytical workflows. Those workflows are called “Processes” in RapidMiner and they consist of multiple “Operators”. 
Each operator performs a single task within the process, and the output of each operator forms the input of the next one. Alternatively, the engine can be called from 
other programs or used as an API. Individual functions can be called from the command line. 
RapidMiner provides learning schemes, models and algorithms and can be extended using R and Python scripts.

### Procedure:
1) ***Import Twitter data:*** Import the Twitter data into RapidMiner. You can do this by selecting the appropriate
data source operator, such as "Read Excel" or "Read CSV," and specifying the location of your Twitter data
file.
2) ***Preprocess data:*** Preprocess the imported data to clean and prepare it for text processing. Use the following
operators for preprocessing:
    <p>a. Tokenize: Split the text into individual words or tokens.
    <p>b. Transform Cases: Convert the text to lowercase or uppercase to ensure consistency.
    <p>c. Remove Stopwords: Remove common words that do not provide much meaningful information.
    <p>d. Remove Special Characters: Eliminate special characters, such as punctuation marks or symbols.
    <p>e. Remove Numbers: Exclude numeric values from the text.
3) ***Stemming:*** Apply stemming to reduce words to their root forms. You can use operators like "Stem (Porter)"
for this purpose.


### Output:
<img width="1082" height="652" alt="image" src="https://github.com/user-attachments/assets/d5f18f66-c59b-4f30-88bc-c0b69a8a6205" />
<img width="1090" height="567" alt="image" src="https://github.com/user-attachments/assets/f22c3f73-c62a-49f6-bc39-0a7691a83eb8" />
<img width="1917" height="1132" alt="Screenshot 2026-09-04 193244" src="https://github.com/user-attachments/assets/2f8e136d-471f-43a3-97c4-3e803b2b34f9" />


### Result:
The Twitter data was successfully preprocessed using tokenization, case transformation, stopword removal, and Porter stemming. The processed text was converted into a TF-IDF word vector successfully.

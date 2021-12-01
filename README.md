# Transcriber
Uses NLP techniques to transcribe a grocery order into a list as a csv file

Save a grocery order in the input.txt file.

![image](https://user-images.githubusercontent.com/41962112/144215286-10b6642d-2ea5-4681-8f20-e4d0b7530382.png)


Run the .ipynb file which reads the input.txt file, processes and transcribes it and outputs a list of **Grocery Items, Quantity and Unit** in the output.csv

![image](https://user-images.githubusercontent.com/41962112/144215503-437045a7-adeb-4b42-8c36-0b2f29a47bf2.png)

POS Tagging was used to extract the Items, Quantity and Unit.

We first identified the Noun Phrases which made it easier to identify the nouns we want.

Example of POS tagging of Noun Phrases (NP):

![image](https://user-images.githubusercontent.com/41962112/144215897-06a83157-12ad-47d9-9edc-a5c77bb0fa83.png)

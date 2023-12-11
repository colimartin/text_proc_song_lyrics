# Song Lyrics Throughout Time: A Visual Story

## Disclaimer:
During development github was not the primary version control method, so the
gitlog is not accurate. 
Aidan did roughly a little more than the first half of the code.
Colin wrote the second half and set up the github. 
We also met up in-person numerous times to collaborate.

## Contents:
The repository contains the file *"script.ipynb"* which contains the source code.
Data comes from *"tcc_ceds_music.csv"*, which is found in src alongside the notebook file. 
The files containing the ".png" extension are the tf-idf outputs for each time period we analyzed.

50viz.png -> 1950's and 1960's;
70viz.png -> 1970's and 1980's;
90viz.png -> 1990's and 2000's;
10viz.png -> 2010's and 2020's;

## How to run the code:
To run the source code open *"script.ipynb"* in VSCode, Jupyter Labs, or your favorite IDE that supports Jupyter Notebooks.  
Make sure all necessary libraries are imported, and the "tcc_ceds_music.csv" file is in the same directory as the notebook.   
Run the entire notebook to generate all bar graphs and wordclouds. 

### Customization:
**Add stop words:** Many stop words have been included but more can be added, or some can be removed by editing the stopwords.extend(...) cell  

**Edit time steps:** The year_step integer variable determines the size of the time periods that are compared. It is 20 by default, meaning a new category is created every 20 years from 1950 to present.  

**Choose genres to compare:** The "used_genres" list variable determines which genres are compared. Of the 7 available genres, "pop", "rock", "country" and "hip hop" are compared by default. Other options are "raggae", "jazz" and "blues".

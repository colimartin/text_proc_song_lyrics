During the development of our project we did not use github for making updates so the
gitlog is not accurate. I, Aidan, did roughly a little more than the first half of the code.
Then emailed it to Colin, who wrote the second half and set up the github. We also collaborated 
on numerous occasions in-person to collaborate.

Contents:
The repository contains the file "script.ipynb" which runs our code for the project.
It gets its data from the file "tcc_ceds_music.csv", which is also in the repository. 
The files containing the ".png" extension are the tf-idf outputs for the different time 
periods.

50viz.png -> 1950's and 1960's
70viz.png -> 1970's and 1980's
90viz.png -> 1990's and 2000's
10viz.png -> 2010's and 2020's

How to run the code:
To run the python notebook file, one must first make sure they have all the libraries that
are imported in the beginning of the file, as well as have the "tcc_ceds_music.csv" file in the 
same directory as the notebook file. One could additionally add more stop words to the stopwords.extend(...)
line, although we already added a bunch. If you wanted to change the different lengths for the time 
periods you would just need to change the "year_step" variable, which is currently set to 20. One can 
also change which genres to compare. One can do this by changing the genres listed in the "use_genres"
variable. 

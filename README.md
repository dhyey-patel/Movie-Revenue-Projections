# Movie-Revenue-Projections

This a project done to see if the "right" combination of variables can be used to produce the highest movie revenue.
There are three R notebooks and their HTML versions (easier to view, and have all the outputs on it) along with various data sets in this project folder.

The original dataset is movies_metadata_abridged.csv, it is abridged as the max size was 25MB and so ~15K data points were removed to upload an abridged version, but the analysis was conducted on the entrie dataset. 

Initially the dataset that was found on Kaggle was inteded for a recommender systems project and as a result there was a lot of cleaning required to perform the analysis.
The first big task that was completed was scrapping the web for movie revenue as there were various rows where there was no revenue indicated. 
The rest of the cleaning and analysis is descriped throughout the notebooks in a comprehensive manner.

There were a lot of other ideas that were not impleted because of the limited computation power that I had access too, but I was also thinking about doing an optimization problem to see what combination of variables generates the highest revenue.

# NFL-stadium-arrests
Clustering and Factor Analysis of NFL Game and Stadium Arrest Data

### Project Summary ###

American football is widely considered to be the most popular professional sport to watch in the United States. From the regular season months of September through December and concluding with the playoffs in January and February, the National Football League (NFL) draws attention from fans all across the country. Most fans watch their favorite teams compete from the comfort of their own homes or at the local bar; however, a considerable number of them purchase tickets and go to NFL stadiums to watch their teams in person. On average, each NFL stadium welcomed 68,400 live spectators per game for the 2011-2015 regular seasons. These consistently high attendance numbers not only attract passionate fans, but can also invite physical clashes between fans of opposing teams, rowdy game watchers, etc. 

This study examined whether certain game attributes are correlated with the number of stadium arrests on a particular game day. The dataset contains game and stadium arrest data acquired from regular season games played during the 2011 to 2015 NFL regular seasons. The summary statistics (e.g. shape, center, spread) of the distribution of the arrest dataset is characterized before any analysis is conducted. Initial clustering algorithms were then used to determine similarities between NFL stadiums regarding the number of arrests and their home team’s performance. Afterwards, a factor analysis of mixed data (FAMD) was conducted to determine which game attributes contain the most information regarding the number of arrests that could be expected at a particular venue. The results of the unsupervised learning and dimensionality reduction analyses are discussed, and recommendations for future studies are proposed.

### File Descriptions ###

1. ProjectPaper_ChungD.pdf - Formal report that explains the clustering (unsupervised learning) and factor analysis phases of my project. 

2. NFL Stadium Arrests.ipynb - iPython Jupyter Notebook that contains code used to clean/prepare the data for analysis and conduct k-means clustering and factor analysis. The code in the notebook is structured as an "interactive" report and is also annotated with summaries that elaborate on the major takeaways from the k-means clustering and factor analysis. 

3. arrests.csv - Raw CSV data file used for the project. 

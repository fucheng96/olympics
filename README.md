**Table of Contents**

1. [Installation](Installation)
2. [Project Motivation](Project-Motivation)
3. [File Descriptions](File-Descriptions)
4. [Results](Results)
5. [Licensing, Authors, and Acknowledgements](Licensing,-Authors,-and-Acknowledgements)

**Installation**

Libraries used were part of the standard libraries that came from the Anaconda distribution of Python:
- Pandas
- Numpy
- MatPlotLib

**Project Motivation**

For this project, I was personally interestested in the 120-year Summer Olympics (or just 'Olympics') data from 1896 to 2016 to better understand:
- Had the Summer Olympics always been gender-balanced?
- How long did it take to make the transition from then male-dominated events?
- Which sports contributed to the rise of female sports events?
- Which countries first started to support their female athletes to compete in the Olympics?

**File Descriptions**

There are 2 data files and 1 Jupyter notebook available here to showcase work related to the above questions. 
- Data/athlete_events.csv: Each row corresponds to an individual athlete competing in an individual Olympic event.
- Data/noc_regions.csv: Each row describes the name of the country based on the initials.
- SummerOlympicsDataAnalytics: Jupyter Notebook that performs the necessary analyses.

The notebook is exploratory in analyzing the data in relation to the questions above. Various sections were labelled using markdown cells in the notebook to help walkthrough thought process.

**Results**

The key findings of this analysis are:
1. It took around 120 years to reach gender balance. Crucial tipping points include the 1950s (afer World War II) and 1980s (after appointment of first female board members of the International Olympic Committee ('IOC'). 

![Graph 1](https://miro.medium.com/max/1400/1*RCoIVERkbcotjoEaUnBj_A.png)

2. Athletics and Swimming are the key sports to the rise in women's participation in the Olympics, at both tipping points.

![Graph 2](https://miro.medium.com/max/692/1*qQ3NooB1203LxA5tVdpEMA.png)

3. Western countries such as UK, USA, Australia, Russia and France that sent the most female athletes around the 1950s and continue to do so in the 1980s till this date.

![Graph 1](https://miro.medium.com/max/1400/1*sMEh9kaUAuwUDNCwt_QW1g.png)

More information can be found at the Medium post available [here](https://medium.com/@fuchengliew/30de67bb087d).

**Licensing, Authors, Acknowledgements**

Credits to user named rgriffin from Kaggle that scraped the data from www.sports-reference.com. You may find the Licensing for the data and other descriptive information at the Kaggle link available [here](https://www.kaggle.com/heesoo37/120-years-of-olympic-history-athletes-and-results).

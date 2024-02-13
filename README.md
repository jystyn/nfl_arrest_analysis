<font size="8">Gridiron Justice: Analyzing NFL Arrests (2000-2017) - Unraveling Patterns, Consequences, and the League's Response

<font size="7"> Project 1 for the University Of Minnesota Data Visualization and Analytics Boot Camp

<font size="7"> Contributers: Gabby Kruger, Jack Maxwell, Justyn Helgeson, Eriel Kabambi

<font size="7">Topic Overview:
The National Football League is no stranger to having its players run into legal issues in its history as a sport. In the last 15 or so years there have been rule changes and initiaves brougt out by the NFL in attempts to bring down the amount of crime associated with its athletes. We used data, from 2000-2017, looking at all the details possible surrounding the arrests in order to unearth patterns, connections and to see if the NFL's goal is trending in the positive direction and working towards becoming accomplished. 

<font size="7">Research Questions and Motivations:
As a group we were curious about whether playing a certain position, how often you're get or getting hit, had an connection to commiting more or less crimes. On top of that we wondered if the NFL's inititives had any affect on the behavior of the players off the field.
  - Are Defensive Players Committing More Violent Crimes?
  - Has the NFL Successfully Decreased Crime in Their Organization?
    
<font size="7">Data Exploration and Clean-Up Process:

We downloaded our dataframe from the Kaggle website linked below. The file was originally a CSV file and we then did our work on both VS Code and Jupyter Notebooks before pushing it all to our GitHub. Our data is filled with 842 rows with detailed information about who committed what crime, when, and what the resolution was. The first important step was cleaning the dataframe to suit our needs. We had to extract keyword data from the resolution column in order to create 5 other columns. These columns were filled with 'Yes/No' and '1/0' values, which were then counted for graphing. We created another subset of data called 'Violent Crimes,' which combined data from a multitude of different crimes to be analyzed under a separate category. We did this same method for creating subsets about Ofeensive, Defensive and Special Teams Players as well. Reading through the dataframe checking for inconsistencies was also necessary to ensure there was no data that would affect our analysis.
Kaggle: https://www.kaggle.com/datasets/patrickmurphy/nfl-arrests/data

<font size="7">Data Analysis Process:
To better understand these statistics we needed to analyze our data and create certain graphs to decide on our hypothesis:
  - <font size="6">Hypothesis Testing
  
  We hypothesized that defensive players would commit more crimes than offensive players because how often they are slamming their heads into the opposition. We also thought that the NFL would not be able to decrease crime amongst its players.
  - <font size="6">Statistical Analysis


  - <font size="6">Bar Graphs


  - <font size="6">Line Graphs


  - <font size="6">Linear Regression



<font size="7">Project Analysis:

  - In our first question, 'Whether Defensive Players commit more violent crimes,' we hypothesized that they would, assuming that these positions involve more physical contact than offensive roles. Consequently, we speculated that defensive players might exhibit more aggression off the field. We reasoned that the repeated trauma from such hits, often associated with conditions like Chronic Traumatic Encephalopathy (CTE), could contribute to increased violence outside of the game. However, based on the available data, we cannot conclusively assert that defensive players commit more violent crimes.

Instead, our analysis suggests a different correlation: players subjected to higher levels of physical contact are more likely to engage in violent and criminal behavior. Notably, among the top four positions associated with violent crimes, half are offensive players, while the other half are defensive players.

  - Our second question aims to determine whether the National Football League (NFL) has succeeded in reducing the incidence of crimes committed by its players. Our hypothesis was that, no, the NFL has not been successful. This conclusion was based on the advancements of social media and the abundance of videos depicting various assaults, along with the significant backlash the NFL faced. We found, however, that following the 2006 change in NFL policy, which addressed all types of crimes, there was a decrease in violent crimes committed year after year. This decline can be attributed to the heightened repercussions outlined in the policy. The r-value (0.7285) indicates a moderately strong correlation between the two variables, while the p-value (< 0.05) suggests that the correlation is significant and not merely due to random fluctuations in the data. Regarding the second graph, which examines the number of players released, the r-value (0.12) indicates a weak correlation. Furthermore, the p-value (0.325), being above the 0.05 threshold, indicates that we cannot confidently conclude the relationship is genuine.

Following the NFL policy change in 2014, which specifically targeted violent crimes, including domestic violence, we observed a decrease in these offenses. However, due to the limited overall data available, our findings were inconclusive. The r-value (0.635) indicates a moderate to strong correlation, but the p-value (0.20), exceeding the 0.05 threshold, does not support statistical significance.

<font size="7">Table of Contents: 
  - 01_charts:
Analyzes of type of arrests over the years. Including Line charts and Linear Regression Analysis. 
  - 02_bar_graphs:
Analyzes who is getting arrested over the years based on position type & Offensive/Defensive players. Including Bar Charts.
  - 03_statistics:
Analyzes the statistical functions of all of our data. 
  - 04_data_library:
Creating new columns to our dataframe, cleaning all of the data in preperation for the analysis.


<font size="7">Limitations: 

  - The dataframe itself was slightly under 1000 values, clocking in at 842, which it is preferred to be above that figure.
  - The dataframe only had the years up until 2017, being that is 2024 we are missing out on 7 years of data which makes it harder to conclude statistical significance when it came to question 2.


<font size="7">Credits/Sources/Thanks: 
  - Kaggle Datasets
  - https://stackoverflow.com/questions/19913659/how-do-i-create-a-new-column-where-the-values-are-selected-based-on-existing-col?newreg=909067fbb9d7451882800c4acc13174a
  - 

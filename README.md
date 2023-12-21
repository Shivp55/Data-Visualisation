# Data-Visualisation
Data: 
The Global Health Observatory (GHO) data repository of the World 
Health OrganisaƟ on (WHO) keeps track of various perƟ nent factors, 
including each country's health status. The datasets are made public 
so that they can be used by anybody to analyse health data. The 
dataset for life expectancy, health factors for 193 countries, and 
associated economic figures were all sourced from the same WHO 
data repository website. From each category of health-related issues, 
only the most representaƟ ve criƟ cal factors were chosen. Human 
mortality rates have improved significantly over the past 15 years, 
especially in emerging naƟ ons, when compared to the previous 30 
years, it has been highlighted. Data for 193 countries were used from 
the years 2000 to 2015 to conduct addiƟ onal analysis for this project. 
The various data sets were combined to form a single dataset. Some 
values were missing when the data were first visually inspected. 
Because the datasets were provided by the WHO, we did not 
discover any obvious errors. To manage missing data, the Missmap 
command in R was employed. The populaƟ on, HepaƟƟ s B, and GDP 
had the most missing data, the results showed. The missing 
informaƟ on was contributed by lesser-known countries like Vanuatu, 
Tonga, Togo, Cabo Verde, etc. It was decided to exclude these 
countries from the final model dataset since it was difficult to find all 
the data for these countries. The resulƟ ng merged file, which 
includes 22 columns and 2938 rows in the final dataset, contains 20 
predicƟ ng variables. Then, all anƟ cipated variables were divided into 
four main groups: immunisaƟ ons, economic factors, societal issues, 
and mortality-related factors. 
The publicly available dataset provides data for 193 countries 
spanning from year 2000 to year 2015 and is structured in 2938 
rows (data points) which are characterized into a total of 22 
columns (features). The features can be categorized into two 
groups: 
 Health factors which are originally provided by the Global 
Health Observatory (GHO) data repository under the Wor 
Health Organization (WHO) 
 Economic factors which have been collected by the United 
Nation (UN) website. 
The link to the dataset is as below: 
Life Expectancy (WHO) | Kaggle

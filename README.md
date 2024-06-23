The following notebook contains an exploratory data analysis of a waterjet-cutting machine. 
The dataset contains data regarding the parameters, quality measures and used materials of a waterjet-cutting machine. 
In the notebook I will clean the data, explore the structure and insights of individual features and extract insights, using a combination of features. 
I will do this by the use of the pandas package and by visualizing the data. The goal is to get a better understanding of the machines function for future operations.

The features of the dataset are the following:\
**prod_day:** A time index for the day of production\
**part_type:** The type of product that is cut, using the machine\
**material:** The material that is cut, using the machine\
**part_number:** The part number of the product that is cut, using the machine\
**nozzle_diameter:** The diameter of the nozzle where the water is directed towards the workpeace (in mm)\
**thickness:** The thickness of the the cut material\
**standoff_distance:** The distance between the nozzle and the cut material (in mm)\
**traverse_speed:** the speed of the nozzle (in mm/min)\
**kerf:** The average acutal cut diameter of the workpeace\
**Ra:** A measure of cut quiality. The lower the Ra-value, the higher the quality of the cut\

Used skills: Data exploration and cleaning, univariate and multivariate analysis, data handling with pandas, data visualization, statistical analysis

++++Please note that this was a group assignment at the Chair of Production Management at the University of Mannheim. Since the data was provided by the chair, I won't publish the dataset.++++

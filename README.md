# Is a High Divorce Rate among Celebrities?

- Author:  Chiyuan Cheng (cyuancheng AT gmail DOT com) 
- Last updated: May 16, 2019

## Table of Contents

1. [Project Motivation](#motivation)
2. [Installation](#installation)
3. [File Description](#files)
4. [Results](#results)
5. [License](#licensing)

## Project Motivation<a name="motivation"></a>

We hear about celebrity breakups almost everyday. I'm curious about if celebrities have a higher divorce rate than the general population. If so, what is their divorce rate? How long are their marriage last? What's the key reason to drive their divorces? Is it predictable? Exploratory data analysis and machine learning were used to answer those questions.

## Installation <a name="installation"></a>

There should be no necessary libraries to run the code here beyond the Anaconda distribution of Python. The code should run with no issues using Python versions 3.*.

## File Descriptions <a name="files"></a>

-  **Data**:  I parsed data of Hollywood's actor and actress from the following two Wikipedia websites. 

   * [List of American film actresses](https://en.wikipedia.org/wiki/List_of_American_film_actresses)    
   * [American male film actors](https://en.wikipedia.org/wiki/Category:American_male_film_actors)


- **Jupyter Notebook**:  

	* `01_get_actress_data.ipynb` - Gather and assess actress data 
	* `02_get_actor_data.ipynb` - Gather and access actor data
	* `03_Scrape_actor_actress_data.ipynb` - Scrape and clean data
	* `04_DataVist.ipynb` - Analyze and visualize data 
	* `05_Prep_ML_data.ipynb` - Feature enginerring and prep of ML data 
	* `06_ML_model_building_tuning.ipynb` - ML model 


## Results<a name="results"></a>

The main findings can be found at the [blog post](https://medium.com/@cyuancheng/is-a-high-divorce-rate-among-celebrities-b87a9b9bdf28) available

1. What is the divorce rate amongst U.S celebrities in Hollywood compared to the general U.S population?
	* 52% divorce rate for celebrity, which is about 2 times higher than the general U.S. population
2. How long is celebrity marriage last?
	* The median value is 6 year in their first marriages
3. Which feature has the most impact on celebrity divorce?
	* Current age and the age at the first marriage. 



## License<a name="licensing"></a>

I will give the credit to Udacity to inspire me to come up with this project.

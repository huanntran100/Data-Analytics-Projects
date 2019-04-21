# Data Analytics Portfolio 
This portfolio is a collection of notebooks for data analysis and machine learning. 

## Classification problems.

### Spotify Song Popularity Prediction 
[Kaggle Kernel](https://www.kaggle.com/huanntran100/spotify-song-popularity-prediction)

Many factors go into whether or not a song becomes popular. Using multiple binary classification algorithms in Python, I predict the popularity or lack thereof of songs based purely on auditory metrics such as tempo, dancibility, and loudness, while excluding nonmusical metrics such as genre, artist name, and release date. A [dataset](https://www.kaggle.com/zaheenhamidani/ultimate-spotify-tracks-db) containing 228,000+ tracks was used for model training and testing. 

## Data Exploration and Analysis

### America Time Use Survey 
[Tableau Viz: Hours spent on leisure activities, average per day by education level and day, 2003 annual averages](https://public.tableau.com/profile/steven.tran1579#!/vizhome/Hoursspentonselectleisureactivitiesaveragesperdaybyeducationallevelandsex2003annualaverages/Dashboard3)  
[Tableau Viz: Hours spent on working and volunteering, average per day by education level and day, 2003 annual averages](https://public.tableau.com/profile/steven.tran1579#!/vizhome/Hoursspentonworkingandvolunteeringaveragesperdaybyeducationallevelandsex2003annualaverages/Dashboard1)

The [American Time Use Survey](https://www.bls.gov/tus/) is an ongoing annual survey since 2003 that collects data on how everyday Americans spend their time according to metrics such as sex, income, education, and age. I investigate various relationships not shown on the website itself. Inspiration for my current visualizations go to charts like this [https://www.bls.gov/charts/american-time-use/activity-by-sex.htm].  


### U.S. Job Automation Potential in 2018
[Tableau Viz: Map of Automation Potential by State, 2018](https://public.tableau.com/profile/steven.tran1579#!/vizhome/AutomationPotentialintheUnitedStates2018/AutomationPotential2018)

With the rise of artificial intelligence and automation in the 21st century, jobs traditionally occupied by humans such as retail, truck driving, and manufacturing are in danger of being replaced by robotcs. As inspiration, I looked at a [2019 Brookings University Report](https://www.brookings.edu/research/automation-and-artificial-intelligence-how-machines-affect-people-and-places/) on job automation to get an idea of what datasets and statistics they used. Using a state-level employment [dataset](https://www.bls.gov/oes/current/oes_nat.htm) from the U.S. Department of Labor and Statitics and automation probability [data](https://data.world/wnedds/occupations-by-state-and-likelihood-of-automation) from the University of Oxford, I create an interative Tableau map visualization for viewing the top 5 jobs with the highest potential for automation in each U.S. state. 

## Machine Learning

### Q-Learning and Sparse Incremental Feature Dependency Discovery (iFDD)
[Jupyter Notebook](https://nbviewer.jupyter.org/github/huanntran100/Learning-RL/blob/master/Bioengineering%20Senior%20Design/Q-Learning%20and%20Sparse%20iFDD%20on%20Swimmer-v1%20Write-Up.ipynb) 

Here, I investigate the use of iFDD for Q-Learning on a 3-jointed robotic snake using OpenAI Gym and Python. Optimal planning and reinforcement learning for robotics is an ongoing challenge due to time and training required to traverse large state-action space. Traditional tabular functions are limited by the curse-of-dimensionality, and thus, linear and nonlinear approximators are used to learn the state-action value Q(s,a) function. [iFDD](http://people.csail.mit.edu/agf/Homepage/Research/Entries/2011/12/13_Incremental_Feature_Dependency_Discovery.html) was developed by a team at MIT in 2013 to accompany linear approximations for Q-Learning in large Markov Decision Spaces for the UAV fueling problem. 

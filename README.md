# CEE506: Environmental Spatial Data Analysis
## Fall 2025

## Course Information
Lectures are on Tuesdays and Thursdays from 8:30 AM - 9:45 AM. The course website is on GitHub (https://github.com/chaneyn/CEE506). Class announcements will be made via Canvas (CEE 506.01.Fa25).

### Instructor
Professor Nathaniel W. Chaney (Nate)  
Email: nathaniel.chaney@duke.edu  
Office: FCIEMAS 2463  
Office hours: by reservation (calendly.com/nathaniel-chaney) Tuesdays 10am-12pm

### TA
Daniel Guyumus Preciado  
Email: daniel.guyumus.preciado@duke.edu 
Office hours location: TBD 
Office hours: TBD

## Course Description
Environmental Spatial Data Analysis (ESDA) provides an introduction on how to leverage large volumes of spatial environmental data using primarily Python. The topics that will be covered include an overview of basic spatial statistics, spatial interpolation, kriging, conditional simulation, terrain analysis, dimensionality reduction, and spatial prediction. Existing software packages in Python will be introduced and used to explore the listed topics. 

## Prerequisites
Although there are no class prerequisistes, a strong foundation in programming will make this class much easier. Please contact Nate if you have concerns. 

## Readings
There are no required textbooks. Reading will be provided via journal articles, online materials, and tutorials.

## Grades and workload
The course grade is based on three items:
* Homework: 55%
* Final Project: 25%
* Quizzes: 10%
* Participation: 10%


### Homework
There will be 4 homework assignments. Each assignment will be provided and completed within a corresponding Jupyter notebook. Completed assignments will be submitted via a private GitHub repository that each student will have for the course; assignments submitted via any other method will not be accepted. Each assignment must be submitted before class on the day listed on the schedule below. Late homeworks will not be accepted. 

### Quizzes
There will be 4 quizzes; one after each homework assignment is due. These 30 min quizzes will be closed book/closed notes and will be based around the previous homework. You are expected to write pseudo-code in Python to answer the questions.  

### Participation
* Students should follow along the lecture on their personal jupyter lab Docker container that they will use for the course. 

### Collaboration
Collaboration in completing assignments is permitted. However, each student must write up their assignment independently. We **will** be checking for identical homeworks. 

### Final Project
The final project can be done in groups or individually. The expectations for the project will increase with the group size. It will involve the following components:
* Proposal (November 7th via email)
  * 3 pages max, single-spaced, 12 point font size, 1 inch margin
  * Contains: Title, introduction, objectives, data, methodology, and timeline of tasks
* Oral presentation (December 7th in class)
  * 12 minute oral presentation, 3 minutes for questions
  * Everyone needs to be present for each presentation
* Final report (December 18th via email)
  * 10 pages max, single-spaced, 12 point font size, 1 inch margin
  * Contains: Title, introduction, data, methods, results, discussion, and conclusion
  
### Schedule
Note that the schedule is subject to change.

|Date|Topic|New Software|Assignments|
|:-:|:-:|:-:|:-:|
|08/27|[Introduction](https://github.com/chaneyn/ESDA_CEE690-02/blob/master/Lectures/Introduction.pdf)|Jupyter/GitHub/Bash|-|
|08/29|[Python overview](https://github.com/chaneyn/ESDA_CEE690-02/blob/master/Lectures/Python_Overview.ipynb)|Python|-| 
|09/03|[Multi-dimensional arrays I](https://github.com/chaneyn/ESDA_CEE690-02/blob/master/Lectures/Numpy.ipynb)|NumPy|HW #0 due|
|09/05|[Probability/Statistics I](https://github.com/chaneyn/ESDA_CEE690-02/blob/master/Lectures/Intro2ProbabilityI.ipynb)|Scipy|-|
|09/10|[Visualizing data](https://github.com/chaneyn/ESDA_CEE690-02/blob/master/Lectures/Visualizing_Data.ipynb)|Matplotlib|-|
|09/12|[Data storage](https://github.com/chaneyn/ESDA_CEE690-02/blob/master/Lectures/DataStorage.ipynb)|Pickle/H5py/NetCDF/GeoTiff|-|
|09/17|[Probability/Statistics II](https://github.com/chaneyn/ESDA_CEE690-02/blob/master/Lectures/Intro2ProbabilityII.ipynb)|-|HW #1 due|
|09/19|[Bayesian Statistics](https://cee-az-00.oit.duke.edu:50000/notebooks/ESDA_CEE690-02/Lectures/BayesianStatistics.ipynb)|-|-|
|09/24|[Map projections I](https://github.com/chaneyn/ESDA_CEE690-02/blob/master/Lectures/MapProjectionsI.ipynb)|Cartopy|-|
|09/26|[Map projections II](https://github.com/chaneyn/ESDA_CEE690-02/blob/master/Lectures/MapProjectionsII.ipynb)|GDAL|-|
|10/01|[Multi-dimensional arrays II](https://github.com/chaneyn/ESDA_CEE690-02/blob/master/Lectures/MultidimensionalArraysII.ipynb)|CDO/Xarray|-|
|10/03|[Vector Data](https://github.com/chaneyn/ESDA_CEE690-02/blob/master/Lectures/VectorData.ipynb)|OGR/Shapely/GeoPandas|-|
|10/8|[Cluster Analysis I](https://github.com/chaneyn/ESDA_CEE690-02/blob/master/Lectures/ClusterAnalysisI.ipynb)|Scikit-Learn|HW #2 due|
|10/10|[Cluster Analysis II](https://github.com/chaneyn/ESDA_CEE690-02/blob/master/Lectures/ClusterAnalysisII.ipynb)|-|-|
|10/17|[Dimensionality Reduction](https://github.com/chaneyn/ESDA_CEE690-02/blob/master/Lectures/DimensionalityReduction.ipynb)|-|-|
|10/22|[Decision Trees](https://github.com/chaneyn/ESDA_CEE690-02/blob/master/Lectures/DecisionTrees.ipynb)|-|-|
|10/24|[Random Forests/Boosting](https://github.com/chaneyn/ESDA_CEE690-02/blob/master/Lectures/RandomForests.ipynb)|-|-|
|10/29|Artificial Neural Networks|-|-|
|10/31|Convolutional Neural Networks|-|HW #3 due|
|11/05|[Simple Kriging](https://github.com/chaneyn/ESDA_CEE690-02/blob/master/Lectures/SimpleKriging.ipynb)|-|**Proposal due**|
|11/07|[Ordinary Kriging](https://github.com/chaneyn/ESDA_CEE690-02/blob/master/Lectures/OrdinaryKriging.ipynb)|-|-|
|11/12|[Semivariogram](https://github.com/chaneyn/ESDA_CEE690-02/blob/master/Lectures/Semivariogram.ipynb)|-|-|
|11/14|[Regression Kriging](https://github.com/chaneyn/ESDA_CEE690-02/blob/master/Lectures/RegressionKriging.ipynb)|-|-|
|11/19|[Terrain Analysis](https://github.com/chaneyn/ESDA_CEE690-02/blob/master/Lectures/TerrainAnalysisI.ipynb)|-|-|
|11/21|TBD|-|-|
|11/26|Scaling up code|Numba/Mpi4py/Dask|HW #4 due|
|12/10|**Oral Presentations**|-|-|-| 
|12/18|**Written report due**|-|-|-| 

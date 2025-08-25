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
|08/29|[Python overview](https://github.com/chaneyn/ESDA_CEE690-02/blob/master/Lectures/Python_Overview.ipynb)|Python|-|-| 
|09/03|[Multi-dimensional arrays I](https://github.com/chaneyn/ESDA_CEE690-02/blob/master/Lectures/Numpy.ipynb)|NumPy|HW #0 due|-|
|09/05|[Probability/Statistics I](https://github.com/chaneyn/ESDA_CEE690-02/blob/master/Lectures/Intro2ProbabilityI.ipynb)|Scipy|-|[Holmes, 2018](https://medium.com/planet-stories/the-explosion-of-geospatial-data-and-the-rise-of-deep-learning-b22aa8fef519) (TBD)|
|09/10|[Visualizing data](https://github.com/chaneyn/ESDA_CEE690-02/blob/master/Lectures/Visualizing_Data.ipynb)|Matplotlib|-|[Rougier et al., 2014](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1003833) (TBD)|
|09/12|[Data storage](https://github.com/chaneyn/ESDA_CEE690-02/blob/master/Lectures/DataStorage.ipynb)|Pickle/H5py/NetCDF/GeoTiff|-|-|
|09/17|[Probability/Statistics II](https://github.com/chaneyn/ESDA_CEE690-02/blob/master/Lectures/Intro2ProbabilityII.ipynb)|-|HW #1 due|[Walther and Moore, 2005](https://onlinelibrary.wiley.com/doi/10.1111/j.2005.0906-7590.04112.x) (TBD)|
|09/19|[Bayesian Statistics](https://cee-az-00.oit.duke.edu:50000/notebooks/ESDA_CEE690-02/Lectures/BayesianStatistics.ipynb)|-|-|-|
|09/24|[Map projections I](https://github.com/chaneyn/ESDA_CEE690-02/blob/master/Lectures/MapProjectionsI.ipynb)|Cartopy|-|[Lapaine, 2017](https://link.springer.com/chapter/10.1007/978-3-319-51835-0_11) (TBD)|
|09/26|[Map projections II](https://github.com/chaneyn/ESDA_CEE690-02/blob/master/Lectures/MapProjectionsII.ipynb)|GDAL|-|[Asay, 2020](https://thenewstack.io/gdal-the-open-source-technology-behind-google-maps/) and [Simmon, 2017](https://medium.com/planet-stories/a-gentle-introduction-to-gdal-part-1-a3253eb96082) (TBD)|
|10/01|[Multi-dimensional arrays II](https://github.com/chaneyn/ESDA_CEE690-02/blob/master/Lectures/MultidimensionalArraysII.ipynb)|CDO/Xarray|-|[Hoyer and Hamman, 2017](https://openresearchsoftware.metajnl.com/articles/10.5334/jors.148/) (TBD)|
|10/03|[Vector Data](https://github.com/chaneyn/ESDA_CEE690-02/blob/master/Lectures/VectorData.ipynb)|OGR/Shapely/GeoPandas|-|[Kreveld, 2006](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.109.2967&rep=rep1&type=pdf#:~:text=The%20research%20area%20of%20computational,an%20algorithm%20solves%20a%20problem.&text=Many%20basic%20problems%20of%20computational,or%20indirect%20use%20to%20GIS.) (TBD)|
|10/8|[Cluster Analysis I](https://github.com/chaneyn/ESDA_CEE690-02/blob/master/Lectures/ClusterAnalysisI.ipynb)|Scikit-Learn|HW #2 due|[Mishra, 2017](https://towardsdatascience.com/unsupervised-learning-and-data-clustering-eeecb78b422a) (TBD)|
|10/10|[Cluster Analysis II](https://github.com/chaneyn/ESDA_CEE690-02/blob/master/Lectures/ClusterAnalysisII.ipynb)|-|-|-|
|10/17|[Dimensionality Reduction](https://github.com/chaneyn/ESDA_CEE690-02/blob/master/Lectures/DimensionalityReduction.ipynb)|-|-|-|
|10/22|[Decision Trees](https://github.com/chaneyn/ESDA_CEE690-02/blob/master/Lectures/DecisionTrees.ipynb)|-|-|[Homer et al., 2004](https://www.ingentaconnect.com/content/asprs/pers/2004/00000070/00000007/art00005#) (TBD)|
|10/24|[Random Forests/Boosting](https://github.com/chaneyn/ESDA_CEE690-02/blob/master/Lectures/RandomForests.ipynb)|-|-|[Kaminska, J., 2018, Cai, J., et al., 2020](https://www.sciencedirect.com/science/article/pii/S030147971830327X) (TBD)|
|10/29|Artificial Neural Networks|-|-|-|
|10/31|Convolutional Neural Networks|-|HW #3 due|-|
|11/05|[Simple Kriging](https://github.com/chaneyn/ESDA_CEE690-02/blob/master/Lectures/SimpleKriging.ipynb)|-|**Proposal due**|[Wong, D., et al., 2004](https://www.nature.com/articles/7500338) (TBD)|
|11/07|[Ordinary Kriging](https://github.com/chaneyn/ESDA_CEE690-02/blob/master/Lectures/OrdinaryKriging.ipynb)|-|-|-|
|11/12|[Semivariogram](https://github.com/chaneyn/ESDA_CEE690-02/blob/master/Lectures/Semivariogram.ipynb)|-|-|[Pouladi, N., et al., 2019](https://www.sciencedirect.com/science/article/abs/pii/S0016706118319621?via%3Dihub) (TBD)|
|11/14|[Regression Kriging](https://github.com/chaneyn/ESDA_CEE690-02/blob/master/Lectures/RegressionKriging.ipynb)|-|-|[Hengl, T., et al., 2007](https://www.sciencedirect.com/science/article/pii/S0098300407001008?via%3Dihub) (TBD)|
|11/19|[Terrain Analysis I](https://github.com/chaneyn/ESDA_CEE690-02/blob/master/Lectures/TerrainAnalysisI.ipynb)|-|-|[Moore, I., et al., 1991](https://onlinelibrary.wiley.com/doi/epdf/10.1002/hyp.3360050103) (TBD)|
|11/21|Visualization II|-|-||
|11/26|Scaling up code|Numba/Mpi4py/Dask|HW #4 due|[Bakharia, A., 2018](https://towardsdatascience.com/why-every-data-scientist-should-use-dask-81b2b850e15b) and [Grover, P., 2018](https://towardsdatascience.com/speed-up-your-algorithms-part-2-numba-293e554c5cc1) (TBD)|
|12/10|**Oral Presentations**|-|-|-| 
|12/18|**Written report due**|-|-|-| 

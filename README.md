# CEE690-02: Environmental Spatial Data Analysis
## Fall 2020

## Course Information
Lectures are on Tuesdays and Thursdays from 3:30 PM - 4:45 PM. The course website is on GitHub (https://github.com/chaneyn/CEE690-02). Class announcements will be made via Sakai (CEE690.02.F20).

### Instructor
Professor Nathaniel W. Chaney (Nate)  
Email: nathaniel.chaney@duke.edu  
Office: FCIEMAS 2463  
Office hours: Thursdays after class via Zoom

### TA
Laura Torres  
Email: lpt14@duke.edu   
Office hours: Mondays 8-10am via Zoom  

## Course Description
Environmental Spatial Data Analysis (ESDA) provides an introduction on how to leverage large volumes of spatial environmental data using primarily Python. The topics that will be covered include an overview of basic spatial statistics, spatial interpolation, kriging, conditional simulation, terrain analysis, dimensionality reduction, and spatial prediction. Existing software packages in Python will be introduced and used to explore the listed topics. 

## Prerequisites
Although there are no class prerequisistes, a strong foundation in programming will make this class much easier. Please contact Nate if you have concerns. 

## Readings
There are no required textbooks. Reading will be provided via journal articles, online materials, and tutorials.

## Grades and workload
The course grade is based on three items:
* Homework: 40%
* Participation: 20%
* Final Project: 40%

### Homework
There will be 4 homework assignments. Each assignment will be provided and completed within a corresponding Jupyter notebook. Completed assignments will be submitted via a private GitHub repository that each student will have for the course; assignments submitted via any other method will not be accepted. Each assignment must be submitted before class on the day listed on the schedule below. Late homeworks will not be accepted. 

### Participation
* Students should follow along the lecture on their personal jupyter lab Docker container that they will use for the course. 
* Each student will present twice. The first presentation will involve describing a dataset and the second will be present a journal article. 

### Collaboration
Collaboration in completing assignments is permitted. However, each student must write up their assignment independently. We **will** be checking for identical homeworks. 

### Final Project
The final project can be done in groups of 2 or individually. The expectations for the project will increase with the group size. It will involve the following components:
* Initial Proposal (October 22nd via email)
  * 3 pages max, single-spaced, 12 point font size, 1 inch margin
  * Contains: Title, introduction, objectives, data, methodology, and timeline of tasks
* Oral presentation (November 17th and 19th in class)
  * 12 minute oral presentation, 3 minutes for questions
  * Everyone needs to be present for each presentation
* Final report (November 24th via email)
  * 10 pages max, single-spaced, 12 point font size, 1 inch margin
  * Contains: Title, introduction, data, methods, results, discussion, and conclusion
  
### Schedule
Note that the schedule is subject to change.

|Date|Topic|New Software|Assignments|Article|
|:-:|:-:|:-:|:-:|:-:|
|08/18|[Introduction](https://github.com/chaneyn/ESDA_CEE690-02/blob/master/Lectures/Introduction.pdf)|Jupyter/GitHub/Bash|-|-|
|08/20|[Python overview](https://github.com/chaneyn/ESDA_CEE690-02/blob/master/Lectures/Python_Overview.ipynb)|Python|-|[Lin, J., 2012](https://journals.ametsoc.org/bams/article/93/12/1823/60266/Why-Python-Is-the-Next-Wave-in-Earth-Sciences)|
|08/25|[Multi-dimensional arrays I](https://github.com/chaneyn/ESDA_CEE690-02/blob/master/Lectures/Numpy.ipynb)|NumPy|-|[Lu et al., 2018](https://www.mdpi.com/2220-9964/7/8/313/htm) (Owen Daly)|
|08/27|[Visualizing data](https://github.com/chaneyn/ESDA_CEE690-02/blob/master/Lectures/Visualizing_Data.ipynb)|Matplotlib|-|[Rougier et al., 2014](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1003833) (Keqi He)|
|09/01|[Data storage](https://github.com/chaneyn/ESDA_CEE690-02/blob/master/Lectures/DataStorage.ipynb)|Pickle/H5py/NetCDF/GeoTiff|-|[Extance, 2016](https://www.nature.com/news/how-dna-could-store-all-the-world-s-data-1.20496) (Laura Torres)|
|09/03|[Probability/Statistics I](https://github.com/chaneyn/ESDA_CEE690-02/blob/master/Lectures/Intro2ProbabilityI.ipynb)|Scipy|-|[Holmes, 2018](https://medium.com/planet-stories/the-explosion-of-geospatial-data-and-the-rise-of-deep-learning-b22aa8fef519) (Celine Robinson)|
|09/08|[Probability/Statistics II](https://github.com/chaneyn/ESDA_CEE690-02/blob/master/Lectures/Intro2ProbabilityII.ipynb)|-|HW #1 due|[Walther and Moore, 2005](https://onlinelibrary.wiley.com/doi/10.1111/j.2005.0906-7590.04112.x) (Sarah Scott)|
|09/10|[Bayesian Statistics](https://cee-az-00.oit.duke.edu:50000/notebooks/ESDA_CEE690-02/Lectures/BayesianStatistics.ipynb)|-|-|[Prathvikumar, 2019](https://towardsdatascience.com/intro-to-bayesian-statistics-5056b43d248d) (Gary Jiang)|
|09/15|[Map projections I](https://github.com/chaneyn/ESDA_CEE690-02/blob/master/Lectures/MapProjectionsI.ipynb)|Cartopy|-|[Lapaine, 2017](https://link.springer.com/chapter/10.1007/978-3-319-51835-0_11) (Lijia Gao)|
|09/17|[Map projections II](https://github.com/chaneyn/ESDA_CEE690-02/blob/master/Lectures/MapProjectionsII.ipynb)|GDAL|-|[Asay, 2020](https://thenewstack.io/gdal-the-open-source-technology-behind-google-maps/) and [Simmon, 2017](https://medium.com/planet-stories/a-gentle-introduction-to-gdal-part-1-a3253eb96082) (Huda Aslam)|
|09/22|[Multi-dimensional arrays II](https://github.com/chaneyn/ESDA_CEE690-02/blob/master/Lectures/MultidimensionalArraysII.ipynb)|CDO/Xarray|-|[Hoyer and Hamman, 2017](https://openresearchsoftware.metajnl.com/articles/10.5334/jors.148/) (Cary Shindell)|
|09/24|[Vector Data](https://github.com/chaneyn/ESDA_CEE690-02/blob/master/Lectures/VectorData.ipynb)|OGR/Shapely/GeoPandas|-|[Kreveld, 2006](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.109.2967&rep=rep1&type=pdf#:~:text=The%20research%20area%20of%20computational,an%20algorithm%20solves%20a%20problem.&text=Many%20basic%20problems%20of%20computational,or%20indirect%20use%20to%20GIS.) (Rundong Ji)|
|09/29|[Cluster Analysis I](https://github.com/chaneyn/ESDA_CEE690-02/blob/master/Lectures/ClusterAnalysisI.ipynb)|Scikit-Learn|-|[Mishra, 2017](https://towardsdatascience.com/unsupervised-learning-and-data-clustering-eeecb78b422a) (Peiran Wang)|
|10/01|[Cluster Analysis II](https://github.com/chaneyn/ESDA_CEE690-02/blob/master/Lectures/ClusterAnalysisII.ipynb)|-|-|-|
|10/06|[Dimensionality Reduction](https://github.com/chaneyn/ESDA_CEE690-02/blob/master/Lectures/DimensionalityReduction.ipynb)|-|HW #2 due|-|
|10/08|[Decision Trees](https://github.com/chaneyn/ESDA_CEE690-02/blob/master/Lectures/DecisionTrees.ipynb)|-|-|[Homer et al., 2004](https://www.ingentaconnect.com/content/asprs/pers/2004/00000070/00000007/art00005#) (Huda Aslam)|
|10/13|No class|-|-|-|
|10/15|[Random Forests](https://github.com/chaneyn/ESDA_CEE690-02/blob/master/Lectures/RandomForests.ipynb)|-|-|[Kaminska, J., 2018](https://www.sciencedirect.com/science/article/pii/S030147971830327X) (Sarah Scott)|
|10/20|[Boosting](https://github.com/chaneyn/ESDA_CEE690-02/blob/master/Lectures/Boosting.ipynb)|-|-|[Cai, J., et al., 2020](https://www.sciencedirect.com/science/article/abs/pii/S0306261920300787) (Celine Robinson)|
|10/22|Geostatistics I|-|**Proposal due**|[Wong, D., et al., 2004](https://www.nature.com/articles/7500338) (Gary Jiang)|
|10/27|Geostatistics II|-|-|[Pouladi, N., et al., 2019](https://www.sciencedirect.com/science/article/abs/pii/S0016706118319621?via%3Dihub) (Lijia Gao)|
|10/29|Geostatistics III|-|-|TBD (Owen Daly)|
|11/03|Geostatistics IV|-|HW #3 due|-|
|11/05|Terrain Analysis I|-|-|TBD (Keqi He)|
|11/10|Terrain Analysis II|-|-|-|
|11/12|Scaling up code|Numba/Mpi4py/Dask|-|TBD (Cary Shindell)|
|11/17|**Oral Presentations**|-|-|-| 
|11/19|**Oral Presentations**|-|-|-| 
|11/24|**Written report due**|-|HW #4 due|-| 

# Data Preprocessing


## Steps Involved in Data Preprocessing:

### 1. Data Cleaning:

The data can have many irrelevant and missing parts. To handle this part, data cleaning is done. It involves handling of missing data, noisy data etc.

#### (a). Missing Data:
This situation arises when some data is missing in the data. It can be handled in various ways.
Some of them are:
##### Ignore the tuples:
This approach is suitable only when the dataset we have is quite large and multiple values are missing within a tuple.
##### Fill the Missing values:
There are various ways to do this task. You can choose to fill the missing values manually, by attribute mean or the most probable value.
#### (b). Noisy Data:
Noisy data is a meaningless data that can’t be interpreted by machines.It can be generated due to faulty data collection, data entry errors etc. It can be handled in following ways :

##### Binning Method:
This method works on sorted data in order to smooth it. The whole data is divided into segments of equal size and then various methods are performed to complete the task. Each segmented is handled separately. One can replace all data in a segment by its mean or boundary values can be used to complete the task.
##### Regression:
Here data can be made smooth by fitting it to a regression function.The regression used may be linear (having one independent variable) or multiple (having multiple independent variables).
##### Clustering:
This approach groups the similar data in a cluster. The outliers may be undetected or it will fall outside the clusters.

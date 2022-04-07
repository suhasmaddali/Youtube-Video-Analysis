# 📽 YouTube Video Analysis

[![](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=darkgreen)](https://www.python.org)  [![](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=TensorFlow&logoColor=white)](https://www.tensorflow.org) [![](https://img.shields.io/badge/scikit_learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/stable/) [![](https://img.shields.io/badge/SciPy-654FF0?style=for-the-badge&logo=SciPy&logoColor=white)](https://www.scipy.org) [![](https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white)](https://numpy.org) [![](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org)  [![](https://img.shields.io/badge/Plotly-239120?style=for-the-badge&logo=plotly&logoColor=white)](https://plotly.com) [![](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=Keras&logoColor=white)](https://keras.io) [![](https://img.shields.io/badge/conda-342B029.svg?&style=for-the-badge&logo=anaconda&logoColor=white)](https://www.anaconda.com)

## Introduction 
There are different types of videos being uploaded everyday at different instants of time in __YouTube__. It would be really useful if the content of these videos is being analysed. It would be good to understand the different category of videos presently being uploaded in __YouTube__ and look at different instances of time where they have been trending. In addition, it would help the users to understand the right time at which the videos could be uploaded and this ensures that a lot of time and effort is being saved during the uploading of different categories of videos. Moreover, these insights would help the company allocate time and resources during different parts of the year so that they get to know the videos that are being uploaded. Getting meaningful insights from the data and placing more emphasis on growing trends can alter the direction at which companies are operating and this would generate __revenue__ and __profits__ for them.

<img src = "https://github.com/suhasmaddali/Images/blob/main/Youtube%20Video%20Image.jpg" width = 750/>


## Steps Considered
In this problem, we would be analyzing the various trends in YouTube which includes views, likes and dislikes. Understanding different trends that are found in YouTube could ensure that best results are being generated. We would be using different data visualization techniques to ensure that we get the best results and insights from the data.

In addition to this, new features would be created so that one could get a good view of the ways in which these features shape likes and views of different set of videos that are trending in youtube. Moreover, we would also look at different dates where the videos were trending just to get a good understanding of the overall distribution of data respectively. 

We would be working with California YouTube data and perform data visualization to observe different trends present in the videos. We would be analyzing the videos and getting a good understanding of the data that is present at hand. 

## Exploratory Data Analysis (EDA)

* Most of the cateogry of videos that were taken are from __"Entertainment"__ compared to other categories such as __"Music"__ or __"Travel & Events"__.
* A large portion of videos had __comments enabled__ compared to a very few videos where they were __disabled__.
* The videos that were of __"Music"__ category were the most viewed compared to other categories such as __"Movies"__ being the second best. 
* The least viewed category of videos were __"Travel & Events"__ compared to the other categories based on the analysis.  
* A large number of comments were also given to __"Music"__ category videos compared to the others. The second best number of comments were given to __"Gaming"__ category videos. 
* A large amount of data was included for the year __"2018"__ compared to the hear __"2017"__ respectively. Therefore, we should be able to get a good estimate of the trends in __YouTube videos__ more accurately compared to the other categories. 
* There was a __good correlation__ between the __number of comments__ given to videos and the __total number of views__. This is true in __real-life__ as well because we know that the higher the number of views, the more would the comments be for the most part. This was being __reflected__ in the data as well. 
* It could also be seen from the __Heatmap__ that there is a __strong correlation__ between the __number of likes__ for a video and __comment counts__.
* Furthermore, there is also a __strong correlation__ between the __number of views__ of a video and also the __total number of likes__ as well.

## 👉 Directions to download the repository and run the notebook 

This is for the Washington Bike Demand Prediction repository. But the same steps could be followed for this repository. 

1. You'll have to download and install Git that could be used for cloning the repositories that are present. The link to download Git is https://git-scm.com/downloads.
 
&emsp;&emsp; <img src = "https://github.com/suhasmaddali/Youtube-Video-Analysis/blob/main/images/Screenshot%20(14).png" width = "600"/>
 
2. Once "Git" is downloaded and installed, you'll have to right-click on the location where you would like to download this repository. I would like to store it in "Git Folder" location. 

&emsp;&emsp; <img src = "https://github.com/suhasmaddali/Youtube-Video-Analysis/blob/main/images/Screenshot%20(15).png" width = "600" />

3. If you have successfully installed Git, you'll get an option called "Gitbash Here" when you right-click on a particular location. 

&emsp;&emsp; <img src = "https://github.com/suhasmaddali/Youtube-Video-Analysis/blob/main/images/Screenshot%20(16).png" width = "600" />


4. Once the Gitbash terminal opens, you'll need to write "Git clone" and then paste the link of the repository.
 
&emsp;&emsp; <img src = "https://github.com/suhasmaddali/Youtube-Video-Analysis/blob/main/images/Screenshot%20(18).png" width = "600" />

5. The link of the repository can be found when you click on "Code" (Green button) and then, there would be a html link just below. Therefore, the command to download a particular repository should be "Git clone html" where the html is replaced by the link to this repository. 

&emsp;&emsp; <img src = "https://github.com/suhasmaddali/Youtube-Video-Analysis/blob/main/images/Screenshot%20(17).png" width = "600" />

6. After successfully downloading the repository, there should be a folder with the name of the repository as can be seen below.

&emsp;&emsp; <img src = "https://github.com/suhasmaddali/Youtube-Video-Analysis/blob/main/images/Screenshot%20(19).png" width = "600" />

7. Once the repository is downloaded, go to the start button and search for "Anaconda Prompt" if you have anaconda installed. 

&emsp;&emsp; <img src = "https://github.com/suhasmaddali/Youtube-Video-Analysis/blob/main/images/Screenshot%20(20).png" width = "600" />

8. Later, open the jupyter notebook by writing "jupyter notebook" in the Anaconda prompt. 

&emsp;&emsp; <img src = "https://github.com/suhasmaddali/Youtube-Video-Analysis/blob/main/images/Screenshot%20(21).png" width = "600" />

9. Now the following would open with a list of directories. 

&emsp;&emsp; <img src = "https://github.com/suhasmaddali/Youtube-Video-Analysis/blob/main/images/Screenshot%20(22).png" width = "600" />

10. Search for the location where you have downloaded the repository. Be sure to open that folder. 

&emsp;&emsp; <img src = "https://github.com/suhasmaddali/Youtube-Video-Analysis/blob/main/images/Screenshot%20(12).png" width = "600" />

11. You might now run the .ipynb files present in the repository to open the notebook and the python code present in it. 

&emsp;&emsp; <img src = "https://github.com/suhasmaddali/Youtube-Video-Analysis/blob/main/images/Screenshot%20(13).png" width = "600" />

That's it, you should be able to read the code now. Thanks. 

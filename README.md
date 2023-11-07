# EX-9-Simulating-Classification-using-WEKA-Tool

# Date: 6.10.2023

# AIM:
To perform a classification technique using WEKA tool

# WEKA:

Weka is a comprehensive software that lets you to preprocess the big data, apply different machine learning algorithms on big data and compare various outputs. This software makes it easy to work with big data and train a machine using machine learning algorithms. This tutorial will guide you in the use of WEKA for achieving all the above requirements. WEKA - an open source software provides tools for data preprocessing, implementation of several Data mining and Machine Learning algorithms, and visualization tools so that you can develop machine learning techniques and apply them to real-world data mining problems. What WEKA offers is summarized in the following diagram −


![280514918-c3702dff-f72d-4ba1-9cca-eb444358ab21](https://github.com/prithviraj5703/EX-9-Simulating-Classification-using-WEKA-Tool/assets/121418418/79e0da39-2d11-4465-8de2-bf3068618f44)


# CLASSIFICATION:
Classification in data mining is a common technique that separates data points into different classes. It allows you to organize data sets of all sorts, including complex and large datasets as well as small and simple ones. It primarily involves using algorithms that you can easily modify to improve the data quality. This is a big reason why supervised learning is particularly common with classification in techniques in data mining. The Classification algorithm is a Supervised Learning technique that is used to identify the category of new observations on the basis of training data. In Classification, a program learns from the given dataset or observations and then classifies new observation into a number of classes or groups. Such as, Yes or No, 0 or 1, Spam or Not Spam, cat or dog, etc. Classes can be called as targets/labels or categories.

# PROCEDURE

  1. Load the data file into the WEKA explorer. The data can be loaded from the following sources − Local file system Web Database
  2. Click on the "Open file" button. A directory navigator window opens as shown in the following screen −
     

  ![280515172-7088c22f-650c-4869-93d0-b070c844c592](https://github.com/prithviraj5703/EX-9-Simulating-Classification-using-WEKA-Tool/assets/121418418/f721ddb9-9c38-490e-9f85-91e95d516938)

   
3.  Click on the Classify tab, and you would see the following screen
    

   ![280515276-d2863bed-3770-4b5b-84c6-c95a7f6f8702](https://github.com/prithviraj5703/EX-9-Simulating-Classification-using-WEKA-Tool/assets/121418418/a7486140-d29c-4833-b610-c5d1718de98a)

4.  Now, keep the default play option for the output class −

![280515305-45296fdf-5c28-4326-91c5-db77a31c7273](https://github.com/prithviraj5703/EX-9-Simulating-Classification-using-WEKA-Tool/assets/121418418/b7e52d4e-4f62-4df2-8997-a9ca7eebcb1c)

  
5.  Click on the Choose button and select the following classifier − weka→classifiers>trees>J48.

![280515336-bdbf5e47-9233-4fdc-a0b6-b22bf4c7aadc](https://github.com/prithviraj5703/EX-9-Simulating-Classification-using-WEKA-Tool/assets/121418418/cc648973-ea01-4c47-a4c3-afb3d391f463)

  
6. Click on the Start button to start the classification process. After a while, the classification results would be presented on your screen as shown here −


![280515360-7341a7e0-cb7c-4fd9-abd7-36cf9d484ae6](https://github.com/prithviraj5703/EX-9-Simulating-Classification-using-WEKA-Tool/assets/121418418/73bc8743-1bd7-49e7-affb-dad1eb33f5ff)


7.  To see the visual representation of the results, right click on the result in the Result list box. Several options would pop up on the screen as shown here −

      
 ![280515397-a846aee3-1e84-4101-932e-83029762593b](https://github.com/prithviraj5703/EX-9-Simulating-Classification-using-WEKA-Tool/assets/121418418/234dc86f-857d-4124-a0fc-06497a099fd1)
  
8.Select Visualize tree to get a visual representation of the traversal tree as seen in the screenshot below −
  
  ![280515424-a2aab1c7-a756-4de7-a1e5-1d6a5fa53321](https://github.com/prithviraj5703/EX-9-Simulating-Classification-using-WEKA-Tool/assets/121418418/8780066e-690d-4aae-8603-dd521466e5c8)

    
  9. Selecting Visualize classifier errors would plot the results of classification as shown here −

   ![280515476-9d39bad9-a77c-4c72-a9bb-0031154ef0c4](https://github.com/prithviraj5703/EX-9-Simulating-Classification-using-WEKA-Tool/assets/121418418/8f5c5964-972f-4845-9fe5-c9fcd1ec81d5)


  10. A cross represents a correctly classified instance while squares represents incorrectly classified instances. At the lower left corner of the plot you see a cross that indicates if outlook is sunny then play the game. So this is a correctly classified instance.

# RESULT:
Thus the simulation of classification technique has been executed using WEKA tool successfully.

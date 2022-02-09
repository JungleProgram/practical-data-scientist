# :mortar_board: The Practical Data Scientist

[![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/camille-vanhoffelen/practical-data-scientist/tree/master/) [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/camille-vanhoffelen/practical-data-scientist/master) [![colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/camille-vanhoffelen/practical-data-scientist/)

#### :hugs: Welcome!

This is a **course** which teaches you how to turn **raw data** into **useful insights**. 

This course aims **wide**. In 6 weeks, we will cover all topics required to join a Data Science team. This includes data munging, data exploration, and machine learning, using python frameworks like numpy, pandas, matplotlib, and sklearn. (for a full list check the [syllabus](#syllabus) and the [learning goals](#learning-goals) section).

This course is **lean**. You will learn just enough to analyse datasets from scratch. However Data Science is a vast subject, so additional resources are provided for deeper dives into any of its subfields.

This course is **pragmatic**. All lectures consist of slides explaining key theoretical concepts, followed by a hands-on python notebook with coding exercises.

#### :white_check_mark: What this course will do:

- teach you all the theory and skills required to load, manipulate, and analyse structured and unstructured datasets
- give you hands-on experience training and evaluating Machine Learning models
- make you employable in the Data Science industry
- turn you into a jack of all trades
- guide you to become a master of few
- share some low quality AI memes

#### :x: What this course won't do:

- give you 10 years of experience in ML
- turn you into a Deep Learning wizard
- make you publish a paper at NeurIPS
- build Skynet

#### :thinking: Why this course?

There are excellent online degrees that focus on ML theory, and great practical tutorials that cover frameworks. The Practical Data Scientist blends both in a guided package to bootstrap your Data Science career. This course's mission is to enable all coders to get out there and analyse the world's problems one dataset at a time.

#### :alien: Who is this for?

This course is perfect for the beginner coder looking to start a career in Data Science, the software engineer curious about Machine Learning technologies, or the AI enthusiast searching for more practical experience.

Beginner programming skills are required. A little python experience (_can you define a function?_), and some statistical basics (_what's a standard deviation?_) are recommended. 


#### :teacher: Who teaches this?

Teacher:  [Amric Trudel](https://www.linkedin.com/in/amrictrudel/) has a Science degree from McGill University (Montréal) and studied Computer Science at 42 Paris.
He has been the president of 42 Artificial Intelligence, an association in which he developed training programs on Machine Learning for his fellow students. Amric has also given Machine Learning initiation workshops to large company executives. He now works at OCTO Technology as a Data Science consultant and industrializes data-oriented projects for clients like InVivo, TotalEnergies, and Accenture.



#### :rocket: How should I use this course?

The Practical Data Scientist is taught as a live online course on [Jungle Program](https://www.jungleprogram.com/). Join the next micro-class and find more details [here](https://docs.google.com/presentation/d/1v9VeVmWo3YR_oYEgTYTFNU_MaAA6a7ZO5BeiKCZY9M0/edit?usp=sharing). 

The course content is also open-source and free to use. Here's a few ideas:

- For each lecture, read the slides, then go through the notebooks. Complete the :muscle: and :brain: exercises, then flip through the additional resources.
- Skip straight to a particular section/lecture if you have already taken 50 billion ML courses.
- Forget about the slides, find the notebook for that method you can't remember how to use, and copy paste to your heart's content.
- Test yourself with the assignments. Become the nerdiest Pokemon trainer there ever was.

Notebooks can be viewed in [github](#syllabus), viewed in [nbviewer](https://nbviewer.jupyter.org/github/camille-vanhoffelen/practical-data-scientist/tree/master/), run locally with [jupyter](prepwork/workstation_setup.ipynb), run with [mybinder](https://mybinder.org/v2/gh/camille-vanhoffelen/practical-data-scientist/master), or run with [google colab](https://colab.research.google.com/github/camille-vanhoffelen/practical-data-scientist/blob/master/prepwork/workstation_setup.ipynb).

## Learning Goals

Data scientists can tame all types of data and reveal their secrets. This course takes us through all the python tools needed to turn raw data into useful insights.

- **Data Munging**  
_Students can manipulate and visualise tabular, time series, image, text, and geospatial datasets_
- **Unsupervised Learning**  
_Students can use clustering, dimensionality reduction, and anomaly detection methods_
- **Supervised Learning**  
_Students can train regression and classification models_
- **Evaluation and Optimisation**  
_Students can build accurate Machine Learning models_
- **Exploratory Data Analysis**  
_Students can analyse a public dataset from scratch_

## Syllabus

### Prepwork

* **Workstation Setup**  
[readme](prepwork/workstation_setup.md)
* **Python Code Challenges**  
[notebook](https://colab.research.google.com/github/JungleProgram/practical-data-scientist/blob/main/prepwork/prepwork.ipynb)

### Week 1: Data Munging

The nitty-gritty of data analysis: this chapter teaches you how to load, clean, and manipulate basic datasets in python.

* **1.0 Introduction**  
[slides](https://docs.google.com/presentation/d/1ZeDqgHTtvzDXDud1cXIeZvuHVtbWJ5ZpXBP74rNZw7w/edit?usp=sharing)  
[live recording](https://drive.google.com/file/d/1EHmMaw7qUMpJ6y0c8vwGP23C2VOENE_H/view?usp=sharing)

* **1.1 Numpy & Pandas**  
[slides](https://docs.google.com/presentation/d/1K-0AAYFPMIoNfI9NDJWeG7UpkzJEZSzm368NDmGL4Zc/edit?usp=sharing)  
[notebook](https://github.com/JungleProgram/practical-data-scientist/blob/main/week_1/1.1_introduction_to_numpy_and_pandas/introduction_to_numpy_and_pandas.ipynb)  

* **1.2 Tabular Data Pt.1**  
[notebook](https://github.com/JungleProgram/practical-data-scientist/blob/main/week_1/1.2_tabular_data_pt.1/tabular_data_pt.1.ipynb)
* **1.3 Tabular Data Pt.2**  
[notebook](https://github.com/JungleProgram/practical-data-scientist/blob/main/week_1/1.3_tabular_data_pt.2/tabular_data_pt.2.ipynb)

### Week 2: Data Exploration

Beyond tables: learn how to extract and communicate key insights from time-series, text, and image datasets.

* **2.1 Time Series Data**  
[slides](https://docs.google.com/presentation/d/1hWkfAqrnUd-xbLJ-X2fiw1Hi50zIdDwu23jTpGgsm-8/edit?usp=sharing)  
[notebook](https://github.com/JungleProgram/practical-data-scientist/blob/main/week_2/2.1_time_series_data/time_series_data.ipynb)  
[recording](https://drive.google.com/file/d/1_OJIg_Kwlykh4LsBNklgubqEjmzmx1I0/view?usp=sharing)


* **2.2 Text & Image Data**  
[notebook](https://github.com/JungleProgram/practical-data-scientist/blob/main/week_2/2.2_text_and_image_data/text_and_image_data.ipynb)  
[recording](https://drive.google.com/file/d/1epgJskuqG1TgLCYYGPeUwqZPepsK58lr/view?usp=sharing)
* **2.3 Data Visualization**  
[slides](https://docs.google.com/presentation/d/1X6hphK0Dh4g9PqC62_r2CtV2CrVw46FuWHbY74Q6lb8/edit?usp=sharing)  
[notebook](https://github.com/JungleProgram/practical-data-scientist/blob/main/week_2/2.3_data_visualization/data_visualization.ipynb)

### Week 3: Unsupervised Learning

Analytical power-up: this chapter adds clustering, dimensionality reduction, and anomaly detection to your data analysis techniques.

* **3.1 Clustering**  
[slides](https://docs.google.com/presentation/d/1hiEjLtkuJK7stT3c-zz4URglGq2oicUX4jFy4cAoo6A/edit?usp=sharing)  
[notebook](https://github.com/JungleProgram/practical-data-scientist/blob/main/week_3/3.1_clustering/clustering.ipynb)  
[recording](https://drive.google.com/file/d/1xAXUyenFvAHGc1GjZKz_NtUpovhq4y04/view?usp=sharing)
* **3.2 Dimensionality Reduction**  
[slides](https://docs.google.com/presentation/d/1bUYH-sEtiyzh7u42uWjQ3tN91V7XQjU4MehDElK4qjw/edit?usp=sharing)  
[notebook](https://github.com/JungleProgram/practical-data-scientist/blob/main/week_3/3.2_dimensionality_reduction/dimensionality_reduction.ipynb)  
[recording](https://drive.google.com/file/d/1qEOxn5IW9t5O9jI1zrpVj_V9fsIVU8la/view?usp=sharing)
* **3.3 Anomaly Detection**  
[slides](https://docs.google.com/presentation/d/1DOyIOlv498eHWP3IDOcMjYdEfgE4ijEGiRLA0KFfG_U/edit?usp=sharing)  
[notebook](https://github.com/JungleProgram/practical-data-scientist/blob/main/week_3/3.3_anomaly_detection/anomaly_detection.ipynb)  


### Week 4: Supervised Learning

Moving past data summaries: this chapter introduces predictive models to solve fundamental machine learning tasks.

* **4.1 Supervised Learning Fundamentals**  
[slides](https://docs.google.com/presentation/d/1uVzlM1TFxKz3jL9JGgEK5m1iuGSrkaY8Bqonc0vxyp0/edit?usp=sharing)
* **4.2 Linear Regression**  
[slides](https://docs.google.com/presentation/d/1HeZf2mNvNrJJqRRjXrMDojmBIVt_wxwI9FPsppzuzZE/edit?usp=sharing)  
[notebook](https://github.com/JungleProgram/practical-data-scientist/blob/main/week_4/4.2_linear_regression/linear_regression.ipynb) 
* **4.3 Logistic Regression**  
[slides](https://docs.google.com/presentation/d/1AE4DBdISt4XrQLhzxS5sqFR-gUYXT8ibMBhIBdgPPeE/edit?usp=sharing)  
[notebook](https://github.com/JungleProgram/practical-data-scientist/blob/main/week_4/4.3_logistic_regression/logistic_regression.ipynb) 

### Week 5: Advanced Supervised Learning  

Taming the beast: this chapter shows how to build accurate and effective machine learning models.

* **5.1 Learning Better Pt.1**  
[slides](https://docs.google.com/presentation/d/1LApkaDeoi6wYkVkVjVOSeBLmhlpMo-JhD-lC4J7sn60/edit?usp=sharing)  
[notebook](https://github.com/JungleProgram/practical-data-scientist/blob/main/week_5/5.1_learning_better_pt.1/learning_better_pt.1.ipynb) 
* **5.2 Learning Better Pt.2**  
[slides](https://docs.google.com/presentation/d/1a2q6zyDf__EkNORbK5pnOE7QGr0tIcMWv6mj56P5AS4/edit?usp=sharing)  
[notebook](https://github.com/JungleProgram/practical-data-scientist/blob/main/week_5/5.2_learning_better_pt.2/learning_better_pt.2.ipynb) 
* **5.3 Evaluation Fundamentals**  
[slides](https://docs.google.com/presentation/d/1N3oxyXCTlsr5GezsumPm1Wq6OkNWl1bUQ88jmnd2Jsk/edit?usp=sharing)  
[notebook](https://github.com/JungleProgram/practical-data-scientist/blob/main/week_5/5.3_evaluation/evaluation.ipynb) 

### Week 6: Non-Linear Models

* **6.1 Support Vector Machines**  
[slides](https://docs.google.com/presentation/d/1bnPhxKKIJCxiMNzFI8EIFiJDDGGubHrKMTpfyFZqtSs/edit?usp=sharing)  
[notebook](https://github.com/JungleProgram/practical-data-scientist/blob/main/week_6/6.1_support_vector_machines/support_vector_machines.ipynb)  

* **6.2 Naive Bayes & Decision Trees**  
[slides](https://docs.google.com/presentation/d/1LsNXco6J8UW7-BB5GSGWeMg-BRbps8YZ7zmPZ4sA1LQ/edit?usp=sharing)  
[notebook](https://github.com/JungleProgram/practical-data-scientist/tree/main/week_6/6.2_naive_bayes_decision_trees) 

* **6.3 Ensemble Methods**  
[slides](https://docs.google.com/presentation/d/1T42nruSeWx_J-FrYaskhaN_nq3CrX2wPCmWV02kM4cs/edit?usp=sharing)  
[notebook](https://github.com/JungleProgram/practical-data-scientist/blob/main/week_6/6.3_ensemble_methods/ensemble_methods.ipynb) 

### Week 7: Final Project

This chapter tests your skills on a public dataset by completing an exploratory data analysis report, and training at least one Machine Learning model.

### Assignments

* [Week 1](https://github.com/JungleProgram/practical-data-scientist/tree/main/homework/week1)
* [Week 2](https://github.com/JungleProgram/practical-data-scientist/tree/main/homework/week2)
* [Week 3](https://github.com/JungleProgram/practical-data-scientist/tree/main/homework/week3)
* [Week 5](https://github.com/JungleProgram/practical-data-scientist/tree/main/homework/week5)
* [Final Project](https://github.com/JungleProgram/practical-data-scientist/tree/main/homework/final_project)
* [Final Presentation](https://github.com/JungleProgram/practical-data-scientist/tree/main/homework/final_project#presentation)


## Assignments

The coursework is split between five small assignments, a final project, and a final presentation.

The **small assignments** serve to synthesise the previous course content on your own, and put it to practice. They are all coding exercises: you will be given resources and/or code stubs, and will submit runnable code and some observations.

The **final project** tests everything that you have learnt from this course. This is a python notebook report like those data scientists make to share their experimental progress. It tests your ability to design, carry out, and communicate machine learning experiments. This is complemented by the **final presentation**, a 10mn talk to synthesize, and discuss the results.

## License
<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/80x15.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.
See the [LICENSE.txt](LICENSE.txt) file for details.

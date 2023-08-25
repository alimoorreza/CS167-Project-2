# CS 167 Project 2: 
Text classification with SVMs, PCA, Perceptrons, MLPs, and RNNs

## Learning Objectives: 📝
For this project, you will use the scikit-learn library to conduct a machine learning experiment, and your write-up will ask you to explain what you did and interpret the results. This directly addresses two of the course learning objectives stated in the syllabus:
- Students will be able to create software which utilizes machine learning programming libraries in order to conduct machine-learning-based data analysis.
- Students will be able to develop and conduct machine-learning-based data analysis experiments, and they will be able to interpret and explain the results.

## Project Description: 🎥 🍿
For this project, we will be using the International Movie Database (IMDB)'s dataset for text classification. This dataset can be found at: http://ai.stanford.edu/~amaas/data/sentiment/, but it also available via Tensorflow's Datasets. I will provide code that shows you how to download the dataset using Tensorflow. You will be using the text from movie reviews to predict what the sentiment of the movie review was--if it was a positive review [1] or a negative review [0]. 

## Project Expectations: ☑️
**New**: At the very top of your notebook, I'm asking that in a text cell, you **describe how many points you attempted to get from this project**. Tell me what you think you deserve on this notebook given the rubric at the bottom of this page. 

You will create a Colab notebook that includes your code and results to document your experiment. Most importantly, you will use text cells in the notebook to explain what you did, interpret the results, and make your recommendations. The written markdown protions must include the following things:
1. **Problem** [1 point]: State the problem you are trying to solve with this machine learning experiment. Include a description of the data, and what you're trying to predict. What are the possible uses for this kind of machine learning model?
2. **Explore the Data** [5 points]: Find the values for the following metrics: 
    - __Number of Samples__: total number of examples you have in the data 
    - __Number of classes__: total number of topics or categories in the data
    - __Number of words per sample__: Median number of words in one sample
    - __Distribution of sample length__: Distribution showing the number of words per sample in the dataset (use the function `hist()` on a list that has the lenght of each row). 
    - __Something Else__: Show me something else about the data--your choice.
3.  **Data Preparation** [1 point]: Explain your data preparation. What did you have to do to get your data in shape for your experiments - word embeddings, stop words, vectorization, tokeniztion, etc. 
4.  **Metrics** [1 point]: What metrics will you use to evaluate your model? Why are these metrics the best for your model? (Hint, this should be more than 'accuracy').
5.  **Model Planning and Execution** [1 point]: Identify which learning algorithms you will try and which important parameters you will tune for each one. 
6.  **Bumps in the Road** [1 point]: What challenges did you encounter? How did you overcome these challenges? Did you have to adapt your strategy to account for these challenges? Why or why not?
7.  **Results** [1 point]: After you conduct your learning experiment, summarize the results you got. Include visualizations as appropriate. 
8.  **Conclusions**: What insights/recommendations do you have? What did you find that was interesting? Which model was your best model, which models didn't work well? Why do you think this is? In general, I want a discussion of your experiment, the results, and what they mean.

### Your Experiments Should Demonstrate the following Machine Leanring Techniques:
From Scikit-Learn:
- **Support Vector Classifer**
- **Principal Component Analysis**
- **Perceptron**
- **MLP**

📉 📊 📈 💹 You also should include at least **4 visualizations (graphs)** of tuning parameters.

## Extra Credit ✨
As promised, you will have an opportunity to earn extra credit on this project. You will be able to earn up to 2 points of extra credit by using the IMDB database to build a **word-level** language model that is able to generate text (much like we did in [Day 23's Notes](https://github.com/merriekay/CS167Code/blob/main/Day23Notes_RNNs4NLP.ipynb). Build your model, train it, evaluate it, and then demonstrate that you are able to use it to generate new movie reviews. 

# Rubric and Grading
Project #2 will be graded using the following rubric. I strongly suggest evaluating your project using this rubric before turning it in.

| **Description/Writing**  |**I think I deserve:**   |**Actual Grade**|**Notes** |
| :------------------------------- | -------: | ----: |:---- |
| 1: Problem                       |        /1|       /1|    |
| 2: Explore the Data              |        /5|       /5|    | 
| 3: Data Prep                     |        /1|       /1|    |
| 4: Metrics                       |        /1|       /1|    | 
| 5: Model Planning and Execution  |        /1|       /1|    |
| 6: Bumps in the Road.            |        /1|       /1|    |
| 7: Results                       |        /1|       /1|    | 
| 8: Discussion/Conclusion.        |        /1|       /1|    |
| <b>Total                         |       /12 |     /12 </b>   |

| **Code**  |**I think I deserve:**   |**Actual Grade**   |**Notes** |
| :------------------------------- | -------: |-------: | :---- |
| 1: SVC                           |        /1|        /1|   |
| 2: PCA                           |        /1|        /1|   | 
| 3: Perceptron                    |        /1|        /1|   |
| 4: Multilayer Perceptron         |        /1|        /1|   | 
| 5: 4 Visualizations              |        /4|        /4|   | 
| <b>Total                         |       /8 |        /8|</b>   |

| **Extra Credit**  |**I think I deserve:**   |**Actual Grade**   |**Notes** |
| :------------------------------- | -------: | ----: |:---- |
| Word-Level Language Model             |        /1|       /1|   |
| Examples of Generated Movie Reveiw    |        /1|       /1|   |


| **Written Portion** 📝 | **Code Portion** 🖥️ | **Extra Credit** ✨  |**Total** ➕ |**Notes** 🗒️|
| ---------: | -------------------: | ------------: |-------------: |---------- |
|       /12  |                  /8 |           /0 |         /20|           |


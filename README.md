## Machine Learning Fundamentals

Welcome to the Machine Learning Fundamentals repository! This collection of Jupyter notebooks serves as a comprehensive resource for practicing and learning essential machine learning concepts. This repository covers a variety of algorithms and theories related to statistics and calculus in the context of machine learning.

### Contents

The repository covers a range of machine learning concepts, including but not limited to:

+ [Empirical Rule](JupyterNotebooks/EmpericalRule.ipynb): Exploring statistical concepts through the empirical rule.
+ [Correlation Coefficient](JupyterNotebooks/CoorelationCoefficient.ipynb): Analyzing relationships between variables using correlation coefficients.
+ [KNN (K-Nearest Neighbors)](JupyterNotebooks/KNearestNeighbor.ipynb): Implementing and understanding the KNN algorithm for classification and regression tasks.
+ [Naive Bayes](JupyterNotebooks/NaiveBayes.ipynb): Explore the basics of Naive Bayes classification.
+ [Logistic Regression](JupyterNotebooks/LogisiticRegression.ipynb): Learn the logistic regression model and its applications.
+ [SVM (Support Vector Machines)](JupyterNotebooks/SupportVectorMachine.ipynb): Gain insights into Support Vector Machines for classification.
+ [Neural Networks with Tensorflow](JupyterNotebooks/NeuralNetworks.ipynb): Dive into the world of neural networks using Tensorflow.

### Data Source

+ To enhance your learning experience, this repository incorporates datasets collected from the [Ontario-RealEstate-DataPipeline](https://github.com/kunalmehta14/Ontario-RealEstate-DataPipeline.git) project. This parallel project is a multi-structured web scraper designed for extracting real estate listings and related data influencing the real estate market. The datasets are obtained through SQL queries and are exported as CSV files.
+ You can find the SQL queries and associated CSV files used for analysis in the respective Jupyter notebooks.

### Data Analysis and Jupyter Notebooks Structure

Each Jupyter notebook in this repository is dedicated to a specific machine learning concept. It provides a comprehensive exploration of the theory behind the concept along with practical examples.

### Docker Compose Configuration

To easily set up the testing/development environment, a Docker Compose setup is provided, which includes the following:

+ The latest TensorFlow image
+ CUDA toolkit and cuDNN libraries to access the GPU for training ML models
+ Other data science-related libraries such as NumPy, pandas, Matplotlib, scikit-learn, etc.
+ Jupyter Notebook server to edit and manage the ML notebooks.

Note: Jupyter Notebook requires setting up a token to access the server over port 9090. To update the token, use the "environment.env.template" file. Add a custom token to it and save the file as "environment.env" at the same level of the directory as the Docker Compose file.

### Contributions and Community

I've maintained this repository as a personal documentation of my machine learning journey, and I'm excited to share it with the community. If you find areas for improvement, have suggestions, or want to contribute, please feel free to open issues or pull requests.

Note: Some notebooks are configured to fetch data directly from a MySQL database; efforts are underway to update them for CSV-based data retrieval. In the meantime, the CSV files associated with these queries are available in the [csv-files](csv-files/) directory.
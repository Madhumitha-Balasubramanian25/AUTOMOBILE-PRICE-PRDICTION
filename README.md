# AUTOMOBILE-PRICE-PRDICTION
MACHINE LEARNING PROJECT

In this experiment, there are three main stages such as create the model, train the model, and score and test the model. Creating the model includes another three sub-activities such as Get the data, Prepare the data, and Define features. Train the model includes, choose and apply an algorithm. Score and test the model includes, predict new automobile prices.

Get the data:

The first thing we need in machine learning is data. We'll use the sample dataset, Automobile price data (Raw), that's included in your workspace. This dataset includes entries for various individual automobiles, including information such as make, model, technical specifications, and price. Prepare the data: A dataset usually requires some preprocessing before it can be analyzed. You might have noticed the missing values present in the columns of various rows. These missing values need to be cleaned so the model can analyze the data correctly. We'll remove any rows that have missing values. Also, the normalized-losses column has a large proportion of missing values, so we'll exclude that column from the model altogether. First, we’ll add a module that removes the normalized-losses column completely. Then we can add another module that removes any row that has missing data. Define features: In machine learning, features are individual measurable properties of something you’re interested in. In our dataset, each row represents one automobile, and each column is a feature of that automobile. Let's build a model that uses a subset of the features in our dataset. You can come back later and select different features, run the experiment again, and see if you get better results.

Choose and apply an algorithm: Now that the data is ready, constructing a predictive model consists of training and testing. We'll use our data to train the model, and then we'll test the model to see how closely it's able to predict prices. Because we want to predict price, which is a number, we'll use a regression algorithm. For this example, we'll use a linear regression model.

Using the visualize option in the score model we can predict new automobile prices.

https://madhumithab338.medium.com/machine-learning-project-72b3bbbead3a

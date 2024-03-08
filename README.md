# PROPOSAL-FIX
Title (example): Predict the age of abalone from physical measurements

Introduction:

- Provide some relevant background information on the topic so that someone unfamiliar with it will be prepared to understand the rest of your proposal
- Clearly state the question you will try to answer with your project
- How accurately can we predict the age of an abalone from the entire weight and diameter of the shell?
- Identify and describe the dataset that will be used to answer the question

Preliminary exploratory data analysis:
- Demonstrate that the dataset can be read from the web into R
- Clean and wrangle your data into a tidy format
- Using only training data, summarize the data in at least one table (this is exploratory data analysis). An example of a useful table could be one that reports the number of observations in each class, the means of the predictor variables you plan to use in your analysis and how many rows have missing data.
- Using only training data, visualize the data with at least one plot relevant to the analysis you plan to do (this is exploratory data analysis). An example of a useful visualization could be one that compares the distributions of each of the predictor variables you plan to use in your analysis.

Methods:
- Explain how you will conduct either your data analysis and which variables/columns you will use. Note - you do not need to use all variables/columns that exist in the raw data set. In fact, that's often not a good idea. For each variable think: is this a useful variable for prediction?
- Describe at least one way that you will visualize the results

Expected outcomes and significance (putri):
- What do you expect to find?

  Predictive models that can accurately estimate the age of abalone based on the physical measurements such as diameter, weight, and rings.
- What impact could such findings have?
1. Time efficiency and cost reduction.
    The traditional process of determining abalone age such as cutting the shell, and manually counting the number of rings under microscope involves costs associated with equipment, labor, and time. By contrast, if age can be reliably predicted using physical measurements and predictive models, it would save a significant amount of time and the overall cost of age determination can be significantly reduced.
     
2. Non-destructive testing.
  Cutting the shell could damages the specimen, and it may not be feasible to sacrifice abalones for age determination especially in conservation efforts where preserving the population is crucial. Thus, by using physical measurements, it allows
researchers to gather age data without harming the abalones.
   
3. Enhance conservation efforts.
   With a more efficient method for age determination, researchers and fisheries can monitor abalone populations more frequently in order to get better understanding of population dynamics, growth rates, and age structure, which are essential for more sustainable fisheries and conservation efforts.
   
- What future questions could this lead to?
  Additional factors beyond physical measurements, such as environmental variables like water temperature, pH levels, or food availability, might be added to improve the accuracy of age prediction models.

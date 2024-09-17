# ECE2112-PA-4
- Robie Galang
- September 17, 2024
- Experiment 4: Data Wrangling and Data Visualization Submission

# Libraries Used:
- pandas - For data manipulation
- matplotlib.pyplot - For plots
- seaborn - For advance visualization

# Problem 1
## Task:
- Load the given dataset
- Construct two data frames which are: Instru and Mindy
    - Contains student from Luzon with Instrumentation track and a score greater than 70 in Electronics (Instru).
    - Contains female students only from Mindanao that has an average score equal or greater than 55 (Mindy).
 
## Approach:
- I just applied the appropriate conditions to filter the data that is required under the specific data frame.
- In creating the Instru data frame, I just filtered the students enrolled in instrumentation track and excluded those with an electronic scores lower than 70. This is done by applying logic. Same is done with the Mindy data frame

## Challenges:
- I wasn't able to run the code first properly as after executing the cells again, I ran into a problem. The Mindy data frame seems to be causing an error when loading it. It was resolved by making a copy of the filtered data frame by using .copy().

# Problem 2:
- Visualize how features such as track, gender, and hometown contribute to the average score in a plot.

# Approach:
- First, I calculate the average score for all the students across Math, GEAS, and Electronics using df.mean(axis=1)
- then I used boxplot as my visualization.

#Learnings
- I learned how to efficiently wrangle data using pandas by applying conditions and filtering
- I also used how to visualize relationships

#Versions:
- 1.0 - Initial release

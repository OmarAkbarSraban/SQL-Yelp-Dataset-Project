# SQL-Yelp-Dataset-Project

This repository contains the work completed for the Coursera Peer-graded Assignment on profiling and analyzing the Yelp dataset. It includes data profiling, exploration, and deeper analyses to draw insights. All SQL queries, results, and detailed explanations are provided to ensure reproducibility and understanding.

## Table of Contents

1. [Course Information](#course-information)
2. [Assignment Description](#assignment-description)
3. [Files in the Repository](#files-in-the-repository)
4. [Part 1: Yelp Dataset Profiling and Understanding](#part-1-yelp-dataset-profiling-and-understanding)
5. [Part 2: Inferences and Analysis](#part-2-inferences-and-analysis)
6. [Usage](#usage)
7. [Conclusion](#conclusion)
8. [Author](#author)

## Course Information

This project is part of the Coursera course [SQL for Data Science](https://www.coursera.org/learn/sql-for-data-science) offered by the University of California, UC Davis. The course is instructed by Sadie St. Lawrence.

## Assignment Description

This assignment is divided into two parts:

1. **Yelp Dataset Profiling and Understanding**: This part involves answering a series of questions to profile and understand the Yelp dataset. The focus is on the correctness of the findings and the readability of the code used to derive the answers.
   
2. **Inferences and Analysis**: In this part, I formulated my own research questions to analyze the dataset. This includes preparing the data and using SQL queries to extract meaningful insights.

## Files in the Repository

- `README.md`: This readme file.
- `Assignment_Instructions.txt`: Detailed instructions for the assignment.
- `Part1_Yelp_Dataset_Profiling_and_Understanding.sql`: SQL queries and answers for Part 1.
- `Part2_Inferences_and_Analysis.sql`: SQL queries and answers for Part 2.
- `Completed_Solution.pdf`: A PDF file containing the completed assignment with all SQL queries and results.
- `Dataset/`: A directory containing the necessary dataset files (if applicable).

## Part 1: Yelp Dataset Profiling and Understanding

In Part 1, the following tasks were performed:

1. **Profiling the data**: Finding the total number of records for each table in the dataset.
2. **Finding distinct records**: Identifying the total distinct records by either the foreign key or primary key for each table.
3. **Checking for null values**: Determining if there are any columns with null values in the Users table.
4. **Statistical analysis**: Displaying the minimum, maximum, and average values for specific columns across various tables.
5. **City review analysis**: Listing cities with the most reviews in descending order.
6. **Star rating distribution**: Finding the distribution of star ratings for businesses in specific cities.
7. **Top users analysis**: Identifying the top 3 users based on their total number of reviews.
8. **Correlation analysis**: Examining if posting more reviews correlates with having more fans.
9. **Sentiment analysis**: Comparing the number of reviews containing the words "love" and "hate".
10. **Top fans**: Listing the top 10 users with the most fans.

## Part 2: Inferences and Analysis

In Part 2, I chose to analyze businesses in Las Vegas under the "Shopping" category. The analysis included:

1. **Distribution of hours**: Comparing the distribution of hours for businesses with different star ratings.
2. **Number of reviews**: Analyzing the number of reviews for businesses with different star ratings.
3. **Location analysis**: Inferring insights from the location data provided for the businesses.
4. **Open vs. closed businesses**: Identifying differences between businesses that are still open and those that are closed.

### Analysis Type Chosen

I conducted an analysis to identify which category of businesses has the highest average reviews and star ratings, considering the operational status of these businesses. I filtered for categories with more than 10 businesses for statistical significance.

### Data Required

I used data on business categories, star ratings, review counts, and business operational status. This data was essential to understand trends and patterns in customer reviews and business performance based on their operational status.

## Usage

1. **Clone the repository**:
    ```sh
    git clone https://github.com/OmarAkbarSraban/SQL-Yelp-Dataset-Project.git
    cd SQL-Yelp-Dataset-Project
    ```

2. **View the SQL files**:
    - Open `Part1_Yelp_Dataset_Profiling_and_Understanding.sql` to see the SQL queries and results for Part 1.
    - Open `Part2_Inferences_and_Analysis.sql` to see the SQL queries and results for Part 2.

3. **View the completed solution**:
    - Open `Completed_Solution.pdf` to see the combined results of the assignment.

## Conclusion

This assignment provided valuable experience in profiling and analyzing a real-world dataset using SQL. The insights derived from the Yelp dataset can help understand business performance, customer sentiments, and operational efficiencies.

## Author

**Omar Akbar Sraban**  
[LinkedIn](https://linkedin.com/in/omarakbar1)  

Feel free to reach out if you have any questions or feedback!

---


# pandas-challenge
This is the challenge assignment for Unit 4. I am submitting this README for the New Attempt on April 11, 2024: 

## PyCity Schools Analysis: 
Summary: 
The dataset, school_data_complete, is a left join between the student_data .csv file and school_data .csv file (implying that all the data contained in the student_data dataset are included in the school_data_complete df; and that the school_data rows could be dropped if there were any null values, although the actual dataset provided for school_data did not have any null values). The school_name column is used as the primary key to join these datasets. The Challenge assignment utilizes all columns of both datasets, except the "gender" column from the student_data dataset. 

Of the 15 schools with 39,170 students, the average math and  reading scores were 78.99 and 81.88 respectively, with passing rates of 74.98 and 85.81, respectively. 

Further, the math and reading scores' metric by school type, the average math and reading scores for Charter schools are higher at 83.47 and 83.90 respectively (v/s 76.96 and 80.97 respectively for District schools).  In terms of the passing rates, Charter schools are much higher at 93.62%, 96.59%, and 90.43% for Math, Reading, and Overall (i.e. both Math and Reading) respectively (v/s 66.55%, 80.80%, and 53.67% respectively for District Schools). 

Based on the Overall passing rate metric, the Top 5 Highest-Performing Schools are all Charter schools (Cabrera H.S., Thomas H.S., Griffin H.S., Wilson H.S., Pena H.S.) and the Bottom 5 schools are all District (Rodriguez H.S., Figueroa H. S., Huang H.S., Johnson H.S.). 

The Per Student Budget ranged between $582.00 - $638 for the Top 5, and $637 - $655 for the Bottom 5 schools. 

While both the math and reading scores over the grades 9 - 12 for the Top 5 schools were in the range of 83-84, for the Bottom 5 schools the math scores were in the 76-78 range and the reading scores were in 80-81. 

Conclusion: 
The above findings indicate that the high-performing schools, especially the Charter schools with high overall passing rates, were performing consistently above the mean for the PyCity schools (math score: 78.99; reading score 81.88). 

Per Student Budget does not seem to be correlated to schools' performance, given that the range is between $582.00 - $638 for the Top 5, and $637 - $655 for the Bottom 5 schools.  Interestingly, for the entire population of the PyCity schools, the Spending Ranges (Per Student) and the % Overall Passing rates are inversely proportional.  

Size of the schools may be strongly correlated in the schools' performance.  While the scores (in the range of 83-84 for both math and reading) and passing rates (math: 93-94; reading: 96-97; overall: 89-91) for Small and Medium size schools are comparable, the same for Large schools are relatively much lower. 


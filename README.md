# (Ford GoBike System Data Exploration)
## by (Takalani Mbooi)


## Dataset

> Dataset for this project includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area. Rows with missing values on variables of member_birth_year and member_gender were dropped from a dataset.


## Summary of Findings

> There is a long tail in the distribution of duration spent on bikes, I then used a log scale. Duration_sec has a long-tailed distribution, with a lot of seconds on the low duration end (less than 10 000 sec), and few on the high duration end. When plotted on a log-scale, the duration_sec distribution was skewed to the right, with a peak around 500 seconds.Most of the participants were born in 1988, followed by those who were born in 1993, the age group between 1986 and 1995 is the dominant group,the counts decreases as we move left and right from the dominant group. In all gender types there are more subscribers than customers. The dominant gender is male.People who rented bikes more were born in the year 1988. There were more males who hired bikes than combined females and other gender. Looking at the point plot for people who were born before 1965, their mean duration for different genders varies by a big gap, and for the male, female and other gender who were born after 1965 their mean duration were similar and they had few outliers.


## Key Insights for Presentation

> Distribution of the main variable of interest: duration_sec.
> Counts of the participants per birth year.
> Looking at the durations of user type and member gender.
> Relationships between three categorical features (user_type, member_gender, and member_birth_year).
> Relationship between bike share for all trip, member gender, and member birth year.
> Relationship between user_type and member gender to the duration.
> Relationship between member birth year, member gender, and the duration.
> Correlation between user_type, member_gether, member_birth_year to the duration.
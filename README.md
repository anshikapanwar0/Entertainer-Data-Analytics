# Entertainer-Data-Analytics

1. Gender Distribution Visualization:

Calculates and visualizes the distribution of entertainers by gender (Gender (traditional) column) using a bar plot (sns.barplot).
Adjusts plot parameters such as title, axis labels, rotation of x-axis labels, tight layout, and grid lines for clarity.
Provides an overview of how many entertainers fall into each gender category based on traditional classifications.

2. Birth Decade Distribution Visualization:

Computes the birth decade for each entertainer using integer division (// 10) and multiplies by 10 to round down to the nearest decade.
Counts and plots the distribution of entertainers by birth decade using another bar plot (sns.barplot).
Sets appropriate plot parameters including title, axis labels, rotation of x-axis labels, tight layout, and grid lines to enhance readability.
Offers insights into the birth period distribution among entertainers, revealing patterns across different decades.

3. Nomination Distribution Visualization:

Calculates and visualizes the distribution of nominations or #1 hits across different years using a bar plot (sns.barplot).
Sets plot parameters including title, x-axis label ('Year of Nominations'), y-axis label ('Total Nominations'), rotation of x-axis labels for better readability, tight layout, and grid lines.

4. Oscar/Grammy/Emmy Distribution Visualization:

Computes and visualizes the distribution of first Oscars/Grammys/Emmys received across different years using another bar plot (sns.barplot).
Sets plot parameters including title, x-axis label ('Year of Oscar/Grammy/Emmy'), y-axis label ('Total Oscar/Grammy/Emmy'), rotation of x-axis labels, tight layout, and grid lines.

5. Entertainers with their years from first nomination to first award
6. Yearly Gender-Award Distribution

Convert 'Year of First Oscar/Grammy/Emmy' to numeric values and drop rows where this column or 'Gender (traditional)' is missing (merged_df.dropna(subset=['Year of First Oscar/Grammy/Emmy', 'Gender (traditional)'])).

7. Overall Gender-Awards Distribution
8. Entertainers with same last major work year and death year
9. Entertainer's age
10. Entertainer's age at First Award
    

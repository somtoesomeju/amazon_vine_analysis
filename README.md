## Amazon_Vine_Analysis

# Overview
The purpose of this project is to explore the use of "big data" using AWS. In this analysis I am using PySpark to connect to PgAdmin. This will allow me to perfom an ETL (extract, transform, load) process with the data and allow it to be stored as a dataframe. Using the data, i am creating an analysis for reviews which will be presented to stakeholders.

# Resources
- Software: PgAdmin 4 Version 5.2, Google collab, Amazon Web Services.
- Languages: Python, SQL

# Results
-  How many Vine Reviews are there? 
There are 8390 total reviews from the data.

- How many non-vine (unpaid) reviews are there?
There are 8343 non-vine reviews.

- How many vine reviews were 5 stars?
15 vine users left 5 star reviews.

- How many non-vine reviews were 5-stars?
There are 4025 reviews from unpaid users

- What percentage of vine reviews were 5-stars?
out of all the vine reviews, 31.92% of the reviews were 5 stars.

- What percent of unpaid reviews were 5-stars?
Out of all the unpaid reviews, 48.244% of the reviews were 5-stars.

# Summary
From my analysis, it doesn't look like there is any bias with the reviews. It is possible that the paid viewers may be a bit more critical since they're paying for the service hence the lower percentage of 5-star reviews. However, the results do not highlight any favouritism towards unpaid reviewers. It is likely just a coincidence.




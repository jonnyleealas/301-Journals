# Jonathon Lee 
# Class 301
# Read 14


# DB Normalization
A process used to organize a database into tables and columns. 
- Limit a table to one purpose helps reduces the number of duplicate data. 
- Helps minimize issues.
- Minimizes modification issues.
- Simplifies queries.
- Tables should have one purpose. Many purposes decreases performance and are difficult to maintain. 
- Use multiple related tables to minimize redundancy.
- We need to reduce repetition of similar data to avoid insertion, deletion, and update issues.
#
Redundancy increases the amount of storage we are using. We can avoid this by avoided the storage of similar data in one table database.
In simpler words, we need to avoid repeating data. Normalization is a way of organizing things.
#
An example of this is having one table for student names and another table for branch. Student table will save student data and the branch will hold the branch data for the student. It's a bit more organized as well and also easier to read. We can connect both tables by adding the branch name into the student table. When the student data is updated the branch will also be updated because it is linked to the student table. This reminds me of smaccs in css.


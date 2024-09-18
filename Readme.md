# MongoDB Aggregation Pipeline Notes and Code


## For Data Used In Tutorial

# [GitHub : dpvasani](https://gist.github.com/dpvasani/0da00b191014dbcee6b077cc9af54b3c)

---

This repository contains comprehensive notes and code examples for MongoDB aggregation pipeline operations. The code files provide examples of how to utilize various stages and operators to handle complex data queries and transformations in MongoDB.

---

### **Files Included:**
- **Q1.json**: Filters active users and counts them.
- **Q2.json**: Groups by gender and calculates the average age.
- **Q3.json**: Groups by favorite fruit, counts occurrences, sorts by count, and limits results to top two.
- **Q4.json**: Groups by gender and counts the number of users per gender.
- **Q5.json**: Groups by country and counts users, sorts by user count, and limits to the top two countries.
- **Q6.json**: Filters active users.
- **Q7.json**: Unwinds `tags`, counts tags per user, calculates the average number of tags.
- **Q8.json**: Filters users with the tag "enim" and counts them.
- **Q9.json**: Filters inactive users with the tag "velit", projects their name and age.
- **Q10.json**: Filters users whose phone number matches a specific pattern and counts them.
- **Q11.json**: Sorts by registration date, limits to 10 users, and projects name, registration date, and favorite fruit.
- **Q12.json**: Groups users by favorite fruit and collects their names.
- **Q13.json**: Filters users where the second tag is "ad" and counts them.
- **Q14.json**: Matches users who have both "enim" and "id" tags.
- **Q15.json**: Groups users by company title and counts the number of users in the USA.
- **Q16.json**: Uses `$lookup` to join `authors` collection and adds the author's details to each document.

---

### **Questions:**
- How to filter active users and count them?
- How to group by gender and calculate average age?
- How to group by favorite fruit, sort, and limit the results?
- How to count the number of users by gender?
- How to group by country and limit the results?
- How to unwind an array and calculate the average number of elements?
- How to filter users with a specific tag and count them?
- How to filter inactive users and project specific fields?
- How to filter users with a specific phone number pattern?
- How to sort by registration date and limit the results?
- How to group users by favorite fruit and push names into an array?
- How to filter users by a specific element in an array?
- How to match users based on multiple tags?
- How to perform a lookup and join collections?

---
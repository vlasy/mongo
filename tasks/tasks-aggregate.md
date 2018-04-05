authors
- for each age, make an overview of average, minimum, maximum, and total salary. Work only with age groups that have more than 1 person. Show salary info (omit _id, age and everything else) of group with highest average salary

- client requests a new feature (again). To support it in database, use aggregation pipeline to create a new collection where each phone type present in `authors` collection will be one document. It will have the phone type as its id, and will contain the list of people (names are OK) which have that phone type

posts
- create an aggregation query, which will output a list of tags and each of the tags will have an embedded array with 5 most popular articles that contain that tag

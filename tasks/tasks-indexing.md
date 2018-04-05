posts
- create index on a field `expiresAt`, that ensures that documents will be deleted at the time specified in that field
- create an index for searching in titles of the most popular posts (more than 900 author views)

movieDetails
- make sure that no two movies have the same poster
- think about: I want to insert a document which has a duplicit poster with document already in database. What are the changes I can do, so that I could insert the new document?

- design queries for:
    - listing all movies from year 2014
    - listing all movies from year 2014 with imdb rating better than 8
    - listing all comedies from year 2014 and sort them by imdb rating from best to worst
    - listing all movies and sorting them from oldest to newest and then from best to worst (according to imdb.rating)
    - listing all comedies from year 2014 with imdb rating better than 8
- now create indexes so that each of these queries use at least one of them
- what is the smallest number of indexes you have to create?


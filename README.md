Indonesian Union Catalogue is an initiative to build a national repository providing standardized bibliographic and authority records. 

models:

- bibliographic
  - entry_date
  - title
  - author_name --> foreign key to author table
  - authorship_type --> choices : single author, collaborative, compilation, others
  - publisher --> foreign key to publisher table
  - publishing_date
  - pages
  - size --> height, width
  - bibliography
  - index
  - genre
  - xxx
 
 - author
  - name
  - category --> personal, corporate, event
  - gender
  - date_birth
  - major
  - affiliation
  - address
  - xxx
  
 - publisher
  - name
  - category --> commercial, government, NGO, personal
  - address
  - xxx

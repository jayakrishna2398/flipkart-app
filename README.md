# flipkart-app

## Tables

### Table 1: books_names
| sno | Name | Price | category | Rating | created date |
| -- | -- | -- | -- | -- | -- |
| 1 | java | 450 | Technical based | 5 | 20/01/19 |
| 2 | c++ | 500 | Technical based | 4 | 16/06/16 |
| 3 | c | 300 | Technical based | 3 | 25/02/18 |
#### List All Books

`
select * from books_names;
`

#### List all books_names - order by asc

`
select * from books_names order by asc;
`

#### List all books_names - order by desc

`
select*from books_names order by desc;
`

#### List all books_names - where range between 

`
select * from books_names where range between 300 and 450;
`

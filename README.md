# flipkart-app

## Tables

### Table 1: books_names
| sno | Name | Price | category | Rating | created date |
| -- | -- | -- | -- | -- | -- |
| 1 | java | 450 | Technical based | 5 | 20/01/19 |
| 2 | c++ | 500 | Technical based | 4 | 16/06/16 |
| 3 | c | 300 | Technical based | 3 | 25/02/18 |
###  Feature 1: List All Books

`
select * from books_names;
`

#### Feature 2: List all books_names - sort by asc

`
select * from books_names order by asc;
`

#### Feature 3: List all books_names - sort by desc

`
select*from books_names order by desc;
`

#### Feature 4: Arrange books_names range between range>=300  and range <= 450

`
select * from books_names where range between range >= 300 and range <= 450;
`

#### Feature 5: To check whether particular column is available or not

`
select * from books_names where range <=500 ;
`

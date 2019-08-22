# Online-app

## Tables
#### Table 1: Books
| S No | Name | Category | Price | Year| Rating |
| -- | -- | -- | -- | -- |--|
| 1 | Java | Technology | 500 | 2017 | 4 |
| 2 | Anatomy | Medicine | 700 | 2016 | 3 |
| 3 | Principles of Management | Management | 450 | 2013| 3.5 |
| 4 | Sql | Technology | 300 | 2017 | 5 |
| 6 | Neuroscience | Medicine | 500 | 2015 | 4 |

#### List All Books
select * from Books;

#### Feature 1: List All Books based on price range from high to low 
select * from Books Order By Price desc;

#### Feature 2:List All Books based on price range from low to high
select * from Books Order By Price asc;

#### Feature 3:List All Books based on Management Category
select * from Books where Category=Management;

#### Feature 4:List All Books based on year 2017
select * from Books where Year=2017;

#### Feature 5: List All Books where the price ranges from 400 to 700
select * from Books where Price range between 400 and 700; 

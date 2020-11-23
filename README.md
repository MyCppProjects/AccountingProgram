# AccountingProgram
This project is for a relative who owns a business and needs to track down his clients' total debts and such. An accounting program, which uses MySQL as database, C++/SLI, and connected to firebase in case sth happens to localhost. Firebase support will come with upcoming updates.

## Installation
```bash

```

## How To Use
Basically, you're gonna download the whole package or just download it through npm. You need to create a mysql database called "stuff" through MYSQL, and run this query.
```SQL
CREATE TABLE clients (
    ID INT AUTO_INCREMENT PRIMARY KEY,
    Name VARCHAR(100) NOT NULL,
    Surname VARCHAR(100) NOT NULL,
    UNIQUE (Name, Surname),
    TotalFee INT NOT NULL,
    CurrentFee INT NOT NULL DEFAULT(TotalFee),
    UpdateDate DATE DEFAULT(CURRENT_DATE)
);
```
### Related Images


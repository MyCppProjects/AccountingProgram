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
If Added Client's current debt is 0, in other words, if the client paid his debt; its row gets green.
![Example](https://user-images.githubusercontent.com/42900996/99983164-8f86a680-2dbc-11eb-9aff-acaae0bfab68.jpg)

![Next](https://user-images.githubusercontent.com/42900996/99983168-90b7d380-2dbc-11eb-9d42-497de755a1d3.jpg)

![Afterxdxd](https://user-images.githubusercontent.com/42900996/99983169-90b7d380-2dbc-11eb-8163-4c37e99a1ca5.jpg)

![AnotherOne](https://user-images.githubusercontent.com/42900996/99983171-91506a00-2dbc-11eb-88e5-8d2c3b3b7684.jpg)

![BeforeDelete](https://user-images.githubusercontent.com/42900996/99983174-91e90080-2dbc-11eb-8330-d8fccae1ff07.jpg)

![AfterTransaction](https://user-images.githubusercontent.com/42900996/99983178-944b5a80-2dbc-11eb-9041-77ea272360be.jpg)

![ClientAdded](https://user-images.githubusercontent.com/42900996/99983180-94e3f100-2dbc-11eb-8379-0845dd048b26.jpg)

![BeforeShow](https://user-images.githubusercontent.com/42900996/99983181-94e3f100-2dbc-11eb-81e4-fd742e668fab.jpg)

![AddingTransaction](https://user-images.githubusercontent.com/42900996/99983182-957c8780-2dbc-11eb-9083-676c6731754b.jpg)

![AfterDelete](https://user-images.githubusercontent.com/42900996/99983194-98777800-2dbc-11eb-94da-6d27dc0d1012.jpg)

### Reach Me

You can reach me through these links

| Program | Nick |
| ------ | ------ |
| Discord | [Fl1ck__#8394] |
| Steam | [Fl1ck__](https://steamcommunity.com/id/lolmylifesucks) |
| Facebook | [Ugur Tasdan](https://www.facebook.com/ugur.tasdan.14/) |
| Instagram | [Fair.lander](https://www.instagram.com/fair.lander/) |
| Email | [ugurtasdan@yahoo.com.tr](mailto:ugurtasdan@yahoo.com.tr) |

### License
[MIT](https://choosealicense.com/licenses/mit/)

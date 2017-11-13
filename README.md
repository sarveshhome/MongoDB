## MongoDB


##setup mongodb with bat file


cd\

c:

cd C:\Program Files\MongoDB\Server\3.2\bin

mongod.exe --dbpath "C:\data\db "

cd\

c:

cd C:\Users\<userName>\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\Node.js

C:\Users\<username>\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\Node.js\Node.js command prompt.lnk

mongo.exe

----------------------------------------------

```sh
`show dbs`	   		Print a list of all databases on the server.

`use <db>`			Switch current database to <db> . The mongo shell variable db is set to the current database.

`show collections`	Print a list of all collections for current database

```


```sh

db.employess.insert(
{
        "EmployeeID": "1",
        "LastName": "Davolio",
        "FirstName": "Nancy",
        "Title": "Sales Representative",
        "TitleOfCourtesy": "Ms.",
        "BirthDate": "1948-12-08T00:00:00",
        "HireDate": "1992-05-01T00:00:00",
        "Address": "507 - 20th Ave. E.Apt. 2A",
        "City": "Seattle",
        "Region": "WA",
        "PostalCode": "98122",
        "Country": "USA",
        "HomePhone": "(206) 555-9857",
        "Extension": "5467",               
        "ReportsTo": "2",
        "PhotoPath": "http://accweb/emmployees/davolio.bmp"
      });
	 
```
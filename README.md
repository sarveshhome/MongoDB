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
show dbs   			Print a list of all databases on the server.

use <db>			Switch current database to <db> . The mongo shell variable db is set to the current database.

show collections	Print a list of all collections for current database

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


```sh

 var mydocuments =
    [
{
        "EmployeeID": "2",
        "LastName": "Fuller",
        "FirstName": "Andrew",
        "Title": "Vice President, Sales",
        "TitleOfCourtesy": "Dr.",
        "BirthDate": "1952-02-19T00:00:00",
        "HireDate": "1992-08-14T00:00:00",
        "Address": "908 W. Capital Way",
        "City": "Tacoma",
        "Region": "WA",
        "PostalCode": "98401",
        "Country": "USA",
        "HomePhone": "(206) 555-9482",
        "Extension": "3457",        
        "Notes": "Andrew received his BTS commercial in 1974 and a Ph.D. in international marketing from the University of Dallas in 1981.  He is fluent in French and Italian and reads German.  He joined the company as a sales representative, was promoted to sales manager in January 1992 and to vice president of sales in March 1993.  Andrew is a member of the Sales Management Roundtable, the Seattle Chamber of Commerce, and the Pacific Rim Importers Association.",
        "PhotoPath": "http://accweb/emmployees/fuller.bmp"
      },
      {
        "EmployeeID": "3",
        "LastName": "Leverling",
        "FirstName": "Janet",
        "Title": "Sales Representative",
        "TitleOfCourtesy": "Ms.",
        "BirthDate": "1963-08-30T00:00:00",
        "HireDate": "1992-04-01T00:00:00",
        "Address": "722 Moss Bay Blvd.",
        "City": "Kirkland",
        "Region": "WA",
        "PostalCode": "98033",
        "Country": "USA",
        "HomePhone": "(206) 555-3412",
        "Extension": "3355",        
        "Notes": "Janet has a BS degree in chemistry from Boston College (1984).  She has also completed a certificate program in food retailing management.  Janet was hired as a sales associate in 1991 and promoted to sales representative in February 1992.",
        "ReportsTo": "2",
        "PhotoPath": "http://accweb/emmployees/leverling.bmp"
      },
      {
        "EmployeeID": "4",
        "LastName": "Peacock",
        "FirstName": "Margaret",
        "Title": "Sales Representative",
        "TitleOfCourtesy": "Mrs.",
        "BirthDate": "1937-09-19T00:00:00",
        "HireDate": "1993-05-03T00:00:00",
        "Address": "4110 Old Redmond Rd.",
        "City": "Redmond",
        "Region": "WA",
        "PostalCode": "98052",
        "Country": "USA",
        "HomePhone": "(206) 555-8122",
        "Extension": "5176",        
        "Notes": "Margaret holds a BA in English literature from Concordia College (1958) and an MA from the American Institute of Culinary Arts (1966).  She was assigned to the London office temporarily from July through November 1992.",
        "ReportsTo": "2",
        "PhotoPath": "http://accweb/emmployees/peacock.bmp"
      },
      {
        "EmployeeID": "5",
        "LastName": "Buchanan",
        "FirstName": "Steven",
        "Title": "Sales Manager",
        "TitleOfCourtesy": "Mr.",
        "BirthDate": "1955-03-04T00:00:00",
        "HireDate": "1993-10-17T00:00:00",
        "Address": "14 Garrett Hill",
        "City": "London",
        "PostalCode": "SW1 8JR",
        "Country": "UK",
        "HomePhone": "(71) 555-4848",
        "Extension": "3453",        
        "Notes": "Steven Buchanan graduated from St. Andrews University, Scotland, with a BSC degree in 1976.  Upon joining the company as a sales representative in 1992, he spent 6 months in an orientation program at the Seattle office and then returned to his permanent post in London.  He was promoted to sales manager in March 1993.  Mr. Buchanan has completed the courses \"Successful Telemarketing\" and \"International Sales Management.\"  He is fluent in French.",
        "ReportsTo": "2",
        "PhotoPath": "http://accweb/emmployees/buchanan.bmp"
      },
      {
        "EmployeeID": "6",
        "LastName": "Suyama",
        "FirstName": "Michael",
        "Title": "Sales Representative",
        "TitleOfCourtesy": "Mr.",
        "BirthDate": "1963-07-02T00:00:00",
        "HireDate": "1993-10-17T00:00:00",
        "Address": "Coventry HouseMiner Rd.",
        "City": "London",
        "PostalCode": "EC2 7JR",
        "Country": "UK",
        "HomePhone": "(71) 555-7773",
        "Extension": "428",        
        "Notes": "Michael is a graduate of Sussex University (MA, economics, 1983) and the University of California at Los Angeles (MBA, marketing, 1986).  He has also taken the courses \"Multi-Cultural Selling\" and \"Time Management for the Sales Professional.\"  He is fluent in Japanese and can read and write French, Portuguese, and Spanish.",
        "ReportsTo": "5",
        "PhotoPath": "http://accweb/emmployees/davolio.bmp"
      },
      {
        "EmployeeID": "7",
        "LastName": "King",
        "FirstName": "Robert",
        "Title": "Sales Representative",
        "TitleOfCourtesy": "Mr.",
        "BirthDate": "1960-05-29T00:00:00",
        "HireDate": "1994-01-02T00:00:00",
        "Address": "Edgeham HollowWinchester Way",
        "City": "London",
        "PostalCode": "RG1 9SP",
        "Country": "UK",
        "HomePhone": "(71) 555-5598",
        "Extension": "465",        
        "Notes": "Robert King served in the Peace Corps and traveled extensively before completing his degree in English at the University of Michigan in 1992, the year he joined the company.  After completing a course entitled \"Selling in Europe,\" he was transferred to the London office in March 1993.",
        "ReportsTo": "5",
        "PhotoPath": "http://accweb/emmployees/davolio.bmp"
      },
      {
        "EmployeeID": "8",
        "LastName": "Callahan",
        "FirstName": "Laura",
        "Title": "Inside Sales Coordinator",
        "TitleOfCourtesy": "Ms.",
        "BirthDate": "1958-01-09T00:00:00",
        "HireDate": "1994-03-05T00:00:00",
        "Address": "4726 - 11th Ave. N.E.",
        "City": "Seattle",
        "Region": "WA",
        "PostalCode": "98105",
        "Country": "USA",
        "HomePhone": "(206) 555-1189",
        "Extension": "2344",        
        "Notes": "Laura received a BA in psychology from the University of Washington.  She has also completed a course in business French.  She reads and writes French.",
        "ReportsTo": "2",
        "PhotoPath": "http://accweb/emmployees/davolio.bmp"
      },
      {
        "EmployeeID": "9",
        "LastName": "Dodsworth",
        "FirstName": "Anne",
        "Title": "Sales Representative",
        "TitleOfCourtesy": "Ms.",
        "BirthDate": "1966-01-27T00:00:00",
        "HireDate": "1994-11-15T00:00:00",
        "Address": "7 Houndstooth Rd.",
        "City": "London",
        "PostalCode": "WG2 7LT",
        "Country": "UK",
        "HomePhone": "(71) 555-4444",
        "Extension": "452",        
        "Notes": "Anne has a BA degree in English from St. Lawrence College.  She is fluent in French and German.",
        "ReportsTo": "5",
        "PhotoPath": "http://accweb/emmployees/davolio.bmp"
      }
	  
    ];
	
	db.employess.insert( mydocuments );
	

```


```sh

show dbs
	use users
	
	Insert Data
	----------------------
	db.users.insert({
	   name:"ali",
	   age:18,
	   status: "D",
	   groups: ["politics","news"]
	})
	-------------
	db.users.insert(
   {
      name: "sue",
      age: 26,
      status: "A"
   })
   -------------------
   update Query
   
   db.users.update(
   { age: { $gt: 18 } },
   { $set: { status: "A" } },
   { multi: true });
   
   
   Remove
   -------------
   db.users.remove(
   { status: "D" });
   
   
  db.users.insert(
  {
     name: "sue",
	 age:26,
	 status:"A",
	 groups:["news","sports"]
  }
  ); 
   db.users.insert(
  {
     name: "lee",
	 age:28,
	 status:"A",
	 groups:["news","software"]
  }); 
  
   db.users.insert(
  {
     name: "jan",
	 age:21,
	 status:"B",
	 groups:["news","software"]
  }); 
  
  db.users.insert(
  {
     name: "Kai",
	 age:38,
	 status:"A",
	 groups:["news","sports"]
  }); 
  
   db.users.insert(
  {
     name: "sam",
	 age:18,
	 status:"C",
	 groups:["news","sports"]
  }); 
  
     db.users.insert(
  {
     name: "mel",
	 age:38,
	 status:"D",
	 groups:["news","sports"]
  }); 
  
     db.users.insert(
  {
     name: "ryan",
	 age:31,
	 status:"E",
	 groups:["news","sports"]
  }); 
  
  Find Query
  --------------
  db.users.find({});
  db.users.find({age: { $gt :18}}).sort({age:1});
   db.users.find({age: { $eq :18}}).sort({age:1});


```


Create Database with command :

=> 	use inventory

insert data with command :


=> db.inventory.insertOne(   { item: "canvas", qty: 100, tags: ["cotton"], size: { h: 28, w: 35.5, uom: "cm" } }
)

db.inventory.find( { } )
db.inventory.find( { item: "canvas" } )



db.inventory.insertMany([
   { item: "journal", qty: 25, tags: ["blank", "red"], size: { h: 14, w: 21, uom: "cm" } },
   { item: "mat", qty: 85, tags: ["gray"], size: { h: 27.9, w: 35.5, uom: "cm" } },
   { item: "mousepad", qty: 25, tags: ["gel", "blue"], size: { h: 19, w: 22.85, uom: "cm" } }
])


db.inventory.insertMany([
   { item: "journal", qty: 25, size: { h: 14, w: 21, uom: "cm" }, status: "A" },
   { item: "notebook", qty: 50, size: { h: 8.5, w: 11, uom: "in" }, status: "A" },
   { item: "paper", qty: 100, size: { h: 8.5, w: 11, uom: "in" }, status: "D" },
   { item: "planner", qty: 75, size: { h: 22.85, w: 30, uom: "cm" }, status: "D" },
   { item: "postcard", qty: 45, size: { h: 10, w: 15.25, uom: "cm" }, status: "A" }
]);

db.inventory.find( { status: "D" } )

db.inventory.find( { status: { $in: [ "A", "D" ] } } )  /*SELECT * FROM inventory WHERE status in ("A", "D")*/

db.inventory.find({status: "A",qty: {$lt : 30 } })   /*SELECT * FROM inventory WHERE status = "A" AND qty < 30*/
db.inventory.find({status: "A",qty: {$gt : 30 } }) 



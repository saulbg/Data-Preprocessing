# Data Importation  

## Data Table
The data tables are ways to present the information to any person with the objective that the person who is reading will be able to understand the data in it. It is composed by rows and colums.  

## Data Types  
### Categorical
Categorical data is a collection of information that is divided into groups. 
- __Nominal Data__: This is a type of data used to name variables without providing any numerical value. 
e.g.
Name, hair colour, sex, size, etc.  

- ___Ordinal Data__: This is a data type with a set order or scale to it. It can include categorical data and numerical data.
e.g.  
Satisfaccion survey, intervale scale, etc.  

### Numerical
Numerical data is a data type expressed in numbers, rather than natural language description.
- __Discrete Data__: It is a type of numerical data which represents countable items.
e.g.
1,2,3, 5 persons, etc.
- __Continuous Data__: It is a type of numerical data which represents measurements. Are all the real numbers and is used for uncountably data.
e.g.
13.4 degrees, 1.5 of water, 6.66, etc.  

Often the people refeers to the numerical data as quantitative data. We can do mathematical operations with this data.  

### Boolean
It is the data type that has one of two possible values (usually true and false) which is intended to represent two truth values of logic and boolean algebra. 
This data is primarily associated with conditionals statements.
In many programming languages the 0 represents the result False and the 1 represents the result True.  

### Dates  
Are values that represents a point of the time and day. 
The TIMESTAMP data type consists of a date and time, with optional time zone.
The format is as follows:  
__ TIMESTAMP [(timestamp_precision)] [time_zone_spec] __ 

### Strings  
It is used to represent text rather than numbers as int,float,etc do. It is composed by a set of characters that can also contain spaces and numbers. 

### Common data formats  
- __csv__: It is a simple format for representing a rectangular array (matrix) of numeric and textual values. It is a delimited data format that has fields/columns separated by the comma character.  
- __json__: It is a text format easier to the interchange of data. It's origin is from the JavaScript language. It is primarily used for transmitting data between a web application and a server.  
- __xml__: It stands for Extensible Markup Language. It is text-based markup language derived from SGML. XML tags identify the data and are used to store and organize the data. Defines set of rules for encoding documents in a format that is both human-readable and machine-readable.
- __xls__: It is a extension which represent Excel Binary File Format. Such files can be created by Microsoft Excell as well other similar spreadsheet programs. Data is stored and displayed to users in table format in worksheet and can span numeric values, text data, formulas, external data connections, images, and charts.  

### Difference between local and remote repository
- __Local__: It is the one which you will make local changes, typically this local repository is on your computer.
- __Remote__: It is located on one server like GitHub, you can access to the repository in any place.  

### Secure data transfer protocols  
- __FTP(File Transfer Protocol)__: It is built for both single file and bulk file transfers. It is useful to transfer files but is not so strong on security.  
- __HTTP(Hypertext Transfer Protocol)__: It allow us to make a request of data an sources, as HTML documents. It is the base of any interchange of data in the web, client-server.
- __WebDAV (Web Distributed Authoring and Versioning)__:Allos the clients to perform remote web content authoring operations. Provides a framewrok for users to create, change and move documents on a server.
- __FTPS__: Is an extension to the commonly FTP that adds support for the TLS. Includes the use of server-side public key authentication certificates and client-side authorization certificates.  

### Procedures for data importing  
A procedure for data importing and exporting involves "translating" from the format used in one application into that used by another, where such translation is accomplished automatically via machine processes, such as transcoding, data transformation, and others.
Example of importing a csv in Python:
from csv import reader
opened_file = open('file.csv')
read_file = reader(opened_file)  









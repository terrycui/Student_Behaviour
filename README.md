Student_Behaviour
===============
##Description

##Project Architectrue
![picture alt](https://github.com/hangfei/CodingChallenge/blob/master/BrightEdge.jpg "Title is optional")

The TextScraper Class is the main class. It coordinates different modules and handles the main procedures.  
The procedures including request search result, and get response and parse through the results. The requesting and response of HTTP to shopping.com is handled by HTTPClient class. The conversion to w3c DOM is handled by DomOperator class. The parsing is handled by WebpageParsingModule. And there are also some helper classes, like FileOpeartor, ProjectHelper and one data model class.

####Exception Handling:
- Network Exception
- User input exception
- Parsing Exception

####Supporting Package:
- jtidy
- org.w3c.dom
- org.apache.http

##Usage instructions 
The programe is provided as a Java runnable jar file.
To run this, you have two options:
- Query 1: (requires a single argument)  
java -jar Assignment.jar <keyword> (e.g. java -jar Assignment.jar "baby strollers") 
- Query 2: (requires two arguments)  
java -jar Assignment.jar <keyword> <page number> (e.g. java -jar Assignment.jar "baby strollers" 2) 


##Where to get help
Please contact ....

##Contribution guidelines
TBD

##Contributor list
Hangfei Lin

##Credits, Inspiration, Alternatives
CIS573, Chris Murphy


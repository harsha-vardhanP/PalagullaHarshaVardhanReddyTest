(Q1) Mention the working of Internet Website in Terms of Front-end & Back-end Divisions
sol:-

Step 1: The user accesses a web application via a web browser or mobile application, triggering a request to the web server over the Internet.

Step 2: The web server forwards the request to the web application server. The web application server performs the requested task – such as querying the database
or processing the data – then generates the results of the requested data.

Step 3: The web application server sends the results back to the web server.

Step 4: the web server delivers the requested information to the client (desktop, mobile device, tablet, etc.) and the information appears on the user’s display.

-------------------------------------------------------------------------------------------------------------------------------

(Q2) What are tags in HTML? Explain the each category of tag with an Example.
sol:-

HTML tags are the keywords on a web page that define how your web browser must format and display your web page. Almost all tags contain two parts, an opening, and
a closing tag. For example, <html> is the opening tag and </html> is the closing tag.

eg:- 

Head Tag: 
The head tag <head> contains all the elements describing the document. 

Title Tag: 
The title tag <title> specifies the HTML page title, which is shown in the browser’s title bar. 

Body Tag: 
The body tag <body> is where you insert your web page’s content. 

Paragraph Tag: 
A paragraph tag <p> is used to define a paragraph on a web page.

Heading Tag:  
The HTML heading tag is used to define the heading of the HTML document. 

-------------------------------------------------------------------------------------------------------------------------------

(Q3) Explain the working Procedure of Virtual DOM.
sol:-

In React, everything is treated as a component be it a functional component or class component.A component can contain a state. whenever the state of any component
is changed react updates its Virtual DOM tree. Though it may sound like it is ineffective the cost is not much significant as updating the virtual DOM doesn’t take
much time. React maintains two Virtual DOM at each time, one contains the updated Virtual DOM and one which is just the pre-update version of this updated Virtual
DOM. Now it compares the pre-update version with the updated Virtual DOM and figures out what exactly has changed in the DOM like which components have been
changed. This process of comparing the current Virtual DOM tree with the previous one is known as ‘diffing’. Once React finds out what exactly has changed then it
updates those objects only, on real DOM. 

Re-rendering of the UI is the most expensive part and React manages to do this most efficiently by ensuring that the Real DOM receives batch updates to re-render
the UI. This entire process of transforming changes to the real DOM is called Reconciliation.

-------------------------------------------------------------------------------------------------------------------------------

(Q4) Mention some Differences between MySQL and No SQL
sol:-

1. SQL databases are relational, and NoSQL databases are non-relational.
2. SQL databases are table-based, while NoSQL databases are document, key-value, graph, or wide-column stores.
3. SQL databases are vertically scalable, while NoSQL databases are horizontally scalable.
4. SQL databases use structured query language (SQL) and have a predefined schema. NoSQL databases have dynamic schemas for unstructured data.
5. SQL databases are better for multi-row transactions, while NoSQL is better for unstructured data like documents or JSON.

-------------------------------------------------------------------------------------------------------------------------------

(Q5) Explain any one DBMS Technology in your own words.
sol:-

MongoDB:-
MongoDB is an open-source document-oriented database that is designed to store a large scale of data and also allows you to work with that data very efficiently.
It is categorized under the NoSQL (Not only SQL) database because the storage and retrieval of data in the MongoDB are not in the form of tables. 

The MongoDB database contains collections just like the MYSQL database contains tables. You are allowed to create multiple databases and multiple collections.

Now inside of the collection we have documents. These documents contain the data we want to store in the MongoDB database and a single collection can contain
multiple documents and you are schema-less means it is not necessary that one document is similar to another.

The documents are created using the fields. Fields are key-value pairs in the documents, it is just like columns in the relation database. The value of the fields
can be of any BSON data types like double, string, boolean, etc.

-------------------------------------------------------------------------------------------------------------------------------

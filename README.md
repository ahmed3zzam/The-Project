# library Management System

## 1.1 Functional Requirement

1.1.1 Manage Shelves [MS]  

1-MS The system must allow the admin to "add" the shelf description.

2-MS The system must allow the admin to "update" the selected shelf description.

3-MS The system must allow the admin to "remove" the selected shelf.
 
1.1.2 Manage Categories [MC] 

1-MC The system must allow the admin to "add" the category data.

2-MC The system must allow the admin to "update" the selected category data.

3-MC The system must allow the admin to "remove" the selected category.

1.1.3 Manage Publishers [MP]

1-MP The system must allow the admin to "add" the publisher data.

2-MP The system must allow the admin to "update" the selected publisher data.

3-MP The system must allow the admin to "remove" the selected publisher.

3.1.4 Manage Authors [MA]

1-MA The system must allow the admin to "add" the author data.

2-MA The system must allow the admin to "update" the selected author data.

3-MA The system must allow the admin to "remove" the selected author.

3.1.5 Manage Books [MB]

1-MB The system must allow the admin to "add" the book data.

2-MB The system must allow the admin to "add" new book quantity

3-MB The system must allow the admin to "update" the selected book data.

4-MB The system must allow the admin to "remove" the selected book.

3.1.6 Generate Books Requests and Returns [GBRR]
 
1-GBRR The system must allow the admin to select member for the book request and generate the orders according to this member date

2-GBRR The system must allow the admin to generate books returns according to member data.

3-GBRR The system must allow the admin to "update" the books requests.

3.1.7 Manage Members [MM]

1-MM The system must allow the admin to "add" the member data.

2-MM The system must allow the admin to "update" the selected member data.

3-MM The system must allow the admin to "remove" the selected member.

## 1.2 Non-Functional Requirements

1.2.1 Performance Requirements [PR]

1-PR The system must respond the business operation in less than 3 seconds for user (admin).

2-PR The system should be compatible with all modern browsers.

3-PR The system should response the operation messages to the users within 2 seconds.

4-PR The system should be reliable.

1.2.2 Safety and Security Requirements [SSR]

1-SSR The system must handle safe login and logout through session. 

2-SSR Hashing technology should be used to handle the secure login for users.

3-SSR The database should be secured from SQL injection to prevent leak or loss of information.

4-SSR The system could use SSL (Secure Socket Layer) certificates to secure the data being transmitted. 

1.2.3 Reliability [R]
 
R-1 System should be designed in a modular manner to ease in software maintenance. By designing modularly, we are able to reduce coupling allowing each module to perform a specific function.

1.2.4 Other Software Quality Attributes 

1.2.4.1 Usability [U]

U-1 The system should have user-friendly interface. 

3.2.4.2 Availability[A]

A-1 The system must be available 24/7, with no more than 20 minutes down time per day.

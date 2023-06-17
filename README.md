1.
 Mention the working of Internet Website in Terms of Front-end & Back-end Divisions
Ans.
 There are two basic components to internet web design: front-end and back-end.
 The front end is the part of the website that users interact with directly. This includes website design, layout and user interface. The interface is written in HTML, CSS, and JavaScript, and runs on the user’s device (e.g. their web browser). When a user visits a web page, their web browser sends a request to the server to provide the website’s HTML, CSS, and JavaScript files. Once the files are received, the web browser uses them to display the website on the user’s device.
 The backend is the part of the website that runs on the server. It contains the database, server-side logic, and APIs that power the functionality of the website. The backend is typically written in languages ​​such as PHP, Python, and Ruby, and runs on a web server. When a user interacts with the web page (e.g., by submitting a form), the front end sends a request back. The backend then processes the request, retrieves or stores the data in the database, and sends a response to the frontend.
 To summarize, the front end is responsible for presenting the website content and user interface to the user, while the back end handles website operations and data management Both elements work together though is a seamless online experience.



2.
 What are tags in HTML? Explain the each category of tag with an Example.
Ans.
 In HTML (Hypertext Markup Language), tags are used to describe the structure and content of a web page. HTML tags are enclosed in angle brackets (< and >) and are used to describe various elements such as titles, paragraphs, images, links, and so on.
 There are three main types of HTML tags:

 Structural tags: These tags are used to describe the basic structure of an HTML document, including headings, paragraphs, and tables. Examples are:
 "<html>": This tag is used to define the beginning of the HTML document.
 "<head>": This tag is used to describe the header section of an HTML document, which typically contains information such as page titles, links to style sheets, and metadata.
 "<body>": This tag is used to describe the main body of the HTML document.

 Formatting tags: These tags are used to define the formatting and style of text and other elements on the web page. Examples are:
 "<strong>": This tag is used to bold text.
 "<em>": This tag is used for italic text.
 "<u>": This tag is used for underlining text.

 Linking/embedded tags: These tags can be used to link to other web pages or embed images, videos and other media. Examples are:
 "<a>": This tag is used to create a hyperlink to another web page or a specific part of the same web page.
 "<img>": This tag is used to embed an image in an HTML document.
 "<video>": This tag is used to embed a video in an HTML document.

3.
 Explain the working Procedure of Virtual DOM.
Ans.
 Virtual DOM is a design concept used in web development to improve the performance of web applications. The idea behind the Virtual DOM is to create a virtual copy of the actual DOM (Document Object Model) that represents the current state of the web page. This virtual copy is then used to calculate and efficiently update the differences to be made in the real DOM.
 The virtual DOM works by creating a new virtual tree that represents the updated state of the web application each time it changes. The Virtual DOM then compares this new virtual tree with the previous virtual tree to distinguish between them. Once the differences are detected, the virtual DOM calculates the most efficient way to update the real DOM to reflect the changes. Eventually the Virtual DOM updates the real DOM with the changes, but only for the parts of the page that have changed.
 Using a virtual DOM makes web applications faster and more efficient, as it reduces the time and resources required to update the actual DOM.


4.
 Mention some Differences between MySQL and No SQL
Ans.
 1. MySQL is a relational database system (RDBMS), while NoSQL (not just SQL) is a database system that does not use traditional table-based relational database systems
 2. Data Structure: MySQL is a relational database, which means it stores data in tables with predefined columns and rows. NoSQL databases, on the other hand, use different data models, such as document, key-value, column-family, and graph.
 3. Scalability: MySQL has scalability limits and requires vertical scaling (upgrading server hardware) to handle high traffic and data. NoSQL databases are horizontally scalable, which means more servers can be added to the system and handle more traffic and data.
 4. Query Language: MySQL uses SQL (Structured Query Language) to query and manipulate data. NoSQL databases use different query languages ​​depending on the data model used. For example, MongoDB uses a query language called MongoDB Query Language (MQL).
 5. Flexibility: MySQL is highly structured and rigid. NoSQL databases are flexible and schema-less, making it easy to manipulate the data model.
 6. ACID Compliance: MySQL follows the ACID (Atomicity, Consistency, Isolation, Durability) property. NoSQL databases do not follow the ACID property.


5
 Explain any one DBMS Technology in your own words.
Ans.
 One popular DBMS technology is MongoDB. MongoDB is a NoSQL database management system that uses a document-based data model. It is designed to be highly scalable and flexible, making it ideally suited for modern web applications that require frequent updates and real-time collaboration.
 Unlike traditional relational databases, MongoDB stores data in documents, which are JSON-like structures that can be nested and have dynamic schemas. This makes it easier to store and retrieve complex data structures, such as hierarchical data or arrays.
 MongoDB also supports horizontal scaling, which means it can handle more data and traffic by adding more servers to the system. It has a powerful query language, called MongoDB Query Language (MQL), which supports advanced query and join capabilities.
 MongoDB is highly customizable, with a wide range of plugins and extensions available for developers to use. It also has a large user base that contributes to its development and supports fellow users.
 Overall, MongoDB is a powerful and flexible DBMS technology that is well suited for modern web applications that require document-based data models and horizontal scalability
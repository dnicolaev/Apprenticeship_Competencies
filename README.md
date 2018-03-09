# Apprenticeship_Competencies
### 1. FRONT END DEVELOPMENT HTML & CSS
Demonstrated proficiency here: https://github.com/TechtonicGroup/TG-Wordpress/pull/33 
- [x] Solid Knowledge of common tag types and how to implement them 
- [x] Understands how the browser handles conflicting styles
- [x] Understands how the DOM is laid out and is structured
- [x] Understands the difference between content & styling
- [x] Understands that different browsers render and interpret things slightly differently and the need to test on commonly used platforms

##### Bootstrap
*Demonstrated proficiency here: https://codepen.io/dnicolaev/full/bvbRjB
- [x] Knowledge of Bootstrap properties and design principles
- [x] Understands grid concept & how to manipulate it
- [x] Can install either by CDN or local file

### 2. MIDDLEWARE DEVELOPMENT
##### JavaScript
Demonstrated proficiency here: https://github.com/TechtonicGroup/HomeVestors_Kentico/pull/643
- [x] Solid understanding of HTML & CSS
- [x] Understanding of browser runtime & where to inject scripts
- [x] Understanding of dynamic typing and how it makes using the language quick and easy
- [x] Understanding of Document Object Model
- [x] Knowledge of JSON and working with JSON objects 
- [x] Knowledge on how to traverse the DOM for element handles 
- [x] Know how to structure native JavaScript classes (OOP, Pub/Sub) using prototype or object literal statements

##### AJAX
Demonstrated proficiency here: https://github.com/TechtonicGroup/HomeVestors_Kentico/pull/643
- [x] Understanding of asynchronous concepts and implications such as callbacks
- [x] Ability to implement AJAX calls in a project 
- [x] Understanding the difference between HTTP methods (get, post, load, etc) and their uses
- [x] Understanding of error handling and promises 

##### HTTP Methods
Demonstrated proficiency here: https://github.com/TechtonicGroup/HomeVestors_Kentico/pull/643
- [x] Understands difference between HTTP Methods POST, GET, and PUT
- [x] Understands difference between AJAX and HTTP Methods 

##### jQuery
Demonstrated proficiency here: https://github.com/TechtonicGroup/HomeVestors_Kentico/pull/561
- [x] Understands where to inject script files and how to make it function 
- [x] Understanding of basic operations & functions
- [x] Able to add localized scripts

### 3. DATABASE DEVELOPMENT 
Learned through: https://developer.couchbase.com/documentation/server/3.x/developer/dev-guide-3.0/compare-docs-vs-relational.html
https://www.upwork.com/hiring/data/sql-vs-nosql-databases-whats-the-difference/
- [x] Understands the difference between a relational database and document based database

##### MongoDB 
- Knowledge of basic installation of MongoDB and C Driver, JSON, schema design, querying, insertion of data, indexing & working with C# driver
- Able to build a MongoDB-based app
- Can Write repository methods that perform basic CRUD operations
- Able to interact with MongoDB documents, & database collections using either RoboMongo or MongoVUE

**SQL**
Demonstrated proficiency here: https://github.com/TechtonicGroup/HomeVestors_Kentico/pull/567
- [x] Can create tables, columns & stored procedures in a timely manner
- [x] Can take business logic and turn it into a database design
- [x] Knowledge of how to make a primary key or foreign key & how all the relationships work
- [x] Can create reliable, tested queries that efficiently return data
- [x] Comfortable with CLI and/or GUI tools
- [x] Can write repository methods that perform basic CRUD operations https://github.com/TechtonicGroup/HomeVestors_Kentico/pull/547

### 4. BACKEND DEVELOPMENT
##### C# ####
Demonstrated proficiency here: worked with HVA which is one big .Net/C# project  https://github.com/TechtonicGroup/HomeVestors_Kentico/tree/devbranches/Dev_Branch_Sprint72
- [x] Solid understanding of object-oriented programming in C#
- [x] Knowledge of Visual Studio, can identify Solution Explorer, the debugging menu, the build, run, and clean functions & unit testing
- [x] Understanding all common modifiers (static, abstract, etc) & can build and implement classes correctly
- [x] Understanding namespaces & how to import dependencies
- [x] Knowledge on how to use model binding
- [x] Knowledge of serialization and deserialization with JSON
- [x] Understanding the difference between pass by reference and pass by value - https://github.com/TechtonicGroup/HomeVestors_Kentico/pull/582

##### Ruby on Rails 
- Understand how an application accesses stored data, and how to reduce load by steamlining data requests
- Strong knowledge of gems, both to locate and install simple add-ons to their application, and create their own custom gems
- Knowledge of unit testing and Spec to produce clean, tested code

##### PHP 
- Solid understanding how to use forms
- Understaning of how to assign variables into HTML elements
- Before writing a function or class, be able to utilize existing functions or classes

##### APIs
Deomonstrated proficiency here: worked with HVA which is one big restful API https://github.com/TechtonicGroup/HomeVestors_Kentico/tree/devbranches/Dev_Branch_Sprint72
- [x] Create modern, REST API's from existing information assets
- [x] Integrates and orchestrates enterprise services across silos
- [x] Secure and authorize information assets exposed via APIs
- [x] Understanding C.R.U.D

### 5. CODING STANDARDS
##### Code Formatting
Demonstrated proficiency here: https://github.com/TechtonicGroup/HomeVestors_Kentico/pull/607
- [x] While going through code, check the code formatting to improve readability and ensure there are no blockers

##### Architecture 
Demonstrated proficiency here: https://github.com/TechtonicGroup/HomeVestors_Kentico/tree/devbranches/Dev_Branch_Sprint73
- [x] Separation of Concerns followed
- [x] Split into respective files (HTML, JavaScript and CSS)
- [x] Split into multiple layers and tiers as per requirements (Presentation, Business, and Data Layers)
- [x] Code is in sync with existing code patterns/technologies
- [x] Design patterns: Use appropriate design pattern (if if helps), after completely understanding the problem and context

##### Coding Best Practices
Demonstrated proficiency here: https://github.com/TechtonicGroup/HomeVestors_Kentico/pull/572
- [x] No hard coding, use constants/configuration values
- [x] Group similar values under an enumeration (enum)
- [x] Comments - Do not write comments for what you are doing, instead write comments on why you are doing. Specify about any hacks workaround and temporary fixes. Additionally mention pending tasks in your to-do comments, which can be tracked easily
- [x] Avoid multiple if/else blocks
- [x] Use framework features, wherever possible instead of writing custom code

##### Non Functional Requirements
Demonstrated proficiency here: https://github.com/TechtonicGroup/HomeVestors_Kentico/pull/643
- [x] a.) Maintainability (Supportability) - The application should require the least amount of effort to support in the near future. It should be easy to identify, fix, and detect.

      	Readability: Code should be self-explanatory. Get a feel of story reading. whlile going through code. Use appropriate name for variables, functions and classes. If you are taking more time to understand  the code, then either code needs refactoring or at least comments have to be written to make it clear.

      	Testability: The code should be easy to test. Refactor into separate function (if required). Use interfaces while talking to other layers, as interfaces can be mocked easily. Try to avoid static functions, singleton classes as these are not easily testable by mocks.

      	Debuggability: Provide support to log the flow of control, paramater data and exception details to find the root cause easily. if you are using Log4Net like component then add support for database logging also as querying the log table is easy.

      	Configurability: Keep the configurable values in place (XML file, database table) so that no code changes are required, if the data is changed frequently.

- [x] b.) Reusability

      	DRY (Do not Repeat Yourself) principle: The same code should not be repeated more than twice

      	Consider reusable services, functions and components

      	Consider generic functions and classes

- [x] c.) Reliability - Exception handling and cleanup (dispose) resources.
- [x] d.) Extensibility - Easy to add enhancements with minimal changes to existing code. One component should be easily replaceable by a better component.
- [x] e.) Security - Authentication, authorization, input data validation against security threats such as SQL injections and Cross Site Scripting (XSS), encrypting the sensitive data (passwords, credit card information etc.) 
- [x] f.) Performance 

      Use a data type that best suits the needs such as StringBuilder, generic collection classes 

      Lazy loading asynchronous and parallel processing 

      Caching and session/application data

- [x] g.) Scalability - Consider if it supports a large user base/data? Can this be deployed into web farms?
- [x] h.) Usability - Put yourself in the shoes of a end-user and ascertain, if the user interface/API is easy to understand and use. If you are not convinced with the user interface design, then start discussing your ideas with the business analyst

##### Object-Oriented Analysis and Design (OOAD) Principles
Learned through: https://scotch.io/bar-talk/s-o-l-i-d-the-first-five-principles-of-object-oriented-design
- [x] Single Responsibility Principle (SRS): Do not place more than one responsibility into a single class of function, refactor into separate classes and functions
- [x] Open Closed Principle: While adding new functionality, existing code should not be modified. New functionality should be written in new classes and functions
- [x] Liskov substitutability principle: The child class should not change the behavior (meaning) of the parent class. The child classcan be used as a substitute for a base class.
- [x] Interface segregation: Do not create lengthy interfaces, instead split them into smaller interfaces based on the functionality. The interface should not contain any dependencies (paramaters), which are not require for the expected functionality
- [x] Dependency Injection: Do not hardcode the dependencies, instead inject them

### 6. GIT
Demonstrated proficiency here: https://github.com/dnicolaev
- [x] Solid knowledge of how source control works why it's important using either CLI or GUI tools
- [x] Know the basic commands: clone, push, fetch, pull, commit
- [x] Understand what remotes are
- [x] Understand how to hide, add, remove, and stash files
- [x] Understand how to branch and merge
- [x] Understand how to resolve merge conflicts
- [x] Can reliably commit based on project needs, with communication to the rest of the team
- [x] Uses relevant and important information in commit notes
- [x] Understands differences between HTTPS SSH validation

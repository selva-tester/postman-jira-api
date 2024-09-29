# postman-jira-api

**Project overview:**
In this project, I conducted API testing using multiple tools and services. I utilized the Jira API for testing issue and project tracking functionalities. For authentication testing, I used the Heroku Booking API to validate end to end Booking processes. Additionally, I implemented CRUD operations and API chaining using the Go REST API. Throughout the testing process, I applied pre-script and post-script logic to validate data schemas, ensuring proper request and response formats and validating different scenarios with different codes.

**Technology used:**
Postman: API development environment for creating and executing HTTP requests.
Newman: Command-line collection runner for Postman.
Newman-HTML-Reporter: Generates HTML reports for test results.
Node.js: For running Newman and associated libraries.

**Once everything is set up, you can run your Postman collection using Newman:**
newman run "https://api.getpostman.com/collections/26798595-ee7e5096-441f-4b74-91c2-71d446a085af?apikey=PMAK-66f951261860f80001c4e139-688cbbaab8a326f411544a9b09b999a45c" 

**To generate an HTML report after running your Newman tests, use the following command:**
newman run "https://api.getpostman.com/collections/26798595-ee7e5096-441f-4b74-91c2-71d446a085af?apikey=PMAK-66f951261860f80001c4e139-688cbbaab8a326f411544a9b09b999a45c" -r htmlextra --reporter-htmlextra-export newman_report.html

Note: Attached the html report in the repository. Feel free to refer to it.





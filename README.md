# CompaniesOrganizationManager
Web application for CRUD organizational structure for parent and child companies.

# Try in action:
https://comorg.herokuapp.com/    - it will become active again after a short delay after transition.

# Used technologies:
- Java 7
- Spring MVC 
- MySQL
- Hibernate 4.2
- Tomcat 8 
- Maven
- AngularJS
- Heroku

For build a tree hierarchy in MySQL database, I used a Nested Set Model. It is pretty slow for CRUD operation, but allow to support non-limited nesting levels.

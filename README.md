# side-project-showcase

# Project Overview
Articles service for a news reader app, developed in Java 8 and latest version of Spring Boot (2.2.1.RELEASE). Backend to provide REST APIs
for the following use cases:

* Allow an editor to create/update/delete an article
* Display one article
* List all articles for a given author
* List all articles for a given period
* List all articles for a specific keyword

# Codebase link
https://github.com/anand2techie/article-repo

# Tech Overview
* Adopted clean & test-driven design for developing REST APIs for CRUD operations on articles.
* Adhered to REST API design standards, ensuring right HTTP methods are used with proper response codes.
* Project structure is laid out with separation of concerns in the first place. Used Hyperlinks/HATEOAS for discoverability.
* Used H2 as the database; Spring data JPA as repository support
* Lombok is used for concise-code writing

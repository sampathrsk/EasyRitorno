# EasyRitorno

## Background:
- From End Users Perspective …
Shopping trends have drastically changed over the past decade. Online Retailer giants like Amazon, eBay have transitioned our cumbersome store hopping to buying goods with a click from the comforts of your own home. However, there are a lot of us who always wonder if we have made the right choice? What if we order the wrong size of our favorite denim? What if we received a malfunctioning Bluetooth speaker? The return process is such a hassle. One need to repack everything, obtain the shipping label and post them to the retailer hub. Imagine a company that would do all this for you? Offer you the service of picking up your return goods from your doorstep, package the product and then ship them to appropriate address. At the end of this project we will have an Enterprise Application that provides customers an Online portal to help them in hassle-free retail return process.
- From Employees of the Company Perspective …
Everyone loves cloud applications. About 56% of organizations use 6 or more SaaS applications like GitHub for version control repository, Jenkins for Continuous Integration. With this growing cloud apps adoption, we are running into overwhelming security issues in organizations. It is humanly impossible for users to remember individual strong passwords for every cloud application used within the organization. Employees generally end up reusing their passwords or create insecure weak passwords, store them in emails which is a huge risk to the organization security. Also, IT department in every company needs to manage multiple vendors and cross platform cloud applications. The situation gets worse when employee accounts are locked down and takes days together to unlock the accounts. A solution to all these problems is a single-sign-on service where employees are provided with a portal wherein with one click can access all their cloud applications.

## Proposed Solution

A simple web portal is developed to help end users have a hassle-free retail return experience. Once the customer logs into the portal, he/she identifies the type of goods he/she wishes to return. The customer places an order for the number boxes or packaging type required. The customer is also given an option to opt the type of shipping (1-day shipping, 2-day shipping, standard shipping). The portal houses an option to upload the return shipping label. The customer specifies the pick-up time and pick-up address. The customer then places an order for the service. The packaging charges, shipping charges and service charge is payable through PayPal. The customer is then provided with a tracking number using which he/she can verify the status of his package. Once the package is picked up and shipped to the appropriate address, customers are notified and can tweet their experience about the service provided.

Developers are provided with a single portal integrated with GitHub and Jenkins. Authentication is done using Active Directory. A single sign on portal is provided for all developers to have a frictionless development environment. GitHub is used as the code repository for both the portals. Jenkins is used to achieve continuous integration.

## Technologies Used

- Server Technology
The sample application is developed to work in any JEE web application container. It uses Spring MVC framework and the deployment files will be provided to run on Apache Tomcat. Configuration details will be provided in the developer instruction pages. The User Interfaces for rendering the application pages are developed using AngularJS.
- Database Technology
The application uses relational database for storage. It will use MySQL Server version 5.7.19. Sample database would be provided.
- Development Environment
1.	Java JDK 1.8
2.	Apache Tomcat 8.5
3.    Spring 3.1.2
4.    Spring Security 3.1.2
5.    Maven 2.9
6.    JUnit 4.10
7.    MySQL 5.x
8.    AngularJS
9.    GitHub/GitLab
10.  Jenkins
11.  Twitter APIs
12.  PayPal APIs
13.  Active Directory
 
- Logging
Spring supports the use of the Apache Commons Logging API. This API provides the ability to use Java 1.4 loggers, the simple Commons loggers, and Apache Log4J loggers.

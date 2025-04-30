# airbnb-clone-project
## This is air-bnb website clone 

###  The project goal is to replicate airbnb web app 

## Team Roles

### Backend Developer - Creates the server side code, implements different api end points, designs database schema, optimize code for better performance
### Database Admin - Responsible for managing the database 
### Devops - works in both development and deployment stages and esure
### QA - tests the code and make sure they perform as expected

## Technology Stack
### Stacks Inlcude Django , PostgreSQL , GraphQL
### Django - python framwork for building api and backend
### PostgreSql - A relational SQL database used for storage
### GraphQL -  Provides a flexible query language for retrieving and manipulating data.
### Celery - to handle asynchronous tasks
### Redis -  Used for caching and session management
### Docker -  Containerization tool
### CI/CD Pipelines-  for testing and deploying code change

## Database Design 
### Entities - Users , Reviews , Bookings ,Properties, Payments
### Fields - Users(names,id,email,password), Reviews(reviewId,Comment,rating) , Bookings(BookingId,PropertyId,UserId) , Properties(ProperyId,PropertyName,PropertyLocation) , Payments(paymentId,amount,recieverId)
### Relationships - A user can have Multiple property , A User can have multiple Payments , a user can also have multiple bookings and reviews, Reviews belong to a user and property 

## Feature BreakDown
### User Management - A user can signup be authenticated and authorized. In addtion a user can manage profile.
### Booking System - Create booking system so users can reserve spot  and manages booking details
### Property Management - Features that include creation deletion updating and reading properties
### Payment Processing - process payment  and handle multiple transactions;
### Review System - Allow users to comment or leave review and their own ratings
### Data Optimization - fast retrieval of data from database


## API Security

### Authentication
### Authorization
### Form validation
### Error handling
### Token Management
### Rate Limitng - For DDos protection

### Security is very important in an organization it plays key role in company success and winning Customer's trust. Secure Payment transasctions and safe user passwords are crucial.

## CI/CD Pipeline

### A Continous Integration and Continous Development Process are set of steps developers follow to develop new softwares and ship them efficinetly
### They helps us to quickly integrate updates and changes to code 
### Tools include containerization like docker , Github Actions for the pipeline
### 

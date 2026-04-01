DevHunt — Remote Jobs Aggregator

DevHunt is a Spring Boot web application that aggregates remote job listings and allows users to apply directly through the platform.
 What you need
- Java 17+
- Maven
- (Optional) H2 (in-memory database)

 Features

 Browse remote developer jobs
View companies and job details
Apply for jobs via web form
Admin panel for managing applications
 Integration with external API (Remotive)
 In-memory database (H2)

 Tech Stack

- Backend: Spring Boot 3
- Database: H2 (in-memory)
- ORM: Spring Data JPA / Hibernate
- Frontend: Thymeleaf
- Build Tool: Maven
- External API: Remotive Jobs API

 Project Structure

src/main/java/com/devhunt
├── config
├── controller
├── dto
├── model
├── repository
├── service

 How to Run

Open project folder
cd devhunt

 Run the application


mvn spring-boot:run



 API Endpoints

GET /api/jobs  
GET /api/applications  
POST /jobs/{id}/apply

 Example Workflow
1. Open job list
2. Select a job
3. Submit application form
4. Check results in admin panel

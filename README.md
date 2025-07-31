# NYU ClubHub - Event & Budget Approval Portal

A full-stack application designed to streamline the student club event approval process at NYU, replacing manual paper-based workflows with an efficient digital solution.

## Features

- Secure user authentication and authorization
- Multi-step approval workflow system
- Event submission and management
- Budget tracking and approval
- Real-time status dashboard
- Club management interface

## Technology Stack

### Backend
- Java 17
- Spring Boot (Spring MVC, Spring Data JPA)
- RESTful APIs
- PostgreSQL Database

### Frontend
- HTML5
- CSS3
- JavaScript (AJAX)

### Development Tools
- Git
- Maven
- Postman

## Project Structure

```
nyu-clubhub/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── edu/nyu/clubhub/
│   │   │       ├── controller/
│   │   │       ├── model/
│   │   │       ├── repository/
│   │   │       ├── service/
│   │   │       └── config/
│   │   ├── resources/
│   │   │   ├── application.properties
│   │   │   ├── static/
│   │   │   └── templates/
│   │   └── webapp/
│   │       ├── css/
│   │       ├── js/
│   │       └── WEB-INF/
│   └── test/
│       └── java/
│           └── edu/nyu/clubhub/
```

## Setup and Installation

1. Clone the repository:
```bash
git clone https://github.com/Aditya-ice/nyu-clubhub.git
```

2. Configure PostgreSQL database and update `application.properties` with your database credentials.

3. Build the project:
```bash
mvn clean install
```

4. Run the application:
```bash
mvn spring-boot:run
```

The application will be available at `http://localhost:8080`

## Database Schema

The application uses the following main entities:

- Users (roles: student leaders, faculty advisors, administrators)
- Clubs
- Events
- Approvals
- Budgets

## API Endpoints

Documentation for the REST API endpoints will be available via Swagger UI at `/swagger-ui.html` when the application is running.

## Contributing

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

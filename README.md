# Hotel Management System

> Hotel management web app for rooms, guests, reservations and reports.

A server-rendered web application (Spring MVC + Thymeleaf) for running a hotel: rooms and room types, guests, reservations and occupancy reports.

## Tech stack

- Java 17, Spring Boot 3.4
- Spring Web (MVC) + Thymeleaf
- Spring Data JPA, JPA Specifications for reservation filtering
- H2 (file-based database, H2 console enabled)
- Maven

## Features

- **Rooms**: add, update, assign and unassign a guest
- **Room types**: add
- **Guests**: add, edit, delete, list
- **Reservations**: create, edit, delete, reservation status, filtering by guest, room, dates and status
- **Reports**: generate a report for a date range

## Running

```bash
./mvnw spring-boot:run
```

App: `http://localhost:8080`, H2 console: `http://localhost:8080/h2-console`.

---

Built for the Database Application Development Methods course, Applied Computer Science, Warsaw University of Technology. The user interface is in Polish.

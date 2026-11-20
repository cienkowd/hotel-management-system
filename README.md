# Hotel Management System

> Hotel management web app for rooms, guests, reservations and reports.

Aplikacja webowa (Spring MVC + Thymeleaf) do obsługi hotelu: pokoje i ich typy, goście, rezerwacje oraz raporty obłożenia.

## Technologie

- Java 17, Spring Boot 3.4
- Spring Web (MVC) + Thymeleaf
- Spring Data JPA, specyfikacje JPA do filtrowania rezerwacji
- H2 (baza plikowa, konsola H2 włączona)
- Maven

## Funkcjonalności

- **Pokoje**: dodawanie, edycja, przypisywanie i odpinanie gościa
- **Typy pokoi**: dodawanie
- **Goście**: dodawanie, edycja, usuwanie, lista
- **Rezerwacje**: tworzenie, edycja, usuwanie, status rezerwacji, filtrowanie po gościu, pokoju, datach i statusie
- **Raporty**: generowanie raportu dla zakresu dat

## Uruchomienie

```bash
./mvnw spring-boot:run
```

Aplikacja: `http://localhost:8080`, konsola H2: `http://localhost:8080/h2-console`.

---

Projekt z przedmiotu Metody Tworzenia Aplikacji Bazodanowych, Informatyka Stosowana, Politechnika Warszawska.

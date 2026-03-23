==========================================================================
  VERTEILTES RESERVIERUNGSSYSTEM (MICROSERVICES) — SPRING BOOT
==========================================================================

## Projektbeschreibung

Dieses Projekt ist ein vollständiges Ticketreservierungssystem für Kino
oder Zugverbindungen, entwickelt mit Spring Boot auf Basis einer
Microservices-Architektur.

Das System besteht aus vier unabhängigen Diensten, die über REST API
oder eine Nachrichtenwarteschlange (RabbitMQ / Apache Kafka) miteinander
kommunizieren:

  - Benutzerdienst (User Service)
      Registrierung, Anmeldung und Authentifizierung (JWT).

  - Katalogdienst (Catalog Service)
      Verwaltung von Filmen, Zügen, Sitzplätzen und Verfügbarkeiten.

  - Zahlungsdienst (Payment Service)
      Verarbeitung von Transaktionen, Zahlungsbestätigungen
      und Rückerstattungen.

  - Reservierungsdienst (Booking Service)
      Koordination der Reservierungen und Verwaltung des
      Buchungsstatus (PENDING → CONFIRMED / CANCELLED).

## Technologie-Stack

  Backend:        Spring Boot 3 (Java 21)
  Datenbank:      PostgreSQL (eine Instanz pro Dienst)
  Messaging:      RabbitMQ oder Apache Kafka
  Containerisierung: Docker + Docker Compose
  API-Gateway:    Spring Cloud Gateway
  Dokumentation:  Swagger / OpenAPI 3

## Was ich dabei gelernt habe

  - Microservices-Architektur und das Prinzip der losen Kopplung
  - Verwaltung verteilter Transaktionen (Saga-Muster)
  - REST API Design und Kommunikation zwischen Diensten
  - Asynchrone Kommunikation mit Nachrichtenwarteschlangen
  - Containerisierung mit Docker und Docker Compose
  - Datenbankisolierung (Database per Service)
  - Fehlertoleranz und Circuit Breaker (Resilience4j)

--------------------------------------------------------------------------

==========================================================================
  DISTRIBUTED RESERVATION SYSTEM (MICROSERVICES) — SPRING BOOT
==========================================================================

## Project Description

This project is a fully functional ticket reservation system for cinema
or train travel, built with Spring Boot using a microservices architecture.

The system consists of four independent services that communicate via
REST API or a message queue (RabbitMQ / Apache Kafka):

  - User Service
      Registration, login and authentication (JWT).

  - Catalog Service
      Management of movies, trains, seats and availability.

  - Payment Service
      Transaction processing, payment confirmation and refunds.

  - Booking Service
      Reservation coordination and booking status management
      (PENDING → CONFIRMED / CANCELLED).

## Technology Stack

  Backend:        Spring Boot 3 (Java 21)
  Database:       PostgreSQL (one instance per service)
  Messaging:      RabbitMQ or Apache Kafka
  Containerization: Docker + Docker Compose
  API Gateway:    Spring Cloud Gateway
  Documentation:  Swagger / OpenAPI 3

## What I Learned

  - Microservices architecture and the principle of loose coupling
  - Managing distributed transactions (Saga pattern)
  - REST API design and inter-service communication
  - Asynchronous communication with message queues
  - Containerization with Docker and Docker Compose
  - Database isolation (Database per Service)
  - Fault tolerance and Circuit Breaker (Resilience4j)

--------------------------------------------------------------------------

==========================================================================
  ROZPROSZONY SYSTEM REZERWACJI (MIKROSERWISY) — SPRING BOOT
==========================================================================

## Opis projektu

Ten projekt to kompletny system rezerwacji biletów do kina lub na pociąg,
zbudowany za pomocą Spring Boot w oparciu o architekturę mikroserwisów.

System składa się z czterech niezależnych usług komunikujących się przez
REST API lub kolejkę wiadomości (RabbitMQ / Apache Kafka):

  - User Service (Użytkownicy)
      Rejestracja, logowanie i uwierzytelnianie (JWT).

  - Catalog Service (Katalog)
      Zarządzanie filmami, pociągami, miejscami i dostępnością.

  - Payment Service (Płatności)
      Przetwarzanie transakcji, potwierdzenia płatności i zwroty.

  - Booking Service (Rezerwacje)
      Koordynacja rezerwacji i zarządzanie statusem zamówienia
      (PENDING → CONFIRMED / CANCELLED).

## Stos technologiczny

  Backend:        Spring Boot 3 (Java 21)
  Baza danych:    PostgreSQL (osobna instancja na usługę)
  Messaging:      RabbitMQ lub Apache Kafka
  Konteneryzacja: Docker + Docker Compose
  API Gateway:    Spring Cloud Gateway
  Dokumentacja:   Swagger / OpenAPI 3

## Czego się nauczyłem

  - Architektury mikroserwisów i zasady luźnego powiązania
  - Obsługi transakcji rozproszonych (wzorzec Saga)
  - Projektowania REST API i komunikacji między usługami
  - Komunikacji asynchronicznej z kolejkami wiadomości
  - Konteneryzacji za pomocą Dockera i Docker Compose
  - Izolacji baz danych (Database per Service)
  - Odporności na błędy i wzorca Circuit Breaker (Resilience4j)

==========================================================================

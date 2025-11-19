# Candidate Processor API
Sistema de Processamento de Candidatos (ATS Simulado)

Objetivo

Sistema que gerencia candidatos e vagas, simulando um ATS (Applicant Tracking System) com processamento assíncrono de candidatos.

Tecnologias

Java 17+, Spring Boot

REST API

PostgreSQL ou MySQL

Multithreading (ExecutorService / CompletableFuture)

Docker

Funcionalidades

CRUD de candidatos e vagas

Processamento assíncrono de lotes de candidatos

Logs e métricas de tempo de processamento

Testes unitários e de integração

Como rodar

Configurar o banco de dados (PostgreSQL ou MySQL)

Rodar via Maven ou Gradle:

mvn spring-boot:run

Acessar endpoints REST via Postman ou cURL

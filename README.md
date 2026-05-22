
---

## 5. `library-services-parent`

**Repository About description:**  
> Parent Maven project for business microservices (Book, Member, Order) as Git submodules.

```markdown
# Library Services Parent

## Mandatory Information

- **Student Name**: [B.K.Harsha Nimeda Sirithunga]
- **Student Number**: [2301691058]
- **Slack Handle**: [@Harsha Nimeda]
- **GCP Project ID**: [indigo-splice-491917-q2]

## Project Description

This repository is the parent Maven project for the business logic microservices of the Library Management System. It aggregates three submodules:

- `book-service` – manages book inventory (MySQL)
- `member-service` – manages library members (MongoDB)
- `order-service` – handles borrowing/returning of books (MySQL)

The parent POM manages common dependencies and versions for all three services.

## Technology Stack

- Java 25
- Spring Boot 3.4.5
- Spring Cloud 2024.0.1
- Maven
- Git Submodules

## Setup / Getting Started Instructions

### Prerequisites
- Git
- Java 25
- Maven

### Clone and Initialize Submodules

```bash
git clone https://github.com/harsha2531/library-services-parent.git
cd library-services-parent
git submodule update --init --recursive

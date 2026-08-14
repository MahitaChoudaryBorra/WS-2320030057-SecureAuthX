# SecureAuthX: A Three-Layer Authentication System

## Team Members

| Name      | ID         |
| --------- | ---------- |
| B. Ananya | 2320030071 |
| B. Mahita | 2320030057 |
| K. Bindu  | 2320030386 |

**Supervisor:** Dr. Archana Kalidindi

## Abstract

SecureAuthX is a three-layer authentication system developed to provide enhanced security for web applications using **password authentication, OTP verification, and facial recognition**. It addresses security threats such as phishing, brute-force attacks, and credential theft.

The authentication process consists of username and password verification, email-based OTP verification, and facial recognition using the user's live facial image. This combination of knowledge-based, possession-based, and biometric authentication provides stronger account security.

## Technologies Used

* **Frontend:** HTML, CSS, JavaScript
* **Backend:** Java, Spring Boot
* **Database:** posgreSQL
* **Face Recognition:** OpenCV
* **Authentication:** Email OTP (JavaMail API / SMTP)
* **Development Tools:** IntelliJ IDEA / Eclipse, Maven
* **Version Control:** Git, GitHub

## Setup and Execution

### Prerequisites

* Java
* Maven
* MySQL
* IntelliJ IDEA or Eclipse
* Git

### Setup

```bash
git clone https://github.com/MahitaChoudaryBorra/WS-2320030057-SecureAuthX.git
cd SecureAuthX
```

Configure the MySQL database and email/SMTP credentials in the Spring Boot application configuration.

### Run

```bash
mvn spring-boot:run
```

## Current Phase Status

**Phase: Planning and Design**

The project is currently in the planning and design phase. The three-layer authentication approach, technologies, and overall system requirements have been identified. Implementation will begin in the upcoming phase.

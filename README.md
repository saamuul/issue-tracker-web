# Issue Tracker

A Jakarta EE-based issue tracking application built with Java EE technologies as a project for Polytechnic Final Year Project.

## Overview

This is a multi-module enterprise Java application for managing and tracking issues. The application uses Jakarta EE components including EJB, JPA, and JSF to provide a complete issue management system.

## Tech Stack

- **Java EE / Jakarta EE**
- **GlassFish 6.1.0** - Application Server
- **Maven** - Build Tool
- **EJB** - Business Logic Layer
- **JPA** - Data Persistence
- **JSF** - Web Interface
- **PrimeFaces** - UI Components

## Project Structure

```
issue-tracker/
├── issue-tracker-web/          # Web module (JSF, Servlets)
├── issue-tracker-issue-ejb/    # Issue management EJB module
├── issue-tracker-staff-ejb/    # Staff/user management EJB module
├── issue-tracker-ear/          # Enterprise Archive (EAR)
├── IssueExtendedAssignment/    # Extended assignment module
└── extras/                     # GlassFish configuration files
```

## Getting Started

### Prerequisites

- Java 11 or higher
- Maven 3.6+
- GlassFish 6.1.0 (included in the project)

### Build

```bash
mvn clean install
```

### Deploy

1. Start GlassFish server from `glassfish-6.1.0/glassfish6/bin/`
2. Deploy the EAR file from `issue-tracker-ear/target/`

## Features

- Issue creation and tracking
- User authentication and authorization
- Role-based access control
- Tag and priority management
- Team assignment
- Dashboard and reporting

## License


This project is for educational purposes.

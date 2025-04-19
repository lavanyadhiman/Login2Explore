# Project Management Form

## Table of Contents
1. [Description](#description)
2. [Benefits of using JsonPowerDB](#benefits-of-using-jsonpowerdb)
3. [Release History](#release-history)
4. [Features](#features)
5. [Illustrations](#illustrations)
6. [How to Use](#how-to-use)
7. [Tech Stack](#tech-stack)
8. [Project Status](#project-status)
9. [Future Scope](#future-scope)

## Description
This project is a web-based Project Management Form that allows users to manage project details effectively. The form integrates with [JsonPowerDB](https://login2explore.com/jpdb/) to provide CRUD (Create, Read, Update, Delete) operations for project data. The form allows users to enter project details such as Project ID, Project Name, Assigned To, Assignment Date, and Deadline, and stores this information in the database.

View live form at https://lavanyadhiman.github.io/Login2Explore/

The form is designed with a user-friendly interface and provides real-time validation and feedback. It checks if a project ID exists in the database and enables appropriate actions based on the result.

## Benefits of using [JsonPowerDB](https://login2explore.com/jpdb/)
- **High Performance**: JsonPowerDB delivers high-performance CRUD operations with minimal development and maintenance efforts.
- **Serverless Support**: It helps in faster development of Web and Mobile applications with serverless technology.
- **Schema-free**: Being schema-free, it's easy to maintain and adapt to changing requirements.
- **Real-time Database**: JPDB is a real-time database that's easy to use with features like multi-mode database.
- **Built on PowerIndex**: One of the fastest indexing engines, PowerIndex, forms the backbone of JPDB.
- **Low Development Cost**: Reduces time to market and overall development cost.
- **Minimizes Data Processing**: Minimizes data processing with a ready-to-use API for JSON document DB.
- **Multiple Security Layers**: JPDB comes with multiple security layers including webToken-based security.
- **Serverless Support**: JPDB supports and advocates for true serverless and pluggable API development.
- **In-built Support**: Supports querying multiple databases, which makes it versatile for various applications.

## Release History
- **v0.1.0 (2025-04-20)**: Initial release with basic CRUD functionality for project management.
  - Created form with fields for Project ID, Project Name, Assigned To, Assignment Date, and Deadline.
  - Implemented functionality to save new projects and update existing ones.
  - Added validation for all form fields.
  - Integrated with [JsonPowerDB](https://login2explore.com/jpdb/).

## Features
- **Dynamic Form Behavior**: The form dynamically changes its behavior based on whether the project ID exists in the database.
- **Real-time Validation**: All fields are validated to ensure data integrity.
- **User-friendly Interface**: Clean and responsive design for better user experience.
- **CRUD Operations**: Supports creating new projects and updating existing ones.
- **Feedback System**: Visual feedback for all operations through status messages.

## Illustrations
The application follows this workflow:
1. User enters a Project ID.
2. System checks if the Project ID exists in the database.
3. If the Project ID is new:
   - All fields are enabled.
   - User enters project details.
   - User clicks **Save** to store the project.
4. If the Project ID exists:
   - The form displays existing project data.
   - User can modify project details.
   - User clicks **Update** to save changes.

## How to Use
Clone the repository  or visit https://lavanyadhiman.github.io/Login2Explore/ to view the live form

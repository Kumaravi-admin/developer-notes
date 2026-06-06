# Laravel 11 Notes [View PDF](https://github.com/Kumaravi-admin/developer-notes/blob/main/Laravel/Laravel-12%20Notes.pdf)

A comprehensive Laravel 11 & Laravel 12 learning guide covering beginner to advanced concepts with practical examples, code snippets, database structures, Eloquent relationships, authentication, authorization, API development, and real-world application workflows.

> **Note:** For a better reading experience and improved visual formatting, download and view the PDF version of these notes.

> **Note:** These notes are designed as a practical reference for developers learning Laravel from scratch or revising important concepts for professional development.

---

# Topics Covered

## Getting Started

- Laravel Installation
- Composer Setup
- XAMPP / Local Development Environment
- Project Creation
- Laravel Folder Structure
- Configuration Files

---

## Blade Templates

- Blade Syntax
- Echo Statements
- Directives
- Template Inheritance
- Layouts & Components

---

## Routing

- Basic Routes
- View Routes
- Named Routes
- Redirect Routes
- Controller Routes
- Route Groups
- Route Parameters

---

## Database & Migrations

- Creating Migrations
- Running Migrations
- Modifying Columns
- Table Alterations
- Primary Keys
- Foreign Keys
- Cascade Operations
- Dropping Constraints

---

## Database Seeding

- Creating Seeders
- Single Record Insertion
- Multiple Record Insertion
- Seeder Organization
- External Seeder Files

---

## Query Builder

- Select Queries
- Insert Operations
- Update Operations
- Delete Operations
- Pagination
- Joins
- Unions
- Conditional Queries
- Chunk Processing
- Raw SQL Queries

---

## Validation

- Form Validation
- Custom Validation Rules
- Form Request Validation
- Validation Messages
- Validation Attributes

---

## Controllers

- Basic Controllers
- Resource Controllers
- Nested Resource Controllers

---

## Eloquent ORM

### CRUD Operations

- Read Data
- Create Records
- Update Records
- Delete Records
- Advanced CRUD Methods

### Eloquent Features

- Mass Assignment
- Model Conventions
- Attribute Casting
- Hidden Attributes
- Fillable & Guarded Properties

---

## Eloquent Relationships

### One-to-One

- Read Relationship Data
- Create Relationship Data
- Inverse Relationships

### One-to-Many

- Read Related Data
- Create Related Data

### Many-to-Many

- Attach Records
- Detach Records
- Sync Relationships

### Through Relationships

- Has One Through
- Has Many Through
- Has One Of Many

### Polymorphic Relationships

- One-to-One Polymorphic
- One-to-Many Polymorphic
- One Of Many Polymorphic
- Many-to-Many Polymorphic

---

## JSON Columns

- JSON Migration Columns
- JSON Casting
- Reading JSON Data
- Updating JSON Data
- Deleting JSON Values
- JSON Query Methods

---

## Eloquent Events

- Creating Events
- Updating Events
- Deleting Events
- Retrieved Events
- Boot Methods

---

## Eloquent Observers

- Observer Classes
- Automatic Slug Generation
- Record Tracking
- Event Handling
- Observer Registration

---

## Query Scopes

### Local Scopes

- Reusable Query Conditions
- Dynamic Scopes

### Global Scopes

- Internal Global Scopes
- External Scope Classes
- Removing Global Scopes

---

## File Management

- File Upload
- Image Preview
- File Update
- File Delete
- Storage Linking
- Public Storage

---

## Authentication & Authorization

### Middleware

- Creating Middleware
- Global Middleware
- Route Middleware
- Middleware Groups
- Middleware Parameters

### Session Management

- Store Session Data
- Retrieve Session Data
- Remove Session Data

### Gates

- Authorization Gates
- Route Authorization
- Controller Authorization

### Policies

- Policy Creation
- Resource Authorization
- User Permissions

---

## Mail

- Sending Emails
- Mailable Classes
- Email Attachments
- Mail Configuration

---

## Laravel Sanctum API

- API Authentication
- User Registration API
- Login API
- Logout API
- Protected Routes
- Token Management

---

## API Testing

- Postman Setup
- API Request Testing
- Authentication Testing

---

# Requirements

- PHP 8.2+
- Composer
- MySQL / MariaDB
- Laravel 11 or Laravel 12
- XAMPP, Laragon, Herd, or Similar Local Server

---

# Quick Start

Create a new Laravel project:

```bash
composer global require laravel/installer

laravel new my-project

cd my-project

php artisan serve
```

Visit:

```text
http://127.0.0.1:8000
```

---

# Intended Audience

These notes are suitable for:

- Laravel Beginners
- PHP Developers
- Backend Developers
- Full Stack Developers
- Students Learning Laravel
- Developers Preparing for Interviews

---

# Learning Path

Recommended study order:

1. Installation & Setup
2. Blade Templates
3. Routing
4. Migrations
5. Seeders
6. Query Builder
7. Validation
8. Controllers
9. Eloquent ORM
10. Relationships
11. JSON Columns
12. Events & Observers
13. Query Scopes
14. File Uploads
15. Middleware
16. Sessions
17. Gates & Policies
18. Mail
19. Sanctum API
20. Postman Testing

---

# Features of These Notes

- Beginner Friendly
- Practical Examples
- Step-by-Step Explanations
- Database Diagrams & Tables
- Real Project Scenarios
- Laravel 11 & 12 Compatible
- Covers Most Common Interview Topics

---

# License

This repository is intended for educational and learning purposes.

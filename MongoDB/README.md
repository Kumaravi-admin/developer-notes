# MongoDB v8.0.9 Notes [View PDF](https://github.com/Kumaravi-admin/developer-notes/blob/main/MongoDB/MongoDB-v8.0.9-notes.pdf)

A comprehensive MongoDB learning guide covering beginner to advanced concepts, including CRUD operations, schema validation, aggregation pipelines, indexing, backup & restore, authentication, and performance optimization.

> **Note:** For a better reading experience and improved visual formatting, download and view the PDF version of these notes.

---

## Topics Covered

### Getting Started

- MongoDB Introduction
- MongoDB Architecture
- Installation & Setup
- MongoDB Shell (mongosh)

### Database & Collections

- Create Database
- Switch Database
- Delete Database
- Create Collections
- Rename Collections
- Drop Collections

### Documents & Data Types

- BSON Document Structure
- String
- Integer (32-bit / 64-bit)
- Boolean
- Array
- Object
- Date
- ObjectId
- Null
- Regular Expressions

### CRUD Operations

#### Create

- insertOne()
- insertMany()

#### Read

- find()
- findOne()
- Projection
- Sorting
- Limiting
- Skipping Records

#### Update

- updateOne()
- updateMany()
- replaceOne()

#### Delete

- deleteOne()
- deleteMany()

---

## JSON Schema Validation

- Collection Validation
- Required Fields
- Data Type Validation
- Range Validation
- Custom Error Messages

---

## Aggregation Pipeline

### Pipeline Stages

- $match
- $project
- $group
- $sort
- $limit
- $skip
- $lookup
- $facet
- $bucket
- $merge
- $unionWith

### String Operators

- $concat
- $split
- $replaceOne
- $replaceAll
- $substrBytes
- $substrCP
- $trim
- $ltrim
- $rtrim
- $toString

### Date Operators

- $year
- $month
- $dayOfMonth
- $dayOfWeek
- $dayOfYear
- $hour
- $minute
- $second
- $millisecond
- $dateAdd
- $dateFromString

---

## Joins

### $lookup

- One-to-One Join
- One-to-Many Join
- Multi Collection Join
- Root Document Merge

---

## Aggregation Utilities

### $facet

Run multiple aggregations in a single query.

### $bucket

Group documents into custom ranges.

---

## Collections

### Capped Collections

- Create Capped Collection
- Convert Collection to Capped
- cappedMax
- cappedSize

---

## Indexing

### Index Types

- Single Field Index
- Compound Index
- Unique Index
- Text Index
- Wildcard Index

### Index Operations

- createIndex()
- getIndexes()
- dropIndex()

### Performance Analysis

- explain()
- executionStats
- IXSCAN
- COLLSCAN
- FETCH

---

## MongoDB Database Tools

### Import

- mongoimport

### Backup

- mongodump

### Restore

- mongorestore

---

## User Management & Security

### Built-in Roles

- read
- readWrite
- dbAdmin
- userAdmin
- dbOwner
- root
- clusterAdmin
- clusterManager
- clusterMonitor

### Authentication

- Enable Authentication
- Create Users
- Assign Roles
- Login with Credentials

---

## Requirements

- MongoDB Server 8.x
- MongoDB Shell (mongosh)
- MongoDB Database Tools
- Windows, Linux, or macOS

---

## Quick Start

### Create Database

```javascript
use school
```

### Create Collection

```javascript
db.createCollection("students");
```

### Insert Document

```javascript
db.students.insertOne({
  name: "John Doe",
  age: 20,
});
```

### Read Documents

```javascript
db.students.find();
```

---

## Who These Notes Are For

- MongoDB Beginners
- Backend Developers
- Node.js Developers
- MERN Stack Developers
- Database Administrators
- Students Preparing for Interviews

---

## Learning Path

1. Installation & Setup
2. Databases & Collections
3. Documents & Data Types
4. CRUD Operations
5. Validation
6. Aggregation Pipeline
7. Joins ($lookup)
8. Indexing
9. Backup & Restore
10. Authentication & Security

---

## Features

- MongoDB 8 Compatible
- Beginner Friendly
- Real Examples
- Aggregation Pipeline Deep Dive
- Indexing & Performance Optimization
- Security & User Management
- Practical Commands & Explanations

---

## License

This repository is intended for educational and learning purposes.

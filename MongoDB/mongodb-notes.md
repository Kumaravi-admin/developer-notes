## Page 1 — MongoDB

**About MongoDB**

MongoDB is a document-oriented, operational database built from the ground up as an alternative to the relational database for modern applications. Unlike relational databases, MongoDB allows developers to store rich JSON-like documents that map naturally to the objects they use in their code.

---

## Page 2 — MongoDB : Notes Index

| Page No | Page Title                                         | Topic                                                                    |
| ------- | -------------------------------------------------- | ------------------------------------------------------------------------ |
| 1       | MongoDB : Introduction & Installation              | What is MongoDB, NoSQL, Installation, mongosh, Verify Setup              |
| 2       | Database : Command & Method                        | show dbs, use, db, dropDatabase(), db.help()                             |
| 3       | Collections : Command & Methods                    | createCollection, show collections, renameCollection, drop(), help()     |
| 4       | Insert Document                                    | insertOne, insertMany                                                    |
| 5       | MongoDB : Data Types & Date method                 | String, Double, Integer, Boolean, Array, Object, Null, ISODate, new Date |
| 6       | Validation : JSON Schema                           | collMod, $jsonSchema, bsonType, required, properties, validator          |
| 7       | Validation : JSON Schema - II                      | createCollection validator, insertOne with validation                    |
| 8       | Update Document : updateOne, updateMany            | $set, $inc, ObjectId                                                     |
| 9       | Update Document : updateOne, updateMany - II       | $mul, $unset, $rename, $currentDate                                      |
| 10      | Update Document : updateOne, updateMany - III      | $min, $max, $addToSet, $push, $pop                                       |
| 11      | Update Document : updateOne, updateMany - III      | $pop, $pull, $pullAll, replaceOne                                        |
| 12      | Update Document : deleteOne, deleteMany            | deleteOne, deleteMany, ObjectId                                          |
| 13      | Read Document : find, findOne                      | find(), findOne(), projection                                            |
| 14      | Read Document : find, findOne                      | count(), sort(), limit(), skip()                                         |
| 15      | Operators : Comparison Operators                   | $eq, $ne, $gt, $gte                                                      |
| 16      | Operators : Comparison Operators - II              | $lt, $lte, $in, $nin                                                     |
| 17      | Operators : Logic Operators                        | $and, $or, $nor, $not                                                    |
| 18      | Operators : Element Operators                      | $exists, $type                                                           |
| 19      | Operators : Evaluation Operators                   | $regex                                                                   |
| 20      | Operators : Evaluation Operators - II              | $expr, $mod                                                              |
| 21      | Operators : findOneAndUpdate                       | findOneAndUpdate, returnDocument, projection, upsert                     |
| 22      | Operators : findOneAndUpdate, Replace, Delete - II | sort, findOneAndReplace, findOneAndDelete                                |
| 23      | Aggregation Pipeline : Operators                   | $match, $count, $sortByCount, $sample                                    |
| 24      | Aggregation Pipeline : Operators - II              | $sort, $project, $skip, $limit                                           |
| 25      | Aggregation Pipeline : $group                      | $group, $sum, $count                                                     |
| 26      | Aggregation Pipeline : $group - II                 | push, $ROOT, $addToSet, $max, $min                                       |
| 27      | Aggregation Pipeline : $group - III                | $avg, $median                                                            |
| 28      | Aggregation Pipeline : $group - IV                 | $first, $top, $last, $topN                                               |
| 29      | Aggregation Pipeline : $group - V                  | $bottom, $bottomN                                                        |
| 30      | Aggregation Pipeline : $lookup                     | $lookup, $unwind                                                         |
| 31      | Aggregation Pipeline : $lookup                     | $lookup, $replaceRoot, $mergeObjects, $project                           |
| 32      | Aggregation Pipeline : $bucket                     | $bucket, $bucketAuto, output, boundaries, default                        |
| 33      | Aggregation Pipeline : $addFields Operators        | addFields, $concat, $REMOVE, $ifNull                                     |
| 34      | Aggregation Pipeline : $addFields Operators - II   | $cond, $match, custom field, if-else                                     |
| 35      | Aggregation Pipeline : $addFields, $unwind - III   | $concatArrays, $sum, $unwind                                             |
| 36      | Aggregation Pipeline : $out Operators              | $out                                                                     |
| 37      | Aggregation Pipeline : merge, $unionWith           | $merge, $unionWith                                                       |
| 38      | Aggregation Pipeline : $facet Operators            | $facet, parallel pipelines                                               |
| 39      | Aggregation Pipeline : $fill Operators             | $fill, value, locf, linear, partitionBy, sortBy                          |

---

## Page 3 — MongoDB : Notes Index (continued)

| Page No | Page Title                                        | Topic                                                                                                      |
| ------- | ------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- |
| 40      | Aggregation Pipeline : Arithmetic Operators       | $add, $subtract, $multiply, $divide                                                                        |
| 41      | Aggregation Pipeline : Arithmetic Operators - II  | $mod, $pow, $sqrt, $ceil, $floor                                                                           |
| 42      | Aggregation Pipeline : Arithmetic Operators - III | $round, $trunc                                                                                             |
| 43      | Aggregation Pipeline : String Operators           | $toUpper, $toLower, $strLenBytes                                                                           |
| 44      | Aggregation Pipeline : String Operators - II      | $strLenCP, $strcasecmp, $substrBytes, $substrCP                                                            |
| 45      | Aggregation Pipeline : String Operators - III     | $replaceOne, $replaceAll, $split, $concat                                                                  |
| 46      | Aggregation Pipeline : String Operators - IV      | $toLower, $ltrim, $rtrim, $trim, $dateFromString                                                           |
| 47      | Aggregation Pipeline : String Operators - V       | $dateToString, $indexOfBytes, $indexOfCP                                                                   |
| 48      | Aggregation Pipeline : String Operators - VI      | $regexMatch, $regexFind, $regexFindAll                                                                     |
| 49      | Aggregation Pipeline : Date Operators             | Date Format Specifiers (%d, %Y, %H, %m, %M, %S, %L)                                                        |
| 50      | Aggregation Pipeline : Date Operators - II        | $year, $month, $week, $dayOfMonth, $dayOfWeek, $dayOfYear, $hour, $minute, $second, $millisecond, $dateAdd |
| 51      | Aggregation Pipeline : Date Operators - III       | $dateSubtract, $dateDiff, $dateFromParts                                                                   |
| 52      | Aggregation Pipeline : Date Operators - IV        | $dateToParts, $dateTrunc, $dateToString                                                                    |
| 53      | Aggregation Pipeline : Date Operators - V         | $toDate, $isoDayOfWeek, $isoWeek, $isoWeekYear                                                             |
| 54      | Aggregation Pipeline : Array Operators            | Collection Setup (students, students2–6)                                                                   |
| 55      | Aggregation Pipeline : Array Operators - II       | $arrayElemAt, $firstN, $lastN                                                                              |
| 56      | Aggregation Pipeline : Array Operators - III      | $maxN, $minN, $slice                                                                                       |
| 57      | Aggregation Pipeline : Array Operators - IV       | $sortArray, $reverseArray, $size                                                                           |
| 58      | Aggregation Pipeline : Array Operators - V        | $in, $indexOfArray, $isArray                                                                               |
| 59      | Aggregation Pipeline : Array Operators - VI       | $map, $filter                                                                                              |
| 60      | Aggregation Pipeline : Array Operators - VII      | $reduce, $range                                                                                            |
| 61      | Aggregation Pipeline : Array Operators - VIII     | $concatArrays, $zip, $arrayToObject, $objectToArray                                                        |
| 62      | Aggregation Pipeline : Type Operators             | $toString, $toInt                                                                                          |
| 63      | Aggregation Pipeline : Type Operators - II        | $toLong, $toDouble, $toDecimal, $type                                                                      |
| 64      | Aggregation Pipeline : Type Operators - III       | $toBool, $toObjectId, $convert, $isNumber                                                                  |
| 65      | Aggregation Pipeline : Conditional Operators      | $cond, if-then-else                                                                                        |
| 66      | Aggregation Pipeline : Conditional Operators - II | $ifNull, $switch, branches, default                                                                        |
| 67      | Aggregation Pipeline : Capped Collection          | capped, isCapped, convertToCapped, cappedMax, cappedSize                                                   |
| 68      | Indexing : Create, Get, Drop Indexes              | createIndex, getIndexes, explain, dropIndex, IXSCAN, COLLSCAN                                              |
| 69      | Indexing : Create, Get, Drop Indexes - II         | Single Index, Compound Index, Unique Index                                                                 |
| 70      | Indexing : Create, Get, Drop Indexes - III        | Text Index, Wildcard Index                                                                                 |
| 71      | MongoDatabase Tool                                | mongoimport, mongodump, mongorestore                                                                       |
| 72      | User Management : Built-in Roles                  | read, readWrite, dbAdmin, userAdmin, dbOwner, root, clusterAdmin                                           |
| 73      | User Management : Enable Authentication           | mongod.cfg, authorization, services.msc                                                                    |
| 74      | User Management : Authentication - Create Users   | Create Admin User, Create Developer user                                                                   |
| 75      | User Management : Authentication - Get Users      | Get all user details, Get single user details                                                              |
| 76      | User Management : Authentication - Update Users   | Update user Details, Update user Password                                                                  |
| 77      | User Management : Authentication - Delete Users   | Drop Single user, Drop all users                                                                           |
| 78      | User Management : Authentication – Grant Roles    | Grant role to user, Revoke role from user                                                                  |

---

## Page 4 — MongoDB : Introduction & Installation

### What is : MongoDB

MongoDB is a **NoSQL database** that stores data not in tables and rows, but in **documents** (JSON-like format). It is an open-source, cross-platform database that is highly flexible and scalable. Unlike traditional SQL databases where you must define a schema first, MongoDB has no such restriction — you can change your data structure anytime. Its name comes from "Humongous" — meaning very large — because it was built to handle massive amounts of data

**Key Points**

- Data is stored in **documents** (BSON format — Binary JSON)
- Documents live inside **collections** (similar to SQL tables)
- **Schema-less** — each document can have a different structure
- Very **fast read/write** — especially for unstructured data
- **Horizontally scalable** — add more servers as data grows
- Powerful **query language** — filter, sort, aggregate all supported
- **MongoDB Atlas** — cloud version available (free tier included)

**Use Case / Example**

- 🛒 E-Commerce — Products, orders, user profiles
- 📱 Mobile Apps — User data, notifications, activity logs
- 🖥 Content Management — Blogs, articles, media metadata
- 🎮 Gaming — Player stats, leaderboards, game state
- ⚡ Real-time Apps — Chat apps, live dashboards
- 📊 Big Data — Logs, analytics, IoT sensor data

---

### Step 1 : Download MongoDB Server

- Version: 8.0.9 (Current)
- Platform: Windows
- Package: MSI
- During install → keep "Install MongoDB as a Service" ✔ checked

1. https://www.mongodb.com/try/download/community

---

### Step 2 : Download mongosh (MongoDB Shell)

Mongosh is installed separately from the server, Download → Install → Path is set automatically

2. https://www.mongodb.com/try/download/shell

---

### Step 3 : Verify Installation

Open CMD (command prompt) and run this command to verify the installation setup

3. `mongosh`

If everything is set up correctly, you will see:

```bash
C:\Users\Hp>mongosh
Current Mongosh Log ID: 6a130e52acaa0005396c4bcf
Connecting to:    mongodb://127.0.0.1:27017/?directConnection=true
Using MongoDB:    8.0.9
Using Mongosh:    2.5.1

test>
```

---

## Page 5 — Database : Command & Method

### Database : Show

This command show all database (with name and size in mongosh shell command tool)

```js
show dbs
```

### Database : Create

This command use create new database or inter if database already exist, use to switch database

```js
use school
```

### Database : Current

This command show currently you in which database, return name of database

```js
db;
```

### Database : Delete

This command delete database currently you use, and return response like : { ok: 1, dropped: 'school' }

```js
db.dropDatabase();
```

### Command : Help

This command show all command related to db

```js
db.help();
```

---

## Page 6 — Collections : Command & Methods

### Collection : Create

This command create new collection name students return response

```js
db.createCollection("students");
```

### Collection : Show

This command return all collection in database

```js
show collections
```

### Collection : Rename

This command rename the collection and return response {ok:1}, example : db.old_name.renameCollection("new_name")

```js
db.students.renameCollection("student");
```

### Collection : Delete

This command delete the collection return response { ok: 1 }, example : db.collectionName.drop()

```js
db.student.drop();
```

### Collection : Help

This command show all command related to collection example db.collectionName.help()

```js
db.student.help();
```

---

## Page 7 — Insert Document : Insert Document

### Insert : One

It inserts a new document into the students collection, name: "Anjesh Kumar" age: 25 class: "None"

```js
db.students.insertOne({ name: "Anjesh Kumar", age: 25, class: "None" });
```

### Insert : Many

It inserts multiple documents (3 in this case) into the students collection at once.
Each document represents a student with name, age, and class fields.
Each will get a unique \_id automatically generated by MongoDB.

```js
db.students.insertMany([
  { name: "Anjesh Kumar", age: 25, class: "None" },
  { name: "Ankit  Kumar", age: 25, class: "None" },
  { name: "Aniket Kumar", age: 10, class: "None" },
]);
```

---

## Page 8 — MongoDB : Data Types & Date method

### Data : Types

This is all available data types in MongoDB

**MongoDB Data Types Listed:**

- String
- Double
- 32-bit Integer (int)
- 64-bit Integer (int)
- Boolean (bool)
- Array
- Object
- Null
- Regular Expression (highlighted in red)
- Timestamp (highlighted in red)
- Date
- ObjectId

```js
{
  name: "Yahoo Baba",
  age: 25,
  married: false,
  dob: ISODate("2000-10-15T08:00:00Z"),
  weight: 72.50,
  kids: null,
  hobbies: ["music", "sports"],
  address: {
    street: "123 Main St",
    city: "New York",
    zip: 10001
  }
}
```

### 32 bit : Integer

Uses 32 bits (4 bytes) of memory to store the integer value.

```
-2,147,483,648  to  2,147,483,647
```

### 64 bit : Integer

Uses 64 bits (8 bytes) of memory to store the integer value.

```
-9,223,372,036,854,775,808  to  9,223,372,036,854,775,807
```

### Date : ISODate

This method use for save date and time, z stand for Coordinate Universal Time, without z then its will a local time zone

```js
{
  dob: ISODate("2000-10-15T08:00:00Z");
}
```

### Date : new Date

This is second method use for save date and time, z stand for Coordinate Universal Time, without z then its will a local time zone

```js
{
  dob: new Date("2000-10-15T08:00:00Z");
}
```

### Date : Current Date

This method save current time

```js
{
  date: new Date();
}
```

---

## Page 9 — Validation : JSON Schema

### Validation Shema : For existing collection

If you wont to add validation schema in existing collection follow this complete example (make collection name personal)

```js
db.runCommand({
  collMod: "personal", //collection name which one you wont add validation
  validator: {
    $jsonSchema: {
      required: ["name", "age", "married", "dob", "weight", "kids", "address"],
      properties: {
        //add property's and validation rule & fails message
        name: {
          bsonType: "string", //string type
          description: "Name must be a string and is required", // fails message
        },
        age: {
          bsonType: "int", //integer type
          minimum: 20,
          maximum: 35,
          description: "Age must be an integer between 20 and 35 is reiquired",
        },
        married: {
          bsonType: "bool", //Boolean type
          description: "Married must be boolean (trune/false)", // fails message
        },
        dob: {
          bsonType: "date", //date type
          description: "DOB must be an date", // fails message
        },
        weight: {
          bsonType: "double", //double or float type
          description: "Weight must be an duble.", // fails message
        },
        kids: {
          bsonType: "int", //integer type
          description: "Kids must be an integer and is required", // fails message
        },
        hobbies: {
          bsonType: "array", //array type
          items: {
            bsonType: "string", //array items data types
          },
          description: "Hobbies must be an array of strings ", // fails message
        },
        address: {
          bsonType: "object", //object type
          required: ["street", "city", "zip"], //object require property's
          properties: {
            street: {
              //object property data type
              bsonType: "string",
              description: "Street must be a string and is required", // fails message
            },
            city: {
              bsonType: "string",
              description: "City must be a string and is required", // fails message
            },
            zip: {
              bsonType: "int",
              description: "Zip must be a int and is required", // fails message
            },
          },
        },
      },
    },
  },
}); // fails message show when validation fails
```

---

## Page 10 — Validation : JSON Schema - II

### Validation Schema : For New Collection

Create new collection and define validation schema

```js
db.createCollection("students", {
  // Main validator object
  validator: {
    $jsonSchema: {
      title: "Student Object validation", // Title show when validation fails
      required: ["name", "age", "course"], // Define all require filed here

      // Define validation rule for all filed in properties object
      properties: {
        name: {
          bsonType: "string", // define type in bsonType properties
          description: "must be a string and is required",
        }, // msg show when validation false (description show when validation false
        age: {
          bsonType: "int", // filed type int = integer
          minimum: 5,
          maximum: 20,
          description: "age must be an integer in [5, 20] and is required",
        },
        course: {
          bsonType: "string",
          enum: ["BCA", "BBA", "BSc", "MCA", "MBA"], // pre-define values in enum array
          description: "course must be a string and is required",
        },
      },
    },
  },
});
```

### Insert : Data

Let's insert data in student collection with correct data type, but when you pass wrong datatype in any filed that throw a error

```js
db.students.insertOne({
  name: "Anjesh Kumar",
  age: 19,
  course: "BCA",
});
```

### Insert : Data

Let's insert data in personal collection with correct data type, but when you pass wrong datatype in any filed that throw a error

```js
db.personal.insertOne({
  name: 22,
  age: 30,
  married: true,
  dob: new Date("1993-05-15"),
  weight: 70.5,
  kids: 2,
  hobbies: ["reading", "traveling"],
  address: {
    street: "123 Main St",
    city: "Delhi",
    zip: 12345,
  },
});
```

---

## Page 11 — Update Document : updateOne, updateMany

### Collection : For Testing Query's

Create a Collection name students for testing updateOne, updateMany Method & Operators

```js
db.students.insertMany([
  { name: "Anjesh Kumar", age: 22, class: "Btech", skills: ["HTML", "PHP"] },
  { name: "Ashito Kumar", age: 20, class: "Btech", skills: ["React", "Js"] },
  { name: "Aniket Kumar", age: 17, class: "Mtech", skills: ["Mongo", "SQL"] },
]);
```

### Operator : $set

Searches for the first document where name is "Anjesh Kumar", Updates the name to "Anjesh" and age to 17

```js
db.students.updateOne(
  { name: "Anjesh Kumar" }, //find the document
  {
    $set: {
      age: 17,
      name: "Anjesh", //update new value
    },
  },
);
```

### Operator : $set

Finds the document with the exact \_id, Updates (or adds) the field class and sets it to "M.tech"

```js
db.students.updateOne(
  { _id: ObjectId("68410ffa1c5b77ca826c4be6") }, // find by id
  {
    $set: {
      class: "M.tech", //update new value to class field
    },
  },
);
```

### Operator : $inc

Finds the first document where name is "Aniket Kumar", Increases the value of the age field by 1

```js
db.students.updateOne(
  { name: "Aniket Kumar" },
  {
    $inc: {
      age: 1, // Increment the age of the student by 1
    },
  },
);
```

### Operator : $inc

Finds the first document where name is "Aniket Kumar", Decrements the age field by 1 using $inc: { age: -1 }

```js
db.students.updateOne(
  { name: "Aniket Kumar" },
  {
    $inc: {
      age: -1, // Decrements the age of the student by 1
    },
  },
);
```

---

## Page 12 — Update Document : updateOne, updateMany - II

### Operator : $mul

Finds the first document where name is "Anjesh", Multiplies the age field by 2 using the $mul operator

```js
db.students.updateOne(
  { name: "Anjesh" },
  {
    $mul: {
      age: 2, // Multiply the age of the student by 2
    },
  },
);
```

### Operator : $unset

Remove the field using $unset operator

```js
db.students.updateOne(
  { name: "Anjesh" },
  {
    $unset: {
      age: "", // Remove the age field from the document
    },
  },
);
```

### Operator : $rename

Rename the field name using $rename operator (using updateOne you can rename only one document)

```js
db.students.updateOne(
  { name: "Anjesh" },
  {
    $rename: {
      skills: "coding_skills", // Rename the skills field to coding_skills
    },
  },
);
```

### Operator : $rename

Rename the filed name for all document in collection using updateMany for update all document in collection

```js
db.students.updateMany(
  {}, //empty object for run operator for all document
  {
    $rename: {
      skills: "coding_skills", // Rename the skills field to coding_skills
    },
  },
);
```

### Operator : $currentDate

Set the current date to all field, if field not exit then this will create the field and add current date, using updateMany

```js
db.students.updateMany(
  {}, //empty object for run operator for all document
  {
    $currentDate: {
      lastModified: true, //field name and value true for add current date
    },
  },
);
```

---

## Page 13 — Update Document : updateOne, updateMany - III

### Operator : $min

Update the minimum value to filed (if filed value less then update value then that value update to document)

```js
db.students.updateOne(
  { name: "Ashito Kumar" },
  {
    $min: {
      age: 18, // Set the minimum age to 18, if the current age is less than 18
    },
  },
);
```

### Operator : $max

Update the Max value to filed (if filed value greater then update value then that value update to document)

```js
db.students.updateOne(
  { name: "Ashito Kumar" },
  {
    $max: {
      age: 25, // Set the maximum age to 25, if the current age is greater than 25
    },
  },
);
```

### Array Operator : $push

Finds the document where name is "Aniket Kumar", Adds "Python" to the coding_skills array using $push.

```js
db.students.updateOne(
  { name: "Aniket Kumar" },
  {
    $push: {
      coding_skills: "Python", // Add "Python" to the coding_skills array
    },
  },
);
```

### Array Operator : $addToSet

Finds the student where name is "Aniket Kumar", Adds "Java" to the coding_skills array only if it's not already present.

```js
db.students.updateOne(
  { name: "Aniket Kumar" },
  {
    $addToSet: {
      coding_skills: "Java", // Add "Java" to the coding_skills array only if it does not already exist
    },
  },
);
```

### Array Operator : $pop

This query will remove the last element from the coding_skills array for the document where the name is "Aniket Kumar".

```js
db.students.updateOne(
  { name: "Aniket Kumar" },
  {
    $pop: {
      coding_skills: 1, // Set 1 for Remove the last value from the coding_skills
    },
    array,
  },
);
```

---

## Page 14 — Update Document : updateOne, updateMany - III

### Array Operator : $pop

This query will remove the first element from the coding_skills array for the document where the name is "Aniket Kumar".

```js
db.students.updateOne(
  { name: "Aniket Kumar" },
  {
    $pop: {
      coding_skills: -1, // Remove the first value from the coding_skills array
    },
  },
);
```

### Array Operator : $pull

Using this operator you can remove specific value from array (but you can only one value find and remove)

```js
db.students.updateOne(
  { name: "Ashito Kumar" },
  {
    $pull: {
      coding_skills: "Js", // Remove "Js" from the coding_skills array
    },
  },
);
```

### Array Operator : $pullAll

Using this operator you can remove multiple specific value form array

```js
db.students.updateOne(
  { name: "Aniket Kumar" },
  {
    $pullAll: {
      coding_skills: ["SQL", "Python"], // Remove multiple value from the
    },                                                coding_skills array
  }
);
```

### Method : replaceOne

Using this Method You can find and replace document values

```js
db.students.replaceOne(
  {
    _id: ObjectId("684114511c5b77ca826c4be7"), //Replace the document with specific
  },                                                                       object id
  {
    name: "Anjesh Kumar",
    age: 18,
    class: "Btech",
    coding_skills: ["Mongo", "SQL", "Python"],
  }
);
```

---

## Page 15 — Update Document : deleteOne, deleteMany

### Collection : For Testing Query's

Create a Collection name students for testing deleteOne, deleteMany Method

```js
db.students.insertMany([
  { name: "Anjesh Kumar", age: 22, class: "Btech", skills: ["HTML", "PHP"] },
  { name: "Ashito Kumar", age: 20, class: "Btech", skills: ["React", "Js"] },
  { name: "Aniket Kumar", age: 17, class: "Mtech", skills: ["Mongo", "SQL"] },
]);
```

### Method : deleteOne

deleteOne() removes only the first matching document based on the given filter.

```js
db.students.deleteOne({
  name: "Anjesh Kumar", // Delete the first document with name "Anjesh Kumar"
});

db.students.deleteOne({
  age: 17, // Delete the first document with age 17
});
```

### Method : deleteOne

Deletes one document from the students collection whose \_id exactly matches

```js
db.students.deleteOne({
  _id: ObjectId("684114511c5b77ca826c4be8"), //Delete the document with the by ObjectId
});
```

### Method : deleteMany

This query deletes all documents from the students collection where the class field is exactly "Btech".

```js
db.students.deleteMany({
  class: "Btech", // Delete all documents with class "Btech"
});
```

### Method : deleteMany

This deletes all documents from the students collection — entire data wipe, but does not delete the collection itself.

```js
db.students.deleteMany({}); // Delete all documents in the collection
```

---

## Page 16 — Read Document : find, findOne

### Collection : For Testing Query's

Create a Collection name students for testing find(), findOne() method

```js
db.students.insertMany([
  { name: "Anjesh Kumar", age: 22, class: "Mtech", city: "Delhi" },
  { name: "Ashito Kumar", age: 22, class: "Btech", city: "Mumbai" },
  { name: "Aniket Kumar", age: 20, class: "Btech", city: "Delhi" },
  { name: "Zubair Ahmad", age: 18, class: "Mtech", city: "Kolkata" },
  { name: "Rajvir Kumar", age: 11, class: "Btech", city: "Bihar" },
]);
```

### Read Data : find

Each .find() returns a cursor (list of matching documents) from the students collection in the current MongoDB database.

```js
db.students.find({
  class: "Btech", // find all students where class = Btech
});

db.students.find({
  age: 20, // find all students where age = 20
});

db.students.find({
  city: "Delhi", // find all students where city = Delhi
});
```

### Read Data : findOne

This code is using db.students.findOne() — which returns only the first matching document from the students collection.

```js
db.students.findOne({
  city: "Delhi", // find first one student in Delhi
});

db.students.findOne({
  class: "Btech", // find first one student in Btech
});
```

### Read Data : findOne with projection

It returns all students, but only shows name and age for each — no \_id

```js
db.students.find().projection({
  name: 1, // projection to include name
  age: 1,
  _id: 0,
});
```

### Read Data : findOne with projection

Finds all students in class "Btech" Displays only name and age Hides the \_id field (which is included by default)

```js
db.students.find(
  {
    class: "Btech", // find all students in Btech
  },
  {
    name: 1, // projection to include name
    age: 1,
    _id: 0,
  },
);
```

---

## Page 17 — Read Document : find, findOne

### Method : count

This returns the total number of documents (students) in the students collection.

```js
db.students.find().count(); // Return total count of all students
```

### Count : with filter

This returns the total number of students in class "Btech".

```js
db.students
  .find({
    class: "Btech", // Return total count of all students in Btec
  })
  .count();
```

### Read data in ascending Order : sort

Returns all students Sorted by the city field in ascending (A–Z) order

```js
db.students.find().sort({
  city: 1, // sort by city in ascending order
});
```

### Read data in descending : sort

Returns all student documents Sorts them by age in descending order (from oldest to youngest)

```js
db.students.find().sort({
  age: -1, // sort by age in descending order
});
```

### Read data in ascending order with filter : sort

Returns all students Shows only their name and city Sorts them by age from youngest to oldest

```js
db.students.find({}, { name: 1, city: 1, _id: 0 }).sort({
  age: 1, // sort by age in ascending order
});
```

### Read limited data : limit

Returns only the first 2 documents from the students collection Based on the default insertion order, unless combined with .sort()

```js
db.students.find().limit(2); // Limit the result to 2 documents
```

### Read limited data : limit

limit(n) to restrict how many results are returned .skip(n) to skip a certain number of documents Together, they enable pagination

```js
db.students.find().limit(2).skip(0);
// Skip the first 0 documents and limit the result to 2 documents

db.students.find().limit(2).skip(2);
// Skip the first 2 documents and limit the result to 2 documents

db.students.find().limit(2).skip(4);
// Skip the first 4 documents and limit the result to 2 documents
```

---

## Page 18 — Operators : Comparison Operators

### Collection : For Testing Query

Create a Collection name students for testing Comparison Operators

```js
db.students.insertMany([
  { name: "Anjesh Kumar", age: 22, class: "Mtech", city: "Delhi" },
  { name: "Ashito Kumar", age: 22, class: "Btech", city: "Mumbai" },
  { name: "Aniket Kumar", age: 20, class: "Btech", city: "Delhi" },
  { name: "Zubair Ahmad", age: 18, class: "Mtech", city: "Kolkata" },
  { name: "Rajvir Kumar", age: 11, class: "Btech", city: "Bihar" },
]);
```

### Equal : $eq

This query finds all documents in the students collection where the age field is exactly equal to 20.

```js
db.students.find({
  age: { $eq: 20 }, //Values are equal
});
```

### Shorthand of : $eq

You can also write this more simply, Both are functionally the same

```js
db.students.find({ age: 20 }); //Values are equal
```

### Not Equal : $ne

This query will return all documents in the students collection where the age is not equal to 20.

```js
db.students.find({
  age: { $ne: 20 }, // Values are not equal
});
```

### Greater Than : $gt

This query fetches all documents from the students collection where the age is greater than 20. (work only with numeric filed)

```js
db.students.find({
  age: { $gt: 20 }, // Value is greater than
});
```

### Greater Than or equal : $gte

This will return all documents in the students collection where age is greater than or equal to 20. (work only with numeric filed)

```js
db.students.find({
  age: { $gte: 20 }, // Value is greater than or equal t
});
```

---

## Page 19 — Operators : Comparison Operators - II

### Less than : $lt

This query returns all documents in the students collection where age is less than 20. (work only with numeric filed)

```js
db.students.find({
  age: { $lt: 20 }, // value is less than another value
});
```

### Less than or equal : $lte

This retrieves all documents in the students collection where the age is less than or equal to 20. (work only with numeric filed)

```js
db.students.find({
  age: { $lte: 20 }, // values is less than or equal to another value
});
```

### In Array : $in

This query returns all documents from the students collection where the age is either 20, 18, or 17.

```js
db.students.find({
  age: { $in: [20, 18, 17] }, // Value is matched within an array
});
```

### Not In Array : $in

This query returns all documents in the students collection where the age is not 20, 18, or 17.

```js
db.students.find({
  age: { $nin: [20, 18, 17] }, // value is not in the array
});
```

### Example in updateMany method : $lte

all student documents where age < 20, those documents by setting a new (or replacing existing) field class with "12th"

```js
db.students.updateMany(
  {
    age: { $lt: 20 }, // Update all students with age less than 20
  },
  {
    $set: {
      class: "12th", // Set class to "12th" for students with age less than 20
    },
  },
);
```

### Example in deleteMany : $lte

This query deletes all student documents from the students collection where the age is less than 20.

```js
db.students.deleteMany({
  age: { $lt: 20 }, // Delete all students with age less than 20
});
```

---

## Page 20 — Operators : Logic Operators

### Collection : For Testing Query

Create a Collection name students for testing Logic Operators

```js
db.students.insertMany([
  { name: "Anjesh Kumar", age: 22, class: "Mtech", city: "Delhi" },
  { name: "Ashito Kumar", age: 22, class: "Btech", city: "Mumbai" },
  { name: "Aniket Kumar", age: 20, class: "Btech", city: "Delhi" },
  { name: "Zubair Ahmad", age: 18, class: "Mtech", city: "Kolkata" },
  { name: "Rajvir Kumar", age: 11, class: "Btech", city: "Bihar" },
]);
```

### Operator : $and

Returns documents where all conditions matches

```js
db.students.find({
  $and: [{ age: { $gt: 20 } }, { age: { $lt: 23 } }],
}); // Find students with age greater than 20 and less than 23

db.students.find({
  $and: [{ age: { $gt: 20 } }, { city: { $eq: "Delhi" } }],
}); // Find students with age greater than 20 and city equal to Delhi
```

### Operator : $or

Returns documents where all or any single condition matches

```js
db.students.find({
  $or: [{ age: { $gt: 20 } }, { city: { $eq: "Delhi" } }],
}); // Find students with age greater than 20 or city equal to Delhi
```

### Operator : $nor

Returns documents where both conditions fails or not matches

```js
db.students.find({
  $nor: [{ age: { $gt: 20 } }, { city: { $eq: "Delhi" } }],
}); // Find students where age is not greater than 20 and city is not equal to Delhi
```

### Operator : $not

Returns documents where the condition does not match

```js
db.students.find({
  age: { $not: { $gt: 20 } },
}); // Find students where age is not greater than 20
```

### $and : with deleteMany

Returns documents where the condition does not match

```js
db.students.deleteMany({
  $and: [{ age: { $gt: 20 } }, { city: { $eq: "Delhi" } }],
}); // Delete students with age greater than 20 and city equal to Delhi
```

## Page 21 — Operators : Element Operators

### Collection : For Testing Query

Create a Collection name students for testing Element Operators

```js
db.students.insertMany([
  { name: "Anjesh Kumar", age: 22, class: "Mtech", city: "Delhi" },
  { name: "Ashito Kumar", age: 22.5, class: "Btech", city: "Mumbai" },
  { name: "Aniket Kumar", age: "20", class: "Btech", city: "Delhi" },
  { name: "Zubair Ahmad", age: 18, city: "Kolkata" },
  { name: "Rajvir Kumar", age: 11, city: "Bihar" },
]);
```

### Operator : $exists

Returns documents where the field exists or not

```js
db.students.find({
  class: { $exists: true },
}); // Find students where class field exists
```

### Operator : $type

Returns documents where the field is of a specific type (example for string type)

```js
db.students.find({
  age: { $type: "string" },
}); // Find students where age field is of type string
```

### Operator : $type

Returns documents where the field is of a specific type (example for Integer type)

```js
db.students.find({
  age: { $type: "int" },
}); // Find students where age field is of type int
```

### Operator : $type

Returns documents where the field is of a specific type (example for double type)

```js
db.students.find({
  age: { $type: "double" },
}); // Find students where age field is of type double
```

### Operator : $type

Returns documents where the field is of a specific type (example for match multiple data types)

```js
db.students.find({
  age: { $type: ["int", "double"] },
}); // Find students where age field is of type int or double
```

---

## Page 22 — Operators : Evaluation Operators

### Collection : For Testing Query

Create a Collection name students for testing Evaluation Operators

```js
db.students.insertMany([
  { name: "Anjesh Kumar", age: 22, class: "Mtech", city: "Delhi" },
  { name: "Ashito Kumar", age: 22, class: "Btech", city: "Mumbai" },
  { name: "Aniket Kumar", age: 20, class: "Btech", city: "Delhi" },
  { name: "Zubair Ahmad", age: 18, class: "Mtech", city: "Kolkata" },
  { name: "Rajvir Kumar", age: 11, class: "Btech", city: "Bihar" },
]);
```

### Operator : $regex

Returns documents where the field matches the regex pattern

```js
db.students.find({
  name: { $regex: "Kumar" }, // Find students where name contains "Kumar"
});
```

### Operator : $regex

Returns documents where the field matches the regex pattern

```js
db.students.find({
  name: { $regex: /kumar/i }, // Find students where name contains "kumar" case
});
insensitive;
```

### Operator : $regex

Returns documents where the field matches the regex pattern

```js
db.students.find({
  name: { $regex: "An" }, // Find students where name starts with "An"
});
```

### Operator : $regex

Returns documents where the field matches the regex pattern

```js
db.students.find({
  name: { $regex: "^A" }, // Find students where name starts with "A"
});
```

### Operator : $regex

Returns documents where the field matches the regex pattern

```js
db.students.find({
  name: { $regex: "ad$" }, // Find students where name ends with "ad"
});
```

---

## Page 23 — Operators : Evaluation Operators-II

### Collection : For Testing Query

Create a Collection name monthlyBudget & sales for testing Evaluation Operators

```js
db.monthlyBudget.insertMany([
  { _id: 1, category: "food", budget: 400, spent: 450 },
  { _id: 2, category: "drink", budget: 100, spent: 150 },
  { _id: 3, category: "clothes", budget: 100, spent: 50 },
  { _id: 4, category: "misc", budget: 500, spent: 300 },
  { _id: 5, category: "travel", budget: 200, spent: 650 },
]);

db.sales.insertMany([
  { _id: 1, product: "apple iPhone 13", cost: 800, price: 1000 },
  { _id: 2, product: "Samsung Galaxy S21", cost: 700, price: 950 },
  { _id: 3, product: "Apple Watch", cost: 300, price: 350 },
]);
```

### Operator : $expr

Allows field comparison using within document

```js
// Find documents where spent is greater than budget
db.monthlyBudget.find({
  $expr: { $gt: ["$spent", "$budget"] },
});
```

### Operator : $expr

Allows field comparison using within document

```js
// Find documents where price is greater than cost multiplied by 1.2
db.sales.find({
  $expr: { $gt: ["$price", { $multiply: ["$cost", 1.2] }] },
});
```

### Operator : $mod

Matches numbers base on remainder

```js
db.sales.find({
  cost: { $mod: [7, 0] }, // Find documents where cost is divisible by 7
});
```

### Operator : $mod

Matches numbers base on remainder

```js
db.sales.find({
  cost: { $mod: [7.0, 0] }, // Find documents where cost is divisible by 7.0
});
```

### Operator : $mod

Matches numbers base on remainder

```js
db.sales.find({
  cost: { $mod: [-7, -0] }, // Find documents where cost is divisible by -7
});
```

---

## Page 24 — Operators : findOneAndUpdate

### Collection : For Testing Query

Create a Collection name students for testing findOneAndUpdate, findOneAndDelete, findOneAndReplace

```js
db.students.insertMany([
  { _id: 1, name: "Akshay Kumar", age: 23, class: "BCA" },
  { _id: 2, name: "Salman Khan", age: 24, class: "Btech" },
  { _id: 3, name: "Shahid Kapoor", age: 20, class: "BSc" },
  { _id: 4, name: "John Abraham", age: 19, class: "BCA" },
  { _id: 5, name: "Amir Khan", age: 24, class: "Btech" },
  { _id: 6, name: "Salman Khan", age: 21, class: "BSc" },
  { _id: 7, name: "Suniel Shetty", age: 22, class: "BCA" },
  { _id: 8, name: "Kartik Aryan", age: 20, class: "Btech" },
]);
```

### Find and Update : findOneAndUpdate

Return inundate document and update the document

```js
db.students.findOneAndUpdate({ name: "Kartik Aryan" }, { $set: { age: 30 } });
```

### Update With : returnDocument

Update the Document and Return updated document

```js
db.students.findOneAndUpdate(
  { name: "Kartik Aryan" },
  { $set: { age: 20 } },
  { returnDocument: "after" }, // return updated document
);
```

### Update With : projection

Update the Document and Return update document with projection (which filed you wont to see)

```js
db.students.findOneAndUpdate(
  { name: "Kartik Aryan" }, // filter
  { $set: { age: 30 } }, // update document
  {
    returnDocument: "after", // return updated document
    projection: { name: 1, age: 1, _id: 0 }, // projection
  },
);
```

### Update : findOneAndUpdate

When filter not find any matched then return null

```js
db.students.findOneAndUpdate(
  { name: "Anjeeeesh Kumar" }, // filter
  { $set: { age: 30 } }, // update document
  { returnDocument: "after" }, // return updated document
);
```

---

## Page 25 — Operators : findOneAndUpdate, Replace, Delete- II

### Update With : upsert

When filter not find any matched then add new document and return the new document

```js
db.students.findOneAndUpdate(
  { name: "Anjesh Kumar" }, // filter
  { $set: { age: 30 } }, // update document
  {
    returnDocument: "after", // return updated document
    projection: { name: 1, age: 1, _id: 0 }, // projection
    upsert: true, // if filter not find any matched then add new document
  },
);
```

### Update With : short

Sort the document ascending order before update, update the first document and return the updated document

```js
db.students.findOneAndUpdate(
  { name: "Salman Khan" },
  { $set: { class: "BTT" } },
  {
    sort: { age: 1 }, // sort by age in ascending order
  },
);
```

### Replace : findOneAndReplace

Replace the document first matched and return the updated document

```js
db.students.findOneAndReplace(
  { name: "Akshay Kumar" }, // filter
  { name: "Sanjay Dutt", age: 35, class: "BCom" },
  { returnDocument: "after" }, // return updated document
);
```

### Delete : findOneAndDelete

First sort the document by age in ascending order, delete the first matched document and return the deleted document

```js
db.students.findOneAndDelete(
  { name: "Salman Khan" },
  {
    projection: { name: 1, age: 1, _id: 0 }, // projection
    sort: { age: 1 }, // sort by age in ascending order
  },
);
```

---

## Page 26 — Aggregation Pipeline : Operators

### Collection : For Testing Query

Create a Collection name students for test Operators

```js
db.students.insertMany([
  { _id: 1, name: "Akshay Kumar", age: 23, class: "BCA" },
  { _id: 2, name: "Salman Khan", age: 24, class: "Btech" },
  { _id: 3, name: "Shahid Kapoor", age: 20, class: "BSc" },
  { _id: 4, name: "John Abraham", age: 19, class: "BCA" },
  { _id: 5, name: "Amir Khan", age: 24, class: "Btech" },
  { _id: 6, name: "Salman Khan", age: 21, class: "BSc" },
  { _id: 7, name: "Suniel Shetty", age: 22, class: "BCA" },
  { _id: 8, name: "Kartik Aryan", age: 20, class: "Btech" },
]);
```

### Aggregate With : $match

Filter the documents based on the condition

```js
// Match all students in BCA class
db.students.aggregate([{ $match: { class: "BCA" } }]);

// Match all students with age greater than 20
db.students.aggregate([{ $match: { age: { $gt: 20 } } }]);
```

### Aggregate With : $match + $and

Match all students with age greater than 20 and class BCA

```js
db.students.aggregate([
  {
    $match: {
      $and: [{ age: { $gt: 20 } }, { class: "BCA" }], // Using $and operator
    },
  },
]);
```

### Aggregate With : $count

Count the number of documents that match the condition,

```js
db.students.aggregate([{ $match: { age: { $gt: 20 } } }, { $count: "name" }]);
```

### Aggregate With : $sortBycount

Count the number of documents for each unique value of a field returning the field and the count

```js
db.students.aggregate([{ $sortByCount: "$class" }]);
```

### Aggregate With : $sample

Randomly select a specified number of documents from the collection

```js
db.students.aggregate([
  { $sample: { size: 2 } }, // Randomly select 2 documents
]);
```

---

## Page 27 — Aggregation Pipeline : Operators-II

### Aggregate With : $sort

Sort the documents based on the field in ascending or descending order

```js
db.students.aggregate([
  { $match: { age: { $gt: 20 } } },
  { $sort: { age: 1 } }, // 1 for ascending order
]);
```

### Aggregate With : $sort

Sort the documents based on the field in descending order

```js
db.students.aggregate([
  { $match: { age: { $gt: 20 } } },
  { $sort: { age: -1 } }, // -1 for descending order
]);
```

### Aggregate With : $sort

Sort the documents based on multiple fields, First by name in ascending order, then by age in ascending order

```js
db.students.aggregate([
  { $match: { age: { $gt: 20 } } }, // Match students with age greater than 20
  { $sort: { name: 1, age: 1 } }, // Sort by name and then by age
]);
```

### Aggregate With : $project

Reshape the documents by including, excluding, or adding new fields

```js
db.students.aggregate([
    { $match: { age: { $gt: 20 } } },
    { $sort: { name: 1, age: 1 } },
    { $project: { name: 1, class: 1, _id: 0 } }, // Project only name and class fields,
]);                                                                          excluding _id
```

### Aggregate With : $project

Reshape the documents by including, excluding, or adding new fields, and add custom filed

```js
db.students.aggregate([
  { $sort: { name: 1, age: 1 } },
  {
    $project: {
      name: 1,
      class: 1,
      _id: 0,
      isValidAge: {
        $gt: ["$age", 20],
      },
    }, // Add a new field isValidAge that checks if age is greater than 20
  },
]);
```

### Aggregate With : $skip + $limit

Skip a specified number of documents in the result set limiting the result set, useful in pagination

```js
db.students.aggregate([
  { $match: { age: { $gt: 20 } } },
  { $sort: { name: 1, age: 1 } },
  { $project: { name: 1, class: 1, _id: 0 } },
  { $skip: 4 }, // Skip the first 4 documents
  { $limit: 2 }, // Skip the first 4 documents and limit the result to 2 documents
]);
```

---

## Page 28 — Aggregation Pipeline : $group

### Aggregate With : $group

Group documents by a specified field and perform aggregations on the grouped data

```js
db.students.aggregate([
  {
    $group: {
      _id: "$class", // Group by class field
    },
  },
]);
```

### Group With : $sum

Group documents by a Class field and calculate the sum of a field in each group

```js
db.students.aggregate([
  {
    $group: {
      _id: "$class", // Group by class field
      count: { $sum: 1 }, // Count custom filed name
    },
  },
]);
```

### Group With : $sum + $match

Group documents by a Class field and calculate the sum of a field in each group after matching a condition

```js
db.students.aggregate([
  { $match: { age: { $gt: 20 } } }, // Match students with age greater than 20
  {
    $group: {
      _id: "$class", // Group by class field
      count: { $sum: 1 }, // Count custom filed name
    },
  },
]);
```

### Group With : $count

Group documents by a Class field and count the number of documents in each group

```js
db.students.aggregate([
  {
    $group: {
      _id: "$class",
      count: { $count: {} },
    }, // count is custom filed name
  },
]);
```

### Group With : $count + $sort

Group documents by a Class field and count the number of documents in each group, then sort by count

```js
db.students.aggregate([
  {
    $group: {
      _id: "$class",
      count: { $count: {} },
    }, // count is custom filed name
  },
  { $sort: { count: 1 } }, // Sort by count in descending order
]);
```

---

## Page 29 — Aggregation Pipeline : $group-II

### Group With : $push

Group documents by a Class field and push all student names into an array

```js
db.students.aggregate([
  {
    $group: {
      _id: "$class",
      students: { $push: "$name" }, // Push all student names into an array
    },
  },
]);
```

### Group With : $push

Group documents by a Class field and push all student names into an array

```js
db.students.aggregate([
  {
    $group: {
      _id: "$class",
      students: { $push: "$$ROOT" }, // Push all student documents into an array using
    },
    $$ROOT,
  },
]);
```

### Group With : $addToSet

Group documents by a Class field and add unique student names to an array

```js
db.students.aggregate([
  {
    $group: {
      _id: "$class",
      students: { $addToSet: "$name" }, // Add unique student names to an array
    },
  },
]);
```

### Group With : $max

Group documents by a Class field and find the maximum age of students in each class

```js
db.students.aggregate([
  { $group: {
      _id: "$class",
      Maximum_Student_Age: { $max: "$age" }, // Find the maximum age of students in each
    },                                                                               class
  },
]);
```

### Group With : $min

Group documents by a Class field and find the minimum age of students in each class

```js
db.students.aggregate([
    {   $group: {
          _id: "$class",
          Minimum_Student_Age: { $min: "$age" }, // Find the minimum age of students in each
        },                                                                               class
    },
]);
```

---

## Page 30 — Aggregation Pipeline : $group-III

### Group With : $avg

Group documents by a Class field and calculate the average age of students in each class

```js
db.students.aggregate([
  { $group: {
      _id: "$class",                      // Group by class field
      Average_Age: { $avg: "$age" }, // Calculate the average age of students in each
    },                                                                             class
  },
]);
```

### Group With : $avg

Group documents without any specific field to get the average age of all students

```js
db.students.aggregate([
  {
    $group: {
      _id: null, // No specific field to group by, so we use null
      Average_Age: { $avg: "$age" }, // Calculate the average age of all students
    },
  },
]);
```

### Group With : $median

Calculate the median age of all students

```js
db.students.aggregate([
  {
    $group: {
      _id: null, // No specific field to group by, so we use null
      Median_Age: {
        // Group by class field
        $median: {
          input: "$age", // Field to calculate the median on
          method: "approximate", // Use "exact" for exact median calculation
        },
      },
    },
  },
]);
```

### Group With : $median

Group documents by a Class field and calculate the median age of students in each class

```js
db.students.aggregate([
  {
    $group: {
      _id: "$class", // Group by class field
      Median_Age: {
        // Custom field name for median age
        $median: {
          input: "$age", // Field to calculate the median on
          method: "approximate", // Use "exact" for exact median calculation
        },
      },
    },
  },
]);
```

---

## Page 31 — Aggregation Pipeline : $group-IV

### Group With : $first

Group documents by a Class field and get the first student name in each class

```js
db.students.aggregate([
  {
    $group: {
      _id: "$class", // Group by class field
      First_Student: { $first: "$name" }, // Get the first student name in each class
    },
  },
]);
```

### Group With : $last

Group documents by a Class field and get the last student name in each class

```js
db.students.aggregate([
  {
    $group: {
      _id: "$class", // Group by class field
      Last_Student: { $last: "$$ROOT" }, // Get the last student name in each class
    },
  },
]);
```

### Group With : $top

Group documents by a Class field and get the top student based on age in each class

```js
db.students.aggregate([
  {
    $group: {
      _id: "$class", // Group by class field
      Top_students: {
        // Custom field name for top students
        $top: {
          output: ["$name", "$class", "$age"], // Fields to include in the output
          sortBy: { age: 1 }, // Sort by age in ascending order
        },
      },
    },
  },
]);
```

### Group With : $topN

Group documents by a Class field and get the top N students based on age in each class

```js
db.students.aggregate([
  {
    $group: {
      _id: "$class", // Group by class field
      Top_students: {
        // Custom field name for top students
        $topN: {
          output: ["$name", "$class", "$age"], // Fields to include in the output
          sortBy: { age: 1 }, // Sort by age in ascending order
          n: 3, // Get the top 2 students in each class
        },
      },
    },
  },
]);
```

---

## Page 32 — Aggregation Pipeline : $group-V

### Group With : $bottom

Group documents by a Class field and get the bottom student based on age in each class

```js
db.students.aggregate([
  {
    $group: {
      _id: "$class", // Group by class field
      Top_students: {
        // Custom field name for bottom students
        $bottom: {
          output: ["$name", "$class", "$age"], // Fields to include in the output
          sortBy: { age: 1 }, // Sort by age in ascending order
        },
      },
    },
  },
]);
```

### Group With : $bottomN

Group documents by a Class field and get the bottom N students based on age in each class

```js
db.students.aggregate([
  {
    $group: {
      _id: "$class", // Group by class field
      Top_students: {
        // Custom field name for bottom students
        $bottomN: {
          output: ["$name", "$class", "$age"], // Fields to include in the output
          sortBy: { age: 1 }, // Sort by age in ascending order
          n: 3, // Get the bottom 3 students in each class
        },
      },
    },
  },
]);
```

---

## Page 33 — Aggregation Pipeline : $lookup

### Collection : For Testing Query

Create a Collection name students & library for test Operators

```js
db.students.insertMany([
  { _id: 1, name: "Akshay Kumar", age: 23, class: "BCA" },
  { _id: 2, name: "Salman Khan", age: 24, class: "Btech" },
  { _id: 3, name: "Shahid Kapoor", age: 20, class: "BSc" },
  { _id: 4, name: "John Abraham", age: 19, class: "BCA" },
]);

db.library.insertMany([
  { _id: 1, book: "Atomic Habits", student_id: 1 },
  { _id: 2, book: "You Can", student_id: 2 },
  { _id: 3, book: "Do It Today", student_id: 4 },
]);
```

### Join Example 1 : $lookup

Join Students Collection to Library Collection throw Library Collection student_id Field to Students Collection \_id Field

```js
db.library.aggregate([
  {
    $lookup: {
      from: "students", // Collection to join with Library Collection
      localField: "student_id", // Field from Library Collection
      foreignField: "_id", // Field from Students Collection
      as: "Student", // Name of the new array field to add to Library
    },
    Collection,
  },
]);
```

### Join Example 2 : $lookup

Join Students Collection to Library Collection throw Students Collection \_id Field to Library Collection Student_id Filed

```js
db.students.aggregate([
  {
    $lookup: {
      from: "library",            // Collection to join with Students Collection
      localField: "_id",          // Field from Students Collection
      foreignField: "student_id", // Field from Library Collection
      as: "Book",                 // Name of the new array field to add to
    },                                                          Students Collection
  },
]);
```

### Join Example 3 : $lookup + $unwind

Join Student Collection to Library collection and use $unwind for if Book Array have only one document then remove Array

```js
db.students.aggregate([
  {
    $lookup: {
      from: "library", // Collection to join with Students Collection
      localField: "_id", // Field from Students Collection
      foreignField: "student_id",// Field from Library Collection
      as: "Book",,// Name of the new array field to add to Students Collection
    },
  },
    { $unwind: "$Book" }, // Unwind Book Array to remove array and make it a single
]);                                                                         document
```

---

## Page 34 — Aggregation Pipeline : $lookup

### Collection : For Testing Query

Create a Collection name customers & orders for test Operators

```js
db.customers.insertMany([
  { _id: 101, name: "Akshay Kumar", city: "Delhi" },
  { _id: 102, name: "John Abraham", city: "Goa" },
  { _id: 103, name: "Salman Khan", city: "Mumbai" },
]);

db.orders.insertMany([
  { _id: 1, customer_id: 101, product: "Laptop", price: 35000 },
  { _id: 2, customer_id: 102, product: "Phone", price: 20000 },
  { _id: 3, customer_id: 101, product: "Phone ABC", price: 22000 },
  { _id: 4, customer_id: 103, product: "Tablet", price: 15000 },
  { _id: 5, customer_id: 102, product: "Tablet", price: 15000 },
]);
```

### Join Example 4 : $lookup

Join Customer Collection to Oder Collection throw Customer \_id to order customer_id filed

```js
db.customers.aggregate([
  {
    $lookup: {
      from:  "orders",                  // Collection to join with Customers Collection
      localField: "_id",                // Field from Customers Collection
      foreignField: "customer_id",      // Field from Orders Collection
      as: "Orders",                     // Name of the new array field to add to
    },                                                          Customers Collection
  },
]);
```

### Join Example 5 : $lookup

Join Library Collection to Students Collection throw Library Collection student_id Field to Students Collection \_id Field
and replace the root document with the merged object
This will merge the Student document into the Library document, removing the Student array

```js
db.library.aggregate([
  {
    $lookup: {
      from: "students",           // Collection to join with Library Collection
      localField: "student_id",   // Field from Library Collection
      foreignField: "_id",        // Field from Students Collection
      as: "Student",              // Name of the new array field to add to Library
    },                                                                      Collection
  },
  {
    $replaceRoot: {               // Replace the root document with a new object
      newRoot: {
        $mergeObjects: [{ $arrayElemAt: ["$Student", 0] }, "$$ROOT"],
                                  // Merge the first element of the Student array with
        },                                                   the current document
    },
  },
    { $project: { Student: 0 } },     // Exclude the Student array from the final output
]);
```

---

## Page 35 — Aggregation Pipeline : $bucket

### Collection : For Testing Query

Create a Collection name students for test Operators

```js
db.students.insertMany([
  { _id: 1, name: "Akshay Kumar", percentage: 52 },
  { _id: 2, name: "Salman Khan", percentage: 67 },
  { _id: 3, name: "Deepika Padukone", percentage: 83 },
  { _id: 4, name: "John Abraham", percentage: 49 },
  { _id: 5, name: "Katrina Kaif", percentage: 77 },
  { _id: 6, name: "Abhishek Bachan", percentage: 44 },
  { _id: 7, name: "Shahid Kaupr", percentage: 25 },
  { _id: 8, name: "Amir Khan", percentage: 38 },
  { _id: 9, name: "Kriti Sanon", percentage: 91 },
  { _id: 10, name: "Anushka Sharma", percentage: 59 },
]);
```

### Example 1 : $bucket + output

Grouping students based on their percentage into different buckets

```js
db.students.aggregate([
  {
    $bucket: {
      groupBy: "$percentage", // Field to group by
      boundaries: [33, 45, 60, 80, 100], // Boundaries for the buckets
      default: "Fail Students", // Default bucket for values outside the boundaries
      output: {
        // Output fields for each bucket
        Count: { $sum: 1 }, // Count of students in each bucket
      },
    },
  },
]);
```

### Example 2 : $bucket without output

Grouping students based on their percentage without specifying output fields

```js
db.students.aggregate([
  {
    $bucket: {
      // Grouping students based on their percentage
      groupBy: "$percentage", // Field to group by
      boundaries: [33, 45, 60, 80, 100], // Boundaries for the buckets
      default: "Fail Students", // Default bucket for values outside the boundaries
    },
  },
]);
```

### Example 3 : $bucketAuto

Automatically grouping students into a specified number of buckets based on their percentage

```js
db.students.aggregate([
  {
    $bucketAuto: {
      // Automatically grouping students into buckets
      groupBy: "$percentage", // Field to group by
      buckets: 3, // Number of buckets to create
      output: {
        Count: { $sum: 1 }, // Count of students in each bucket
        Average_percentage: { $avg: "$percentage" }, //Average % of students in each bucket
        Total_percentage: { $sum: "$percentage" }, // Total & of students in each bucket
      },
    },
  },
]);
```

---

## Page 36 — Aggregation Pipeline : $addFields Operators

### Collection : For Testing Query

Create a Collection name students for test Operators

```js
db.students.insertMany([
  {
    _id: 1,
    firstname: "Akshay",
    lastName: "Kumar",
    marks: [52, 59, 67],
    city: "Delhi",
  },
  {
    _id: 2,
    firstname: "Salman",
    lastName: "Khan",
    marks: [77, 74, 69],
    city: "Mumbai",
  },
  {
    _id: 3,
    firstname: "Deepika",
    lastName: "Padukon",
    marks: [83, 64, 75],
    city: null,
  },
  {
    _id: 4,
    firstname: "John",
    lastName: "Abraham",
    marks: [49, 66, 58],
    city: "Goa",
  },
  { _id: 5, firstname: "Katrina", lastName: "Kaif", marks: [69, 74, 64] },
]);
```

### Example 1 : $addFileds + $concat

Fetch Document and concat field in contact first name & last name and how in fullName field

```js
db.students.aggregate([
  {
    $addFields: {
      // Add new field fullName
      // Concatenate firstname and lastName with a space in between
      fullName: { $concat: ["$firstname", " ", "$lastName"] },
    },
  },
]);
```

### Example 2 : $addFileds + $$REMOVE

Fetch Document and concat field in existing \_id field, show full name in \_id field,
Remove existing fields firstname and lastName after concatenating them into fullName

```js
db.students.aggregate([
  {
    $addFields: {
      _id: { $concat: ["$firstname", " ", "$lastName"] },
      firstname: "$$REMOVE", // Remove firstname field
      lastName: "$$REMOVE", // Remove lastNam field
    },
  },
]);
```

### Example 3 : $addFileds + ifNull

Fetch Document and concat field in existing \_id field, show full name in \_id field, If city is null, remove it from the output

```js
db.students.aggregate([
  {
    $addFields: {
      _id: { $concat: ["$firstname", " ", "$lastName"] }, // Add new field fullName
      firstname: "$$REMOVE", // Remove firstname field
      lastName: "$$REMOVE", // Remove lastNam field
      city: { $ifNull: ["$city", "$$REMOVE"] }, // If city is null, remove it from the
    },
    output,
  },
]);
```

---

## Page 37 — Aggregation Pipeline : $addFields Operators-II

### Example 4 : $addFileds + $cond (if else)

Fetch Document and concat field in existing \_id field, show full name in \_id field,
If city is "Delhi", remove it from the output, otherwise keep

```js
db.students.aggregate([
  {
    $addFields: {
      fullName: { $concat: ["$firstname", " ", "$lastName"] },
      firstname: "$$REMOVE", // Remove firstname field
      lastName: "$$REMOVE", // Remove lastName field
      city: {
        $cond: {
          // Conditional logic to check if city is "Delhi"
          if: {
            $eq: ["$city", "Delhi"],
          },
          then: "$$REMOVE", // If city is "Delhi", remove it from the output
          else: "$city", // Otherwise, keep the city field
        },
      },
    },
  },
]);
```

### Example 5 : $addFileds + $match

Match document with \_id 1 and add fullName field, add firstname and lastName fields to fullName, and remove firstname and lastName fields

```js
db.students.aggregate([
  { $match: { _id: 1 } }, // Match document with _id 1
  {
    $addFields: {
      fullName: { $concat: ["$firstname", " ", "$lastName"] },
      firstname: "$$REMOVE", // Remove firstname field
      lastName: "$$REMOVE", // Remove lastName field
    },
  },
]);
```

### Example 6 : $addFileds + custome field

Match document with \_id 1 and add fullName field, and remove firstname and lastName fields Also, add a new field "age" to the "profile" object

```js
db.students.aggregate([
  { $match: { _id: 1 } }, // Match document with _id 1
  {
    $addFields: {
      fullName: { $concat: ["$firstname", " ", "$lastName"] },
      firstname: "$$REMOVE", // Remove firstname field
      lastName: "$$REMOVE", // Remove  lastName fields
      "profile.age": 30, // Add a new field "age" to the "profile" object
    },
  },
]);
```

---

## Page 38 — Aggregation Pipeline : $addFields, $unwind-III

### Example 7 : $addFileds

add new value in marks array Match document with \_id 1 and add fullName field, add a new value to the marks array, and remove firstname and lastName fields

```js
db.students.aggregate([
  { $match: { _id: 1 } }, // Match document with _id 1
  {
    $addFields: {
      fullName: { $concat: ["$firstname", " ", "$lastName"] },
      firstname: "$$REMOVE",
      lastName: "$$REMOVE",
      marks: { $concatArrays: ["$marks", [70]] }, // Add a new value 70 to the marks
    },
    array,
  },
]);
```

### Example 8 : $addFileds

Match document with \_id 1 and add fullName field, remove firstname and lastName fields, and calculate total marks

```js
db.students.aggregate([
  { $match: { _id: 1 } },
  {
    $addFields: {
      fullName: { $concat: ["$firstname", " ", "$lastName"] },
      firstname: "$$REMOVE",
      lastName: "$$REMOVE",
      TatalMarks: { $sum: "$marks" }, // New Field TatalMarks in this fild show sum how
    },
    marks,
  },
]);
```

### Example of : $unwind

Unwind the sizes array in the inventory collection
This will create a separate document for each size in the sizes array

```js
// Create a collection named inventory with an array field sizes
db.inventory.insertMany([
  { _id: 1, item: "ABC", sizes: ["S", "M", "L"] },
  { _id: 2, item: "XYZ", sizes: ["S", "M", "L", "XL"] },
]);

db.inventory.aggregate([
  {
    $unwind: "$sizes", // Unwind the sizes array to create a separate document for each
  },
  size,
]);
```

---

## Page 39 — Aggregation Pipeline : $out Operators

### Collection : For Testing Query

Create a Collection name students for test Operators

```js
db.students.insertMany([
  { _id: 1, name: "Akshay Kumar", age: 23, class: "BCA" },
  { _id: 2, name: "Salman Khan", age: 24, class: "Btech" },
  { _id: 3, name: "Shahid Kapoor", age: 20, class: "BSc" },
  { _id: 4, name: "John Abraham", age: 19, class: "BCA" },
  { _id: 5, name: "Amir Khan", age: 24, class: "Btech" },
  { _id: 6, name: "Salman Khan", age: 21, class: "BSc" },
  { _id: 7, name: "Suniel Shetty", age: 22, class: "BCA" },
  { _id: 8, name: "Kartik Aryan", age: 20, class: "Btech" },
]);
```

### Example of : $out

This example filters students older than 20 and outputs them to a new collection called "valid_students".

```js
db.students.aggregate([
  { $match: { age: { $gt: 20 } } }, // filter students older than 20
  { $out: "valid_students" }, // output to a new collection
]);
```

### Example 2 : $out

This example outputs all students to a new collection called "valid_students".

```js
// output all students to a new collection
db.students.aggregate([{ $out: "valid_students" }]);
```

### Example 3 : $out

This example groups students by class and outputs the result to a new collection called "class_data".

```js
db.students.aggregate([
  { $group: { _id: "$class", Student: { $push: "$name" } } }, // group by class
  { $out: "class_data" }, // output to a new collection
]);
```

---

## Page 40 — Aggregation Pipeline : merge, $unionWith

### Collection : For Testing Query

Create a Collection name personal, students1, students2 for test Operators

```js
db.personal.insertMany([
  { _id: 1, city: "Delhi", phone: 3030320 },
  { _id: 2, city: "Gao", phone: 445522 },
  { _id: 3, city: "Mumbai", phone: 223347 },
  { _id: 4, city: "Delhi", phone: 303085 },
  { _id: 5, city: "Agra", phone: 221135 },
  { _id: 6, city: "Delhi", phone: 648877 },
  { _id: 7, city: "Goa", phone: 309988 },
  { _id: 8, city: "Mumbai", phone: 223355 },
]);

db.students1.insertMany([
  { _id: 1, name: "Kartik Aryan", role: "Student" },
  { _id: 2, name: "RajKumar Rao", role: "Student" },
]);

db.students2.insertMany([
  { _id: 1, name: "Salman Khan", role: "Alumnus" },
  { _id: 2, name: "Akshay Kumar", role: "Alumnus" },
]);
```

### Example of : merge

This example merges students older than 20 into the "students" collection.

```js
db.personal.aggregate([
  {
    $merge: {
      into: "students", // target collection
      on: "_id", // field to match on
      whenMatched: "merge", // options for matched ("merge", "replace", "keepExisting")
      whenNotMatched: "insert", // other options for unmatched ("insert", "discard")
    },
  },
]);
```

### Example of : $unionWith

This example creates two collections: students1 and students2, and then uses $unionWith to combine them.

```js
// This example combines documents from two collections: students1 and students2.
db.students1.aggregate([
  {
    $unionWith: {
      coll: "students2", // collection to union with
    },
  },
]);
```

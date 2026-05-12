# Salesforce Summer Program – Day 3
## Introduction
In Day 3, I learned how Salesforce stores and manages business data using objects, fields, records, relationships, formula fields, and validation rules. I also understood how enterprise systems organize structured data instead of depending on random spreadsheets.
 # Difference Between App, Object, Record, and Field
 | Term | Meaning |
|------|---------|
| App | A collection of related tools and objects used for a specific business purpose |
| Object | A database table that stores a particular type of information |
| Record | A single entry inside an object |
| Field | A specific piece of information stored in a record |
 ### Example
- Object → Student
- Record → Priyanka
- Field → Email, Roll Number, Department
# Standard vs Custom Objects
## Standard Objects
These are already provided by Salesforce.
Examples:
- Account
- Contact
- Lead
- Opportunity
## Custom Objects
These are created based on business requirements.
Examples:
- Student
- Faculty
- Course
- Department
# College Management System Data Model
## Objects
- Student
- Faculty
- Course
- Department
## Relationships
- One Department can have many Faculty members.
- One Department can offer many Courses.
- One Faculty member can teach many Courses.
- Many Students can enroll in Courses.
## Relationship Type
Lookup relationships are used to connect these objects.
# Simple Data Model Diagram

Department
↓
Faculty
↓
Course
↓
Student
# Formula Fields
## 1. Full Name
Automatically combines First Name and Last Name.
### Why?
It reduces manual work and avoids typing mistakes.
## 2. Percentage
Calculates student percentage automatically from marks.
### Why?
Automatic calculations improve accuracy and save time.
## 3. Remaining Seats
Calculates available seats in a course.
### Why?
It helps manage course capacity efficiently.
# Validation Rules
## 1. Email Cannot Be Empty
Prevents saving student records without email addresses.
### Why?
Communication details are important.
## 2. Student Age Cannot Be Negative
Prevents invalid age values.
### Why?
Incorrect data affects reports and system accuracy.
## 3. Course Seats Cannot Exceed Limit
Blocks entering more students than allowed.
### Why?
Prevents overbooking and confusion.
# Reflection
Companies cannot manage large amounts of business data using random spreadsheets because data becomes inconsistent, duplicated, and difficult to maintain. Structured enterprise systems like Salesforce help organizations connect related information, improve security, automate calculations, maintain accurate records, and reduce human errors.

I also learned that relationships between objects are very important because businesses need connected data to track operations efficiently.
# What I Learned
- Difference between objects, fields, and records
- Importance of relationships in enterprise systems
- Formula Fields and Validation Rules
- Schema Builder basics
- Structured data management in Salesforce

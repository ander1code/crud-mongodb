
# CRUD-Sharp-MongoDB

![C#](https://img.shields.io/badge/C%23-239120?logo=csharp&color=blue&logoColor=white) ![Java](https://img.shields.io/badge/Java-007396?logo=openjdk&logoColor=white&color=red)
![.NET Framework](https://img.shields.io/badge/.NET_Framework-512BD4?logo=.net&logoColor=white&color=blue)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=white)
![Platform: Windows](https://img.shields.io/badge/Windows-0078D4?logo=windows&logoColor=white)
![Last Commit](https://img.shields.io/github/last-commit/ander1code/crud-sharp-mongodb?color=yellown&logo=github) ![Size](https://img.shields.io/github/repo-size/ander1code/crud-sharp-mongodb?color=blue&logo=files) ![License](https://img.shields.io/github/license/ander1code/crud-sharp-mongodb?color=black&logo=open-source-initiative)

## 1. Description
A **registration system** developed using **C# (crud-sharp-mongodb)** and **Java (java-mongo-app)**, integrated with **MongoDB (NoSQL)** as the database. The project showcases robust features for handling data and security across different frameworks and programming languages.

## 2. Features

### 2.1. Person Registration
- Create, edit, and delete person records.

### 2.2. Person Search
- Retrieve person data by ID.
- Search for person data by name.

### 2.3. Login
- User authentication with secure **SHA512 encryption**.

### 2.4. Reports (Aggregate Functions)
- Salary range analysis.
- Average salary report generation.
- Fetch all registered persons.
- Retrieve persons by salary range.
- Fetch persons based on their birthday month.

**Note:** The **Java version** (`java-mongo-app`) does not include features described in **2.3** (Login) and **2.4** (Reports).

## 3. Tools and Technologies

### 3.1. Database
- **MongoDB:** Version 3.4.4

### 3.2. C# Version (crud-sharp-mongodb)
- **IDE:** Visual Studio 2013 Ultimate
- **Framework:** .NET Framework 4.5
- **Driver:** MongoDB Driver 2.6

### 3.3. Java Version (java-mongo-app)
- **IDE:** NetBeans 8.2
- **Java SE:** Version 1.8.0_161
- **Driver:** MongoDB Java Driver 3.2.2

## 4. Utilization
- **Step A.1:** Install MongoDB on your system.
- **Step A.2:** Create a database named **`dbSharp`**.

**Notes:**
1. For licensing reasons, the original project database has been removed. To test the application:
   - Update the project with your own database connection string.
   - Execute the `.sql` file provided separately to initialize the database structure.

---
# CS3700 – Database Management System

This repository contains my coursework for **CS3700: Database Management System** at IIT Madras.

The main database project is a **State Election Database Management System**, designed to store and manage information related to political parties, candidates, voters, constituencies, polling booths, election officers, campaign events, votes, and election results.

---

## Repository Contents

```text
CS3700-DBMS/
│
├── databaseDesign.pdf
├── electionData.sql
├── sqlQueries.pdf
└── README.md
```

---

## Database Design

**File:** `databaseDesign.pdf`

Designed a **State Election Database Management System**.

The database models a state election in which:

* A state is divided into multiple constituencies.
* Candidates contest elections from constituencies.
* Candidates may represent political parties or contest independently.
* Registered voters belong to constituencies and cast votes.
* Voting takes place at polling booths.
* Election officers supervise and manage election activities.
* Candidates can organize campaign events.
* Votes are counted to determine election results.

### Main components

The database design includes:

* Candidate
* Political Party
* Voter
* Constituency
* Polling Booth
* Vote
* Election Officer
* Family Member
* Result
* Campaign Event

The relational schema contains these relations along with their primary keys and relational integrity constraints.

The assignment includes:

1. Domain description
2. ER diagram
3. Entity and attribute descriptions
4. Relationship descriptions
5. Relational schema
6. Relational integrity constraints

---

## SQL on the database created

**File:** `electionData.sql` \& sqlQueries.pdf

Created and populated the State Election database and developed individual SQL queries on the database.

The submission contains 8 queries covering different SQL techniques.

### Queries included

1. Number of Candidates per Constituency
2. Candidates with More Than 10 Votes
3. Constituency Vote Count
4. Campaign Events per Candidate
5. Candidates with No Votes
6. Officers and Their Subordinates
7. Winning Candidate Details
8. Polling Booth with Maximum Turnout

#### The queries use operations such as `COUNT`, `GROUP BY`, `HAVING`, joins, self-joins, `LEFT JOIN`, and subqueries.

## Technologies Used

* **MySQL 8.0**
* **SQL**
* **ER Modeling**
* **Relational Database Design**
* **Database Indexing**
* **Python / Java / C / C++** for application development

---

## Course

**CS3700 – Database Management System**
**IIT Madras**

---

## Author

**Rishitha Patel**
Roll No: `CS23B077`

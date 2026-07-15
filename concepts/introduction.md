# Basic Units in a Database

## Objective

The student will be capable to identify the following elements:

- **Table**
- **Record**
- **Field**

---

# What is a database?

A **database** is a organized set of information that allows store, query and manage data in a efficient way.

### Example

A school can have a database to store students information:

- Student Id
- Name
- Degree Program
- Year

---

# 1. Table

A **table** is the main structure of a database. It contains rows and columns with information related to the same topic or entity.

### For example a table named `Students`

| StudentId | Name | Degree | Year |
|------------|---------|----------|-----------|
| 2025001 | Thomas Martin | Licence en Droit | L3 |
| 2025002 | Léa Bernard | Licence en Gestion | L2 |
| 2025003 | Lucas Dubois | Génie Mécanique | L1 |

### Features

- Manage information in rows and columns.
- Store data related to an specific entity.
- Each tabla has a unique name within the database.

---

# 2. Record

A **record** is a complete row within a table.

Each record contains all the information related with an especific element.

### Example

In the following table:

| StudentId | Name | Degree | Year |
|------------|---------|----------|-----------|
| 2025001 | Thomas Martin | Licence en Droit | L3 |

The record is:

```text
StudentId: 2025001
Name: Thomas Martin
Degree: Licence en Droit
Year: L3
```

### Features

- It represents an instance or unique element.
- It is form by several fields.
- Each column of the table is related to one record.

---

# 3. Field

A **Field** is each of the columns of a table.

The fields describe features or attribute of the records.

### Example

In the table Students:

| StudentId | Name | Degree | Year |
|------------|---------|----------|-----------|

The fields are::

- StudentId
- Name
- Degree
- Year

### Features

- It defines the type of data that will be stored.
- Each field has a name.
- Can store one of the following data types:
  - Text
  - Numbers
  - Dates
  - Logical values (Yes/No)
  - Other tyoes that we will review leater.

---

# Relationship among Table, Record and Field

```text
TABLE
│
├── Record 1
│   ├── Field: StudentId
│   ├── Field: Name
│   ├── Field: Degree
│   └── Field: Year
│
├── Record 2
│   ├── Field: StudentId
│   ├── Field: Name
│   ├── Field: Degree
│   └── Field: Year
│
└── Record 3
    ├── Field: StudentId
    ├── Field: Name
    ├── Field: Degree
    └── Field: Year
```

---

# Summary

| Concept | Description | Equivalent |
|-----------|------------|--------------|
| Table | Set of organized data | Full sheet |
| Record | Row of information | An element or individual record |
| Field | Column that describes a feature | An attribute of the record |

---

# Activity

Look at the table below:

| ID | Product | Price |
|----|----------|---------|
| 1 | Clavier d'ordinateur | 50 |
| 2 | Souris d'ordenateur | 5 |
| 3 | Ordinateur portable | 800 |

### Questions

1. What is the name of the records?
2. How many records there are?
3. Which information contains the record with ID = 2?

### Answers

1. 
2. 
3. 

---

# Conclusion

The databases organize information using **tables**. Within each table there are **records** (rows) that store specific information and **fields** (columns) that describe features of each record.

Assignment 5 – CO5: Data Persistence Engineering (Files and Databases)
Student Name: P.V.BHANU PRAKASH Register Number: 192411105 Course: Programming in Java (CSA09)
Course Outcome: CO5
Java Version: OpenJDK 17.0.21.0.2 LTS

📌 Overview
This assignment evaluates architectural design and practical implementation decisions in Java data persistence. It contrasts text files, binary streams, object serialization, and relational databases using JDBC. Focus areas include stream buffering, DAO patterns, object-graph serialization, SQL injection defense, batch loading, transaction atomicity (commit/rollback), and enterprise migration.

📁 Directory Structure
Assignment5/
├── PartA_Design/
│   └── PartA_PersistenceDesign.md  # Record layouts, pseudocode, DAO & security analysis
├── TaskB1_FileStore/
│   └── PassStore.java              # File store with BufferedReader & damaged line tolerance
├── TaskB2_Adversarial/
│   └── AdversarialSecurityDemo.java # SQL injection exploit vs PreparedStatement defense
├── TaskB3_BatchTransactions/
│   └── PassLoader.java             # Batch insert & atomic transaction rollback
├── TaskB4_FinalDecision/
│   └── EnterpriseMigrationDemo.java # Multi-campus migration audit & persistence decision
└── README.md
🚀 Compilation and Execution Instructions
From the Assignment5 directory:

# Task B1: File Store & Stream Buffering
javac TaskB1_FileStore/PassStore.java
java TaskB1_FileStore.PassStore

# Task B2: Adversarial SQL Injection & Malformed File Test
javac TaskB2_Adversarial/AdversarialSecurityDemo.java
java TaskB2_Adversarial.AdversarialSecurityDemo

# Task B3: Batch Processing & Transaction Rollback
javac TaskB3_BatchTransactions/PassLoader.java
java TaskB3_BatchTransactions.PassLoader

# Task B4: Enterprise Migration & Final Architecture Evaluation
javac TaskB4_FinalDecision/EnterpriseMigrationDemo.java
java TaskB4_FinalDecision.EnterpriseMigrationDemo

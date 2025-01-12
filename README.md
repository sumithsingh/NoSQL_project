# **Medical Data Management System**

## **Project Description**  
This project demonstrates the use of three NoSQL databases—**MongoDB**, **Neo4j** , and,**Redis** —to tackle diverse data management challenges. Each database is utilized for its unique strengths: document storage, graph-based relationship modeling, and in-memory caching.

---

## **Features**  

### **MongoDB**  
- Manages structured and semi-structured data like medical records.
- Implements CRUD operations to store and retrieve doctors and patients information.

### **Neo4j**  
- Graph database used for modeling complex relationships such as doctor-patient interactions.
- Executes graph queries and network analysis using Cypher.

### **Redis**  
- High-speed in-memory database for caching and real-time session management.
- Performs real-time data processing for faster operations.
- Used to get real-time appointment details.

---

## **Getting Started**  

### **Prerequisites**  
1. Install the required databases:
   - [MongoDB Installation Guide](https://www.mongodb.com/docs/manual/installation/)
   - [Redis Installation Guide](https://redis.io/docs/getting-started/)
   - [Neo4j Installation Guide](https://neo4j.com/docs/)
2. Install Python dependencies:
   ```bash
   pip install pymongo redis neo4j
   

# Travel Agency Platform – CS281 Project

## Overview
This project is a backend system simulation of a Travel Agency Platform developed as part of the CS281 course. It models a multi-user environment where different roles interact with the system to manage tours, bookings, and customer experiences.

The platform integrates application logic with a database system to simulate real-world operations in a travel agency setting.

---

## Objectives
- Design a system with multiple user roles and interactions  
- Implement realistic business rules (capacity, availability, payments)  
- Integrate a database for persistent data management  
- Simulate end-to-end workflow of a travel agency system  

---

## User Roles
- **Admin**  
  - Create and manage tours  
  - Assign transportation, hotels, and tour guides  
  - Monitor ratings and update system parameters  

- **Customer**  
  - Search and filter available tours  
  - View detailed tour information  
  - Book and pay for tours  
  - View purchased tours  
  - Leave reviews and ratings  

- **Tour Guide**  
  - View assigned tours  
  - Access customer details  

---

## Key Features
- Tour creation and scheduling  
- Resource assignment (transportation, accommodation, guides)  
- Tour search and filtering system  
- Booking and payment validation  
- Capacity control and constraint handling  
- Review and rating system  
- Role-based system interactions  

---

## Methods & Concepts
- Object-oriented programming  
- System simulation and workflow design  
- Constraint handling (capacity, availability, payments)  
- Multi-user interaction modeling  
- Backend logic development  

---

## Database Integration
The system uses an SQLite database to manage and persist data.

### Stored Data Includes:
- Users (admins, customers, tour guides)  
- Tours and schedules  
- Bookings and transactions  
- Reviews and ratings  

### SQL is used for:
- Data storage and retrieval  
- Filtering and querying tours  
- Managing transactions and constraints  
- Updating system state dynamically  

---

## Technologies Used
- Python  
- Jupyter Notebook  
- SQLite (SQL database)  

---

## Project Structure
- `DataSmiths_Final_Stage.ipynb` → Main implementation  
- `project_database.db` → SQLite database file  
- `Functional_Requirements.pdf` → Project requirements and system specifications  

---

## How to Run
1. Ensure Python and Jupyter Notebook are installed  
2. Place all files in the same directory  
3. Open the notebook:

```bash
jupyter notebook DataSmiths_Final_Stage.ipynb
```

4. Run all cells sequentially  

---

##  Inustrial Engineering Perspective
This project reflects key industrial engineering concepts such as:
- Resource allocation (transportation, hotels, tour guides)  
- Capacity planning and management  
- Process and workflow design  
- Database-driven decision systems  
- Multi-stage service operations  

---

## 📌 Notes
- The project focuses on backend system logic rather than user interface design  
- Running the system requires all files (including the database) to be in the same directory  ject focuses on system logic, user operations, and platform workflow design.

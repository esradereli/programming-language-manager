# Programming Language Manager  

A console-based CRUD application built with Java.  
This project allows users to add, list, update, delete, and search programming languages by ID using a clean service–repository architecture.

## Features
- Add a new programming language  
- List all programming languages  
- Get a language by its ID  
- Update the name of a language  
- Delete a language  
- Exit the system  

## Architecture
This project uses a simple layered design:
**ProgrammingLanguage.java** → Model (entity)  
**plRepository.java** → In-memory data storage (ArrayList)  
**plService.java** → Business logic (CRUD + validation)  
**Main.java** → Console menu & user interaction  

## 🛠️ Technologies Used
- Java  
- OOP principles  
- Service–Repository pattern  
- Collections (ArrayList)  
- Scanner-based console interaction  


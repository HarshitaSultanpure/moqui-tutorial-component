# Moqui Tutorial Component

This project is a simple tutorial component for the **Moqui Framework**.  
It shows how to create a new component, define entities, build screens, configure authorization, and implement basic CRUD (Create, Read, Update, Delete) functionality.

📌 Features

* Custom Moqui component named tutorial
* Entity definition for Tutorial
* Automatic Find Screen with search and sorting
* Popup Create Tutorial form
* Custom service for creating records
* Authorization setup for screen access
* Demo and seed data support
* Mounted under /apps/tutorial

## Folder Structure
```
runtime/component/tutorial/
├── data
│   └── TutorialSetupData.xml
├── entity
│   └── TutorialEntities.xml
├── screen
│   ├── tutorial.xml
│   └── tutorial
│       ├── FindTutorial.xml
│       └── hello.html
├── service
│   └── tutorial
│       └── TutorialServices.xml
├── script
└── MoquiConf.xml
```


## 🚀 How to Run the Project

### 1️⃣ Clone the Repository

```bash
git clone <your-repo-url>
cd tutorial-github
```

### 2️⃣ Start Moqui
```
./gradlew load

```

### 3️⃣ Open the Tutorial App
```
http://localhost:8080/vapps/tutorial
```











# Moqui Tutorial Component

This project is a simple tutorial component for the **Moqui Framework**.  
It shows how to create a new component, add a screen, and mount it inside the Moqui application.

## What’s Inside

- A custom Moqui component named `tutorial`
- A basic **Hello World** screen  
- Screen mounted under `/apps/tutorial`  
- HTML content included using `render-mode`

## Folder Structure
```
runtime/component/tutorial/
├── data
├── entity
├── screen
│ ├── tutorial.xml
│ └── tutorial/hello.html
├── script
├── service
└── MoquiConf.xml
```

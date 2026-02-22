# 🪺 Nest.js

---

## 📖 Introduction

Nest.js is a framework for building efficient, scalable Node.js server-side applications.

### **Core Technology Stack**

```
Nest.js = JavaScript + TypeScript + OOPS
```

### **Key Features**

Nest provides an out-of-the-box application architecture which allows developers and teams to create highly testable, scalable, loosely coupled, and easily maintainable applications.

---

## 🚀 Installation

To scaffold the project with the Nest CLI, run the following commands:

**1. Install Nest CLI globally**
```bash
npm i -g @nestjs/cli
```

**2. Create new project**
```bash
nest new project-name
```

---

## ✨ Benefits

| Feature | Description |
|---------|-------------|
| **Testable** | Highly testable architecture |
| **Scalable** | Built for large applications |
| **Loosely Coupled** | Modular structure |
| **Maintainable** | Easy to maintain and extend |

## 👟 First Steps

To get familiar with the essential building blocks of Nest applications, we'll build a basic CRUD application with features that cover a lot of ground at an introductory level.

### **Language**

```
Nest.js = TypeScript + Node JS
```

### **Pre-requisites**

- Install Node.js

### **Setup**

**1. Install Nest CLI globally**
```bash
npm i -g @nestjs/cli
```

**2. Create new project**
```bash
nest new nest-app
```

The nest-app directory will be created, node modules and a few other boilerplate files will be installed, and a src/ directory will be created and populated with several core files.

---

## 📁 Project Structure

```
src
  app.controller.spec.ts
  app.controller.ts
  app.module.ts
  app.service.ts  
  main.ts
```

### **Core Files Explained**

| File | Description |
|------|-------------|
| `app.controller.ts` | A basic controller with a single route. |
| `app.controller.spec.ts` | The unit tests for the controller. |
| `app.module.ts` | The root module of the application. |
| `app.service.ts` | A basic service with a single method. |
| `main.ts` | The entry file of the application which uses the core function NestFactory to create a Nest application instance. |

---

## ▶️ Running the Application

**Start the application**
```bash
npm run start
```

**Watch mode (recommended for development)**

To watch for changes in your files, you can run the following command to start the application:

```bash
npm run start:dev
```
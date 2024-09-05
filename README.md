# 🚀 Feature-Sliced Design Todo App

A modern and scalable **TODO** app built using **Feature-Sliced Design (FSD)** architecture. The project is powered by **React** with **MobX** for state management, **TypeScript** for type safety, and **Vite** for lightning-fast development.

## 🛠️ Tech Stack

- **React**: A JavaScript library for building user interfaces.
- **MobX**: Simple, scalable state management using observables.
- **TypeScript**: Superset of JavaScript for static typing.
- **Vite**: A fast build tool for optimized performance.

## 📂 Project Structure (Feature-Sliced Design)

![Feature-Sliced Design Architecture](https://miro.medium.com/v2/resize:fit:1400/1*XNbZ3dfdLYRdKw8Gl4ClTA.jpeg)

The **Feature-Sliced Design (FSD)** is the core of this project. It introduces a modular, scalable approach for organizing the app, allowing for better separation of concerns, maintainability, and easier collaboration.

In **FSD**, the app is divided into independent layers and feature modules that encourage reuse and better control over the business logic.

### Key Benefits of FSD

1. **Clear Separation of Concerns**:
    - Each feature is self-contained and isolated from others, making it easier to track the flow of data.
    - Developers work within clearly defined layers (`app`, `processes`, `pages`, `features`, `entities`, `shared`) that encapsulate specific roles and responsibilities.

2. **Scalability**:
    - As the app grows, new features can be added independently without affecting the rest of the system.
    - Each feature is a module, promoting reusability across different parts of the app.

3. **Improved Maintainability**:
    - Features are self-contained and encapsulated, making it easier to update or refactor without breaking other parts of the system.

4. **Optimized for Collaboration**:
    - The clear modular structure makes it easy for teams to work on different features without conflicts.
    - Encourages vertical slicing of features, where each feature is developed from front-end UI to business logic in isolation.

---


## 🛠️ Installation and Setup

### Prerequisites

Make sure you have the following installed on your machine:

- **Node.js** (v14 or higher)
- **npm** or **yarn**

### Clone the Repository

Start by cloning the repository from GitHub:

```bash
git clone https://github.com/All1in/my-fsd-todo.git

# 🌍 Tiny Planet
# 🌍 Tiny Planet

## 🪐 About Tiny Planet

**Tiny Planet** is a cozy, interactive disaster preparedness simulation game designed to make learning about emergency preparedness simple, engaging, and approachable.

Instead of presenting disaster preparedness through traditional instructions or serious training materials, Tiny Planet uses a **playful map-based environment, animated characters, interactive scenarios, and game-based decision making** to help players understand how to respond to different emergency situations.

Players explore a small virtual world, interact with characters and objects, encounter different scenarios, and make decisions based on the situation. The game provides feedback and hints through interactive notifications, allowing players to learn preparedness strategies in a low-pressure environment.

The project combines **education, interactive storytelling, game mechanics, and modern web technologies** to create an experience that is both informative and enjoyable.

---

## 👥 Contributors

* **Sana Tasneem Azimudin**
* **Nivriti Muthu Vairavan**
* **Yashika V**
* **Sharmu R**

---

## 🎯 Objectives

Tiny Planet was developed with the following goals:

* Make disaster preparedness more accessible and engaging.
* Teach basic emergency preparedness through interactive gameplay.
* Encourage players to think about appropriate responses to different situations.
* Replace fear-based disaster education with a calm and approachable experience.
* Use game mechanics to encourage exploration and learning.
* Demonstrate how web technologies can be used to create interactive educational experiences.

---

## ✨ Key Features

### 🌌 Interactive Start Screen

* Animated starry background.
* Smooth fade-in and fade-out transitions.
* Minimal and cozy visual design.
* Interactive **Start Game** button.
* Smooth transition from the start screen into the game.

### 🗺️ Map-Based Gameplay

* Interactive game environment built around a map.
* Players can explore different areas of the virtual world.
* Map locations can trigger different events and scenarios.
* Characters and objects are integrated into the environment.

### 👤 Avatars and NPCs

* Interactive player avatar.
* Non-player characters (NPCs) provide interactions and scenario-based experiences.
* Characters help make the game world feel more engaging and interactive.

### 🚨 Disaster Scenarios

* Players encounter different preparedness-related situations.
* Scenarios encourage players to think about what action should be taken.
* Scenario triggers allow the gameplay to respond to player interactions.
* The game focuses on learning through exploration rather than simply presenting information.

### 💬 Toast Notifications

* Provides immediate feedback to the player.
* Displays hints, messages, and gameplay information.
* Helps players understand the results of their interactions.
* Keeps the interface clean without interrupting gameplay.

### 🎨 Cozy Visual Experience

* Soft and playful visual style.
* Animated elements create a more dynamic environment.
* Designed to make disaster-related learning feel less intimidating.
* Focuses on exploration and interaction.

### ⚡ Responsive Game State

* Game state is managed using **Zustand**.
* Player interactions can update the current game state.
* Centralized state management makes the application easier to maintain and extend.

---

## 🎮 Gameplay Flow

The basic gameplay experience follows this flow:

```text
        ┌──────────────────┐
        │   Start Screen   │
        └────────┬─────────┘
                 │
                 ▼
        ┌──────────────────┐
        │    Start Game    │
        └────────┬─────────┘
                 │
                 ▼
        ┌──────────────────┐
        │   Explore Map    │
        └────────┬─────────┘
                 │
                 ▼
        ┌──────────────────┐
        │ Interact with    │
        │ NPCs / Objects   │
        └────────┬─────────┘
                 │
                 ▼
        ┌──────────────────┐
        │ Scenario Trigger │
        └────────┬─────────┘
                 │
                 ▼
        ┌──────────────────┐
        │ Make / Learn     │
        │ Preparedness     │
        │ Decisions        │
        └────────┬─────────┘
                 │
                 ▼
        ┌──────────────────┐
        │ Feedback / Hints │
        └──────────────────┘
```

---

## 🧠 Learning Through Gameplay

Tiny Planet uses **experiential learning** rather than relying only on static educational content.

Instead of simply telling the player what to do during an emergency, the game allows them to:

1. Explore the environment.
2. Discover interactive elements.
3. Encounter a scenario.
4. Consider an appropriate response.
5. Receive feedback or hints.
6. Continue exploring and learning.

This approach helps transform disaster preparedness from a passive learning activity into an **interactive experience**.

---

## 🛠️ Tech Stack

### Frontend

* **React** – Component-based user interface.
* **TypeScript** – Type-safe application development.
* **Vite** – Fast development environment and build tool.

### State Management

* **Zustand** – Lightweight state management for game state and interactions.

### Styling

* **TailwindCSS** – Utility-first styling and responsive UI development.

### Animation

* **Framer Motion** – Smooth UI transitions and animations.

### UI Components

* **Radix UI** – Accessible and reusable UI primitives.
* **Lucide Icons** – Consistent iconography throughout the application.

### Deployment

* **GitHub Pages** – Hosting the production build.

---

## 🏗️ Application Architecture

The project follows a component-based React architecture.

```text
Tiny Planet
│
├── User Interface
│   ├── Start Screen
│   ├── Game Map
│   ├── Player Avatar
│   ├── NPCs
│   └── Notifications
│
├── Game Logic
│   ├── Scenario Triggers
│   ├── Player Interactions
│   └── Game State
│
├── State Management
│   └── Zustand Store
│
└── Supporting Components
    ├── UI Components
    ├── Hooks
    └── Pages
```

---

## 📂 Project Structure

```text
Tiny-Planet/
│
├── src/
│   ├── components/
│   │   └── # Reusable UI and game components
│   │
│   ├── hooks/
│   │   └── # Custom React hooks
│   │
│   ├── store/
│   │   └── # Zustand game state
│   │
│   ├── pages/
│   │   ├── StartScreen
│   │   └── Index
│   │
│   └── main.tsx
│
├── public/
│   └── 404.html
│
├── package.json
├── package-lock.json
├── vite.config.ts
└── README.md
```

---

## 🚀 Getting Started

### Prerequisites

Make sure you have the following installed:

* **Node.js 18 or later**
* **npm 9 or later**
* A modern web browser
* Git

You can verify your installations using:

```bash
node --version
npm --version
git --version
```

---

## 📥 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/<your-username>/Tiny-Planet.git
```

### 2. Navigate to the Project

```bash
cd Tiny-Planet
```

### 3. Install Dependencies

```bash
npm install
```

---

## 💻 Running the Project

Start the development server:

```bash
npm run dev
```

The terminal will provide the local development URL.

Usually, the application can be accessed at:

```text
http://localhost:5173/
```

Open the URL in your browser to start exploring Tiny Planet.

---

## 🏭 Production Build

To create an optimized production build:

```bash
npm run build
```

To preview the production build locally:

```bash
npm run preview
```

---

## 🌐 Deployment

Tiny Planet can be deployed using **GitHub Pages**.

### Vite Configuration

Make sure the `base` property in `vite.config.ts` is configured according to your repository name:

```ts
export default defineConfig({
  base: "/Tiny-Planet/",
});
```

### Deploy

Run:

```bash
npm run build
npm run deploy
```

After deployment, the application will be available at:

```text
https://<your-username>.github.io/Tiny-Planet/
```

---

## 📜 Available Scripts

| Command           | Description                             |
| ----------------- | --------------------------------------- |
| `npm run dev`     | Starts the development server           |
| `npm run build`   | Creates the production build            |
| `npm run preview` | Previews the production build           |
| `npm run deploy`  | Deploys the application to GitHub Pages |

---

## 🔧 Development Highlights

Some of the important development concepts demonstrated in this project include:

* Component-based React development.
* Type-safe programming using TypeScript.
* Global game-state management using Zustand.
* Reusable UI components.
* Interactive map-based interfaces.
* Event-driven gameplay interactions.
* Animated UI transitions.
* Toast-based user feedback.
* Responsive styling using TailwindCSS.
* Client-side application routing.
* Production deployment using GitHub Pages.

---

## 🌱 Future Improvements

Potential future enhancements for Tiny Planet include:

* 🌪️ Add more disaster scenarios.
* 🏠 Introduce additional interactive locations.
* 🎒 Add an inventory system for emergency supplies.
* 🏆 Introduce points, achievements, and progression.
* 📊 Add a preparedness score based on player decisions.
* 👥 Expand NPC interactions and dialogue.
* 🎮 Add multiple difficulty levels.
* 💾 Add game progress persistence.
* 📱 Improve mobile and tablet gameplay.
* 🔊 Add optional sound effects and background music.
* 🌍 Expand the game world with additional environments.
* 🧑‍🤝‍🧑 Add multiplayer or collaborative preparedness challenges.

---

## 💡 Why Tiny Planet?

Disaster preparedness is often taught through serious instructions, warnings, and emergency manuals. While these resources are important, they can sometimes feel intimidating or difficult to engage with.

**Tiny Planet takes a different approach.**

By combining a cozy visual environment with interactive scenarios and game-based learning, the project aims to make preparedness education feel more approachable.

The idea is simple:

> **Learn by exploring, interact by playing, and become better prepared along the way.**

---

## 📌 Project Highlights

* 🎮 Interactive educational game
* 🗺️ Map-driven gameplay
* 🚨 Disaster preparedness scenarios
* 👤 Avatar and NPC interactions
* 🌌 Animated start screen
* 💬 Interactive feedback and notifications
* ⚛️ React + TypeScript architecture
* 🐻 Zustand state management
* 🎨 TailwindCSS styling
* ✨ Framer Motion animations
* 📱 Responsive web interface
* 🚀 GitHub Pages deployment

---

## 👥 Contributors

| Contributor            |
| ---------------------- |
| Sana Tasneem Azimudin  |
| Nivriti Muthu Vairavan |
| Yashika V              |
| Sharmu R               |

---

## 📄 License

This project was developed for educational and project-development purposes.


# Text-Based Game

Welcome to the **Text-Based Game** repository!  
This is a console-based adventure game written in **Java**, where players interact with the game using text commands.

## Features
- Interactive text-based gameplay
- Simple command-line interface
- Easy to extend with new storylines or features

## Getting Started

### Prerequisites
- Java Development Kit (JDK) installed (version 8 or higher recommended)
- Basic familiarity with running Java programs from the terminal or an IDE

### How to Compile and Run

Open your terminal, navigate to the project directory, then run:

```bash
javac Main.java
java Main

# 🗺️ Adventure

**By Charlie Minges**

Welcome to **Adventure** – a mysterious journey where exploration is your greatest asset. Your goal is to escape an unknown landscape by interacting with your environment, collecting items, and reaching key objectives.

---

## 1. 📘 Introduction

You wake up in an unfamiliar world. With no idea how you got here, your only option is to explore. You'll traverse different rooms, collect useful items, and make important decisions. Ultimately, your goal is to **escape** — and maybe score some points along the way!

---

## 2. 🕹️ Interacting with the World

> **NOTE:** Commands are **NOT case-sensitive**.

### 🔍 `look`

- Use `look` to get a description of your current room, visible directions, and any items present.

### 🔎 `look @ OBJECT`

- Use `look [item_name]` to inspect an object in your **inventory** and get its description.

### 🧭 `move` / `go` / `direction`

- Move using `move north`, `go east`, or just `south`.
- Room descriptions are shown after successful movement.

### 📦 `take` / `get`

- Use `take [item]` to pick up an item in your current room and add it to your inventory.

### 🗑️ `drop`

- Use `drop [item]` to remove an item from your inventory and place it in the current room.

### 🎒 `inventory`

- Shows all items in your inventory (or indicates if it’s empty).

### 🏆 `score`

- Displays your current score.

---

## 3. 🎯 Goals and Scoring

To win, you must:

- Reach a total score of **500 points** by:
  - Taking or dropping specific items in specific rooms.
  - Visiting certain rooms.
- Once you reach 500, you’ll be directed to a final room to escape.

---

## 4. 📄 Text File Format

The game uses **text files** to define rooms, items, and scoring rules.

### 🏠 Rooms

Each room has:
- Name
- Neighbors (north, south, east, west)
- Description (multi-line supported)

**Format:**


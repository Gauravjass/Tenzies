# 🎲 Tenzies Game

A simple and fun implementation of the classic **Tenzies** dice game built with **React**, **TypeScript**, and **Vite**.

The goal of the game is to roll all dice until they show the same number. You can click on individual dice to “hold” them between rolls.

---

## 🚀 Features

- **Hold Mechanism:** Click individual dice to "freeze" them at their current value.
- **Smart Rolling:** Only unheld dice change values when the "Roll" button is clicked.
- **Win Detection:** Automatically detects when all dice match and are held.
- **Accessibility (A11y):** \* Uses `aria-live` regions to announce wins to screen readers.
  - Includes `aria-pressed` states on dice for better context.
  - **Focus Management:** The "New Game" button is automatically focused upon winning for keyboard-friendly restarts.
- **Visual Celebration:** Integrated `react-confetti` to celebrate your victory!

---

## 🛠️ Tech Stack

- **Framework:** React 19
- **Language:** TypeScript
- **Build Tool:** Vite
- **ID Generation:** nanoid for unique React keys.
- **Styling:** CSS3 (Flexbox & Grid).

---

## 📦 Installation & Setup

1.  **Clone the repository:**

    ```bash
    git clone https://github.com/Gauravjass/tenzies.git
    cd tenzies
    ```

2.  **Install dependencies:**

    ```bash
    npm install
    ```

3.  **Start the development server:**

    ```bash
    npm run dev
    ```

4.  **Build for production:**
    ```bash
    npm run build
    ```

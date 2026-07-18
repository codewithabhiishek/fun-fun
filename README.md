# 💾 Windows XP / 95 Desktop Simulator

An interactive, nostalgia-fueled simulation of classic operating systems (Windows 95/XP) built with **TypeScript**, **Tailwind CSS**, and **ESM modules**. This environment features draggable windows, a start menu taskbar, classic retro applications, and interactive layout management.

---

## 🖥️ Active Applications

*   **🎨 GemPaint:** A pixel art canvas drawer featuring active drawing tools, color palettes, and retro canvas brushes.
*   **📝 GemNotes:** A fully functional rich text notepad editor for document formatting, text edits, and brainstorming.
*   **💣 Minesweeper:** The authentic, logic-based minefield grid game with custom difficulty selectors and elapsed timer tracking.
*   **😈 Doom II:** An emulated, classic DOS-run session of Doom II directly inside a draggable desktop window.
*   **🎵 GemPlayer:** A retro Winamp-styled media player for loading and playing YouTube video links.
*   **🌐 Chrome Browser:** A sandboxed in-window web browser emulator.
*   **📂 My Gemtop:** A retro filesystem explorer recreating standard drives and directories.

---

## ⚙️ Core Technical Architecture

*   **Window Manager:** A custom, absolute-positioning z-index coordinate manager implemented in pure TypeScript. It handles smooth dragging, double-click maximization, minimize/restore animation flows, and focus elevation.
*   **Modular Styling:** Handled via Tailwind CSS for the classic pixel-perfect gray bevels, system fonts, and 3D industrial borders.
*   **Module Bundling:** Configured via Vite + TypeScript, deploying optimized ESM build assets.

---

## 🛠️ Running Locally

### Prerequisites
*   Node.js (v18+)

### Setup
1.  **Install dependencies:**
    ```bash
    npm install
    ```
2.  **Start development server:**
    ```bash
    npm run dev
    ```
    Open the local server link in your browser: `http://localhost:3000`

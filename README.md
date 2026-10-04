# Pawn (WotLK 3.3.5 Edition)

**Pawn** helps you find upgrades for your gear by calculating scores for items based on stat weights. It tells you at a glance whether an item is better for your specific spec and shows you exactly how much of an upgrade it is based on customizable scales.

This version is optimized and verified compatible with **World of Warcraft: Wrath of the Lich King (Patch 3.3.5a)** client structures.

---

## 🚀 Features

*   **In-Game Upgrade Tooltips:** Displays absolute score values and upgrade percentages directly on item tooltips.
*   **Custom Stat Scales:** Build your own scale strings or import optimized stat weights for your class and spec.
*   **Dual-Spec Tracking:** Easily compare items against multiple specs simultaneously.
*   **Gem & Enchant Calculation:** Automatically accounts for sockets, socket bonuses, and baseline item stats when determining value.

---

## 🛠️ Installation

1.  **Download** the latest repository archive or clone the project.
2.  Extract or move the folder to your World of Warcraft directory:
    ```text
    C:\YourWoWDirectory\Interface\AddOns\
    ```
    *(Ensure the folder is named exactly `Pawn`. Do not leave it as `Pawn-master` or include nested subfolders.)*
3.  Launch the game client. Ensure "Load out-of-date AddOns" is checked in your character select screen AddOn menu.

---

## ⌨️ Slash Commands

Open the main configuration interface using either of the following chat commands:

*   `/pawn`
*   `/pawn ui`

---

## 📊 How to Import Custom Weights

1.  Open the Pawn interface (`/pawn`).
2.  Navigate to the **Scale** tab.
3.  Click the **Import** button.
4.  Paste your 3.3.5-compatible scale string (e.g., from Rawr or community spreadsheets) into the text field and click **OK**.

---

## 🤝 Contributing

If you find a broken tooltip calculation or want to contribute updated default presets for 3.3.5 raiding phases:

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a Pull Request.

---

## 📝 License

Distributed under the MIT License. See `LICENSE` for more information.

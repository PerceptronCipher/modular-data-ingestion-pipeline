**🚀 Modular Data Ingestion Pipeline**

**Crafted by The PerceptronCipher**

**📌 The Mission**

Most write scripts that only work once. I built this to be a reusable, 'bulletproof' engine for the most critical stage of any AI/ML project: Data Ingestion. This pipeline automates fetching raw data from the web, cleaning the 'junk' columns, and splitting the results into training and testing sets—all while keeping a professional log of every single move.

**🛠️ Engineering Highlights**

📍 Reusability (DRY): Built with a modular function structure (Load → Preprocess → Save) so I can swap datasets in minutes instead of rewriting code.

📍 No more print() debugging: I implemented a professional dual-handler logger that reports status to the console and writes a persistent history to a local .log file.

📍 Defensive Coding: The script is designed to fail gracefully. It uses specific try-except blocks to catch missing columns or network errors and logs exactly what went wrong.

📍 Production Standards: Used the if __name__ == "__main__": pattern to ensure this module is importable into larger ML systems without side effects.


**📂 Project Structure**
🚦 Quick Start

    Clone the repo:

    Install the gear:

    Launch the engine:
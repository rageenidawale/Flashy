# 📖 Flashy Language Learning App

## Overview
A **flashcard-based language learning app** built with Python and Tkinter to help users memorize French-English words. The app displays French words on flashcards, and after a few seconds, it flips to reveal the English translation. Users can mark words they know, which are removed from future learning sessions.

## Features
- **Random word selection** for efficient learning.
- **Automatic card flipping** after 3 seconds.
- **Track words to learn** (removes known words).
- **Data persistence**: Saves progress in `words_to_learn.csv`.

## Requirements
- Python 3.x
- `tkinter` (built-in with Python)
- `pandas` (for data handling)
- `random` (for word selection)

## Installation
1. Clone or download this repository.
2. Ensure the following files exist:
   ```
   |-- data/
     |-- french_words.csv # Original dataset
     |-- words_to_learn.csv # Saves user progress (auto-generated)
   |-- images/
     |-- card_front.png
     |-- card_back.png
     |-- right.png
     |-- wrong.png
     |-- main.py # Main script
   ```
3. Install dependencies:
```bash
pip install pandas
```
4. Run the script:
```bash
python main.py
```

## Usage

1. The app displays a **French word** on a flashcard.
2. After **3 seconds**, it flips to reveal the **English translation**.
3. Click:
   - ✅ **(Right Button)** if you know the word _(removes it from future sessions)_.
   - ❌ **(Wrong Button)** to keep the word _(for further learning)_.
4. The app **remembers known words**, so each session improves efficiency.


## Future Enhancements
- **Add more languages (Spanish, German, etc.).**
- **Include pronunciation audio for better learning.**
- **Improve UI with animations for smooth transitions.**

Start learning French with this interactive **flashcard app!** 📖

   

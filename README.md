# Brute Force List Generator

This Python script generates a wordlist containing all possible combinations of characters up to a specified length. The generated wordlist is saved to a file in the `wordlist` directory.

## 🪄 Features
- Supports all ASCII letters, digits, and punctuation characters.
- Allows the user to specify the desired length of character combinations.
- Buffers combinations to optimize file writing.
- Ensures the output file does not overwrite existing files.

## ✨ How to Use
1. Run the script `main.py`.
2. Enter the desired file name for the wordlist.
3. Specify the maximum length of character combinations.
4. The script will generate the wordlist and save it to the specified file in the `wordlist` directory.

## 🧩 Example
```
Enter the file name: example_wordlist.txt
Enter the desired length of character combinations:
2
Done. The file example_wordlist.txt has been created.
```

## 🛡️ Requirements
- Python 3.x

## 📚 Notes
- The script creates a `wordlist` directory if it does not already exist.
- If the specified file name already exists, the script will prompt the user to choose another name.
- A short pause is added during file writing to reduce CPU usage.

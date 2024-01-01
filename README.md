# Project Description
This project presents a real-time system designed to identify and correct both non-word errors (misspelled words) and real-word errors (correctly spelled but contextually incorrect words) in text. Utilizing fundamental natural language processing (NLP) techniques, this system offers an efficient and user-friendly interface for enhancing writing accuracy and clarity.

# Installation
Before you begin, ensure you have Python installed on your system. Installation
1) Clone or Download the Project: use git clone to clone the repository, or download it as a ZIP file and extract it.
```bash
git clone https://github.com/alexy208/Simple-realtime-grammar-and-spelling-checker.git
```

2) Install Required Libraries: This project requires several Python libraries. You can install them using pip. Open your terminal or command prompt and navigate to the project directory, then run the following command:
   ```bash
   pip install nltk tkinter Levenshtein
   ```

3) Running the Application Launch the Application: Open a terminal or command prompt. Navigate to the project directory and the codes folder. Run the following command:
   ```bash
   python NLP_word_checker.py
   ```

# How It Works
The system operates in real-time, analyzing text input by the user. It employs two primary mechanisms:

- Non-Word Error Detection: Identifies misspelled words that do not match any word in the language dictionary.
- Real-Word Error Detection: Recognizes correctly spelled words that are used incorrectly within the given context.

Using a combination of dictionary-based checks and contextual analysis, the system not only flags errors but also suggests appropriate corrections.

https://github.com/alexy208/Simple-realtime-grammar-and-spelling-checker/assets/126884588/bcb80744-26fe-4ea9-8c2e-a9cb73e24a86

For a comprehensive understanding of this project, including its design philosophy, development process, and technical specifications, please refer to our detailed project report. The report offers in-depth insights into the project's creation and can serve as a valuable resource for those interested in the finer details or the educational aspects of this project. 

You can access the report here: [NLP word checker report.docx](https://github.com/alexy208/Simple-realtime-grammar-and-spelling-checker/blob/44870aa944fc7d0a232ad1b7e55cef425ee4c0b5/NLP%20word%20checker%20report.docx).

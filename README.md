# Translation Comparison and Accuracy Verifier

## Description
This program compares an English-translated document with its original Portuguese version to verify translation accuracy. It leverages **Python** and integrates libraries such as `docx`, `deep_translator`, `difflib`, and `tqdm` to extract content, translate text, and generate detailed reports highlighting differences.

## Features
- **Text Extraction**: Extracts content from `.docx` files, including paragraphs and table data.
- **Automated Translation**: Utilizes the `deep_translator` library with **GoogleTranslator** for translating Portuguese text into English.
- **Similarity Analysis**: Compares original and translated texts using a configurable similarity threshold.
- **Report Generation**: Produces comprehensive reports detailing differences, including context and suggested corrections.
- **Customizable Threshold**: Allows users to define the similarity threshold to refine comparison sensitivity.
- **Progress Tracking**: Displays progress bars for text processing and comparisons using `tqdm`.

## Setup
### Prerequisites:
- Python 3.7+
- Install the required libraries:
  ```bash
  pip install python-docx deep-translator tqdm


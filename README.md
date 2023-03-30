# NCERT Book PDF Text Extractor

This repository contains the code for an NCERT book PDF text extractor. The extractor extracts the text of the book, cleans it using Natural Language Processing techniques, and then splits the text into separate entries in a CSV file.

## Usage

To use the extractor, follow these steps:

1. Download the NCERT book PDF that you want to extract the text from.

2. Install the required packages.

3. Run the `NCERT_Book_Text_Extraction` file. This will first clean the text and then split the it into separate entries in a CSV file.

## Cleaning

The text is cleaned using the following Natural Language Processing techniques:

1. **Stop Word Removal**: Remove commonly used words that don't add much meaning to the text, such as "the", "and", and "is".

2. **Regex Cleaning**: Remove any unnecessary characters and symbols from the text, such as punctuation marks and special characters.(According to the need) 

## Output

The output CSV file contains three columns, `text`, which contains the split text, 'page no' that refers to page of that text and 'book_name' that can be used when multiple books dataset is created.

## Conclusion

This NCERT book PDF text extractor demonstrates how Natural Language Processing techniques can be used to clean and extract text from PDF files. With the cleaned text in a CSV file, it is now easier to perform further analysis and processing on the text.


Spacy NLP Task2
This program demonstrates the use of the Spacy library for natural language processing (NLP).

Installation
To use this program, you will need to have Spacy installed. You can install it using pip:

Copy code
pip install spacy
You will also need to download the en_core_web_md language model:

Copy code
python -m spacy download en_core_web_md
Usage
This program shows two examples of working with Spacy.

Working with vectors
The first example demonstrates how to work with vectors in Spacy. It loads the en_core_web_md model and calculates the similarity between each pair of tokens in the input string "cat apple monkey banana".

Working with sentences
The second example demonstrates how to work with sentences in Spacy. It compares the similarity between the input sentence "Why is my cat on the car" and a list of other sentences.

To run the program, simply run the following command in your terminal:

Copy code
python spacy_example.py
Note
This is just a simple example to demonstrate some basic functionalities of the Spacy library. Spacy has many more powerful features and capabilities for natural language processing, and I encourage you to explore them further.
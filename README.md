# Vigenère Cipher Decoder

## Introduction

This project demonstrates how to decode a message encrypted with the Vigenère cipher. The Vigenère cipher is a method of encrypting alphabetic text using a simple form of polyalphabetic substitution. It uses a keyword to shift letters in the plaintext to create the ciphertext. To decrypt, we shift each letter in the opposite direction based on the corresponding letter in the keyword.

## Example

In this example, we use the key **MENSA** to decode an encrypted message that consists of two parts:
- The first line is a message in 粵語拼音 (Yale romanization for Cantonese).
- The second line is a hidden message in English.

## How It Works

1. **Encoding**: Each letter in the plaintext is shifted by a certain number of positions down the alphabet, determined by the corresponding letter in the keyword.
2. **Decoding**: Each letter in the ciphertext is shifted back by the same number of positions up the alphabet, using the same keyword.

## Notebook Overview

The notebook includes:
- An explanation of the Vigenère cipher.
- A Python function to decode messages encrypted with the Vigenère cipher.
- An example of an encrypted message and the key used for decoding.
- A step-by-step walkthrough of the decoding process.
- Interpretation of the decoded message.

You can run the notebook on Google Colab using the following link:
[Run on Google Colab](https://colab.research.google.com/drive/1lrGJsmJ970G0yjWFwl5JlUZN5eA_9Y9g?usp=sharing)

## Conclusion

This project demonstrates how the Vigenère cipher can be used to encode and decode messages in multiple languages using the same key. It provides a practical example of how polyalphabetic substitution ciphers work and how they can be implemented in Python.

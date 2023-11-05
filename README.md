# SummPip - Multi-Document Summarizer

## Project Description

SummPip is a comprehensive multi-document summarizer that provides various summarization techniques for different use cases. It is designed to handle extractive summarization, abstractive summarization, and cluster-based compression. The project consists of several Jupyter notebooks, each focusing on a specific aspect of summarization.

## Notebooks and Functionality

1. **SMAI_part1.ipynb**
   - This notebook contains the implementation of Frequency-based and Tf-Idf-based extractive summarization techniques.

2. **SMAI_part2.ipynb**
   - It contains the implementation of the project paper's SummPip algorithm. This paper is a reference for the project's core functionality.

3. **SMAI_part3.ipynb**
   - This notebook focuses on the implementation of seq2seq LSTM-based abstractive summarization.

4. **SMAI_part4.ipynb**
   - It contains the implementation of seq2seq bidirectional LSTM for abstractive summarization.

5. **SMAI_part5.ipynb**
   - This notebook demonstrates the use of pre-trained Hugging Face Transformer models for abstractive summarization.

## Installation and Dependencies

To run the provided notebooks and the SummPip project, make sure to install all the required dependencies. You can find these dependencies in the `requirements.txt` file. Use the following command to install them:

```bash```
pip install -r requirements.txt

Compression Module
In the project directory, you will find ./Resources/takahe.py. This module contains functions for cluster-based compression, which is a unique feature of SummPip.

Trained Model
A trained seq2seq model is available at the following link:
Trained Seq2Seq Model

This model can be used in conjunction with the provided notebooks to perform abstractive summarization.

How to Use
Each notebook provides documentation and examples for its specific summarization technique. Follow the instructions and code provided in the notebooks to generate summaries for your multi-document content.

Contribution
We welcome contributions from the open-source community. If you'd like to enhance the project, report issues, or suggest improvements, please feel free to do so.

License
The SummPip project is open-source and available under a permissive license. You are encouraged to collaborate, modify, and distribute the project as needed.

Acknowledgments
We extend our gratitude to the open-source community and contributors who have supported the development of SummPip. Our goal is to provide a versatile summarization tool for a wide range of use cases.

For more information and details, please refer to the project's specific notebooks and documentation.

kotlin
Copy code

Feel free to adjust this README.md as needed and provide more specific details

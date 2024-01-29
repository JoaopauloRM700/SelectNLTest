# SelectNLTest

## Overview

SelectNLTest aims to enhance your testing process by addressing two key objectives: the removal of duplicate test cases and the transcription of these cases into natural language. This module specifically targets test cases generated by the DRL-MOBTEST tool.
Key Objectives

  - Duplicate Test Case Removal: SelectNLTest is designed to identify and eliminate duplicate test cases, optimizing the efficiency and organization of your test suite.

  - Natural Language Transcription: The module employs advanced techniques to transcribe test cases into natural language, making them more accessible and comprehensible to a wider audience.

## How It Works

  - Duplicate Test Case Identification: SelectNLTest analyzes test cases produced by the DRL-MOBTEST tool, identifying and removing duplicates to streamline the testing process.

  - Natural Language Transcription: Leveraging advanced algorithms, the module transforms test cases into a more human-readable format, improving overall clarity and understanding.
    
### 📋 Requirements

- Python 3.10.9

### 🔧 Installation

```bash
pip install -r requirements.txt
```

### 🚀 Getting Started

Setting Up the Virtual Environment

Install virtualenv using the following command:


    pip install virtualenv

Create a virtual environment named venv:

    virtualenv venv

Activate the virtual environment:

    source venv/bin/activate


### ⚙️ Running the Similarity Removal and Transcription

To execute the transcription process, run the `main.py` script. This script utilizes the OpenAI GPT-3.5 Turbo model to generate transcriptions for a set of input documents. Adjust the paths in the `input_folder` and `output_folder` variables according to your project structure.

```bash
python main.py
```


### 🖇️ Contributing

If you are interested in contributing to this project, feel free to create a pull request. Please adhere to our code of conduct to ensure a positive and collaborative environment.


###✒️ Authors

- André Santos
- João Paulo Marques
- Bruno Souza 
- Mônica Lima 
- Eloise Miranda
- Eliane Collins

## 📄 Article

## Title: SelectNLTest - Selection and Natural Language Rewriting of Test Cases Generated by the DRL-MOBTEST Tool

### Abstract
The software testing process is important to ensure quality, especially in mobile applications that have characteristics such as platform diversity, hardware limitations, portability, frequent updates, among others. Software companies need to deliver quickly with increasingly complex functionalities; therefore, the testing process must be efficient and avoid bottlenecks, such as the creation of test cases. Among the solutions found in the literature, the state-of-the-art tool DRL-MOBTEST aims to assist in the automatic generation of test cases for mobile applications using deep reinforcement learning. The experiments show promising results; however, the tool has some limitations, such as generating duplicate and less readable tests. In this article, we present SelectNLTest, a module developed to identify and remove similar test scripts and transcribe the test cases generated by the tool using Natural Language Processing techniques. This allows for the removal of similar tests and improves the readability and understanding of the generated test cases for professionals in the field. The results of the experiments showed that, in 10 Android applications used in the comparative analysis, the proposed module reduced the number of test cases by 58.3% while maintaining code coverage and application functionality.
### Link
[Read the full article](https://dl.acm.org/doi/10.1145/3624032.3624043)

### 📜 License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
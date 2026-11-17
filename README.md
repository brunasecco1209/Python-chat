# Python Consulting and Programming

## About the Project

This project consists of developing a **second brain** powered by Generative Artificial Intelligence (LLM), through NotebookLM, based on Gemini models, with a focus on **Python Consulting and Programming**.

The goal is to create a specialized assistant that uses a previously curated knowledge base to answer questions, explain concepts, assist in algorithm development, analyze code, identify potential errors, and suggest corrections based on the provided materials.

The purpose is to use artificial intelligence as a tool to support learning and Python development, ensuring that responses are grounded in the sources added to the notebook, with references that allow users to verify the origin of the information.

## Objectives

- Centralize Python-related content and study materials in a single knowledge base.
- Use artificial intelligence to interpret and explain programming concepts.
- Assist in writing, analyzing, and debugging Python code.
- Identify errors and provide possible solutions based on the available sources.
- Facilitate learning through practical explanations and code examples.
- Improve response reliability through citations of the sources used.

## Knowledge Organization

The notebook's knowledge base is organized into eight main areas:

1. **Logic and Algorithms:** programming logic fundamentals, algorithm representation, and problem-solving.
2. **Integrated Development Environments (IDEs):** tools used for Python development, such as VS Code and Spyder.
3. **Data Types and Variables:** primitive data types, type conversion, variable declaration, and manipulation.
4. **Operators:** arithmetic, relational, and logical operators and their applications.
5. **Control Structures:** conditional statements, loops, and execution flow control.
6. **Functions and Modularization:** function creation, parameters, arguments, return values, and code organization.
7. **Data Structures:** lists, tuples, sets, dictionaries, and matrices.
8. **Exception Handling:** identifying and handling errors during program execution.

## Knowledge Sources

Educational materials, books, technical documents, and video tutorials on Python programming were selected, covering topics ranging from fundamental concepts to more advanced subjects.

### Books and Technical Materials

| Source | Reason for Selection |
|---|---|
| [Learning Python](https://cfm.ehu.es/ricardo/docs/python/Learning_Python.pdf) | Reference material for a deeper understanding of the language fundamentals. |
| [Python Programming](https://www.halvorsen.blog/documents/programming/python/resources/Python%20Programming.pdf) | Educational material focused on learning and practical Python applications. |
| [Introduction to Python – IFRN Publishing](https://memoria.ifrn.edu.br/bitstream/handle/1044/2090/EBOOK%20-%20INTRODU%C3%87%C3%83O%20A%20PYTHON%20%28EDITORA%20IFRN%29.pdf?sequence=1&isAllowed=y) | Educational material available through the institutional repository of the Federal Institute of Rio Grande do Norte (IFRN), Brazil. |
| [Programming with Python](https://thomasweise.github.io/programmingWithPython/programmingWithPython.pdf) | Complementary material for studying programming concepts and practices. |

### Video Tutorials

Videos were added as complementary resources to reinforce theoretical concepts and provide practical examples.

- [Video Tutorial 01](https://www.youtube.com/watch?v=QA1S4wCNvEE)
- [Video Tutorial 02](https://www.youtube.com/watch?v=K5KVEU3aaeQ)
- [Video Tutorial 03](https://www.youtube.com/watch?v=_uQrJ0TkZlc)
- [Video Tutorial 04](https://www.youtube.com/watch?v=H2E2JuAcrZYU)
- [Video Tutorial 05](https://www.youtube.com/watch?v=mDKM-JtUhhc)
- [Video Tutorial 06](https://www.youtube.com/watch?v=3Ozrs0MpW5s)

### Source Reliability Criteria

The selection of sources considers their educational purpose, direct relevance to Python programming topics, availability for consultation, and institutional or technical background whenever identifiable.

For example, the material provided by IFRN originates from an institutional repository. The other documents are used as complementary study references.

The video tutorials are considered supplementary learning materials, and their authorship, the contributors' expertise, and content relevance should also be considered.

## Notebook Behavior Guidelines

The notebook was configured to act as a consultant specialized in Python programming, primarily using the sources provided in its knowledge base.

Its behavioral guidelines instruct the model to:

- Base its responses on the provided materials.
- Include citations that allow users to identify the sources used.
- Explain concepts clearly, didactically, and in an organized manner.
- Provide practical Python code examples when necessary.
- Analyze user-submitted code and identify potential errors.
- Suggest corrections while preserving the original code structure whenever possible.
- Avoid unnecessary modifications and prioritize simple, clean, and functional solutions.
- State when certain information is not covered by the available sources.
- Avoid presenting unsupported information as if it came from the consulted materials.

## Notebook Testing and Interaction

**Question asked:**

How can I write a Python program to add two numbers entered by the user?

**Response provided:**

The notebook presented four steps for building the program:

1. Data input: using the `input()` function to receive the numbers.
2. Type conversion: using `float()` to allow decimal numbers or `int()` to work with integers.
3. Mathematical operation: using the `+` operator to perform the addition.
4. Data output: using `print()` to display the result.

**Code example provided:**

```python
# Request the two numbers from the user
n1 = float(input('Enter the first number: '))
n2 = float(input('Enter the second number: '))

# Perform the addition
sum_result = n1 + n2

# Display the result
print('The sum of the two numbers is:', sum_result)
```

**Sources used:** The notebook displayed numbered citations throughout the response. The specific source names should be recorded based on the references displayed in the original interaction.

**Evidence:**

<img width="1071" height="735" alt="Notebook response screenshot" src="https://github.com/user-attachments/assets/649a2479-f953-4e55-a517-30186ff283ba" />

## Project Materials

The materials created and collected for the project are available in this repository.

These include:

- Mind map organizing the programming topics.
- Briefing document.
- Video demonstrating how loops work.

## Notebook Access

The notebook can be accessed through the link below:

[**Access Python Consulting and Programming – NotebookLM**](https://notebook.google.com/notebook/924a2e50-20a0-4e1f-b5a2-1becf4b7fa44)

## Final Considerations

This project demonstrates the application of Generative Artificial Intelligence as a tool to support learning and problem-solving in programming.

Combining a structured knowledge base with the interpretative capabilities of an LLM makes it possible to build an assistant that not only provides solutions but also contextualizes its responses and offers references for further consultation.

Rather than simply using artificial intelligence to generate code, the goal is to develop a knowledge-based learning environment that encourages understanding of programming logic, code quality, and independence in problem-solving.

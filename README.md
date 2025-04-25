# Structured Reasoning Dataset

## Overview

This repository contains a collection of structured data representing various types of reasoning problems and their corresponding solutions or explanations. The data is designed for use in AI research, natural language processing (NLP), educational applications, and anyone interested in computational logic and reasoning processes.

The datasets cover a range of reasoning types, including:

*   Logical Deduction (Syllogisms, Conditionals)
*   Scientific Reasoning (Causal Explanations, Predictions, Applying Principles)
*   Abductive Reasoning (Inference to Best Explanation)
*   Inductive Reasoning (Pattern Recognition, Generalization)
*   Problem Solving (Mathematical, Algorithmic)
*   Code Generation/Explanation/Debugging
*   Concept Explanation
*   Fallacy Identification

## Data Format

The data is primarily stored in plain text files (`.txt`) containing JSON-like structures or directly in JSON files (`.json`). Each entry typically represents a single reasoning task and includes fields such as:

*   **`id`**: A unique identifier for the item.
*   **`input` / `problem` / `Problem Statement`**: The question, prompt, or scenario presented.
*   **`output` / `answer` / `Solution`**: The expected correct answer or generated output (e.g., code, explanation, classification).
*   **`reasoning_steps` / `explanation` / `Step-by-Step Explanation`**: A breakdown of the logical or procedural steps taken to arrive at the answer/output.
*   **`meta` / `Metadata`**: Additional information about the task, such as:
    *   `language` (e.g., python, javascript, git)
    *   `type` / `Type of Reasoning` (e.g., deductive, inductive, causal explanation)
    *   `task_type` (e.g., function_generation, concept_explanation, bug_fixing, complexity_analysis)
    *   `difficulty` (e.g., easy, medium, hard)
    *   `tags` (relevant keywords)

*Note: Field names may vary slightly between different files.*

## Files

*   `code.txt`: Examples related to code generation, explanation, and debugging in Python and JavaScript.
*   `deep logical resoning.txt`: More complex reasoning problems with detailed step-by-step explanations (scheduling, diagnosis, logical puzzles).
*   `logical short reasoning.txt`: A large set of short, formal logic problems (syllogisms, conditionals) with brief reasoning.
*   `science_logic_reasoning_data.json`: Structured JSON data combining scientific and logical reasoning tasks.
*   `simple short science reasoning.txt`: Basic science-related reasoning questions and explanations.
*   `symbolic reasoning.txt`: Examples focused on reasoning with scientific principles presented symbolically or contextually.
*   `syntehtic data for long general reasoning.txt`: General knowledge reasoning problems requiring multi-step explanations.
*   `syntehtic data for short general reasoning.txt`: Concise general knowledge reasoning problems.
*   `.gitattributes`: Configuration file for Git handling line endings.

## How to Use

This dataset can be used for various purposes:

*   **Training AI Models:** Fine-tuning large language models (LLMs) or developing specialized models for logical reasoning, code understanding, scientific explanation, or step-by-step problem solving.
*   **Evaluating Models:** Assessing the reasoning capabilities of AI systems.
*   **Educational Resource:** Providing examples for teaching logic, critical thinking, and scientific reasoning.
*   **Data Analysis:** Studying patterns in different types of reasoning.

## Contributing

Contributions are welcome! If you find issues, have suggestions, or want to add more data, please feel free to open an issue or submit a pull request.



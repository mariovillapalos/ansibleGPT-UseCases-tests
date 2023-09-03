# ansibleGPT: Use Case Tests

This repository contains the tests conducted to evaluate the use cases of AnsibleGPT, a natural language-based infrastructure automation tool. These tests are divided into nine use cases, each of which has two variants: "low" (less detailed) and "high" (highly detailed), representing different levels of complexity in the prompts used.

## Folder Structure

The repository is organized as follows:

- `case1/`: Tests corresponding to Use Case 1.
  - `low/`: Tests with less detailed prompts.
    - `playbook_low.yml`: Playbook generated with a less detailed prompt.
    - `output_low.txt`: Result of the execution of the less detailed playbook.
  - `high/`: Tests with highly detailed prompts.
    - `playbook_high.yml`: Playbook generated with a highly detailed prompt.
    - `output_high.txt`: Result of the execution of the highly detailed playbook.
  (Repeat structure for Use Cases 2 through 9)

## Project Description

The aim of this project is to assess the performance and effectiveness of AnsibleGPT in different usage scenarios. Each use case represents a different application scenario, and prompts with varying levels of detail are used to generate the playbooks.

## Configuration and Usage

To run these tests in your local environment, follow these steps:

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/mariovillapalos/ansibleGPT



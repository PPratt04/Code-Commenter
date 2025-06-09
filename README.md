# Code Commenter

**Code Commenter** is a Python 3-based tool that automatically generates descriptive comments for Python code. It is designed to assist developers, students, and educators by improving code readability and documentation with minimal manual effort.

## Features

- Parses Python source files and inserts meaningful comments.
- Supports function-level and line-by-line annotation.
- Lightweight and easy to integrate into existing workflows.
- Ideal for educational use, code reviews, and onboarding new developers.

## Getting Started

### Prerequisites

- Python 3.7 or higher
- `ast` (built-in)
- Any additional dependencies (list them here if applicable)

### Installation

Clone the repository:

```bash
git clone https://github.com/PPratt04/Code-Commenter.git
cd Code-Commenter
```

(Optional) Create a virtual environment:

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

### Usage

Run the script on a Python file:

```bash
python commenter.py path/to/your_script.py
```

The tool will output a new version of the file with comments inserted above functions and key logic blocks.

## Example

**Input:**

```python
def add(a, b):
    return a + b
```

**Output:**

```python
# This function adds two numbers and returns the result
def add(a, b):
    return a + b
```

## Contributing

Contributions are welcome! Feel free to fork the repo and submit a pull request.


## Author

Created by **Parker Pratt**  
For questions or suggestions, please open an issue or contact via GitHub, Handshake, LinkedIn, or email.

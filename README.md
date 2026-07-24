# Python Tutorial for Absolute Beginners
 
This is a beginner-friendly, self-paced introduction to Python programming using interactive Jupyter notebooks. 

This tutorial is designed for people who are learning programming for the first time. It uses simple explanations, relatable analogies, runnable examples, and practice exercises to help learners understand Python without being overwhelmed by too many resources.

The notebooks are arranged in a recommended learning order. Learners should follow them sequentially because each lesson builds on concepts introduced earlier.

This repository does not include video lectures or recorded explanations. Additional books, documentation, and course recommendations are provided for learners who would like further explanation.

## Who This Tutorial Is For

This tutorial is suitable for:

- Complete programming beginners
- Students learning Python for the first time
- Learners who prefer hands-on examples
- Anyone who wants to refresh basic Python concepts

No previous programming experience is required.

## Learning Approach

Each notebook may include:

- Learning objectives
- Simple analogies and explanations
- Runnable Python examples
- Line-by-line code explanations
- Common mistakes
- Practice exercises
- Small coding challenges

For the best learning experience:

1. Follow the notebooks in numerical order.
2. Run every code cell.
3. Modify the examples and observe what changes.
4. Predict the output before running the code.
5. Attempt the exercises before checking the solutions.
6. Revisit previous lessons whenever a concept is unclear.

## Topics Covered

The tutorial covers:

- Introduction to programming
- Why Python is useful
- Setting up Python and Visual Studio Code
- Printing output
- Variables, values, and basic data types
- Identifiers, keywords, and naming conventions
- Operators and expressions
- User input
- Conditional statements
- Loops and iteration
- Strings
- Lists
- Tuples
- Dictionaries
- Sets
- Functions
- Variable scope
- Files and paths
- Errors and debugging
- Exception handling

Advanced Python, object-oriented programming, and data structures and algorithms will be covered separately.

## Running the Tutorial Online

You may read the notebooks directly on GitHub. However, GitHub displays notebooks as static pages, so the code cannot be executed there.

To run and modify the examples, download the repository and open the notebooks locally using Visual Studio Code or Jupyter.

## Running the Tutorial Offline

### Option 1: Download as a ZIP File

This is the simplest option for complete beginners.

1. Open the repository on GitHub.
2. Select Code.
3. Select Download ZIP.
4. Extract the downloaded ZIP file.
5. Open the extracted folder in Visual Studio Code.

### Option 2: Fork and Clone the Repository

Git is optional and is not required to complete this tutorial.

Learners who already have Git installed can clone the repository:

```bash
git clone https://github.com/AnusreeSunilkumar/python-for-absolute-beginners.git
cd python-for-absolute-beginners
```

### Option 3: Fork and Clone the Repository 

Forking is optional. Use this option if you have a GitHub account and want your own online copy of the repository. 

1. Open the repository on GitHub. 
2. Select **Fork**. 
3. Create the fork under your GitHub account. 
4. Open your forked repository. 
5. Select **Code** and copy its URL. 
6. Clone your fork: 
```bash 
git clone https://github.com/your-username/python-for-absolute-beginners.git 
cd python-for-absolute-beginners 
``` 

Replace `your-username` with your GitHub username.

Forking allows you to save your changes to your own GitHub repository and submit contributions later.

## Setting Up the Environment

Install a stable version of Python and Visual Studio Code.

Recommended Visual Studio Code extensions:

- Python
- Jupyter

### Create a virtual environment:

#### Windows Command Prompt 

```bat 
python -m venv .venv 
.venv\Scripts\activate 
```

#### Windows PowerShell 

```powershell 
python -m venv .venv 
.venv\Scripts\Activate.ps1 
``` 
#### macOS or Linux 

```bash 
python3 -m venv .venv 
source .venv/bin/activate 
```

### Install the required packages:

```bash
pip install -r requirements.txt
```

Open Visual Studio Code and select the Python interpreter from the `.venv` environment.

## References

The tutorial is supported by the following resources:

1. Python Crash Course by Eric Matthes
2. Think Python by Allen B. Downey
3. [Python documentation](https://docs.python.org)

See [Learning Resources](references/learning_resources.md) for additional books and course recommendations.

## Contributions

Corrections and suggestions are welcome.

When contributing:

- Keep explanations suitable for complete beginners.
- Use simple and meaningful examples.
- Avoid introducing concepts before they are explained.
- Make sure notebook cells run in the correct order.
- Avoid unnecessary dependencies.
- Use current Python syntax and recommended practices.

## License

This project is licensed under the MIT License.

See the [LICENSE](LICENSE.txt) file for details.
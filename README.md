# Code-Refactoring-Tools
Awesome Tools For Refactoring Code

## Python Tools For Refactoring Code
### What is Refactoring?
+ The process of restructuring existing computer code—changing —without changing its external behavior. 
+ Refactoring is intended to improve nonfunctional attributes of the software. 

#### Advantages of Refactoring
+ Improved code readability
+ Reduced complexity; 
+ Improve source-code maintainability 
+ Improve extensibility.

#### It includes
+ Upgrade your dependencies to newer version
+ Rename your code functions, classes, modules, etc
+ Reorganize your code base, moving a function from a file to another
+ Improve implementation of a function to increase performance
+ Reformat your code to make it standards compliant
+ Following design patterns

#### Pre-Refactoring & Refactoring and Post-Refactoring
+ Check Code Quality
+ Static Code Analysis [easily identify the vulnerabilities without executing the program]
+ Measure Code Metrics[Complexity of Code/Maintainablity]
+ Testing
+ Structuring or Reorganizing
+ Remove duplicates and Reduntant Code
+ Decomposition/Separation
+ Backward Compatibility
+ Design Patterns and Style Guide
+ Documentation of Differences and Updates

### Tools and Description
#### IDE Plugins +
+ PyCharm – Cross-platform Python IDE with code inspections available for analyzing code on-the-fly in the editor and bulk analysis of the whole project.
+ PyDev – Eclipse-based Python IDE with code analysis available on-the-fly in the editor or at save time.

#### Check Security and Vulnerabilities
+ bandit - a tool to find common security issues in Python code
+ py-find-injection - find SQL injection vulnerabilities in Python code
+ Dlint - a tool for ensuring Python code is secure

#### Formating and Linting
+ bellybutton - a linting engine supporting custom project-specific rules
+ Black - The uncompromising Python code formatter
+ PyLint

#### Static Type Checking
+ mypy - a static type checker that aims to combine the benefits of duck typing and static typing, frequently used with MonkeyType
+ pyre-check - A fast, scalable type checker for large Python codebases
+ PyT - Python Taint - A static analysis tool for detecting security vulnerabilities in Python web applications.
+ pytype - A static type analyzer for Python code.
+ pyright - Static type checker for Python, created to address gaps in existing tools like mypy.
+ jedi - autocompletion/static analysis library for Python
+ Pylint – Static code analyzer. Quite stringent; includes many stylistic warnings as well.
+ Sonargraph  – Static analyzer for Python 3 with focus on structure, architecture and metrics.

#### Code Metrics and Complexity
+ mccabe - check McCabe complexity
+ radon - a Python tool that computes various metrics from the source code
+ xenon - monitor code complexity using radon

#### Styling and Formating
+ pycodestyle - (formerly pep8) check Python code against some of the style conventions in PEP 8
+ pydocstyle - check compliance with Python docstring conventions
+ pyroma - rate how well a Python project complies with the best practices of the Python packaging ecosystem, and list issues that could be improved
+ wemake-python-styleguide - the strictest and most opinionated python linter ever

#### Error Checking
+ pyflakes - check Python source files for errors
+ pylint - looks for programming errors, helps enforcing a coding standard and sniffs for some code smells. It additionally includes pyreverse (an UML diagram generator) and symilar (a similarities checker).
+ linty fresh - parse lint errors and report them to Github as comments on a pull request

#### Others
+ wily - a command-line tool for archiving, exploring and graphing the complexity of Python source code
+ vulture - find unused classes, functions and variables in Python code
+ cohesion - a tool for measuring Python class cohesion

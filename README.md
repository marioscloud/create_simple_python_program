# Python Programming 

In this lab, we will create and run a simple Python program. We will install a library, create a code file, save it, and edit it to make changes.

## Objectives

1. Install a python package using the terminal.
2. Create a simple Python program using bash.
3. Execute the program.
4. Edit the source code and re-run the program.

This hands-on lab is part of the course **Developing AI Applications with Python and Flask** within the **IBM DevOps and Software Engineering Professional Certificate**.

## Getting Started

Follow these steps to get started with the lab:

1. **Install a Package Using Terminal**:
   - Open the terminal.
   - Verify that python is installed:
   ```bash
   python3 --version
   ```
   - You should see output similar to this, though the versions may be different:
    Python 3.12.3
   - Install the numpy package.
     python3.11 -m pip install numpy

2. **Create a Simple Python Program Using Bash**:
   - In the terminal, create a new Python file (e.g., `hello_world.py`):
     ```bash
     touch python_program1.py
     ```
   - Open the file in your console and write a simple Python program:
     ```bash
     import numpy as np
     a = np.array([1,2])
     b = np.array([3,4])
     c = a + b
     print(c)
     ```
     
3. **Execute the Program**:
   - Run the Python program using the terminal:
     ```bash
     python python_program1.py
     ```

4. **You will get the following output!**:
     ```bash
     [4 6]
     ```

## Additional Resources

- [Python Documentation](https://docs.python.org/3/)
- [IBM DevOps and Software Engineering Professional Certificate](https://www.ibm.com/training/certification/)

Feel free to explore additional features and experiment with your Python code. Happy coding!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) 

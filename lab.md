# Practice Lab: Build a Command Line tool to list files in a directory

In this practice lab, you will build a command line tool that lists files in a directory. The tool will take a directory path as an argument and list all the files in the directory. If no argument is provided, the tool will list files in the current directory.

**Learning Objectives**

- Create a command line tool using Python
- Use pure Python to list files in a directory
- Use a framework like Click to create a command line tool

**Steps:**

For an easy setup with all dependencies installed and a pre-configured `virtualenv`, [open the repository with Codespaces](https://codespaces.new/alfredodeza/python-cli-example?quickstart=1)

Alternate setup: Create a new repository in your account for your Python project. Use the [Python template repository](https://github.com/alfredodeza/python-cli-example/) to quickly generate one for your own account. Use this link to [create it in one step](https://github.com/alfredodeza/python-cli-example/generate).

1. Use the Click framework to handle arguments and options. Refer to the [framework example](./examples/framework.py) in this repository as a guide
1. Use the `os.listdir()` module to list files in a directory:

    ```python
    import os

    def list_files(path):
        return os.listdir(path)
    ```

**Bonus challenge:** Add options to your tool so that it can list files in a directory recursively, and/or filter files by extension.

**Concepts Covered:**

- [x] Building a command line tool in Python
- [x] Using a framework like Click to create a command line tool
- [x] Using pure Python to list files in a directory

By completing this lab, you have demonstrated that you can create a command line tool using Python. You can use this tool to list files in a directory, and you can extend it to add more functionality.

# [![Coursera Course](./assets/banner.svg)](https://insight.paiml.com/nvd "Coursera Course")

# Python CLI Example
A small Python CLI example you can use to build on. With an emphasis on Linux and creating automation tools that solve a problem for you. THis is the basis for DevOps principles that you can apply in your own environment as well as production environments.

💡 Are you just looking for a 👉 [Rust template](https://github.com/alfredodeza/rust-template) to get started easily with a Rust project? The [template](https://github.com/alfredodeza/rust-template/generate) has everything you need!

This repository is part of the Python and Rust CLI tools course:

- [1: Resources](https://github.com/alfredodeza/python-and-rust-tools) 
- [2: Python CLI](https://github.com/alfredodeza/python-cli-example)  👈 You are here!
- [3: Rust CLI](https://github.com/alfredodeza/rust-cli-example)
- [4: Python Advanced CLI](https://github.com/alfredodeza/advanced-python-cli)
- [5: Rust Advanced CLI](https://github.com/alfredodeza/advanced-rust-cli)

## Practice Lab
Use the [included practice lab](./lab.md) to apply the content you've learned in this week. Follow the steps to create your own repository and apply the requirements to complete the lab.

## Setting up the environment
Python development will require you to have Python installed on your system. For Linux systems, you should prefer the Python that comes available through the package manager. For example, on Ubuntu, you can install Python with the following command:

```bash
sudo apt-get update && sudo apt-get install python3
``` 

The _update_ part is required if this is a fresh install of the system. Any Python version above 3.6 should work well for this repository, its examples, and most of the work shown in the video course.

The course uses [Visual Studio Code](https://code.visualstudio.com/?WT.mc_id=academic-0000-alfredodeza) exclusively, but you can use any other text editor as well. 

These are all the tools and editor extensions recommended for Python development:

- [Visual Studio Code](https://code.visualstudio.com/?WT.mc_id=academic-0000-alfredodeza)
- [Python extension for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=ms-python.python&WT.mc_id=academic-0000-alfredodeza)
- [GitHub Copilot](https://marketplace.visualstudio.com/items?itemName=GitHub.copilot&WT.mc_id=academic-0000-alfredodeza)

## Working with Modules
Adding modules (Python files) is as easy as adding more files. But you can also add a directory and add an `__init__.py` file to it. This will allow you to import the modules from the directory as if they were part of the same file. There are some caveats and things to keep in mind when working with modules, and what strategies you can use to make your code more maintainable and easier to understand for you as well as other developers.

1. Use the [ceph-volume](https://github.com/ceph/ceph/tree/main/src/ceph-volume/ceph_volume) command-line tool as an example to explore module organizing
1. Add imports to `__init__.py` as a shorthand for making modules available, but be aware of side effects
1. Use relative imports to avoid circular imports and understand absolute 

## Dependencies and libraries
Using dependencies can be tricky, but you can use the well known `requirements.txt` file to keep track of the dependencies for your projects which is something that works with the `pip` installer tool. Here are some things to be aware of when working with dependencies:

1. Create a `requirements.txt` file, optionally read it in for the `setup.py` file
1. Use separate files for development and testing like `dev-requirements.txt` and `test-requirements.txt` when needed
1. Use `pip` to install dependencies and use `pip freeze` to _pin_ dependencies. Be aware of the caveats and positive aspects of pinning.
1. Understand how relaxed dependencies can be instead of pinning

## Resources
Explore additional content that you can use to learn more about the topics covered in this course.

**Coursera Courses**

- [Linux and Bash for Data Engineering](https://www.coursera.org/learn/linux-and-bash-for-data-engineering-duke)
- [Open Source Platforms for MLOps](https://www.coursera.org/learn/open-source-platforms-duke)
- [Python Essentials for MLOps](https://www.coursera.org/learn/python-essentials-mlops-duke)
- [Web Applications and Command-Line tools for Data Engineering](https://www.coursera.org/learn/web-app-command-line-tools-for-data-engineering-duke)
- [Python and Pandas for Data Engineering](https://www.coursera.org/learn/python-and-pandas-for-data-engineering-duke)
- [Scripting with Python and SQL for Data Engineering](https://www.coursera.org/learn/scripting-with-python-sql-for-data-engineering-duke)

**O'Reilly Courses and Books**

- [Python for DevOps](https://www.oreilly.com/library/view/python-for-devops/9781492057680/) (Book)
- [Practical MLOps](https://www.oreilly.com/library/view/practical-mlops/9781098103002/) (Book)
- [Linux For Beginners](https://learning.oreilly.com/videos/-/27922450VIDEOPAIML/) (Video)
- [GitHub Codespaces Course](https://learning.oreilly.com/videos/-/27724023VIDEOPAIML/) (Video)
- [Python Command-line Tools course](https://learning.oreilly.com/videos/python-command-line/50131VIDEOPAIML/) (Video)

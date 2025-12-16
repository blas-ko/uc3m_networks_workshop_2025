# Introduction to Networks and Python
**Blas Kolic, 2025**

Welcome to the Networks Workshop for the uc3m PhD program on Social Sciences! I hope you find this course useful and gain knowledge and experience with Python and Network Theory applied to the Social Sciences :). If you have problems setting up Python, find a set of instructions at [`python_setup.md`](https://blas-ko.github.io/uc3m_networks_workshop_2025/python_setup.md) in the course repository.

### Introduction to Python and Jupyter Notebooks

Python is a very popular **high-level programming language**. If you have never programmed before, you can think of programming as using a very powerful calculator, one that works not only with numbers but with any kind of *object* a computer can represent. These objects include numbers, of course, but also words or characters (called **strings**), lists, matrices, functions, dictionaries, and even custom-made structures such as **networks**.

Python runs code by reading a sequence of instructions written in a text file known as a **script**. In this workshop, however, we will primarily work with **Jupyter Notebooks**, which offer a more interactive and beginner-friendly environment.

A **Jupyter Notebook** is an interactive workspace where you can run code, write notes, and explore data—similar to notebooks in [RStudio](https://posit.co/download/rstudio-desktop/). A notebook is divided into **cells**. Some cells contain Python code that you can execute independently, while others contain text written in **Markdown** (like the cell you are reading now). This setup makes notebooks ideal for learning, experimenting, and documenting your work all in one place.

Like any calculator, Python’s basic functionality can be extended through **packages** (also called *libraries*). These are add-ons written by others to provide specific features that are not built into core Python. For example, the package `matplotlib` allows us to create plots and visualize data. Unlike app-store plugins, Python packages are free and widely shared within the community.
In this first tutorial, we will cover the basics of programming in Python and introduce a few essential packages for data and network analysis:

- **NumPy** – for working with numerical data and arrays  
- **Pandas** – for reading, saving and handling datasets in table form  
- **Matplotlib** – for plotting and visualizing data  
- **NetworkX** – the most widely used Python library for analyzing networks  

By the end, you’ll have a foundation strong enough to dive into network analysis and the more advanced tools used throughout the workshop.

**Outline of the tutorial**
1. **Simple operations**: Learn the basic python operations, starting from using it as a calculator to handling different types
2. **Functions**: Learn how to use built-in functions as well to define your own
3. **Control flow**: Learn the basics of `if-else` blocks and `for` loops.
4. **Importing libraries**: Learn to import python libraries/packages for extra functionalities
5. **Basic network analysis with `networkx`**: Import library `networkx` to construct a network and perform a basic analysis.

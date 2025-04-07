---
title: Tutorials
description: Tutorials will be held April 11, 2025.
---

## Schedule

|       Time        |                               Tutorial                                |  Instructor  |
| :---------------: | :-------------------------------------------------------------------: | :----------: |
| 09:00am - 12:00pm |   [Python Tools in the Real World](#python-tools-in-the-real-world)   | Al Sweigart  |
| 02:00pm - 05:00pm | [The new wave of Python Packaging](#the-new-wave-of-python-packaging) | Bernát Gábor |

## Tutorials

### Python Tools in the Real World

Learning Python’s syntax and features is just the beginning. When it’s time to build software that others can use, understanding Python’s rich ecosystem of tools becomes essential. This 3-hour hands-on tutorial introduces you to powerful tools that bridge the gap between writing code and developing real-world applications. You’ll gain practical experience with tools like venv, pypi, black, mypy, cookiecutter, and Python’s debugging and logging facilities.
This is a hands-on tutorial with several mini projects to learn enough about these tools that you can continue to teach yourself later. We will cover:

- **Virtual Environments**: Learn how to create and manage isolated environments using venv and pyenv, and understand their critical role in application development.
- **Package Management**: Master pip for installing and managing dependencies from PyPI, evaluate third-party packages, and demystify Python’s packaging ecosystem.
- **Project Templates with Cookiecutter**: Discover how to streamline project setup and create your own reusable Python package templates.
- **Static Code Analysis**: Use Black and Ruff to format and lint your code, and seamlessly integrate these tools into your preferred editor.
- **Type Checking with Mypy**: Learn to add type hints and use mypy for early detection of runtime errors, enhancing code quality and reliability.
- **Debugging and Logging**: Dive into Python’s debugger and logging module, and see how to use them effectively in Visual Studio Code, Jupyter Notebooks, and the terminal.

You'll leave this tutorial with concrete experience working with these tools, ready to apply them to your projects and continue your learning journey. And you'll also leave with a renewed excitement about the vast world that Python's ecosystem offers.

### Prerequisites

Hello, and thank you for signing up for my tutorial, "Python Tools for the Real World" on Friday, April 11th from 9 am to noon. The Python ecosystem has an intimidating size, but I'd like to give you a shallow but wide introduction to the tools you've probably heard of but never had time to explore.

This tutorial is three hours (with two breaks) and covers the terminal, pip, venv, black, ruff, mypy, cookiecutter, uv, pdb, and the logging module. I don't want to lecture the entire time, so there will be exercises you can do on your laptop to build up "muscle memory" of using these tools. You can just take notes with pen and paper, but a lot of the benefit of this tutorial comes from the exercises. (These exercises will be available online after the tutorial as well.)

To get a better idea of the tutorial participants, it'd be great if you could fill out this [short 7-question survey today](https://docs.google.com/forms/d/e/1FAIpQLScLWH9tKbkU-hIHlm4W4W7clLbLN-f0eXXEJF370Q573Mn0lw/viewform?usp=sharing) or sometime before the tutorial.

Al


#### Presenter: Al Sweigart

![Al Sweigart Avatar](https://i.imgur.com/7vNlokH.png){: style="height:150px;width:150px" align=left}

_Al Sweigart is a software developer, artist, Fellow of the Python Software Foundation, and the author of Automate the Boring Stuff with Python and other programming books freely available under the Creative Commons license at [https://inventwithpython.com](https://inventwithpython.com)._

<br clear="all">

### The new wave of Python Packaging

Python has become the #1 programming language on GitHub (ranked by number of individual contributors) in 2024. Such a popular language deserves the very best when it comes to the developer experience when shipping your code. While this hasn't historically been the case, we made huge steps towards this in 2024.

In this workshop, I will introduce you to the TL;DR ("too long, didn't read") version of how you should handle Python packaging in 2025. You will learn about the current best practices when it comes packaging either your favorite library or your fancy new web application. Note, this session will focus on using the PyPI ecosystem, not the Conda ecosystem (at least not today).

### Prerequisites

Hey folks,

Can't wait to dig into the new wave of Python packaging with you next week at PyTexas!

The workshop will have a good mix of me walking through how things work, but the best way to learn is by following along and trying things out yourself—especially with the exercises we'll be doing throughout.

To save us some time getting started, please make sure you've got [Docker](https://www.docker.com) installed and working. Then go ahead and clone this GitHub repository [https://github.com/gaborbernat/new-wave-of-python-packaging-binder](https://github.com/gaborbernat/new-wave-of-python-packaging-binder). You'll find setup instructions in the README—just follow one of the local setup options.

We'll also have the option to use [https://mybinder.org](https://mybinder.org), but heads up: it can be a bit flaky at times. Running things locally will give you the smoothest experience. If you hit any snags, feel free to open an issue in the GitHub repo.

Looking forward to seeing you there!

Cheers, Bernát


#### Presenter: Bernát Gábor

![Bernát Gábor Avatar](https://pretalx.com/media/avatars/EGPZKP_JRfRMlH.jpeg){: style="height:150px;width:150px" align=left}

_Bernát works at Bloomberg US - Los Angeles on the data ingestion pipelines quality control segment. He is a PSF Fellow and has authored numerous highly used Python packages. You can find a full list [here](https://bernat.tech/about/)_

# Flakes Installation

The first step of using any piece of software is to install it properly. Let's take a look at how to do this:

## Dependencies

- Flakes is written in, and thus required [Python V3.13](https://www.python.org/downloads/release/python-3130/) or newer. We are currently working on backwards compatibility, but recommend the latest stable version of Python.
- With Python, will come `pip`, Pythons default package manager. This is required to install Flakes, but you can use another `pip`-based package manager. (E.g. `Pipenv`, `pipx`, ect..)
- Additionally, you should also be familiar with working from the command line, and have a text editor to use. **Notepad does not count as a text editor, we recommend [Visual Studio Code](https://code.visualstudio.com)**.

!!! tip

    Check your Python and `pip` versions with the following commands: `python -v`, and `pip -v`.

## Distributions

Upon installing Flakes, you should know there are several packages that come budled with it. These are:

- Requests, for helping with HTTPS requests. (Duh)
- Jinja2, a popular Python templating engine.

## Virtual Enviroments

We highly recommend the use of Python Virtual Enviroments when installing packages. This way, project dependencies are managed automatically, both in development and production.

## Install Flakes

Now that you have gone through all of these steps, finally, you can install Flakes.

``` console
pip install flakes
```
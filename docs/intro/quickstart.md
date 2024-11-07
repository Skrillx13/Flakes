# Quickstart

A simple 5 minute fast paced course for those who wish to jump right in. This is intended to be a refresher in case you might have forgotten some of the basics, but if you are a beginner, we recommend checking out the tutorial.

## 1. Installation

Install Flakes through `pip` by running the following command:

``` console
pip install flakes
```

Afterwards, we suggest running the command `flake mkdir app.py`. This will create a file named `app.py` at the base of your directory.

## 2. Setting up the application

The simplest and most basic code rerquired to create a application is as follows:

``` python
from flakes import flakes

app = My first application

@app.route("/")
def hello_world():
    print("Hello World")
```

Afterwrads, open up a terminal, and enter
``` console
flakes run
```
to start a local server at [http://127.0.0.1:8000](http://127.0.0.1:8000). There, you will see your text, "hello world".

## 3. Explanation

So what did this do? Let's break it down:

1. `from flakes import flakes` imports the Flakes library, which is a necessity.
2. `app = My first application` creates a title for our document.
3. The entirety of the `@app.route` section was defining a variable, telling Flakes to render it through the `app` route, and display it to us.
4. Starting a local server allows us to see our works while coding. The server includes hot-refresh, so everytime you save your changes, it will refresh.

## 4. Next Steps

After going through the quickstart, I highly recommend going through the tutorial if you have not, or checking out the other Documents in the Introduction section.
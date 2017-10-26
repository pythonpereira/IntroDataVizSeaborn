# Introduction to DataViz in Python

This repository shows the visualizations presented during a talk in the first meetup of
PyPereira. Slides can be found [here](https://speakerdeck.com/sebasvega95/introduccion-a-la-visualizacion-de-datos-en-python)
(in spanish).

## Installation (Mac and Linux)

You should have python 3.6 and virtualenv installed in your computer. 
In a terminal, from the directory of this repository run

```bash
virtualenv -p $(which python3) env
```

to install the environment in a new folder called `env`. To activate it run

```bash
source env/bin/activate
```

You should see `(env)` at the begining of the comand prompt.
Now, install dependencies with

```bash
pip install -r top-requirements.txt
```

Finally, you can run jupyter using


```bash
jupyter notebook
```

This will open a browser window where you can see the notebook, named
`TalkNotebook.ipynb`.

Feel free to ask me any questions by opening an issue or via [twitter](https://twitter.com/sebasvega95) :blush:.

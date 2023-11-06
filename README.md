# Working With APIs : Code-Along

## Learning Goals

- Learning goal 1.

---

## Key Vocab

- **Routing**: the association of a URL and the code that should execute when a
  request comes in for that URL.

---

## Introduction

blah blah

---

## Setup

> Please fork and clone the repo.

Run `pipenv install && pipenv shell` to generate and enter your virtual
environment.

```console
$ pipenv install && pipenv shell
```

Change into the `server` directory, where you will run the application and
tests:

```console
$ cd server
```

You can run the application as a script within the `server/` directory:

```console
$ python app.py
```

If you prefer working in a Flask environment, remember to configure it with the
following commands within the `server/` directory:

```console
$ export FLASK_APP=app.py
$ export FLASK_RUN_PORT=5555
$ flask run
```

## Topic 1

---

## Conclusion

blah blah

---

## Solution Code

```py
#!/usr/bin/env python3
# server/app.py

from flask import Flask

app = Flask(__name__)

```

Once you complete this code-along, push your work using `git` to submit.

---

## Resources

- [Resource 1](https://www.python.org/doc/essays/blurb/)
- [Reused Resource][reused resource]

[reused resource]: https://docs.python.org/3/

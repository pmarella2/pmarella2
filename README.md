<!-- Zero width character is used to put extra blank lines before and after code -->
<h3>

```python
from dataclasses import dataclass
from typing import Tuple

@dataclass
class Info:
    name        : str = "Praneeth Marella"
    location    : str = "Washington D.C.-Metro Area"
    occupation  : str = "Assoc. Detection and Response Analyst"
    school      : str = "George Mason Unviersity"
​
@dataclass
class Stack:
    languages   : Tuple[str, ...] = ("Python", "Java", "JavaScript", "LaTeX")
    frameworks  : Tuple[str, ...] = ("Django", "Mongo", "Redis")
    misc        : Tuple[str, ...] = ("Docker", "Celery")
    ongoing     : Tuple[str, ...] = ("Django", "GraphQL")

@dataclass
class Social:
    website     : str = "praneethmarella.xyz"
    github      : str = "github.com/pmarella2"
    linkedin    : str = "linkedin.com/in/praneethmarella"
    medium      : str = "medium.com/@pmarella"
    g-scholar   : str = "scholar.google.com/citations?user=f5mz_tAAAAAJ&hl=en&oi=ao"
```
</h3>

<h3>

```console
foo@bar:~$ whoami
name       = "Praneeth Marella"
location   = "Washington D.C.-Metro Area"
occupation = "Assoc. Detection and Response Analyst"
school     = "George Mason Unviersity"
```
</h3>
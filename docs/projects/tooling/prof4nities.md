---
tags:
  - Python
  - Moderation
---

<div style="display: flex;">


<div>
A small Python library to detect and optionally censor profane or inappropriate words using language-specific wordlists, Levenshtein distance, and fuzzy string matching.
</div>
</div>

[PyPi :material-web:](https://pypi.org/project/iragca/){ .md-button }
[GitHub :simple-github:](https://github.com/iragca/statewatch){ .md-button }


## Example Usage

```python
from prof4nities import Censor

censor = Censor(language="en")

# assuming "badword" is in the wordlist
print(censor("badword in a sentence"))
# >>> ******* in a sentence

print(censor(["badword", "in", "a", "sentence"]))
# >>> ******* in a sentence

print(censor(["badword", "in", "a", "sentence"], stringify=False))
# >>> [Word('badword'), Word('in'), Word('a'), Word('sentence')]
```
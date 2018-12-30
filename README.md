# Document moderator
Searches for words in the selected document with selected Levenshtein distance to words in the selected dictionary

## Dependencies
- [Python 3.7](https://www.python.org/downloads/)
- [pipenv](https://pipenv.readthedocs.io/en/latest/)

## Installation
```
pipenv install
```

## Usage
```
usage: main.py [-h] -d TARGET_WORDS -a ARTICLE -o OUTPUT -l DISTANCE

find words in document

optional arguments:
  -h, --help       show this help message and exit
  -d TARGET_WORDS  dictionary (txt)
  -a ARTICLE       article (docx)
  -o OUTPUT        article with highlighted words
  -l DISTANCE      editor distance
```

## Authors
- Kirill Syomin
- Oleg Utkin

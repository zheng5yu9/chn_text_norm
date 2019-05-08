# chn-text-norm
this is a repo for chinese text normalization.

## Quick Start ##

### Git Clone Repo ###
git clone this repo to the root directory of your project which need to use it.

    cd /path/to/proj
    git clone https://github.com/Joee1995/chn-text-norm.git

After that, your doc tree should be:
```
proj   # root of your project
  |- chn_text_norm
      |- text.py
      |- ...
  |- text_normalize.py   # your text normalization code
  |- ...
```

### How to Use ? ###

    from chn_text_norm.text import *
    
    raw_text = 'your raw text'
    text = Text(raw_text=raw_text).normalize()

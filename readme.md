# art
Article template compatilble with Overleaf.
Includes TexnicCenter project file.

## Installation
check out with

`git clone https://github.com/jonlighthall/art.git` (HTTPS)

`git clone git@github.com:jonlighthall/art.git` (SSH)

## Submodule
This repository includes a copy of the files from https://github.com/jonlighthall/src.git.
As of this writing, Overleaf does not support Git submodules.
To restore the repository and remote, use the following commands.
```
cd src
git init
git remote add origin git@github.com:jonlighthall/art.git
git pull origin master

```
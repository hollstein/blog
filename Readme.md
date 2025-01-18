# Setup

## Initial setup

```bash
hugo new site blog --format yaml
cd blog
git init
# https://github.com/adityatelange/hugo-PaperMod/wiki/Installation
git submodule add --depth=1 https://github.com/adityatelange/hugo-PaperMod.git themes/PaperMod
git submodule update --init --recursive # needed when you reclone your repo (submodules may not get cloned automatically)
git submodule update --remote --merge
```

## Run server

```bash
hugo server
```

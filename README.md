
TM Grammar debugger
====

# Install

## Method 1: npm

To get `grammar-debug ` in your PATH, do

    npm install -g https://github.com/maelvalais/grammar-debug

Usage: `grammar-debug <grammarPath> <filePath>`, where
- `<filePath>` is the file on which you want to test the syntax
- `<grammarPath>` is the `.tmLanguage` or `.json` tmlanguage syntax file
  you want to test

The script will output to stdout the parsing steps in order to
help you debug the textmate grammar.

## Method 2: by cloning the repo
* `git clone https://github.com/maelvalais/grammar-debug`
* go in `sample/`
* edit `grammar.tmLanguage` with your language
* edit `file.txt` with your test file
* execute `run.bat`
* look at `result.txt`

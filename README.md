# Kitty Ipsum Translator
This project is part of the freeCodeCamp Build a Kitty Ipsum Translator workshop.
In this workshop, I learned how to use more advanced Bash commands, input/output redirection, pipes, pattern matching, and text-processing tools to analyze and transform text files.

## Project Description
The program translates " kitty ipsum" test into "doggy ipsum" text by replacing cat-related words with dog-related words.
For example:
- `cat`, `cats`, `catnip` become dog-related words
- `meow`, `meowzer` become `woof`

## Files
- `kitty_ipsum_1.txt` - sample kitty ipsum text
- `kitty_ipsum_2.txt` - another sample kitty ipsum text
- `doggy_ipsum_1.txt` - translated output from the first file
- `doggy_ipsum_2.txt` - translated output from the second file
- `kitty_info.txt` - file statistics and search results
- `translate.sh` - Bash script used to translate kitty ipsum into doggy ipsum

## What I Learned
Through this project, I practiced using:
- `echo`
- `cat`
- `wc`
- `grep`
- `sed`
- `diff`
- input redirection `<`
- output redirection `>`
- append redirection `>>`
- pipes `|`
- standard output and standard error
- execuatable Bash scripts

## How to Run
Make the script excutable:
`chmod +x translate.sh`
Run the translator with a file:
`./translate.sh kitty_ipsum_1.txt`
Save the translated output to a new file:
`./translate.sh kitty_ipsum_1.txt > doggy_ipsum_1.txt`
Compare the original and translated files:
`diff --color kitty_ipsum_1.txt doggy_ipsum_1.txt`

## Original Source
freeCodeCamp

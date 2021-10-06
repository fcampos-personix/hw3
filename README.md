# Homework 3: Decoding
The purpose of this task was to improve translations from French to English using a monotone (stric pruning) decoder as a baseline.
Base model
```
decoder.py
```
Base model + reorderign and future costs
```
decoder-ext.py
```
A * Search model + reorderign and future costs
```
decoder-ext-ext.py
```
## Language:
Python

## Executing the program
To run the models, there is no mandatory parameters, however to change the pruning limit (default = 1) you should include '-s' followed by the sentence limit per stack.
```
python decode-ext
```
With stack limit of 100 sentences
```
python decode-ext -s 100
```


# NLP Question generation from text in python
## Installation
```
pip install textblob
nltk.download('all') 
``` 

## How to Run
```
python genQ.py "text from where you need to generate questions"
``` 
## Example 
### Input
```
python genQ.py "Python is an interpreted, high-level, general-purpose programming language. Created by Guido van Rossum and first released in 1991, Python has a design philosophy that emphasizes code readability, notably using significant whitespace. It provides constructs that enable clear programming on both small and large scales"
``` 

### Output 
```
Created by Guido van Rossum and first released in 1991, __________________ has a design philosophy that emphasizes code readability, notably using significant whitespace.
 $
Python
 $
It provides constructs that enable clear __________________ on both small and large scales
 $
programming
``` 




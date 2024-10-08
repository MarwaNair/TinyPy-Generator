# TinyPy Generator

<p align="center">
  <img src="https://github.com/MarwaNair/Simple-Python-CFG-Generator/assets/86785811/8f8f8cc2-4427-4828-b195-258c3b026f2d" width="250" >
</p>


This repository contains the code associated with the presentation titled [“Automatic Generation of Python Programs Using Context-Free Grammars.”](https://jnamaral.github.io/LATHC24/program/) TinyPy Generator is a tool that generates code with different levels of complexity, ranging from code containing only assignments to more complex code containing conditionals and loops.


Link to the paper: https://arxiv.org/abs/2403.06503
## How to Use

### Command Line Arguments

To use the code generator with different configurations, you can specify command line arguments. Here's how to add command line arguments:

1. **num_programs**: Number of programs to generate and write (default is 1000).
2. **level**: The level of the programs (default is ALL). Choose from:
   - "1.1" for Simple arithmetic.
   - "1.2" for Advanced arithmetic with enclosed expressions.
   - "2.1" for Simple If-elif-else statements.
   - "2.2" for Advanced If-elif-else statements with advanced arithmetic expressions.
   - "3.1" for Simple for loops.
   - "3.2" for Advanced for loops with advanced arithmetic expressions.
   - "4.1" for Simple while loops.
   - “ALL” for all of the above levels.

3. **filename**: Name of the file to write the programs (default is 'data/data.txt').

4. **deduplicate**: Perform deduplication of generated programs. If specified, the output file will contain unique programs (default is True).

### Example Usage

Generate 5000 programs of level "3.1" and save them to a file named "output.txt" with deduplication:

```bash
python3 code_generator.py --num_programs 5000 --level 3.1 --filename output.txt --deduplicate
```


Feel free to modify and expand based on your specific requirements.

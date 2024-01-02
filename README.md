# Simple-Python-CFG-Generator

In recent years, data has emerged as a valuable resource for creating intelligent systems. Procuring high-quality data, especially for code, remains challenging. To address this, we developed a tool that autonomously generates syntactically correct Python programs using context-free grammars.

Our system establishes production rules that are recursively implemented to generate code. This process produces comprehensive code snippets with adjustable complexity, from basic assignments to advanced conditionals and loops. We validate correctness by executing the programs and capturing output. This enables effortless large-scale Python code generation, beneficial for applications like machine learning.

Unlike existing research, we provide open-source implementation code. This allows customization according to user needs and extends potential usage to other languages.

## How to Use

### Command Line Arguments

To use the code generator with different configurations, you can specify command line arguments. Here's how to add command line arguments:

1. **num_programs**: Number of programs to generate and write (default is 10000).
2. **level**: The level of the programs. Choose from:
   - "1.1" for Simple arithmetic.
   - "1.2" for Advanced arithmetic with enclosed expressions.
   - "2.1" for Simple If-elif-else statements.
   - "2.2" for Advanced If-elif-else statements with advanced arithmetic expressions.
   - "3.1" for Simple for loops.
   - "3.2" for Advanced for loops with advanced arithmetic expressions.

3. **filename**: Name of the file to write the programs (default is 'data.txt').

### Example Usage

Generate 5000 programs of level "3.1" and save them to a file named "output.txt":

```bash
python your_script.py --num_programs 5000 --level "3.1" --filename "output.txt"
```

Feel free to experiment with different values for `num_programs`, `level`, and `filename` to suit your requirements.
Feel free to modify and expand this template based on your specific requirements or additional information you want to provide.

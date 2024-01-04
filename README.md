
## How to Use

### Command Line Arguments

To use the code generator with different configurations, you can specify command line arguments. Here's how to add command line arguments:

1. **num_programs**: Number of programs to generate and write (default is 1000).
2. **level (required)**: The level of the programs. Choose from:
   - "1.1" for Simple arithmetic.
   - "1.2" for Advanced arithmetic with enclosed expressions.
   - "2.1" for Simple If-elif-else statements.
   - "2.2" for Advanced If-elif-else statements with advanced arithmetic expressions.
   - "3.1" for Simple for loops.
   - "3.2" for Advanced for loops with advanced arithmetic expressions.

3. **filename**: Name of the file to write the programs (default is 'data/data.txt').

4. **deduplicate**: Perform deduplication of generated programs. If specified, the output file will contain unique programs (default is True).

### Example Usage

Generate 5000 programs of level "3.1" and save them to a file named "output.txt" with deduplication:

```bash
python3 code_generator.py --num_programs 5000 --level "3.1" --filename "output.txt" --deduplicate
```


Feel free to modify and expand this template based on your specific requirements.

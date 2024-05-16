# Minilang_Compiler
Design and Implementation of a Compiler for a C-like Programming Language
## Steps:
### Language Specification:
• Define the grammar of your language using CFG/BNF notation.
• Describe the supported features and limitations.
### Conversion to Automata:
• Convert your language's grammar into a finite automaton using JFLAP.
• Document the conversion process and any optimizations applied to the automata.
### Compiler Design:
• Lexical Analysis: Implement a lexer that converts a sequence of characters into a
sequence of tokens.
• Syntax Analysis: Develop a parser that constructs a parse tree or an abstract
syntax tree (AST) from the tokens.
• Semantic Analysis: Perform type checking and ensure semantic correctness.
• Intermediate Code Generation: Generate an intermediate representation of the
abstract syntax tree.
• Code Optimization: Optimize the intermediate code to improve performance.
• Code Generation: Translate the optimized intermediate code into a simple
assembly or machine-like code.
### Testing and Documentation:
• Test your compiler with various code snippets to ensure it handles all constructs
correctly.
• Prepare a comprehensive report documenting your design decisions, the
challenges faced, the testing methodology, and examples of input-output

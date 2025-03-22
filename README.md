# ReplSchemeLite
A lite interpreter for a subset of the Scheme language using Python.
```
ReplSchemeLite 
│── scheme.py               # The interpreter REPL (user interface)  
│── scheme_eval_apply.py    # Recursive evaluator for Scheme expressions  
│── scheme_forms.py         # Python functions for special forms (define, lambda, cond, etc.)  
│── scheme_classes.py       # Python classes describing Scheme expressions  
│── scheme_builtins.py      # Built-in Scheme procedures  
│── scheme_reader.py        # The reader for Scheme input  
│── scheme_tokens.py        # Tokenizer for Scheme input  
│── scheme_utils.py         # Utility functions for inspecting Scheme expressions  
│── pair.py                 # Defines the Pair class and the nil object  
│── ucb.py                  # Utility functions for 61A projects  
│── questions.scm           # Scheme procedures for implementation (lab/homework style)  
│── tests.scm               # Collection of test cases written in Scheme  
│── mytests.rst             # File to add custom tests  
│── ok                      # The autograder  
└── tests/                  # Directory containing tests used by "ok"
```

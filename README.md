# ALPH-open-sorce-pro


⚠️ A Note for "Producers"

If you're one of those so-called "producers" who spend hours making flashy intros instead of writing actual code, this project might not be for you. But if you're here for real programming, welcome aboard.


---

About This Project

This is a transpiler that converts an Arabic-based programming syntax into Python. Unlike certain "attempts" at Arabic programming languages that merely wrap Python functions with Arabic keywords, this project is designed to function as a proper preprocessor with tokenization and syntax handling.

Features

Arabic Keyword Replacement – Translates Arabic programming terms into Python equivalents.

Basic Tokenization – Handles syntax parsing with custom delimiters.

Modular Codebase – Well-structured C++ implementation.

Future Enhancements:

Error Handling (coming soon)

File Handling (coming soon)



Current Limitations

Error messages are not yet fully implemented.

File input/output operations are planned but not yet integrated.

May not handle deeply nested structures perfectly (work in progress).



---

Technical Overview

This project consists of:

Tokenizer (tokenrfunc.hpp): Breaks down Arabic source code into meaningful tokens.

Replacer (replacer.hpp): Maps Arabic syntax elements to Python keywords.

Core Compiler (main.cpp): Handles input processing and token manipulation.


Memory usage is optimized through map-based lookups for keyword replacement, ensuring efficiency. However, the error-handling system is yet to be implemented, meaning incorrect syntax might cause crashes instead of friendly warnings (for now).


---

Installation & Usage

To build and run the transpiler:

g++ main.cpp -o transpiler
 ./transpiler

Then, enter your Arabic-based code as input.

Example Input:

إذا صواب:
    اطبع("Hello, Arabic Programming!")

Output:

if True:
    print("Hello, Arabic Programming!")


---

Contributing

Contributions are welcome, but keep them meaningful. No "fancy intros," just solid code.


---

Final Words

While others are busy making animated tutorials with 5-minute intros, I'm actually building something. Error handling and file operations are coming soon, so stay tuned. Until then, happy coding!


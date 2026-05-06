# autocomplete

Developed an autocomplete system in C++ using a Binary Search Tree (BST) to efficiently store and retrieve key-value pairs, where values represent the frequency (weight) of entries such as words, cities, or movie names. The system enables fast prefix-based search by traversing the BST to identify matching entries and returning results sorted by frequency.

The project includes a modular design with separate components for BST implementation, autocomplete logic, and testing. Performance and correctness were validated using multiple datasets ranging from small word lists to large-scale inputs (e.g., Wiktionary and city datasets).

Additionally, the project incorporates automated build and testing workflows using shell scripts, along with code quality checks through tools like clang-tidy, clang-format, and Valgrind, ensuring memory safety, code consistency, and full test coverage.

### cpp files

- bstmap.h/cpp: Binary Search Tree header and implementation
- bstmapprinter.cpp: Functions for printing BST on screen
- autocomple.h/cpp: Autocomplete
- testbst.cpp: Testing BST functions
- testac.cpp: Testing Autocomplete functions
- main.cpp: Accepts inputs to return strings sorted by their frequency

### Text files for testing
- small.txt Short list of words
- wiktionary.txt Large list of words
- cities.txt Cities

### Shell scripts

- runit.sh: compile and run he program
- create-output.sh: compile, run, check for clang-tidy, clang-format and valgrind warnings
- check-code-coverage: examine if any lines not executed during tests




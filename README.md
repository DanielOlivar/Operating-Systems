# Operating Systems 🚀

## Description 📋

This project is a C programming exercise related to process management in operating systems. It utilizes concepts of pipes, child processes, and file reading/writing to process a character matrix and perform certain operations on it, all in an environment controlled by parent and child processes.

The program does the following:
1. Creates a matrix of characters (with a variable number of rows and columns provided by the user).
2. Processes this matrix in several child processes, where each child searches for and manipulates specific characters in the matrix.
3. Creates an output file and uses it to store results.
4. Uses pipes for communication between the parent and the child processes.
5. Manages an input file with names, processing each one and generating moves and reports on the positions of characters.

## Requirements ✅

- Unix-like operating system (Linux, macOS, etc.)
- C compiler (e.g., GCC)
- Input files (`nombres.txt`)

## Files 🗂️

- **salida.txt**: The file where the processed results are stored.
- **nombres.txt**: An input file containing a list of names to be processed by the program.
- **examen2b.c**: The main source code file of the program.


## Usage Instructions 📋

1. Clone this repository: 🖥

   ```bash
   git clone https://github.com/DanielOlivar/operating-systems.git
   cd operating-systems

2. Compile the program: 💻
   ```bash
   gcc examen2b.c -o examen2b
3. Run the program: ▶️
   ```bash
   ./examen2b

---


---

### 👨‍💻 Author

**Daniel Olivar**  
Computer Engineer
[GitHub: @DanielOlivar](https://github.com/DanielOlivar)




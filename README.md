# File Compression Tool

## Project Overview

This project implements a file compression tool utilizing Huffman encoding to efficiently compress and decompress text files. It features a comprehensive implementation in C++, showcasing core data structures like linked lists, binary trees, min-heaps, and hash tables.

## Directory Structure

```
eshwar11034-file-compression-tool/
├── README.md
├── compressed.txt
├── decompress.txt
├── Header.h
├── input.txt
└── Source.cpp
```

## Technologies Used

- **C++**: Core programming language
- **Standard Template Library (STL)**: Utilizes vectors, iterators, and other STL containers
- **File I/O**: For handling input and output operations

## Key Functionalities

- **Compression**: Compresses text files using Huffman encoding.
- **Decompression**: Decompresses the compressed files back to their original content.
- **Hash Tables**: Efficiently manages and retrieves character frequencies and encoding mappings.
- **Huffman Algorithm**: Constructs optimal prefix codes to minimize file size.

## Usage

### Compilation

Compile the program using a C++ compiler (e.g., g++):

```bash
g++ Source.cpp -o compression_tool
```

### Execution

Run the compiled executable:

```bash
./compression_tool
```

The program reads from `input.txt`, compresses the content, and writes the compressed data to `compressed.txt`. It then decompresses the data from `compressed.txt` and outputs the result to `decompress.txt`.

## Files Description

- **`Header.h`**: Contains data structures (linked lists, binary trees, min-heaps, hash tables) and Huffman encoding logic.
- **`Source.cpp`**: Implements the main workflow for file compression and decompression.
- **`input.txt`**: Input file containing text to be compressed.
- **`compressed.txt`**: Output file containing compressed binary data.
- **`decompress.txt`**: Output file containing decompressed text matching original content.

## Functional Overview

- Reads the input text file and generates frequency data for each character.
- Constructs a Huffman tree based on character frequencies.
- Generates binary codes for each character using the Huffman tree.
- Compresses the input text into binary format and writes it to `compressed.txt`.
- Decompresses the binary data back into the original text and writes it to `decompress.txt`.



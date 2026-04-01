# 📦 File Compressor using Huffman Coding (C++)

## 🚀 Overview

This project is a **file compressor and decompressor** built using the **Huffman Coding algorithm** in C++.
It reduces file size by assigning shorter binary codes to frequently occurring characters and longer codes to less frequent ones.

---

## 🧠 How It Works

### 🔹 Compression

1. Reads input file
2. Calculates frequency of each character
3. Builds Huffman Tree using Min Heap
4. Generates binary codes
5. Encodes data and saves compressed file

### 🔹 Decompression

1. Reads compressed file
2. Reconstructs Huffman Tree
3. Decodes binary data
4. Restores original file

---
🟢 Huffman Tree Diagram
<img width="1443" height="1077" alt="image" src="https://github.com/user-attachments/assets/dfce2fa7-f8f3-4d6b-b226-70199e9e60c9" />

## 📁 Project Structure

```
├── encode.cpp      # Compression (main function)
├── decode.cpp      # Decompression (main function)
├── huffman.cpp     # Huffman logic implementation
├── huffman.hpp     # Class declarations
├── inputFile.txt   # Sample input
├── outputFile.txt  # Sample output
```

---

## ⚙️ Compilation & Execution

### 🟢 Compile

```
g++ encode.cpp huffman.cpp -o encode
g++ decode.cpp huffman.cpp -o decode
```

### 🟢 Run Compression

```
./encode inputFile.txt compressed.huf
```

### 🔵 Run Decompression

```
./decode compressed.huf outputFile.txt
```

---
🟢 Terminal Output Screenshot
<img width="1152" height="930" alt="image" src="https://github.com/user-attachments/assets/43d14ad5-30bd-4226-a586-f04af09c3b52" />

## ✨ Features

* Lossless compression using Huffman Coding
* Supports text file compression
* Binary file handling with padding
* Tree reconstruction during decompression
* Efficient encoding using priority queue (min heap)

---

## 📌 Technologies Used

* C++
* STL (vector, priority_queue, string)
* File Handling (fstream)

---

## ⚠️ Limitations

* Works primarily with text files
* Not optimized for large binary files (images, videos)
* Compression ratio depends on input data

---

## 📊 Future Improvements

* Bit-level compression optimization
* Support for binary files (images, PDFs)
* GUI interface
* Compression ratio display

---

## 🎯 Learning Outcomes

* Greedy Algorithms (Huffman Coding)
* Binary Trees
* Priority Queues
* File Handling in C++
* Data Compression Techniques

---


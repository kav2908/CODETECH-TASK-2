CODETECH TASK-2

*COMPANY* : CODETECH IT SOLUTIONS

*NAME* : MONDETI KAVYA

*INTERN ID* :  CT04DF2134

*DOMAIN* : C++ PROGRAMMING

*DURATION* : 4 WEEKS

*MENTOR* : NEELA SANTHOSH

*DESCRIPTION* : Core Functionality:
Compression: This involves encoding data to use less space. Common algorithms include:
Huffman Coding: Assigns shorter codes to frequent characters and longer codes to less frequent ones.
Lempel-Ziv (LZ77, LZ78, LZW): Replaces repeating sequences with references to earlier occurrences.
Deflate: A combination of LZ77 and Huffman coding, used in ZIP files.
Bzip2: Employs the Burrows-Wheeler transform and Huffman coding, known for higher compression ratios.
Zstandard (ZSTD): A modern algorithm focusing on speed and good compression.
Decompression: Reverses the compression process to restore the original data.
Archiving: Some tools combine compression with archiving, packaging multiple files into a single archive

#OUTPUT : 
File compressed and decompressed successfully.

🔍 Detailed Output Breakdown:

1. Console Output:

File compressed and decompressed successfully.

This is printed at the end of the main() if no exceptions were thrown during the process.

2. File Output:

compressed. zlib:
Contains the compressed binary data from input.txt, using zlib's deflate.

decompressed.txt:
Contains the decompressed data, which should exactly match the original input.txt.


✅ To Verify It Works:

You can add a check to compare input and decompressed output:

if (inputData == decompressedData) {
    std::cout << "Decompressed data matches original input." << std::endl;
} else {
    std::cerr << "Mismatch between original and decompressed data!" << std::endl;
}
![image](https://github.com/user-attachments/assets/2d08f68e-7f71-4afc-9903-a4beafa34a73)

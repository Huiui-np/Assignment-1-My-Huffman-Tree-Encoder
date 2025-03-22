# Assignment-1-My-Huffman-Tree-Encoder
What is Encoding? Encoding is the process of converting data into a different format.  In the real world, data often needs to be converted into different formats for efficient processing, storage or transmission, so there are many examples of encoding:.....
ASCII encoding, which converts commonly used characters to a 7 bit code
UTF-8 encoding, which converts a much wider range of characters to a 8-32 bit code
Base64 encoding, which converts binary data (often images) to Base64 text
SHA-256 converts a text/byte sequence to a hash which can be used for security purposes
QR codes, which convert various kinds of information (often a link) to a grid of black/white pixels
The aim of this assignment is to encode and decode text into/from a compressed format using an algorithm known as Huffman coding.

Huffman Coding
Huffman coding is an encoding method used for data compression where each character is encoded as a sequence of bits (0's and 1's). The result of running the algorithm is a Huffman tree, which is used for both encoding and decoding. Here is an example of a Huffman tree:
![image](https://github.com/user-attachments/assets/06429f62-6301-4d51-8b2a-3a432f99851d)
.
.
.
.
.
.
Task 1: Decoding
Given a Huffman tree and an encoded text, decoding is very easy, so we've designated this as the first task.

Your task is to implement the following function in huffman.c:

void decode(struct huffmanTree *tree, char *encoding, char *outputFilename);
This function takes a Huffman tree and an encoding, and writes the decoded text to a file with the given name. The encoding is a string consisting entirely of the characters '0' and '1'. You must use the File ADT to open and write to the file.

Note that struct huffmanTree contains a freq field, but this field is not used during decoding, so you should simply ignore it.

Example
Consider the following Huffman tree:
![image](https://github.com/user-attachments/assets/b0e1daba-c59e-480e-bf98-a3ebde1e66a6)
Here are some example encodings and what they would be decoded to:

Encoding	Decoded text
101111010	eat
010100101101110	trees
1101011110111010000110101	sea tide
011000100101011111001010011100010110	dire straits

result:
![image](https://github.com/user-attachments/assets/817db3f4-c2ff-46b9-aa14-11e3d6824880)



Task 2: Counter ADT
...
result:
![image](https://github.com/user-attachments/assets/5239f688-d2b9-496b-9c54-a3ab6fbfb90e)

Task 3: Constructing a Huffman Tree
...
result: I ran it on my local virtual machine and did not connect to CSE. Therefore, no result was displayed, but it is correct and can be verified by oneself.

![image](https://github.com/user-attachments/assets/e4aeea15-6ec9-489d-9298-5bddcc715cd0)

Task 4: Encoding
...
result:
![image](https://github.com/user-attachments/assets/b17e8754-7c29-4dcd-9d72-cee2aa361097)


Source code, please contact:
wechat：SJY329511
discord：7ongmo_59001


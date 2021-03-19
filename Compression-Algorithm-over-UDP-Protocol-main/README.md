# Compression Algorithm and secure transmission over UDP protocol <img src="https://cdn.kastatic.org/ka-perseus-images/cdaa3bfc074058fe11e9fd6dad9ae3f419359372.svg" align="right" width="250" height="200"/>

Developed an architecture to compress files, using Huffman compression Algorithm and using secure transmission over UDP Protocol. The main objectives are:
- To establish a connection between CLIENT and SERVER using socket programming.
- To implement compression algorithm to compress the text file.
- To implement de-compression algorithm to de-compress the text file.
- To calculate the compression ratio, and space saving percentage.

-----------------------
## Technology Used
- Linux Based OS (Ubuntu)
- C Language
- Socket Programming

------------------------
## Client Server Architecture (CSA)
Client/server architecture is a computing model in which multiple components work in strictly defined roles to communicate. The server hosts, delivers and manages most of the resources and services to be consumed by the client

Client/server architecture works when the client computer sends a resource or process request to the server over the network connection, which is then processed and delivered to the client.

### Socket Programming
A socket programming is a way to establish a connection between a client and a server.It is a way of connecting two nodes on a network to communicate with each other. One socket (node) listens on a particular port at an IP, while other socket reaches out to the other in order to form a connection.
<br><br>
<img src="https://github.com/Pranay2000/Compression-Algorithm-over-UDP-Protocol/blob/main/CSA/SS/CSA1.PNG" align="center" />
<img src="https://github.com/Pranay2000/Compression-Algorithm-over-UDP-Protocol/blob/main/CSA/SS/CSA2.PNG" align="center" />

---------------------------
## Huffman Compression Algorithm
Huffman encoding is used for lossless compression of data. Huffman, uses variable length encoding where length codes are assigned to characters on the basis of frequency of occurrence of character. The character which has the maximum frequency is allotted with smallest bit code and character which has least occurrence gets the highest bit code.

> - Data Compression : Data compression is the process of modifying, encoding or converting the bits structure of data in such a way that it consumes less space on disk.
It enables reducing the storage size of one or more data instances or elements.

> - Data Decompression: Decompression is the process of restoring compressed data to its original form. Data decompression is required in almost all cases of compressed data, including lossy and lossless compression.

<img src="https://github.com/Pranay2000/Compression-Algorithm-over-UDP-Protocol/blob/main/Huffman_Algorithm/SS/1.PNG" align="center" height=550 width=650 />
<img src="https://github.com/Pranay2000/Compression-Algorithm-over-UDP-Protocol/blob/main/Huffman_Algorithm/SS/2.PNG" align="center" />
<img src="https://github.com/Pranay2000/Compression-Algorithm-over-UDP-Protocol/blob/main/Huffman_Algorithm/SS/4.PNG" align="center" />
<img src="https://github.com/Pranay2000/Compression-Algorithm-over-UDP-Protocol/blob/main/Huffman_Algorithm/SS/5.PNG" align="center" />

-----------------------------
## Limitations and Future Enhancements
- It deals only with text files.
<br>

Some of the possible amendments and improvements to be carried out in future are:
- Include transfer of other files such as jpg, mp4 etc.
- Include encryption algorithm for secure transmission of files.



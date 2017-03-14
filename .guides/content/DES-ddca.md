![](.guides/img/dia-des.png)


||| guidance
Rudolf, D. (2000). “Figure 2. Block diagram of the DES algorithm.” Development and Analysis of Block Ciphers and the DES System. http://homepage.usask.ca/~dtr467/400/.

Below text: http://homepage.usask.ca/~dtr467/400/ Dave Rudolf 2000.  Author page: http://homepage.usask.ca/~dtr467/. 

A diagram showing how DES encrypts messages. It encrypts 64 bits at a time, first running a permutation (reordering) of the bits, then operating on the right-half and XORing the result with the left half, switching them and repeating the process 16 times. 

This diagram is not to be discussed in detail. It is included to show that DES is not as simple as some of the classical ciphers to describe but it is a well-defined algorithm with 16 rounds. Also note that there is a key scheduling algorithm (the right side of the picture) where keys for each round are generated. 

This cipher can be contrasted with public key algorithms (such as RSA in part 3) which involve more theory and advanced topics  from mathematics .

This and the next diagram for AES are to show that modern ciphers are not as easy to describe as some of the classical ones.
|||
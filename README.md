# ECC/ElGamal Implementation

Worked by: Hoyos Pedraza Nicolas, Mejia Borda Nicolas Dario, Vargas Morales Cristian Camilo

An implementation proposal of the use of the ElGamal algorithm for the encryption of text under points belonging to an ECC curve.

One of the great problems of the XXI century is the search for alternatives to cryptographic systems for their efficient use; In 1993 Peter Shor published his algorithm (Shor's algorithm) showing that a quantum computer could improve factorization in polynomial time, showing RSA as an obsolete algorithm. However, quantum computers are not expected to finish their development for many years. At present, the Shor algorithm has been demonstrated under a correct probabilistic response, which is why it is necessary to search for a new model that allows us to encrypt the information in an optimal and safe way.

In 1897 Neal Koblitz published in his book an alternative to traditional cryptographic systems called Elliptic Curve Criptography which, Koblitz argues, would become faster, require fewer resources and would become the same or more secure than algorithms like RSA.

By 2005, cryptographic protocols such as Diffie-Hellman began to appear, in which the first steps were taken for the complete implementation of the first cryptographic system based on ECC. Later, towards the end of 2006, the cryptanalyst and mathematician Daniel J. Bernstein published the document with the first software implementation under the public domain called curve25519, a document which specifies the results of the first real-time execution; Currently companies such as Apple (ios) and Facebook (WhatsApp, Messenger) implement this algorithm in their commercial products.

# Cipher

Caesar Cipher realisation as a problem set of the course
"MITx: 6.00.1x Introduction to Computer Science and Programming Using Python" at edx.org.

Compatibility: Python 3.4+.

A cipher is an algorithm for performing encryption (and the reverse, decryption). The original information is called plaintext. After it is encrypted, it is called ciphertext. The ciphertext message contains all the information of the plaintext message, but it is not in a format readable by a human or computer without the proper mechanism to decrypt it; it should resemble random gibberish to those for whom it is not intended.

Implemented classes with methods:
— class Message (superclass)
— class PlaintextMessage (subclass of Message)
— class CiphertextMessage (subclass of Message)
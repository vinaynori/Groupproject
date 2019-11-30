# Secret message Parent Package
######  This Package contains two subpackages: Simpleencryption (Sub package 1)  and Complexencryption (Subpackage 2)

## Simpleencryption Subpackage
###### Simpleencryption subpackage contains three modules: `Ceasercipher.py ( Module 1) `,`Reversecipher.py ( Module 2)`,`Doublecipher.py (Module 3) `

### ceasercipher.py
- Using `ceaserencrypt` module, the user can create a encryption and decryption of messages using Python jupyter notebook,
-This module has `ceaserencrypt`,`ceaserdecrypt` functions with two functionalities of encryption and decryption
-This module uses concepts of substitution cipher in which each letter in the plaintext is replaced by a letter some
fixed number of positions down the alphabet.

### Reversecipher.py
- Using `Reversecipher` module, the user can create a encryption and decryption of messages using Python jupyter notebook,
-This module has `revencrypt`,`revdecrypt` with two functionalities of encryption and decryption
-This module uses concepts of reversing a cipher for encryption and decryption

### Doublecipher.py
- Using `Doublecipher` module, the user can create a double strength encryption and decryption of messages using Python jupyter notebook,
-This module has `dbencrypt`,`dbdecrypt` with two functionalities of encryption and decryption
-This module uses concepts of ceaser cipher and apply the result with a Reversecipher for encryption and decryption

## Complexencryption (Subpackage 2)
###### Complexencryption subpackage contains two modules: `Transpositioncipher.py  `,`Multiplicativecipher.py(Module 2) `.

### Transpositioncipher.py
- Using `Transpositioncipher` module, the user can create a encryption and decryption of messages using Python jupyter notebook,
-This module has `tranencrypt`,`trandecrypt` functions with two functionalities of encryption and decryption
-This module uses concepts of columnar transposition cipher where each character in the plain text is written horizontally with specified alphabet width. The cipher is written vertically, which creates an entirely different cipher text.

### Multiplicativecipher.py
- Using `Multiplicativecipher` module, the user can create a encryption and decryption of messages using Python jupyter notebook,
-This module has `mulencrypt`,`muldecrypt` with two functionalities of encryption and decryption
- (Alphabet Number * key)mod(total number of alphabets) concept used to encrypt a letter

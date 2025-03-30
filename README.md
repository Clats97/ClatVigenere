# ClatVinegere
A simple Android app to encrypt and decrypt text using the Vigenere cipher with a keyword. This is not a ciphertext cracker, it is used to turn plaintext into ciphertext and vice versa.

The Vinegere cipher is a poly-alphabetic substitution cipher used to encrypt text. It is a significant improvement of the Caeser cipher, which has a fixed shift. The Vinegere cipher uses a keyword of any length, and combines the plaintext number in the alphabet with the corresponding letter from the key-phrase modulo 26, so the shift is changing for every character. This makes it hard to crack (but certainly not impossible) because a simple frequency analysis will not work, nor will the shift be identifiable based on correctly determining the shift from 2 exploited letters if it were the Caesar cipher. 

There will only be an Android version of this app, so requesting an iOS app will not get you anywhere.

If you go to my other repositories, you will see that I have a CLI and GUI Python script that does exactly what this app does. 

Have fun!

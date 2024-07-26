To make a Caesar Cipher program, we start by creating the encryption function. This function goes through each character in the message.
If the character is a letter, it shifts it by a given number of positions in the alphabet, wrapping around if needed using modulo 26. Characters that aren't letters stay the same.
The function then gives back the encrypted message.
Next, we create the decryption function. This function uses the encryption function but shifts the letters in the opposite direction to decode the message and get the original text back.
The main function is where the user interacts with the program. It asks if the user wants to encrypt or decrypt a message, then asks for the message and the shift number. 
Depending on the choice, it calls either the encryption or decryption function and prints the result. If the user makes an invalid choice, it shows an error message.
Finally, we add a program entry point to make sure the main function runs if we execute the script directly, starting the whole process of user interaction and encryption/decryption.

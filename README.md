# English-Text-Encoder-Decoder-Using-Caesar-Cipher
This project is a simple text encryption and decryption tool implemented in Python using the Tkinter library for the graphical user interface (GUI). It uses the Caesar Cipher algorithm to encode and decode English text. The Caesar Cipher is a type of substitution cipher where each letter in the plaintext is shifted a certain number of places down or up the alphabet.

Features:
Encrypt Text: Encrypts the input text by shifting each letter by a specified key value.
Decrypt Text: Decrypts the input text by shifting each letter back by the specified key value.

GUI Components:
Input Text: Text box to input the text to be encrypted or decrypted.
Key: Entry widget to input the key (shift value).
Encrypt Button: Button to encrypt the input text.
Decrypt Button: Button to decrypt the input text.
Output Text: Text box to display the encrypted or decrypted text.

Code Explanation:

1) Encryption Function (encrypt):
Loops through each character in the input text.
Checks if the character is an alphabet letter.
If it's an uppercase letter, shifts it by the key value within the range of 'A' to 'Z'.
If it's a lowercase letter, shifts it by the key value within the range of 'a' to 'z'.
Non-alphabetic characters remain unchanged.
Returns the encrypted text.

2) Decryption Function (decrypt):
Loops through each character in the input text.
Checks if the character is an alphabet letter.
If it's an uppercase letter, shifts it back by the key value within the range of 'A' to 'Z'.
If it's a lowercase letter, shifts it back by the key value within the range of 'a' to 'z'.
Non-alphabetic characters remain unchanged.
Returns the decrypted text.

3) GUI Functions:
encrypt_text: Gets the input text and key from the GUI, encrypts the text, and displays the encrypted text in the output text box.
decrypt_text: Gets the input text and key from the GUI, decrypts the text, and displays the decrypted text in the output text box.

4) Tkinter GUI Setup:
Creates the main window with a title.
Adds labels, text boxes, entry widgets, and buttons for user interaction.
Packs the widgets into the window.
Runs the Tkinter main loop to display the GUI.

You can now try out some encryption yourself. This time you are going to open up a Linux terminal window and run the command yourself.

On the left hand side is a terminal window. We have written a program in the Python language to handle this. 

Press the button below to clean up the folder with the various files each time you want to experiment again.

{Clean Up}(rm aes/deciphered.txt aes/cipher.txt)

## Edit your plain text
The first thing to do is to type some plain text into a file. Click on `aes` folder and then on `plaintext.txt` in the file tree to open it up.

## Encrypt
Press the button below to encrypt the file `plaintext.txt`. You will be prompted to enter a password. Enter something short and simple.

{Encrypt|terminal}(python /home/codio/workspace/.guides/aes.py encrypt /home/codio/workspace/aes/plain.txt ~/workspace/aes/cipher.txt)

## Open the cipher text
Once you have run the program, you will be able to see an encrypted file in the file tree. Open it and take a look.

This would be the file that you would send to someone.

## Decrypt the cipher text
The encrypted `cipher.txt` is now deciphered by someone using the same password. 

We will do this in the same place using the following command.

{Decrypt|terminal}(python /home/codio/workspace/.guides/aes.py decrypt /home/codio/workspace/aes/cipher.txt /home/codio/workspace/aes/decipher.txt)

## Get the password wrong
Try the decryption step again but use the wrong password. If you then try to open the file, you will probably get an error saying `can't open binary file`. This is because the decryption step mangled things and it cannot be shown as text.

Feel free to press the button at the top of the page and start again.




# MonoAlphabeticChipher_Java
<P>
This code defines a Java class called MonoAlphabeticChipher that contains two static arrays of characters called normalChar and codedChar. normalChar is initialized to an empty array with 26 elements, while codedChar is initialized with the 26 capital letters of the English alphabet in that order.

The main method of the MonoAlphabeticChipher class asks the user to input a new order for the alphabet and then a message they want to encrypt. It converts the message to lowercase and then calls the stringEncryption method on it, storing the result in a variable called encryptedString. It then prints the original message, the encrypted message, and the result of calling stringDecryption on the encrypted message.

The stringEncryption method takes in a string and returns an encrypted version of that string. It does this by iterating through each character in the input string and comparing it to each character in the normalChar array. When it finds a match, it adds the corresponding character from the codedChar array to the output string. If the character is not in the normalChar array, it is added to the output string as is.

The stringDecryption method is similar to stringEncryption, but it operates in the opposite direction. It takes an encrypted string as input and returns the original message by comparing each character in the input string to each character in the codedChar array and adding the corresponding character from the normalChar array to the output string. If the character is not in the codedChar array, it is added to the output string as is.
</p>

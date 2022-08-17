This project is a Java Console Application to generate Random passwords and performing a password strength check.

I decided to build this project during my third year after taking the Object-Oriented Effective Java Programming course, I wanted to build something interesting with Java to practice and see what I could do on my own. However, I still wasn't sure what I wanted to do. Then one night, I was explaining to my friend the importance of having a strong password for his social media accounts I got the idea of doing a random password generator, a week later it was done. While working on it I decided to include a password strength checker feature that checks for the overall strength of the entered password and I was pretty happy with how it came out but I realised that it was not very straightforward to use for someone who does not know how it is supposed to work so I decided to create a GUI for the application for the next step it is available in the Password-Services repository

Functionalities:

1- Generating a Password:

a- The user must answer by Yes or No the questions to know if he desires to use Uppercase/Lowercase letters, Numbers or Symbols

b- The user then enters the desired length of the password

c- A password alphabet is generated according to the Yes/No answers it is a String that contains the choices of the user

d- Depending on the length random characters from the password alphabet are selected and put back to back to form a totally random string according to the user's needs

e- The randomly generated password is then displayed on the console

2- Checking a Password's Strength:

The Strength check is based on the following criteria:

a- The password uses Uppercase Letters, Lowercase Letters, Numbers and Symbols  

b- The length of the password is 8 or more (8 is often the minimum required length for a decent password)

c- The length of the password is 16 or more (16 is considered to be the minimum length for good password)

These are used to calculate a score for the password used to know what message to display to the user weak/medium/good/great password

3- Displaying Useful Information:

This is a minor feature that displays on the console so information for the user about password security (Avoid using the same password twice/ Avoid character repetition, keyboard patterns, dictionary words, letter or number sequences, etc.)

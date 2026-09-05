# Passwords and Usernames

## Project Overview

This project explores usernames and passwords, including the random generation of both usernames and passwords by employing the random function in Python. The next steps for the project will be to create a **password strength checker
** and then to implement a **database** using SQL that stores usernames with their corresponding password and other account information. 

## About this Project - Random Password Generator

This project explores, using Python, password generation following standard rules for passwords given on websites namely: 
 - Between 8 and 16 characters long
 - Contains one uppercase letter
 - Contains one lowercase letter
 - Contains one number
 - Contains one special character

The code is based off: https://tcloud9.medium.com/creating-a-random-password-generator-using-python-6e3a6480532c . 
My code can be accessed here: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1NoshbceuLuRag_U9fMCW6qPyffzkg89X#scrollTo=KrhCN7p1Djm_)

The password is then shuffled in order to randomise the password more. 

### How the Code works

This code ensures that there is at least one uppercase character, one lowercase character, one number and one special character. The password is then bulked out to be between 8 and 16 characters with any random combination of uppercase characters, lowercase characters, numbers and special characters. 

After generating a password, it is then randomly shuffled in order to increase security. 

## About this Project - Random Username Generator

This code works in a similar way to the random password generator, meaning that it utilises the random function in python to create a pseudorandom combination of lowercase letters, numbers and other approved characters, and makes sure that the username is between 3 and 11 characters long. 
However, this code differs from the password generator, because unlike passwords, usernames have to be unique to each individual user. This code ensures that this is possible, firstly by storing a list of already generated usernames and once a new username has been generated, adding this username to the list. The code also makes use of a file that stores usernames. This ensures that across multiple runs the same username will not be generated twice. 

The code can be accessed here: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1actgtQQgnFgWN6u8UUdnrQwP4dRYPRx7)

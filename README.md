# Bandit
This repository consists of writeup for the solutions of bandits - Prasanna

# Level 0
SSH, or Secure Shell, constitutes a cryptographic network protocol designed to enable secure communication between two systems over networks that may not be secure.
Using the command ssh bandit0@bandit.labs.overthewire.org -p 2220
and the password bandit0 we go into the next level.

# Level 0 -> 1

Using the cat command we can print the file content
cat readme is used to show the password for the first level that is saved in the readme file

## Password 
NH2SXQwcBdpmTEzi3bvBHMM9H66vVXjL

# Level 1 -> 2

Connect to the Bandit shell using ssh bandit2@bandit.labs.overthewire.org -p 2220

The password is stored in the file named - , to open this use cat ./-

## Password
rRGizSaX8Mk1RTb1CNQoXTcYZWU6lgzi

# Level 2 -> 3
In this level the password is stored in the file which has spaces in it's name so we use \ to write the filename

Using the command cat spaces\ in\ this\ filename we get the password

## Password
aBZ0W5EmUfAf7kHTQeOwd8bauFJ2lAiG

# Level 3 -> 4

This time the password is in another directory. We use cd command to change directory.
Using the command cd inhere we go into the inhere directory and using ls -a command we get .hidden file which was hidden in which the passwordis stored

## Password
2EW7BBsr6aMMoJ2HjW067dm8EgX26xNe

# Level 4 -> 5
Go to inhere directory using cd inhere
and open the file using cat ./-filename and in 7th file there will be password that can be found using cat ./-file07

## Password
lrIWWI6bB37kxfiCQZqUdOIYfr6eEeqR

# Level 5 -> 6

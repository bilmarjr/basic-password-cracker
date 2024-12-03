# basic-password-cracker

## Password Brute Force Attack
This Python script performs a simple brute force attack on a password using a pre-defined wordlist.

## Features:
* Reads a wordlist from a remote URL
* Attempts to crack a predefined password hash
* Prints the cracked password if found

## Usage:
* Install required libraries 
> pip install requests
* Run script
> python brute_force.py

### Important Notes:
* This script is intended for educational purposes only, so use responsibly and with permission

## Code Structure:
* readwordlist(url): Downloads wordlist from URL
* hash(password): Generates SHA1 hash of password
* bruteforce(guesspasswordlist, actual_password_hash): Attempts to crack password
* Security Considerations:

Never use this against systems without explicit permission
Always use strong, unique passwords
This method is easily detectable by modern systems

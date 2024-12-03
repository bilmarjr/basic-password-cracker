# basic-password-cracker

## password Brute Force Attack
this Python script performs a simple brute force attack on a password using a pre-defined wordlist

## features:
* reads a wordlist from a remote URL
* attempts to crack a predefined password hash
* prints the cracked password if found

## usage:
* install required libraries 
> pip install requests
* run script
> python brute_force.py

### Important Notes:
* this script is intended for educational purposes only, so use responsibly and with permission

## Code Structure:
* readwordlist(url): Downloads wordlist from URL
* hash(password): Generates SHA1 hash of password
* bruteforce(guesspasswordlist, actual_password_hash): Attempts to crack password
* Security Considerations:

never use this against systems without explicit permission, always use strong, unique passwords, this method is easily detectable by modern systems

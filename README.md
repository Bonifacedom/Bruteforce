# Bruteforce
A bruteforce tool that tries all combo for the password field to gain access


Brute Force Attack Script

Description:
This executable performs a brute force attack on a login endpoint by systematically trying all possible combinations of usernames and passwords.

Usage:
1. Open a command prompt or terminal.
2. Navigate to the directory containing the executable.
3. Run the executable with the appropriate arguments:

   brute_force.exe <url><max_length> username [--verbose] [--delay <seconds>]

Example:
brute_force.exe http://localhost:3000/login username 4 --verbose --delay 0.5

Parameters:
- <url>: The URL of the login endpoint.
- <max_length>: The maximum length of the username and password combinations to try.
- --verbose (optional): Enable verbose output.
- --delay <seconds> (optional): Add a delay between requests.


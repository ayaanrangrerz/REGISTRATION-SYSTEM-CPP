# Login and Registration System (C++)

A small console program demonstrating registration, login checks, and basic file handling.

## Features
- Register a username
- Reject a username already present in the records
- Check a username and password during login
- Store records in `users.txt`

## Build and run
Requires a C++ compiler with C++11 support.

```bash
g++ -std=c++11 registration-system.cpp -o registration-system
./registration-system
```

On Windows, run `registration-system.exe` after compiling.

## Security note
This is a classroom demonstration. It writes passwords as plain text to `users.txt`; do not use it for real accounts or sensitive credentials.

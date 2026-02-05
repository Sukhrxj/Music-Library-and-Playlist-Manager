# Music Library & Playlist Manager

A command-line music management system written in C that allows users to manage a music library and playlists using structured data and file-based input.

## Features
- Load song data from a CSV file
- Add and delete songs from the music library
- Search and play songs by ID or name
- Create and delete playlists
- Play all songs within a playlist
- Analyze musical note counts within songs

## Technologies Used
- C (ANSI C)
- GCC compiler
- Modular programming with header files
- CSV file processing
- Pointers and structured data
- Command-line interface (CLI)

## What I Built
- Implemented a modular C program to manage songs and playlists
- Parsed and processed CSV data to dynamically load song information
- Designed functions for adding, deleting, searching, and playing songs
- Built playlist management functionality supporting multiple playlists
- Used structs, pointers, and arrays to manage program state efficiently
- Integrated all features through a centralized driver program

## What I Learned
- Designing multi-file C projects with clear separation of concerns
- Working with pointers, structs, and memory management
- Parsing and validating external data files in C
- Debugging segmentation faults and logic errors
- Writing maintainable low-level code following strict specifications

## How to Run
1. Compile the program using GCC (or the provided Makefile, if applicable)
2. Ensure the CSV file is in the correct directory
3. Run the executable from the command line
4. Follow the menu prompts to interact with the music library

## Future Improvements
- Persistent storage for playlists
- Improved error handling and input validation
- Enhanced user interface

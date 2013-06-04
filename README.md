secure-diary
============

# SYNOPSIS
**sdy** [OPTIONS] [FILES...]

# DESCRIPTION
Diary to log experiences, movies, songs, photos...

# OPTIONS
    -d, --diary			Write the entry on the diary
    -h, --help			Display this message
    -m, --movie			Write an entry about a movie
    -t, --treasure file[s]	Load file[s] into the treasure
    -q, --quit			Disconnect and encrypt the container

    Example: $PROGNAME -t '/path/to/file' -d -q 
    That will load a file in the treasure, then write a diary entry and then disconnect

# Dependencies
    - [Truecrypt](http://www.truecrypt.org/downloads)
    - Vim

# Install
Execute `./install` it may need sudo privileges

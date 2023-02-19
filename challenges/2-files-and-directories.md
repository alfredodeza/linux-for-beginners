# Files and directories challenges
Use this challenge to practice working with files and directories in a Linux environment. This challenge covers creating, moving, copying, and deleting files and directories.

## Listing files and directories
1. Use the `ls` command to list the contents of the current directory
2. Use the `ls` command to list the contents of the root directory
3. Use the `ls` command to list the contents of the `challenges` directory
4. Use the `ls` command to list the contents of the `challenges` directory using a relative path
5. Use an absolute path to list the contents of the `challenges` directory


## Changing directories
1. Use the `cd` command to change to the root directory of this repository
2. Use the `cd` command to change to the `challenges` directory
3. Use a relative path to change to the `challenges` directory
4. Use an absolute path to change to the `etc` directory

## Using globs and wildcards
Head to the [exercise 1 directory](/../../exercises/1) for this challenge. 

Context: You have a directory called "Photos" which contains several subdirectories, each representing a different year. Each year's subdirectory contains a number of image files with the extension ".jpg". Your task is to move all the image files from the year 2019 and 2020 into a subdirectory called "2022".

## Copying files and directories
Head to the [exercise 2 directory](/../../exercises/2) for this challenge.

Context: You have a directory called "Music" which contains several subdirectories, each representing a different genre of music. Within each genre subdirectory, there are multiple files with different file extensions. Your task is to list all the files in the "rock" genre subdirectory that have the extension ".mp3".

Use BASH glob and wildcards with the ls command to list all the files in the "Rock" subdirectory that have the extension ".mp3". For example, the command might look like this: `ls Music/rock/*.mp3`

Extra challenge: Try to use a single command to list all the files in the "Rock" subdirectory that have the extension ".mp3" or ".wav".
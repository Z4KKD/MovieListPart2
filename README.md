# Movie Guide Part 2

This Python script serves as a movie guide that allows users to manage a list of movies. It enhances the functionality of the Movie List Program by adding the capability to read and write movie data to a text file.

## Commands

- **list:** List all movies in the movie list.
- **add:** Add a new movie to the list.
- **del:** Delete a movie from the list.
- **exit:** Exit the program.

## File Management

The script reads and writes movie data to a text file named `movies.txt`. This file will be created in the same directory as the Python script if it does not already exist. The movie data is stored in a simple text format, with each movie listed on a separate line.

## Example

```
The Movie List program

COMMAND MENU
list - List all movies
add -  Add a movie
del -  Delete a movie
exit - Exit program

Command: list
1. The Shawshank Redemption
2. The Godfather
3. The Dark Knight

Command: add
Movie: Pulp Fiction
Pulp Fiction was added.

Command: del
Number: 2
The Godfather was deleted.

Command: exit
Bye!
```

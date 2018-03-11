# Drupal Shell Scripts

Useful scripts to quickly work with common tasks in Drupal. Export the directory to your PATH and enjoy!

## d8_new
This script creates a drupal project using Composer, initializes git with a first commit, installs the site using MySQL and runs PHP's built-in http server at localhost:8888.

**PARAMETERS**
It uses the first parameter as the project folder name and database name.
It uses the second optional parameter to set the site name, otherwise it uses the folder name.

Example:
`d8_new d8_sample "Drupal 8 Sample Site"`

## d8_remove

Removes a folder in the current directory and a MySQL directory with the same name passed as argument. A useful way to remove a site previously installed with d8_new.

Example:
`d8_remove d8_sample`

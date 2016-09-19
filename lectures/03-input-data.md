---
layout: lecture
title: "Using R: Data Input"
---


### Operating System Dependencies

- Displaying platform specific values with `.Platform`
- Character string used for separating files: `.Platform$file.sep`
- Constructing paths to files with `file.path()` (in a platform independent way)
- e.g. `file.path("directory", "subdir", "file.csv")`


### Interacting with the file system

- Displaying the current working directory with `getwd()`
- Setting the working directory with `setwd()`
- Listing files in a directory with `list.files()` and `dir()`
- Creating files with `file.create()`
- Checking whether a file exists with `file.exists()`
- Renaming files `file.rename()`
- Appending content to a file with `file.append()`
- Copying a file with `file.copy()`
- Deleting files with `file.remove()`
- Deleting files with `unlink()`
- Information about a file with `file.info()`
- Display file permissions with `file.access()`
- Download a file with `download.file()`


### Invoking shell commands

- Invoking shell commands with `system()` (or `system2()`)
- Windows users have also the `shell()` function


### Importing Data Tables

- Tables in Plain text files:
	+ blank sapce delimiter
	+ comma-separated values: csv
	+ european csv (semicolon)
	+ tab-separated values (aka _tsv_)
	+ fixed-width files
- `read.table()` and friends
	+ `read.csv()` and `read.csv2()`
	+ `read.delim()` and `read.delim2()`
- `read.fwf()`
- Package "readr"
- Tables in excel files
- Tables in google sheets: package "googlesheets"
- Tables in HTML: package "XML"
- Foreign programs
	+ SAS
	+ SPSS
	+ Matlab
	+ Stat
	+ Minitab
	+ etc


### Low level data input functions

- The most low-level reading function is `scan()`
- Default: reading numeric data with `scan()`
- More complex: reading data in columns with `scan()`
- The other generic function function for file input is `readLines()`
- Reading multiple lines with `readLines()`


### R's binary format

- R objects can be saved in a standard binary format
- R's binary format is platform independent
- An arbitrary number of R objects can be saved into a single file using `save()`
- The default binary file extension is `.RData` (or the old format `.Rda`)
- Use `load()` to read in an `.RData` file


### Connections

- Underlying the reading data functions we have the concept of __connections__
- create and manipulate a file connection with `file()`
- URL resource connections with `url()`
- closing connection with `close()`


### References

- __[R Data Import/Export Data](https://cran.r-project.org/doc/manuals/r-release/R-data.html)__ by R Development Core Team
- Chapter 2: Reading and Writing Data, __[Data Manipulation with R](http://link.springer.com/book/10.1007%2F978-0-387-74731-6)__ by Phil Spector
- Chapter 4: Input and Output in R, __[R Programming for Bioinformatics](http://uclibs.org/PID/137017)__ by Robert Gentleman
- Chapter 10: Input/Output, __[The Art of R Programming](http://site.ebrary.com/lib/berkeley/Doc?id=10513550)__ by Norman Matloff

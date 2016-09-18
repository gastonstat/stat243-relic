---
layout: lecture
title: "Using R: Data Input"
---


### Interacting with the file system

- Invoking shell commands with `system()` (or `system2()`)
- Windows users have also the `shell()` function
- Listing files in a directory with `list.files()` and `dir()`
- Creating files with `file.create()`
- Checking whether a file exists with `file.exists()`
- Renaming files `file.rename()`
- Appending content to a file with `file.append()`
- Copying a file with `file.copy()`
- Deleting files with `file.remove()`
- Deleting files with `unlink()`
- Download a file with `download.file()`


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

- Reading numeric data with `scan()`
- Reading data in columns with `scan()`
- Reading multiple lines with `readLines()`


### References

- __[R Data Import/Export Data](https://cran.r-project.org/doc/manuals/r-release/R-data.html)__ by R Development Core Team
- Chapter 2: Reading and Writing Data, __[Data Manipulation with R](http://link.springer.com/book/10.1007%2F978-0-387-74731-6)__ by Phil Spector
- Chapter 4: Input and Output in R, __[R Programming for Bioinformatics](http://uclibs.org/PID/137017)__ by Robert Gentleman
- Chapter 10: Input/Output, __[The Art of R Programming](http://site.ebrary.com/lib/berkeley/Doc?id=10513550)__ by Norman Matloff

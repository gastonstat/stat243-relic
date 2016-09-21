---
layout: lecture
title: "Manipulating Strings"
---

### Strings and Regex

[Handling and Processing Strings in R](http://gastonsanchez.com/Handling_and_Processing_Strings_in_R.pdf)

- Character vectors
- Function `character()`
- Functions `readLines()`
- Creating character vectors with `paste()` and `paste0()`
- Printing functions:
	+ `print()`
	+ `sprintf()`
	+ `cat()`
- Basic manipulation functions:
	+ counting characters with `nchar()`
	+ case-folding with `tolower()`, `toupper()`, `casefold()`
	+ abbreviating strings with `abbreviate()`
	+ repalcing strings with `substr()` and `substring()`
- R package `"stringr"`
- Basics of Regular Expressions:
	+ Literal characters
	+ Metacharacters
	+ Character Classes
	+ Quantifiers
- Regex with `"stringr"`
	+ dectecting patterns with `str_detect()`
	+ extracting matches with `str_extract()` and `str_extract_all()`
	+ locating matches with `str_locate()` and `str_locate_all()`
	+ replacing matches with `str_replace()` and `str_replace_all()`
	+ splitting strings with `str_split()` and `str_split_all()`



### References

- __[R Data Import/Export Data](https://cran.r-project.org/doc/manuals/r-release/R-data.html)__ by R Development Core Team
- Chapter 7: Character Manipulation, __[Data Manipulation with R](http://link.springer.com/book/10.1007%2F978-0-387-74731-6)__ by Phil Spector
- Chapter 5: Working with Character Data, __[R Programming for Bioinformatics](http://uclibs.org/PID/137017)__ by Robert Gentleman
- Chapter 18: String Manipulation, __[The Art of R Programming](http://site.ebrary.com/lib/berkeley/Doc?id=10513550)__ by Norman Matloff

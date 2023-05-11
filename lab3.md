## Lab Report 3
The command that I am going to use for this lab report is `find`. 

# Option 1
The first option that I am going to use is `-type`.
Example 1:
`find ./technical -type f -name "*.txt"`
This command finds all regular files with the extension .txt in the ./technical directory.

Example 2:
The second example is used to find a directory. 
`find ./technical -type d -name "fortnite"`
This command searches for directories named "fortnite" in the ./technical directory.

# Option 2
The second option that I am going to use is `-size`
Example 1:
`find ./technical -type f -size 30c`
This command finds all regular files that are larger than 30 bytes. 

Example 2:
`find ./techincal -type d -size 1G`
This command searches for directories smaller than 1 gigabyte.

# Option 3
The third option I am using is `-mtime`.
Example 1:
`find ./technical -type f -mtime -5`
This command finds all regular files that have been modified within the past 5 days.

Example 2:
`find ./technical -type d -mtime +8 -name "mcdonalds"`
This command would search for directories modified more than 8 days ago and are named "mcdonalds".

# Option 4
The fourth option I am using is `-print`
Example 1:
`find ./technical -type f -name "*.txt" -print`
This command would find all files with the extension ".txt" and print their respective file paths.

Example 2:
`find ./ technical -type d -name "fortnite" -print`
This command would search for directors named "fortnite" and prints their paths.

All alternate commands were found from the Linux manual find page. [here](https://man7.org/linux/man-pages/man1/find.1.html)

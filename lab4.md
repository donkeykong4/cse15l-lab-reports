## Lab Report 4

# Step 4
![Image](step4.png)
`ssh <space> cse15lsp23os@ieng6.ucsd.edu <enter>`
In this step, I logged into my course-specific account for the remote server.

# Step 5
![Image](step5.png)
`git <space> clone <space> https://github.com/ucsd-cse15l-s23/lab7 <enter>`
I cloned the given repository in the terminal.

# Step 6
![Image](step6.png)
```
cd <space> lab7 <enter>
chmod <space> +x <space> test.sh <enter>
./test.sh <enter>
```
I changed the directory to the one currently being worked on. Then I allowed permission for the test.sh file to be ran and then ran the file.

# Step 7
![Image](step7.png)
```
vim <space> ListExamples.java <enter>
jjjjjjkkkkkkkr2:wq <enter>
```
I accessed the ListExamples.java file in vim and fixed the code by changing index1 to index2 and then saved the file.

# Step 8
![Image](step8.png)
`./test.sh <enter>`

Ran the test.sh file to show that the bug is now fixed.
# Step 9
![Image](step9.png)
```
git <space> add <space> ListExamples.java <enter>
git <space> -m <space> "Fixed <space> ListExamples.java" <enter>
git <space> push <enter>
```

Commit and push the changes to main.

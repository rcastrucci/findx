# Findx
### Is a python script ready to run on terminal

<p>
Why have I done that? <br>
Well! I couldn't find a file in my computer. And the mac search box wouldn't go through hidden files or in specific system folders.
So I developed this easy python scrypt to find files for me. It will find files with similar names or exact name. I couldn't recall where I had put my <strong>ojdbc8.jar</strong> file. Well just use:    
</p>

        findx -search ojdbc8.jar /
     
<p> It will find!! Inclusive all duplicated copies you have on your computer! And for my surprise, check this out: </p>

<img src="https://github.com/rcastrucci/findx/blob/main/print.png" width="360" height="auto"/>

<p> While studying and doing projects I had 60 copies of this same file! Not good! </p>
<p> Bellow some examples and link to clone ;) </p>

run:

    git clone https://github.com/rcastrucci/findx.git
    
###### The command bellow will display the options
Displaying options:

    ./findx -help

###### The command bellow will search for a file named as filename or part of the name containg the string filename in your entire home folder.
Searching for a file:

    ./findx -search filename ~/

###### The command bellow will search for a word inside the file test.txt located in Desktop folder. Once found, will return line and position number.
Searching for a word in a file:

    ./findx -find ~/Desktop/test.txt word

<br>

#Lab 6 Notes  

Commands sent over email overwrote default mac commands with more standard versions of those utilities  

find . -name "ABCABC*" 
- . means find here
- * means anything, so if at beginning it means start with anything or at end means end with anything
- ex: find . -name "ora*.tx*" is find a file with ora at the beginning and .tx at the end  

wget did not work for me, had to save as into test folder

grep "Moby Dick" filename.file
- grep is a full text search for Moby Dick in that file
- grep "fdf" * searches whole directory
- grep -r "fdf" will search in other directories underneath the directory you are in as well
- grep "test" file.file | wc give you work count, numbers represent lines, words, characters

sort file.file will sort each line alphabetically with words, numbers you have to specify
- adding uniq -c after it will search for unique lines and tell you how many times each line appears

sed: streamline editory
- ex: sed 's/day/night/' file.file will substitute all words from day into night and display it, but not change the file
- precede w/ -i to change the file (dangerous)
- -i did not work with a mac 
- to be safe do not overwrite data but >> file.txt to create a new file for the replacement

##Assignment: analyze treatment of gender in Moby Dick
- create new project directory
- grab text of moby dick
- make 2 lists of gendered word with each word a new line 
- ex: male words are he, male, man, et. and do the same w/ females
- grep context of all the male and female files, and create 2 moby dicks one with all male words and one with all female words
- get rid of common english words from each of those files and be left with non-common gender context words in a separate file and sort and count

##Weasel Words
- take a piece of writing and check for the clarity of writing
- take 3 pieces of writing and put them in file and save as plain text
- make a list of files of weasel words such as clearly, obviously (google it)
- write a script that replaces those weasel words with something else


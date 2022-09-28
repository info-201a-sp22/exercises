# Exercise 1
Here are the solutions for this exercise:

```bash
# Navigate to your "Desktop" folder
cd ~/Desktop

# Create a new folder called "quick-exercise"
mkdir quick-exercise

# Navigate into that folder
cd quick-exercise

# Download file from Project Gutenberg
# Mac
curl -O https://www.gutenberg.org/cache/epub/37106/pg37106.txt
# Windows
wget https://www.gutenberg.org/cache/epub/37106/pg37106.txt -OutFile LittleWomen.txt
# or manually create the empty file

# List the contents of the folder to verify the new file is there
ls

# Display the contents of the folder in the terminal
# Mac
less LittleWomen.txt
# Windows
more LittleWomen.txt

# Bonus: Search for a word in the address
# Mac 
grep "dress" ../Desktop/quick-exercise/LittleWomen.txt
# Windows
findstr "dress" ../Desktop/quick-exercise/LittleWomen.txt

# Navigate to the "Documents" folder for your machine
cd ../../Documents #path may vary

# Display the contents of the "Desktop/quick-exercise/ittleWomen.txt" file in the Terminal *without changing directories again!*
cat ../Desktop/quick-exercise/LittleWomen.txt
# cat shows entire contents in one dump; less is also an acceptable command

```

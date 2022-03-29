# Exercise 1
Here are the solutions for this exercise:

```bash
# Navigate to your "Desktop" folder
cd ~/Desktop

# Create a new folder called "quick-exercise"
mkdir quick-exercise

# Navigate into that folder
cd quick-exercise

# Using the text editor of your choice (e.g., Atom, TextEdit), create a new (empty) file called "address.txt" inside the "quick-exercise" folder you made
# Mac
touch address.txt
# Windows
ni address.txt
# or manually create the empty file

# List the contents of the folder to verify the new file is there
ls

# Display the contents of the folder in the terminal
# Mac
less address.txt
# Windows
more address.txt

# Navigate to the "Documents" folder for your machine
cd ../../Documents #path may vary

# Display the contents of the "Desktop/quick-exercise/constitution.txt" file in the Terminal *without changing directories again!*
cat ../Desktop/quick-exercise/address.txt
# cat shows entire contents in one dump; less is also an acceptable command

# Bonus: Search for a word in the address
# Mac 
grep "tax" ../Desktop/quick-exercise/address.txt
grep "tax" ../Desktop/quick-exercise/address.txt -n -- color 
# Windows
findstr "tax" ../Desktop/quick-exercise/address.txt
```

# Exercise 1
Here are the solutions for this exercise:

```bash
# Navigate to your "Documents" folder
cd ~/Documents

# Create a new folder called "quick-exercise"
mkdir quick-exercise

# Navigate into that folder
cd quick-exercise

# Using the text editor of your choice (e.g., Atom, TextEdit), create a new (empty) file called "constitution.txt" inside the "quick-exercise" folder you made
# Mac
touch constitution.txt
# Windows
ni constitution.txt
# or manually create the empty file

# List the contents of the folder to verify the new file is there
ls

# Search online for the text of the US Constitution (while it's still around!) and paste it into the "constitution.txt" file you created. Save your changes in the editor.
# No command for this one

# Display the contents of the folder in the terminal
# Mac
less constitution.txt
# Windows
more constitution.txt

# Navigate to the "Desktop" folder for your machine
cd ../../Desktop #path may vary

# Display the contents of the "Documents/quick-exercise/constitution.txt" file in the Terminal *without changing directories again!*
cat ../Documents/quick-exercise/constitution.txt
# cat shows entire contents in one dump; less is also and acceptable command

# Bonus: Search for a word in the US Constitution
# Mac 
grep "tax" constitution.txt
grep "tax" constitution.txt -n -- color 
# Windows
findstr "tax" constitution.txt

```

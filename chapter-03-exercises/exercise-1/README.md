# Exercise 1
In this exercise you'll practice using git to clone and edit repositories, as will be required for later exercises.

1. If you haven't already, configure your name and email address for your GitHub account using the terminal.

	```bash
	# enter your full name (without the dashes)
	git config --global user.name "your-full-name"

	# enter your email address (the one associated with your GitHub account)
	git config --global user.email "your-email-address"
	```

3. Using the terminal, clone **your repository** to your machine (make sure you're in the desired directory on your terminal).

	```bash
	# Enter a desired directory
	cd ~/Documents

	# Get the URL by clicking the "Clone or Download" button on GitHub, then clicking the clipboard icon

	# Clone the repository
	git clone https://github.com/info-201a-au21/exercises-melaniewalsh.git
	```

4. On your machine, open up this file (`exercise-1/README.md`) in a text editor of your choice.

	```bash
	# Open up the file
	```

5. In the `README.md` file, below these instructions, add an h1 header "Favorite Foods" and an ordered list of your 3 favorite foods.

	```markdown
	# Favorite Foods
	1. Mochi ice cream
	2. Scallops
	3. Brussel sprouts
	```

6. Using your terminal, add and commit the changes you've made to your repository

	```bash
	# Add changes from all files in the repository
	git add .

	# Commit changes making sure to include a descriptive message
	git commit -m "Adds fav foods"
	```

7. Push changes up to GitHub, and view them in your web browser. Make sure you are looking at the repository under _your_ account!

	```bash
	# Push changes
	git push origin master
	```
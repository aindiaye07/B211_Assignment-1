# B211_Assignment-1

A) Purpose of the Program(s):
This code generates secure passwords of two types:
- Memorable: Combination of random dictionary words, numbers, and hyphens.
- Random: Random mix of letters, numbers, and symbols.
Saved generated passwords with timestamps to specific modules within organized libraries.

B) Input
- Select Type (1 for Memorable, 2 for Random)
Memorable Inputs:
- How many words in the password (num_words).
- Choosing 'lower,' 'upper,' or 'title' (capitalized); ('case').
Random Inputs:
- Desired character length ('length').
- Adding special symbols ('include punctuation').
- Specific characters to omit ('exclude characters').

C) Output 
- Displays generated password
Files
- 'Memorables/Generated_Passwords.txt'
- 'Random/Generated_Passwords.txt'

D) Libraries Used
- 'random' = Selecting random words/characters.
- 'string' = Access ASCII letters, digits, and punctuation.
- 'os' = Creating directories ('Memorable' and 'Random') if they don't exist.
- 'datetime' = Timestamping password creation time.

# Navigating
- Arrow keys - move the cursor around
- j, k, h, l - move the cursor down, up, left and right (similar to the arrow keys)
- ^ (caret) - move cursor to beginning of current line
- $ - move cursor to end of the current line
- nG - move to the nth line (eg 5G moves to 5th line)
- G - move to the last line
- w - move to the beginning of the next word
- nw - move forward n word (eg 2w moves two words forwards)
- b - move to the beginning of the previous word
- nb - move back n word
- { - move backward one paragraph
- } - move forward one paragraph

# Deleting content
- x - delete a single character
- nx - delete n characters (eg 5x deletes five characters)
- dd - delete the current line
- dn - d followed by a movement command. Delete to where the movement command would have taken you. (eg d5w means delete 5 words)

#Tips
If you type :set nu in edit mode within vi it will enable line numbers. I find that turning line numbers on makes working with files a lot easier.

# css_unix_tutorial
 
This repository has a sample set of files which students will interact with during their css tutorial.  Below are the tasks students are asked to complete.

## Tasks

1. We'll start like most academic papers, with a literature review. Look at the folder `literature`, and just using the `ls` command (and its various flags), tell me which of the files is the longest.
1. Use the `wc` command to confirm that the largest file also has the largest number of words and lines.
1. Try both `cat` and `more` to read `literature/thebrotherskaramazov.txt`, and learn quickly why you choose one over the other.
1. Time to create a poetry anthology. Create a new file called `anthology.txt` which contains the five poems in `literature`, but *not* the Brothers Karamazov, in only one single command.
1. OK, enough high-minded literature.  Let's dive into file systems. There is an innocent file trapped someplace under `folders/ohnoanotherfolder`.  Find him, and copy him to the `folders` folder *without using a pathname*.  (Hint: dots)
1. Will has misplaced a very important file called 'youfoundit.txt' inside the hellscape that is the `foldersplosion` folder.  Find it, without using `find` or `locate`.
    - Now find it using `find`.  The man page for this program is missing on datahub, but it's also available at <https://linux.die.net/man/1/find>
1. Will's CV could use a bit of padding.  Please change the author of 'The Red Wheelbarrow' in `literature/wcw_barrow.txt` to read 'Will Styler, 2022'.  Use `nano` (or your cli editor or choice) to edit this file, or if you're experienced with the command line, find a way to do it without an editor.
1. You'd better change the name of the file too.  Turn that poem into `ws_barrow.txt`
1. Oh no, the academic integrity people have caught wind of my scheme!  Quick, hide the evidence by moving that modified file into a new folder called `academic_misdeeds` inside `foldersplosion/folder_2974_bbq`.  Do this in less than three commands.
1. That's it, if Will's going to be a fugitive from the academic law, you're going to join him.  Commit some unix crimes by moving around the file system and running commands such that you run into three `Permission Denied` or similar 'you can't do that' messages

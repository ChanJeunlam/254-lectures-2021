# Instructions to use this repository with syzygy

Advanced users will not need my instructions, nor syzygy. 

## If first cloning into syzygy:

1. Go to https://utoronto.syzygy.ca, log in with your UTorID, and start the server.
2. Near the top-right-hand corner of the home menu, hit the drop-down menu "New", and click on Terminal.
3. Clone the repo of my chapters by typing
    ```
    git clone git@github.com:ngrisouard/254-lectures-2021.git
    ```
    in the Terminal and hit return. This should create a new directory called `254-lectures-2020`, containing my lecture notes.

## Refreshing the lecture notes

At the beginning of the term, the lectures will be quite empty. As the term progresses, I will add to them, correct typos, etc. You will want to refresh the contents periodically, before and after each lecture.

4. To get the latest updates, repeat steps 1-2 above.
5. In the Terminal, change directory to go to the repository by typing
    ```
    cd 254-lectures-2020
    ```
    and hit return.

6. If you just want to play around with the notes a little in-between two updates but want your repository to closely match what I have on GitHub, enter the commands
    ```
    git fetch --all
    git reset --hard origin/master
    ```
    in the Terminal, where you left at the end of step 5, whenever you want to re-align your notes with mine.

7. If you want to be more fancy, modify the notebooks significantly and keep your modifications while keeping up-to-date with my content, I suggest you create your own "fork" and work on it. You can then sync your fork with my repository by following these instructions: https://help.github.com/en/articles/syncing-a-fork

## Opening a Jupyter notebook:

8. Repeat steps 1-3 above.
9. Repeat step 6 or 7 above, probably.
10. You can navigate to the Jupyter file, using the graphical interface of the home menu of syzygy. You are looking for a `.ipynb` file.

**Please let me know if you encounter problems with this procedure.**
# Ultimate Pig
This notebook analyzes the game of pig solitaire, a single-player dice game. A player has 7 turns in which to score the most number of points possible.

### Game Rules
* If the player rolls a 1, all points are lost and the turn is over
* The player must roll at least once, but may roll as many times as they wish during a turn
* Each turn's score is the sum of their rolls (except if they roll a 1, in which case that turn is worth 0 points)
* The player may choose to hold their current turn score at any time after a non-1 roll

## Objective
Find the best strategy for this game, the "ultimate pig" player.


## To View This Notebook
Just click on the `ultimate-pig.ipynb` file above.

## To Run This Notebook
#### System Requirements / Installation

* You will need to have **python&nbsp;3** installed on your machine. See [python's site](https://www.python.org/) for details.

* Clone this repo onto your machine.

* You will need to make sure that you have a virtual environment running in the folder that you intend to work from. [See this site for details if you're not familiar.](http://docs.python-guide.org/en/latest/dev/virtualenvs/) **Complete this step before attempting the below.**

* In your command-line program (such as Terminal on Mac&nbsp;OS&nbsp;X), navigate into the newly created repo. By default, this will be called `flipping-out`. Install the requirements file by runnning **`pip install -r requirements.txt`**.

#### Opening the Notebook
* Using a command-line program, navigate to the folder containing the downloaded file and run the following line: **`ipython notebook ultimate-pig.ipynb`**

* **Note:** This will open in a browser window and take over the command-line program's window until you close out of IPython Notebook. If you have closed your browser window, but your command line is still running the notebook, kill the process by pressing `Ctrl+C` or quitting the program entirely.

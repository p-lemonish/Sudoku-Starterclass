---
permalink: /basics/
sidebar:
  nav: "docs"
title: Basics of Sudoku
header:
    overlay_image: /images/sudoku-header-image.jpg
    overlay_filter: 0.3
    caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
---
In this section, you will cover the fundamental rules of Sudoku. Learn how to fill in the grid, understand the concept of rows, columns, and boxes, and discover the strategies to ensure that each number appears only once in every row, column, and box. Mastering these rules is the first step towards becoming a Sudoku expert.
### Overview of Sudoku Rules
Sudoku is played on a 9x9 grid, divided into nine 3x3 sub-grids (also called boxes). The objective is to fill in the grid so that each row, column, and 3x3 box contains all the digits from 1 to 9, with no repetition. Remember, every number must appear only once in each row, column, and box.
![An empty Sudoku grid](https://p-lemonish.github.io/Sudoku-Starterclass/images/basics/empty-grid.png){:style="display: block; margin: auto;"}
<div style="text-align: center; font-style: italic; font-size: 0.8em; margin-top: -1.5em">
    An empty Sudoku grid
</div>

### Rules for Filling the Grid

Now that we understand the grid's structure, let's go over the fundamental rules of Sudoku:

1. **No Repetition**:
   - In every row, column, and box, each of the digits from 1 to 9 must appear exactly once. This means no repetition of numbers within these units.

2. **Logical Deduction**:
   - Sudoku is a game of logical deduction. It does not involve any guessing or random placement of numbers.

3. **Starting Clues**:
   - A Sudoku puzzle typically starts with some numbers already filled in. These are the "clues" that provide the initial information to kickstart the puzzle.

4. **Step-by-Step Filling**:
   - Players solve Sudoku puzzles by placing one number at a time, making sure it fits the rules of the game.

![A partially solved Sudoku puzzle](/images/basics/partially-filled-grid.png){:style="display: block; margin: auto;"}
<div style="text-align: center; font-style: italic; font-size: 0.8em; margin-top: -1.5em">
    A partially solved Sudoku puzzle
</div>

### Example: Solving a Sudoku Puzzle

Let's walk through a simple example to illustrate how numbers are positioned within the grid. Starting with a partially filled puzzle, we'll use logical deduction to complete it step by step.

Let's take a look at the previously seen partially solved Sudoku. I've highlighted a box (we can also call it box #8, since it's the 8th box in the grid) that interests me when I'm beginning to solve the puzzle.

![A partially solved Sudoku puzzle with a highlighted box of interest](/images/basics/partially-filled-grid-highlight-1.png){:style="display: block; margin: auto;"}
<div style="text-align: center; font-style: italic; font-size: 0.8em; margin-top: -1.5em">
    A partially solved Sudoku puzzle with a highlighted box of interest (box #8)
</div>

The numbers 1 and 8 are missing from the highlighted box. We can start by looking at each of the empty cells within the box if it's possible to enter either of those numbers 1 or 8 into the cell without breaking the Sudoku rules of repetition. The empty cells can be called cell #2 and cell #4, since they're the 2nd and 4th cells in the box respectively. Next I've added a highlight of the column that the empty cell #2 sees as a result of the Sudoku rules.

![A partially solved Sudoku puzzle with a highlighted box and column of interest](/images/basics/partially-filled-grid-highlight-2-alt.png){:style="display: block; margin: auto;"}
<div style="text-align: center; font-style: italic; font-size: 0.8em; margin-top: -1.5em">
    Highlighted column of interest (column #5)
</div>

As can be seen, since we need to enter either 1 or 8 into cell #2, we can conclude from the highlighted column that cell #2 cannot have 1 in it, as it would break the rules of repetition for Sudoku! Therefore we have logically deduced that cell #2 must have 8 in it. We can further conclude that the last remaining empty cell (cell #4) in box #8 must be 1.

![A partially solved Sudoku puzzle with a highlighted box that is completed](/images/basics/partially-filled-grid-highlight-3.png){:style="display: block; margin: auto;"}
<div style="text-align: center; font-style: italic; font-size: 0.8em; margin-top: -1.5em">
    Box #8 is now complete!
</div>

Now the next step is to see what is unlocked by solving the previous steps. We can see that row #7 has only one missing digit. I will highlight it so that it's easier to see

![A partially solved Sudoku puzzle with a highlighted box that is completed and a row of interest](/images/basics/partially-filled-grid-highlight-4.png){:style="display: block; margin: auto;"}
<div style="text-align: center; font-style: italic; font-size: 0.8em; margin-top: -1.5em">
    Highlighted row of interest (row #7)
</div>

As can be seen, the last missing digit on row #7 is 1. Let's add it!

![A partially solved Sudoku puzzle with a highlighted box that is completed and a now completed row of interest](/images/basics/partially-filled-grid-highlight-5.png){:style="display: block; margin: auto;"}
<div style="text-align: center; font-style: italic; font-size: 0.8em; margin-top: -1.5em">
    Row #7 is now complete as well!
</div>

By following these rules and employing logical reasoning, players can gradually fill in the Sudoku grid until it's completed.


Once you're done here, you're ready to head to the next section where you will learn [slightly more advanced solving tips!](/solving-tips)


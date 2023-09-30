---
permalink: /solving-tips/
sidebar:
  nav: "docs"
title: Solving tips
header:
    overlay_image: /images/sudoku-header-image.jpg
    overlay_filter: 0.3
    caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
---
Ready to take your Sudoku skills to the next level? In this section, you will find valuable tips and techniques to help you solve Sudoku puzzles efficiently. With these simple strategies you'll learn how to analyze the grid, identify patterns, and make logical deductions that will help you solve some harder Sudoku puzzles!

### Writing Down Candidate Numbers in Cells

In more complex Sudoku puzzles, it's often beneficial to write down potential candidate numbers within empty cells. This technique provides a visual aid and helps narrow down possibilities as you progress through the puzzle. Here's how you can effectively write down candidate numbers:

1. **Understanding Candidate Number Notations**:
   - Candidate number notations involve placing small numbers (1-9) within the cells to indicate potential candidates. These numbers represent the possible values that can be placed in the cell.

2. **Using Pencil Marks**:
   - These markings are often referred to as "pencil marks" because they are typically written lightly or in a smaller font to distinguish them from actual placed numbers.

3. **Observing Patterns**:
   - By writing down candidate numbers, you can start to notice patterns and relationships between numbers in different cells, which can lead to more advanced solving techniques.

**Example**:

Let's take a look at a simple Sudoku puzzle and see how writing down candidate numbers can be helpful:

![Writing down candidates example](https://p-lemonish.github.io/Sudoku-Starterclass/images/solving-tips/writing-down-candidates.png){:style="display: block; margin: auto;"}
<div style="text-align: center; font-style: italic; font-size: 0.8em; margin-top: -1.5em">
    An example of box #6 pencil marked with all possible candidates in each cell
</div>

In the example above, I've written down potential candidate numbers in each empty cell for box #6. This allows us to quickly identify which numbers can potentially go in each cell, aiding in the solving process.

By incorporating the practice of writing down candidate numbers into your Sudoku-solving strategy, you'll have a powerful tool at your disposal. It enables you to approach even the most challenging puzzles with confidence and precision. Practice this technique, and you'll find it significantly enhances your ability to solve Sudoku puzzles efficiently.

### Naked Pairs
Naked Pairs is an advanced technique that involves identifying a set of candidate numbers that can only appear in a specific set of cells within a box, row, or column. Here's how it works:

1. **Candidate Exclusion**:
   - Look for instances where a set of candidate numbers is confined to a few cells within a unit. This means those numbers cannot appear in other cells of the unit.

2. **Elimination**:
   - Once you've identified naked candidates, you can eliminate those numbers as possibilities in other cells of the unit.

**Example**:

As an example, let's take a single box from another Sudoku puzzle. Let's start by writing down candidates.
![Naked Pairs Example](https://p-lemonish.github.io/Sudoku-Starterclass/images/solving-tips/naked-pair-example-1.png){:style="display: block; margin: auto;"}
<div style="text-align: center; font-style: italic; font-size: 0.8em; margin-top: -1.5em">
    An example of a box with all of the possible candidates set in each cell
</div>
Next let's look to see if there are any candidates confined to a few cells within the unit. Unit in this case is the box we're analyzing.
![Naked Pairs Example](https://p-lemonish.github.io/Sudoku-Starterclass/images/solving-tips/naked-pair-example-2.png){:style="display: block; margin: auto;"}
<div style="text-align: center; font-style: italic; font-size: 0.8em; margin-top: -1.5em">
    Naked 5 and 6 pair circled for visibility
</div>
After noticing the naked 5-6 pair, since there cannot be any other numbers in those two cells, we can logically deduce that 5 and 6 can be removed from all other cells within the unit.
![Naked Pairs Example](https://p-lemonish.github.io/Sudoku-Starterclass/images/solving-tips/naked-pair-example-3.png){:style="display: block; margin: auto;"}
<div style="text-align: center; font-style: italic; font-size: 0.8em; margin-top: -1.5em">
    Eliminate the digits 5 and 6 from all the other cells due to the elimination rule
</div>
<details>
<b>A: There is a 1-2 naked pair that appeared in the top left corner!</b>
<summary>
Q: Do you notice the next naked pair appearing after eliminating 5-6 from all the other cells? (click to expand for a hint)
</summary>
</details>
<br>
What happens to the bottom right corner cell with candidates 1, 7, and 9 in it?

### Hidden Pairs
Hidden Pairs is another powerful technique used in Sudoku solving. It involves identifying a set of candidate numbers that are confined to a specific set of cells within a box, row, or column, but they may also have additional candidates. Here's what you need to know:

1. **Hidden Pairs/Triples**:
   - Look for groups of cells that contain the same set of candidates. Even though there may be additional candidates, these numbers are 'hidden' within the group.

2. **Exclusion**:
   - Once you've identified hidden candidates, you can exclude those numbers from being possibilities in other cells of the unit.

**Example**:
As an example, let's take the same box from the previous example although this time let's make it slightly harder. Let's start by writing down candidates.
![Hidden Pairs Example](https://p-lemonish.github.io/Sudoku-Starterclass/images/solving-tips/hidden-pair-example-1.png){:style="display: block; margin: auto;"}
<div style="text-align: center; font-style: italic; font-size: 0.8em; margin-top: -1.5em">
    An example of a box with all of the possible candidates set in each cell
</div>
As opposed to the example seen previously, the 5-6 naked pair is no longer there, so what can be seen? There are only two cells in which the digits 1 and 2 can go into, they're hidden between all the other candidates so it might be hard to see.
![Hidden Pairs Example](https://p-lemonish.github.io/Sudoku-Starterclass/images/solving-tips/hidden-pair-example-2.png){:style="display: block; margin: auto;"}
<div style="text-align: center; font-style: italic; font-size: 0.8em; margin-top: -1.5em">
    Hidden 1 and 2 pair circled for visibility
</div>
Since 1 and 2 cannot be placed anywhere else in the unit, we can remove all the other candidates from these two cells making the unit neater.
![Hidden Pairs Example](https://p-lemonish.github.io/Sudoku-Starterclass/images/solving-tips/hidden-pair-example-3.png){:style="display: block; margin: auto;"}
<div style="text-align: center; font-style: italic; font-size: 0.8em; margin-top: -1.5em">
    Exclude all other digits from the 1-2 pair cells due to there being no other possible cells to place those digits in
</div>

With these techniques, you'll be equipped to tackle more challening Sudoku puzzles. Practice and patience are key, so don't be discouraged if it takes some time to master these strategies. Happy Sudoku solving!

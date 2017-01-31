# GVC Developer Test

Where possible please code using ES2015 and above.

#### Submitting Code

Please clone this project and commit to your personal Github account. Then forward the link onto HR.

### Challenge 1

**Description**

Given an n x n multidimensional array, traverse around it in a cyclical motion to return the array with its elements arranged from outermost elements to middle element, traveling clockwise.

For example the following multidimensional array:

```javascript
const input = [
	[1, 2, 3],
	[4, 5, 6],
	[7, 8, 9],
]; 

```

Should become:

```javascript
const output = [1, 2, 3, 6, 9, 8, 7, 4, 5];
```

The function should work with a multidimensional array of any size.

This code is expected to work on node v5.00. You may test it here: https://repl.it/languages/nodejs


### Challenge 2

**Description**

Build a simple React app that consumes two feeds and outputs a grid list of games showing the game image, title, description and CTA button.

**Instructions**

1. Before starting, please look at **test-mockup.jpg**, **categories.json** and **games.json**
2. The **games.json** file contains a list of the individual game objects, each associated with a numeric key. This numeric key corresponds to the gameId field in the **categories.json** file.
3. For the **'Home view'**, please initially display 5 items for each of the new, scratchcards and jackpot categories with an option to show another 5 items on click of the **'Show More'** button.
4. When all the items for a particular section has been shown, please hide the button.
5. For the **'New'**, **'Scratch Cards'** & **'Jackpot'** views, please show a grid list of all the games for the selected section.
6. For the CTA button, please create a simple hash link using the **playURL** in the format of `#launch-${playURL}`
8. Any CSS can be embedded directly into the **index.html** file

### Nice to haves
- Use of Promises for feed requests
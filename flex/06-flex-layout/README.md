# An entire page!

Flexbox is useful for laying out entire pages as well as the smaller components we've already been working with. For this exercise, we're leaving you with a little more work to do, with some things you may not have encountered yet. It's perfectly acceptable to google things you're unsure of!

### Hints
- You may want to search something like `CSS remove list bullets`.  We've done this for you in previous examples, but not here. Yay learning.
- Finding out how to style links in CSS might help you get rid of that pesky underline decoration...
- We've added `height: 100vh` to the `body`... this makes the body exactly the same height as the viewport. To stick the footer to the bottom you will need to use flex and change the direction to column.

## Desired Outcome
![desired outcome](./desired-outcome.png)

### Self Check

- The header is at the top of the page, the footer is at the bottom, and they stay in place if you resize your screen.
** display: flex in class header and footer 
- The header and footer have padding.
- The links in the header and footer are pushed to either side.
** justify-content: space-between in class header and footer
- There is space between the links in the header and footer.
** ul gap??? 
- The footer has a light gray background (`#eeeeee`).
** class footer has background
- The logo, input and buttons are centered in the screen.
** class content is the div with the logo, input, and buttons 
** so class content, display flex; and then i need to change the axis, so it is vertical flex-direction: column; align-items: center;
- The buttons have an appropriate amount of padding.
- There is space between the logo, input and buttons.

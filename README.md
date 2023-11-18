# Challenge: "Name Picker App(React)"

![Example Screenshot from the finished challenge](./example-screenshots/finished.png)

## Challenge Overview

Make a React app which shows some baby names and lets you pick your favourites. The names data is provided for you.

### The data:

The data is available in the file [./namesData.json](./namesData.json).

Copy across this file to your src/ directory, and then import it.

# Level 1 Challenge

- Write a react app which lists names from the given file.

- It should display boys' and girls' names differently - your choice\*

- The names should be displayed in alphabetical order, ascending.

(\*) Please, please feel free to break from the the "blue-for-boys/pink-for-girls" stereotyping and style it differently. The best creative solution will be included in this challenge document for subsequent cohorts to admire.

### Example Screenshot

![Level 1 Example Screenshot](./example-screenshots/level-1.png)

# Level 2 challenge

- Add a search bar.

- When someone types into it, your app should update the displayed list of baby names to only show matches.

- Matches should be case-insensitive.

- When the search bar is clear, all names should be shown.

### Example Screenshot

![Level 2 Example Screenshot](./example-screenshots/level-2.png)

# Level 3 challenge

- Add "favourites".

- When the user clicks a name from the main list, it should be moved to a "favourites" list, displayed separately.
  It should disappear from the main list!

- When the user clicks a name from the _favourites_ list, it should be moved back to the main list. It should disappear from the favourites list!

### Example Screenshot

![Level 3 Example Screenshot](./example-screenshots/level-3.png)

# Level 4 challenge

Add "name gender" filter buttons.

Add buttons that allow the user to only see boy or girl names (or all names).

The buttons should operate as "radio" buttons - exactly one should be active at any time.

The app should start by showing all names.

The app should make it clear which filter is in effect.

_How it works with search:_

If there is also a search term in effect, your app should apply any name gender filter to those search results.

### Example Screenshot

![Level 4 Example Screenshot](./example-screenshots/level-4.png)

# Beyond - ideas for more work

- Find a way to persist the favourites even after the browser tab is closed
- Add the ability for the user to shuffle the list of names
- Add the ability for the user to be presented with one or two randomly chosen names.

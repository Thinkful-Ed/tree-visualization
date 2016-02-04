# Thinkful / tree-visualization
Binary trees and other data structures are cool, but as programmer with practical knowledge of web development learning data structures and algorithms it can be tricky to visualize what's going on and why you migh care about certain properties, like tree height or balance. This project aims to provide a visualization of different kinds of binary trees, like binary search trees and AVL trees, as well as their operations like inserting, searching and deleting nodes.

### Who is this for?
The target user is a programmer with practical working knowledge of web development interested in learning more about data structures and algorithms. They may not know about data structures typically introduced before trees like stacks and queues, and they may not know about algorithmic concepts like recursion or time complexity and big O notation.

### Who can contribute?
Anyone familiar with front end development, web design, or data structures and algorithms is welcome to contribute. Take some time to look over the project documentation and issues list.

### What will this look like when it's done?
Good question. Designs aren't settled yet, but the goal is to create a playground for tinkering with binary trees with a clean, modern design. Here are preliminary features for the v1.0.0 milestone:
 * Display arbitrary binary trees to the user (with some reasonable limit on length)
 * User interface for performing standard operations like inserting, searching and deleting, and for intermediate steps like rotations, retracing, and recursive comparisons.
 * User interface for populating balanced, unbalanced, and random trees
 * User interface for switching between different types of trees
 * Clean, intuitive visualizations for operations

For an example of a good visualization, check out this rotation animation from [Wikipedia](https://en.wikipedia.org/wiki/Tree_rotation):
![tree rotation animation](https://en.wikipedia.org/wiki/Tree_rotation#/media/File:Tree_rotation_animation_250x250.gif)

### What parts does this project have?
Several. An initial wireframe is on the way, but we don't yet have a more detailed mockup for the page or designs for the tree elements. Designers welcome :D

We'll need to implement the particular data structures we're using in JavaScript. (Yes, we could import an [existing solution](https://github.com/vadimg/js_bintrees), but that's boring.)

We'll want to display the data to the user, likely using a tool that's handy for displaying data and creating visualizations like [D3.js](http://d3js.org/).

And, of course, we'll need the remaining UI elements. For this we can stick with D3 or, if appropriate, rope in another tool like React to build components and handle the views.

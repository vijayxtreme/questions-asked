# Hypothetical

- Design a front-end menu system for McDonalds, that would take a customer’s order.. how would you organize everything and explain your design choices.
- How would you return a list of stars closest to a random star picked in our universe, ordered from closest to farthest?  (Using a whiteboard, show us how you would solve this problem)
  - I wrote a solution to this one in a doc called Stars in Galaxy Question
  - Would need an array to fill up all the stars (assume done)
  - Search the array matching string (O(N) time).  Could use Merge Sort or Binary Search Algorithm if array is sorted, reduce to (O(LogN) time)
  - After getting the star document, get its coordinates
  - Sort array by coordinates
  - Return the closest matching coordinates by creating a sub array containing the matching star and the items left and right of the star document
- You’ve been reduced to the size of a bug, and a blender is about to turn on-- how would you make your way out before getting crushed?  
  - Jump out (this is more a physics problem than a coding problem)

> For certain hypothetical problems -- good understanding of geometry and linear algebra are essential (being able to determine distance between two points, graphing, curves); also understanding of basic physics helps as well (determining if you want to move into gaming or animation).

# CMPS 2200 Assignment 3
## Answers

**Name:**__Amara Midouhas_______________________


Place all written answers from `assignment-03.md` here for easier grading.






- **b.**
Since we are iterating through the characters in a list, the work depends on the size of the list to the work is constant so this would be O(n). For span, there are nested loops where the first loop goes through a list of strings and then the characters in that string, so there is a dependency. Also since we have a count to keep track of the paranthesis, there cant be parrel processing. Since each process of characters depends on the one before, the length or amount of characters is the span which is O(n)



- **d.** For work, since the mapping is depenndent on the size of the list, it will take O(n). The Scan operation is also O(n) because it is applying f to the pair of elements in a so it depends on the length of the list. Since we are combining elements together and then cutting the size of the list in half and also creating a new list, it is O(log n).





- **f.** Since we are splitting the list in two and having two parrel recursive calls it would be W(n)=2*W(n). Then to merge the left and right it will always be a fixed amount of operations which is O(1), so it will be O(n) . Then for span, since we are recursively dividing the list, it is log n. Therefore, it will be O(log n)

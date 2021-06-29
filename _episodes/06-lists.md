---
title: "Creating Lists"
teaching: 0
exercises: 0
questions:
- "How can I create bullet (unordered) lists?"
- "How can I create numbered lists?"
- "How can I create todo lists?"
objectives:
- "Creating lists."
keypoints:
- You can use ```-```, ```+``` or ```*``` at the very beginning of the line to create an unordered list.
- You can use a digit followed by a fullstop, eg. ```1.``` to create a numbered list
- You can create a list with tickboxes by using ```- [ ]```

---

{% include base_path.html %}

### Making lists:
There are three types of lists that can be created with MarkDown. The first type of list is the ordered list where every item in the list is numbered. The second type of list is the unordered list where each item in the list is marked with a bullet. The third type of list is a todo list where each item in the lists starts with a tickbox.

#### ordered lists
Ordered lists can be created by starting a line with a number followed by a fullstop followed by a space, eg. ```1. ```. The value of the number doesn't matter and the numbers also do not need to be sequential. The value of the number is inconsequential except for the very first number which will indicate where the numbering should start. MarkDown will make the numbers sequential. So whether you enter

```markdown
1. one
1. two
1. three
1. four
```
or
```markdown
1. item one
2. item two
3. item three
4. item four
```
or
```markdown
1. item one
10. item two
1. item three
1000. item four
```
They will all display as:

1. item one
1. item two
1000. item three
10. item four

If however, the number you start with will determine the number of the first element in the list with following items incrementing from the first value. The following examples will all result in the same list:

```markdown
23. twenty-three
1. twenty-four
1. twenty-five
1. twenty-six
```
```markdown
23. twenty-three
1. twenty-four
1000. twenty-five
1. twenty-six
```
```markdown
23. twenty-three
24. twenty-four
25. twenty-five
26. twenty-six
```
results in:

23. twenty-three
1. twenty-four
1000. twenty-five
1. twenty-six


#### unordered lists
Some editors will allow the use of ```-```, ```+``` and ```*``` to create unordered lists. However, some editors only allow ```-```. You need to try it out and see what works for your chosen editor.
##### using -
- item one
- item two
- item three

##### using +
+ item one
+ item two
+ item three

##### using *
* item one
* item two
* item three

#### To-do lists
In editors such as HackMD, Joplin and GitHub, you can create todo lists with tick boxes. To create such a list you start the line with ```- [ ]```. Note that there is a space between the square brackets. To create a ticked box you place an ```x``` between the square brackets: ```- [x]```. You'll notice that you cannot tick the boxes on this web page. However, in the previous mentioned editors you can usually tick the boxes in either display or editing mode.

- [ ] todo one
- [ ] todo two
- [x] todo three

## Sub lists:
To create sub-lists you need to indent the sublist items with two spaces. Some editors might require more spaces. So if things do not display as you expect, try adding an extra space or two:

1. first item
	1. sub item
	1. second sub item
2. second item
	- first sub item
	- second sub item


{% include links.md %}


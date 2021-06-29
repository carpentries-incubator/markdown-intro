---
title: "Adding text to a MarkDown document"
teaching: 0
exercises: 0
questions:
- "How do I add text to a MarkDown document?"
- "How can I make different levels of headings?"
- "How do I make text bold?"
- "How do I format text as italic?"
- "How do I format text as bold and italic"
objectives:
- "Adding text to a MarkDown document."
keypoints:
- Adding text to a MarkDown document.

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

## Sub lists:
1. first item
	1. sub item
	1. second sub item
2. second item
	- first sub item
	- second sub item

### Links
Links are created by using square brackets around the text to be displayed, followed by round brackets for the link to be used. For example, to create a link to the GitHub website we can do this:

~~~markdown
[GitHub Website](https://github.com)
~~~
This will be displayed as:

[Github Website](https://github.com).

{% include links.md %}


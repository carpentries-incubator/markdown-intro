---
title: "Adding Links"
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

### Links
Links are created by using square brackets around the text to be displayed, followed by round brackets for the link to be used. For example, to create a link to the GitHub website we can do this:

~~~markdown
[GitHub Website](https://github.com)
~~~
This will be displayed as:

[Github Website](https://github.com).

### Images
To add an image the MarkDown is similar to that of a link but a ```!``` is added to the front, eg. 
```
![alt text](https://carpentries.github.io/lesson-example/assets/img/cp-logo-blue.svg "Carpentries Logo")
```

That should result in:

![Carpentries Logo](https://carpentries.github.io/lesson-example/assets/img/cp-logo-blue.svg "Carpentries Logo")

As you can, the above link references and images that is in another repository. If you uploaded the image to your local repository, you only need to specify the name. If it is in a sub-directory below your Markdown file it is referenced in a relative way, eg.
```
![Double helix](fig/DNA_double_helix_horizontal.png)
```
![Double helix]({{relative_root_path}}/fig/DNA_double_helix_horizontal.png)

Image Credit: By Jerome Walker - Own work, created from GDFL work created by Michael Ströck, Public Domain, https://commons.wikimedia.org/w/index.php?curid=934419

### Code and Syntax Highlighting

You have probably seen how code is displayed in the Carpentries lessons in a grey block and with syntax highlighting. Since most of what we do is about coding, this is a very handy feature. Whenever you surround text with three back quotes (`) the text will be displayed monospace and in a gray box:

~~~
```
s = "This is a Python string"
print(s)
```
~~~

To get syntax highlighting, just add the name of the programming language directly after the first three back quotes:

~~~
```python
s = "This is a Python string"
print(s)
```
~~~
{: .source}

This will be displayed as:

~~~python
s = "This is a Python string"
print(s)
~~~
{: .output}

### Tables
### Blockquotes

Blockquotes are created by adding ```>``` in front of every line of the block, followed by a space eg.

> This is a block quote
> 
> Every line starts with a > symbol followed by a space
> 
>> This line started with two > symbols followed by a space, thus: >> .This mimmicks the type of formatting you get in emails that have been forwarded.
>> 

### Horizontal Rule
Horizontal rules can be created in one of three ways

1. ```---```
1. ```***```
1. ```___```

### Task list
- [ ] a tick box is created by starting the line with a - followed by a space, an open square bracket, another space and then a close square bracket followed by another space, i.e. ```- [ ] ```
- [x] To tick the box, replace the space between the two sqare brackets with an x, i.e. ```- [x] ```


- Use MarkDown tas to format text

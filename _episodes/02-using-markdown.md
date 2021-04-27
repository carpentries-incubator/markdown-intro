---
title: "Creating a MarkDown Document in GitHub"
teaching: 0
exercises: 0
questions:
- "How do you create a new MarkDown document on GitHub?"
- "What tags are available for MarkDown?"
objectives:
- "Create a new document on GitHub"
- "Use MarkDown tags to format text"
keypoints:
- Create a new document on GitHub
- Use MarkDown tags to format text

---

{% include base_path.html %}

# Creating a New Note

Log into GitHub and select a repository or create a new one. A MarkDown file is created like any other file but it needs to have a .md extension. So click on the ```Add file```button and select ```Create new file```:

![GitHub]({{relative_root_path}}/fig/Create_new_file_GitHub.png)

Enter a filename and make sure to end it with the extension .md:

![Name file]({{relative_root_path}}/fig/Enter_filename.png)

Remember: If at any stage, you would like to see the rendered version of what you have typed, select the ```Preview``` tab.

### Adding text:
Let's start creating our document by entering some text in the editor. We'll make our own MarkDown cheat-sheet and we'll start it with a heading. To create a heading we start the line with ```#```. Notice the space after the hash:

~~~
# My Own MarkDown Cheat-Sheet
~~~
{: .source}

We can also create a subheading by using two hashes. Don't forget the space after the hashes:

``` 
## How to create headings
```

Followed by some text:

```markdown
To create a heading we need to start a line with a # followed by a space. Sub-headings can be created by using two hashes, eg ##. Several levels of headings can be created by adding more hashes.

To start a new paragraph we need to press enter twice.
```
We can italisize some of the text by adding an asterisk on each side

```markdown
To italisize text we add an asterisk on each side of the text, for example, *this text should be italisized*
```

With two asterisks on each side we can make the text bold

```markdown
By adding two asterisks on each side the text will be rendered as bold: **This text should be bold**
```

To make the text italisized and bold we use three asterisks on each side: 

~~~markdown
***By adding three asterisks on each side of the text, the text will be displayed as bold and italisized.***
~~~

By now the text in the editor should look more or less like this:

![Text entered in editor]({{relative_root_path}}/fig/Part1.png)

And, if we select the preview, it should look like this:

![Text entered in preview]({{relative_root_path}}/fig/Part2.png)


### Making lists:

#### ordered lists
1. item one
1. item two
1. item three

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




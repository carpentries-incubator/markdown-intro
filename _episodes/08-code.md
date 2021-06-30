---
title: "Adding Code With Syntax Highlighting"
teaching: 0
exercises: 0
questions:
- "How does one add code?"
- "How does one add syntax highlighting for a specific language?"
objectives:
- "Adding code and syntax highlighting"
keypoints:
- Using back quotes for code

---

{% include base_path.html %}

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


{% include links.md %}


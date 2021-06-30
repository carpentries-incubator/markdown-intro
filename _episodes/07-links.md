---
title: "Adding Links and Images"
teaching: 0
exercises: 0
questions:
- "How does one add a link?"
- "How does one add an image?"
- "How does one add an image that is also a link?"
objectives:
- "Adding links and images."
keypoints:
- Use ```[]``` and ```()``` to add images and links

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

{% include links.md %}


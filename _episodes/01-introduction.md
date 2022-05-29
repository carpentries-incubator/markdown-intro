---
title: "Introduction"
teaching: 0
exercises: 0
questions:
- "What is MarkDown?"
- "Where can I use MarkDown?"
objectives:
- "Finding a suitable MarkDown Editor"
- "What to look for in a MarkDown Editor"
keypoints:
- Determine what you want to use MarkDown for
- Find a suitable MarkDown editor
- Determine whether the editor needs installing


---
 {% include base_path.html %}

## What is MarkDown

Before explaining what MarkDown is we should just mention what "markup" is. In the days before computers had graphic user interfaces (GUIs), authors of documents had to find a way to indicate how they wanted their text formatted. When this was done on paper the text would be marked up with a red or blue pen. When computers came into play, markup was done by **tags** embedded in plain texts files. The tags had to be distinguishable from the manuscript text and would be interpreted by a separate program that would create an appropriately formatted document - mostly for printing. Markup was never completely replaced as it is still being used for web pages and online documentation but GUI environments became more popular and word processors took over which were WYSIWYG (What You See Is What You Get). WYSIWIG was much simpler and more intuitive for non-technical people to use. However, things have changed. We are moving away from using so much paper. Most of our documentation is now meant for online reading. There was a need for some kind of markup that would be simpler than the markup used for web pages or for technical documentation such as in LaTeX. In 2004 Aaron Swartz and Joh Gruber worked together to create **MarkDown** with the aim of enabling people "write using easy-to-read and easy-to-write plain text format". 

## Where can I use MarkDown

MarkDown is most suitable for online documentation. It is much simpler than HTML (Hyper Text Markup Language) which is the standard for creating web pages. MarkDown is turned into HTML by your editor and thus, depending on your editor, you might also be able to use inline HTML in your MarkDown document to do formatting which MarkDown cannot do. It is also important to take note of the fact that there are some non-standard features that are available in some editors. So you have to make sure that, what you want to do, is implemented in your editor.

To allow people to format their text well for readability, Markdown is now used on several platforms such as
- Version control websites such as GitHub and BitBucket
- Question and Answer websites such as Stack Overflow
- Note taking applications such as Evernote and Joplin
- Team communication and collaboration applications such as Slack, Discord and Zulip
- Jupyter Notebooks

> ## Where would you use MarkDown?
> 
> List some things that you think you will be using MarkDown for
{: .discussion}

## Finding an editor
A MarkDown document is a plain text document. So you can use any plain text editor to create the document. Obviously, not all plain text editors will render the document for you but fortunately there are several options available for creating, rendering and viewing MarkDown documents.

If you use websites such as [GitHub](github.com), [BitBucket](https://bitbucket.org/), [Medium](https://medium.com/), [Stack Overflow](https://stackoverflow.com/), Evernote, Slack, Discord and Zulip, then they all have MarkDown already built into their web pages. The image below shows how it is implemented in **GitHub**. Notice that there are two tabs, **<>Edit File** and &#128065;**Preview changes**. To see what your text will like, once rendered, you have to click on the preview tab.

![GitHub]({{relative_root_path}}/fig/GitHub.png)

**Stack Overflow** has a different approach. Your rendered text is displayed below the editor as you type:

![Stack Overflow]({{relative_root_path}}/fig/StackOverflow.png)

For these, built-in editors, you don't need to install anything on your computer. However, let's say you don't want to work online. For instance, you might just want to make notes using Joplin and keep it on your own computer. Or, you might want to work on your GitHub repository on your own computer before uploading it the Internet at a later stage. Applications such as Evernote provide an online and an offline option. The offer an application that you can download and install onto your computer. When you go online, Evernote will automatically synchronise your notes with the online server.

GitHub does not offer an offline editor, but you can use any editor, such as nano or vim, to edit your file and then push it to the server when ready. These two editors won't show you the rendered version of your document but if you use an editor such as ghostwriter it will show you the rendered version of your document as you type:

![ghostwriter]({{relative_root_path}}/fig/GhostWriter.png)

Evernote is a commercial option with a free tier, but Joplin, being open source, is completely free. Joplin does not provide an online server but you can run your own server or synchronise to your own cloud spaces such as Dropbox and OneDrive. So Joplin has to be downloaded and installed:

![Joplin]({{relative_root_path}}/fig/Joplin.png)

Another very useful application of MarkDown is for collaborative documentation. These are online options so they don't need installing. [HackMd](https://hackmd.io/) is an open source platform. You can host it on a server in the cloud yourself or you can use the service at [https://hackmd.io/](https://hackmd.io/)  which offers a free tier if you are happy to have all your documents being public. For Carpentries related documents you can use the Carpentries' instance of HackMd at [codimd.carpentries.org/](codimd.carpentries.org/)


{% include links.md %}


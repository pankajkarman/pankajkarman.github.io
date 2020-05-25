<!--
.. title: Writing papers and reports in markdown
.. slug: markdown
.. date: 2020-05-08 06:46:34 UTC+05:30
.. tags: 
.. category: 
.. link: 
.. description: 
.. type: text
-->

This blog was inspired by [this Peerj article.](https://peerj.com/articles/cs-112.pdf)

Disclosure: This blog was written in Markdown.

## Introduction

A major time and cost factor during report/paper writing is the formatting of manuscripts. In this blog, I'll explain how to write manuscripts in plain markdown text files, which can be easily converted into common formats, such as PDF, HTML, DOCX or EPUB using Pandoc. Not only that the use of templates enable the automated generation of documents according to specific journal styles. The simple syntax of markdown facilitates document editing and collaborative writing. Reducing the work spent on manuscript formatting translates directly to time and cost savings for all stakeholders, such as writers, publishers and readers.

> The overriding design goal for Markdown’s formatting syntax is to make it as readable as possible. The idea is that a Markdown-formatted document should be publishable as-is, as plain text, without looking like it’s been marked up with tags or formatting instructions.

## A very brief markdown tutorial

Paragraphs are separated by a blank line.

Here , special symbols are used for formatting texts.

~~~Markdown
# A h1 header
## A h2 header
### A h3 header
~~~

~~~Markdown
*Italic*, **bold** and ***both***
~~~

Here is an unordered list:
~~~Markdown
- apple
	- green apple
	- red apple
- banana
- orange
~~~

and it would be rendered as
>
- apple
	- green apple
	- red apple
- banana
- orange

Here is a numbered list:
~~~Markdown
1. apple
	1. green apple
	1. red apple
2. banana
5. orange
~~~
and it would be rendered as
>
1. apple
	1. green apple
	2. red apple
2. banana
3. orange

To write code, you indent it by 4 spaces or a tab. Markdown will guess what language you are writing
~~~markdown
	def main():
		print "Say Hello!!"
~~~

would be rendered as

~~~python
def main():
      print "Say Hello!!"
~~~

You can specifiy which programming language you are using with delimited blocks if you wish



<div class="highlighter-rouge"><div class="highlight"><pre class="highlight"><code>```python
def say_hello():
    print('Hi Everybody')
```</code></pre></div></div>


and it would be rendered as
 
```python
def say_hello():
    print('Hi Everybody')
```

Here is a link to the my website
~~~markdown
[Pankaj Kumar](https://pankajkarman.github.io/)
~~~
 and it would be rendered as 
 
 > [Pankaj Kumar](https://pankajkarman.github.io/)

Here is how to specify an image
~~~markdown
![Caption](images/ex.png){width=25%}
~~~

which would be rendered as

![Caption](/images/pk.jpg){width=35%}


Here is how to insert a table

~~~markdown
| Syntax      | Description | Text     |
| :----        |    :----:   |          ----: |
| Header      | Title       | Here's this   |
| Paragraph   | Text        | And more      |
~~~

And it would be rendered as 

> | Syntax      | Description | Text|
| :----        |    :----:   |          ----: |
| Header      | Title       | Here's this   |
| Paragraph   | Text        | And more      |


~~~markdown
A horizontal rule is given by 3 dashes as follows:
---
~~~

would be rendered as 

---



~~~markdown
~~Strikethrough text~~
~~~

would be rendered as

> ~~Strikethrough text~~

~~~markdown
Some text ~Subscript~

Some text ^Superscript^
~~~

~~~markdown
You can specify an inline quation like latex $x^2+y^2=z^2$

Or a block level equation with two dollar signs on both sides of the equation:
$$\sum_{i=0}^n i^2 = \frac{(n^2+n)(2n+1)}{6}$$
~~~

### A list of useful links for further learning about Markdown

- [Extended Markdown instrutions](https://www.markdownguide.org/extended-syntax/)
- [Github Flavoured Markdown](https://guides.github.com/features/mastering-markdown/) 
- [Markdwon cheat sheet](https://www.makeuseof.com/tag/printable-markdown-cheat-sheet/)
- [One More cheat sheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#code)

### Markdown Editors

While any plain text editor can work with markdown, there are some editors dedicated for markdown providing key bindings for common operations like making text bold, italic etc. Some of the open-source editors are:

- [Remarkable](remarkableapp.github.io)
- [ReText](https://github.com/retext-project/retext)
- [Atom](https://atom.io/)

## Writing reports/papers

[Link for markdown paper-template.](https://github.com/pankajkarman/paper-template)

Markdown depends on [*pandoc*](https://pandoc.org) for all conversion tasks. Please follow the steps mentioned in the above link for installation of all dependencies. Installation steps may differ depending on the operating system. Instruction mentioned in the link are pretty generic and can be easily followed on any operating system.

A technical report is different from other writing formats in the sense that it contains tables, images and plenty of references with specific styles followed by different univeristies, organisations and journals. 

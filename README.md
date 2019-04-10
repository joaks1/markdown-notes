Markdown is a "lightweight" markup language (HTML is another example of a
markup language).
The goal of Markdown is to be easy to write and read in plain text format,
and easily converted into HTML and other formats.
Most people writing plain text files tended to follow
similar syntax norms; Markdown formalized these
norms into a language.

GitHub has a nice feature in that any file with a `.md` or `.markdown`
extension will be rendered as "pretty" HTML.
If you format your README as Markdown, and give it one of these extensions
(i.e., `README.md`), your repository will have a nice looking landing page.

Below is a brief introduction into some of the commonly used features
of Markdown.
For more details about Markdown see
[John Gruber's original description](https://daringfireball.net/projects/markdown/)
of the language.
GitHub has its own "dialect" that supports some additional features;
for full details on 
[GitHub-flavored Markdown go here](https://github.github.com/gfm/).


# Contents

-   [Basic Text Formatting](#basic-text-formatting)
    -   [Emphasizing words](#emphasizing-words)
    -   [Paragraphs](#paragraphs)
-   [Section Headers](#section-headers)
-   [Lists](#lists)
-   [Links](#links)
-   [Images](#images)
-   [Code and Syntax Highlighting](#code-and-syntax-highlighting)
-   [Inline code](#inline-code)
-   [Code blocks](#code-blocks)


# Basic Text Formatting

## Emphasizing words

You can *italicize* text by surrounding it with **one** asterisk or underscore
character.

```no-highlight
For example, I want to emphasize *these words* and these _other words_.
```
For example, I want to emphasize *these words* and these _other words_.

You can **bold** text by surrounding it with **two** asterisk or underscore
characters.
```no-highlight
For example, I want to bold **these words** and these __other words__.
```
For example, I want to bold **these words** and these __other words__.

Why two ways to do the same thing?! Good question, but it does allow us to
nest one inside the other in a more readable fashion.
```no-highlight
These notes are an **absolute _disaster_**!

is a bit more readable than

These notes are an **absolute *disaster***!

but both work.
```
These notes are an **absolute _disaster_**!

is a bit more readable than

These notes are an **absolute *disaster***!

but both work.

## Paragraphs

```no-highlight
Lines separated by one newline character
will be part of the same paragraph.

But, a line separated by two newline characters will be a different paragraph
```
Lines separated by one newline character
will be part of the same paragraph.

But, a line separated by two newline characters will be a different paragraph


# Section Headers

Starting a line with 1-6 `#` characters will result in a section heading.

```no-highlight
# Header 1
## Header 2
### Header 3
#### Header 4
##### Header 5
###### Header 6
```

# Header 1
## Header 2
### Header 3
#### Header 4
##### Header 5
###### Header 6


# Lists

You can create unordered lists using asterisks `*`, dashes `-`, or pluses `+`.

```no-highlight
-   First item
-   Second item

    You can add a second paragraph to this item as long as you indent to align
    with the text above.

-   Third item
    - A sub item
-   A forth item
```
-   First item
-   Second item

    You can add a second paragraph to this item as long as you indent to align
    with the text above.

-   Third item
    - A sub item
-   A forth item

If you want to enumerate the list, then use numbers.
```no-highlight
1.  First item
2.  Second item

    You can add a second paragraph to this item as long as you indent to align
    with the text above.
    
3.  The third item has a
    1.  Sub item.
4.  Note
1.  The numbers
5.  Don't matter
```
1.  First item
2.  Second item

    You can add a second paragraph to this item as long as you indent to align
    with the text above.
    
3.  The third item has a
    1.  Sub item.
4.  Note
1.  The numbers
5.  Don't matter


# Links

You can create links using the syntax `[text to display](URL HERE)`.

```no-highlight
Try this [little-known search engine](https://www.google.com) to learn more
about MarkDown.
```
Try this [little-known search engine](https://www.google.com) to learn more
about MarkDown.

You can use angle brackets to turn a URL into a link
```no-highlight
The URL for GitHub is <https://github.com/>
```
The URL for GitHub is <https://github.com/>


# Images

The syntax for embedding images is very similar to links, `![alt
text](PATH-or-URL-of-image "optional title text")`.
```no-highlight
![Lizard photo](./images/gecko-photo.jpg "Cute gecko")

![Lizard photo](https://github.com/joaks1/markdown-notes/raw/master/images/gecko-photo.jpg "Cute gecko")
```
![Lizard photo](./images/gecko-photo.jpg "Cute gecko")

![Lizard photo](https://github.com/joaks1/markdown-notes/raw/master/images/gecko-photo.jpg "Cute gecko")


# Code and Syntax Highlighting

## Inline code
```no-highlight
You can format `code` inline by surrounding it with single backticks
```
You can format `code` inline by surrounding it with single backticks


## Code blocks
<pre lang="no-highlight"><code>
Blocks of code can be done by indenting:

    print("Hello Word")

Or by surrounding the line with triple backticks:

```
print("Hello World")
```
</code></pre>

Blocks of code can be done by indenting:

    print("Hello Word")

Or by surrounding the line with triple backticks:

```
print("Hello World")
```

<pre lang="no-highlight"><code>
The triple backticks has the advantage of being able
to specify the language for nice syntax highlighting:

```python
# Note that markdown *syntax* is **ignored** in here
for i in range(10):
    s = "Hello World " + str(i)
    print(s)
```
</code></pre>

The triple backticks has the advantage of being able
to specify the language for nice syntax highlighting:

```python
# Note that markdown *syntax* is **ignored** in here
for i in range(10):
    s = "Hello World " + str(i)
    print(s)
```

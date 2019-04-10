# Formatting Text

You can *italicize* text by surrounding it with **one** asterisk or underscore
character.

```
For example, I want to emphasize *these words* and these _other words_.
```
For example, I want to emphasize *these words* and these _other words_.

You can **bold** text by surrounding it with **two** asterisk or underscore
characters.
```
For example, I want to bold **these words** and these __other words__.
```
For example, I want to bold **these words** and these __other words__.

Why two ways to do the same thing?! Good question, but it does allow us to
nest one inside the other in a more readable fashion.
```
These notes are an **absolute _disaster_**!

is a bit more readable than

These notes are an **absolute *disaster***!

but both work.
```
These notes are an **absolute _disaster_**!

is a bit more readable than

These notes are an **absolute *disaster***!

but both work.


# Section Headers

Starting a line with 1-6 `#` characters will result in a section heading.

```
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

```
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

```
Try this [little known search engine](https://www.google.com) to learn more
about MarkDown.
```
Try this [little known search engine](https://www.google.com) to learn more
about MarkDown.

You can use angle brackets to turn a URL into a link
```
The URL for GitHub is <https://github.com/>
```
The URL for GitHub is <https://github.com/>

# Images

The syntax for embedding images is very similar to links, `![alt
text](PATH-or-URL-of-image "optional title text"`.
```
![Lizard photo](./images/gecko-photo.jpg "Cute gecko")

```

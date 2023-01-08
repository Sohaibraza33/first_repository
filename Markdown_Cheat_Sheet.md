Github session 2023
# 1- Heading
How to give headings in markdown file?
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6
It goes upto 6 headings


# 2- Block of words/Citations

To start underline use <ins> and to finish underline use </ins> . Thats it.

<ins> this is an apple.</ins>

This is a normal text in Markdown.

> This is a block of special text.
>
>This is a second line.

# 3- Line breaks
This is a 40 days long course Data science with Python AKA Python_ka_chilla.\
This is second line.

# 4- Combine two things
we will combine heading and block of words as

> ## Heading 2
>
> ### Heading 3

# 5- Face of text
To make word italic, bold or both bold and italic use * in front and end of the word as

*Italic*

**Bold**

***Bold and Italic***

or we can use underscore symbol as

_Italic_

__Bold__

___Bold and Italic___

# 6- Bullet points/Lists
- Day-1
- Day-2
- Day-3
- Day-4
- Day-5
    - Day-5a
        - Sub list (Anything)
    - Day-5b
- Day-6
- Day-7
> For Numbering List

1. Day-1
2. Day-2
3. Day-3
4. Day-4
5. Day-5
    1. Day-5a
    1. Day-5b
6. Day-6
7. Day-7
7. Day-8
1. Day-9

we can also use * or + to make the lists as

> __use * or +__
* Day-1
* Day-2
+ Day-3
+ Day-4

# 7- Break Through Line/Page Break
we can use --- or ___ or *** to make a line as

This is line 1.

---
This is line 2.



This is line 1.
___
This is line 2.



This is line 1.

***
This is line 2.

# 8- Links and Hyperlinks
To make links and Hyper

<https://twitter.com/home>

or

[link is here](https://twitter.com/home)

link is here

if we write same sentence here then link does not work. we have to do the same thing again for link in text, which is actually time consuming if we want to use the link text again and again. So for that write as,

[Codanics]:https://www.youtube.com/watch?v=qJqAXjz-Rh4&list=PL9XvIvvVL50HVsu-Ao8NBr0UJSO8O6lBI&index=22&ab_channel=Codanics

The link of the channel is

 [here][Codanics]

 [there][Codanics]

 [Codanics]

 [Codanics]

 [Codanics]

 # 9- Images and figures with link

To join the course please scan the following QR code:

![QR](1.jpg)


[QR](1.jpg)

To comment out a text use "ctrl+/" or  "<!--text-->"

<!-- This is a line. -->

For online images to show here

![online](https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.123rf.com%2Fphoto_63970642_it-is-too-small-emoticon-showing-small-size-with-fingers.html&psig=AOvVaw35S3A6ZA28UZ8ADphwQBI9&ust=1672907988736000&source=images&cd=vfe&ved=0CBAQjRxqFwoTCIDs64bCrfwCFQAAAAAdAAAAABAZ)

# 10- Adding code/Block of code
To use code within text

To print a string use `print("Hello")`

For block of code

```
x=5+6
y=3-2
z=x+y
print(z)
```

>This code with show color according to Python language syntax

```Python
x=5+6
y=3-2
z=x+y
print(z)
```

>This code with show color according to R language syntax

```R
x=5+6
y=3-2
z=x+y
print(z)
```

# 11- Adding tables
make table as

|species|petal_length|sepal_length|
|:-----:|:-----:|:-----:|
|virginica|18.2|19.2|
|setosa|15.1|17.2|
|versicolor|12.2|12.2|
|virginica|18.2|19.2|
|setosa|15.1|17.2|
|versicolor|12.2|12.2|

# 12- Table of content
[1- Headings](#1--heading)\
[2- Block of words / Citations](#2--block-of-wordscitations)\
[3- Line Breaks](#3--line-breaks)\
[4- Combine two things](#4--combine-two-things)\
[5- Text Face](#5--face-of-text)\
[6- Bullets](#6--bullet-pointslists)\
[7- Line/Page Breaks](#7--break-through-linepage-break)\
[8- Links](#8--links-and-hyperlinks)\
[9- Figure Links](#9--images-and-figures-with-link)\
[10- Adding code/code block](#10--adding-codeblock-of-code)\
[11- Tables](#11--adding-tables)


# 13- Installing Extensions
1- Markdown All in one\
2- Markdown pdf\
3- Markdown lint\
4- Markdown Shortcuts

select word then right click to select toggle bold option

**bold**

select word press ctrl+b

**bold**

_italic_

_italic_

**_bold and italic_**

for hyperlink write word then select and press right click to choose toggle hyperlink or use ctrl+L

Toggle hyperlink

[Twitter](https://twitter.com/home)

Toggle image

![Image](1.jpg)


toggle Block of code

```
x=1+2
y=2+2
z=x+y
print(z)
```
toggle strikethrough

~~Image~~

toggle citation/block of words

> this is a line.
> 
> this is a 2nd line.

toggle checkboxes

- [ ] lists
- [ ] tables

Add table with header

Column A | Column B | Column C
---------|----------|---------
 A1 | B1 | C1
 A2 | B2 | C2
 A3 | B3 | C3

 


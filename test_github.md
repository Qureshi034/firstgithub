# 1-headings
How to give heading in markdown file?
# Heading1
## Heading2
### Heading3
#### Heading4
###### Heading6

# Block of words
This is a normal text in markdown

>This is a block of special text .
>
>THis is second line text.

# 2-break of line
This a 40 day long course in the datascience. \
This is the second line.

# 3-combine two things
Block of word and heading
> # heading 2
 
# 5-Face of text
**Bold**\
*italic*\
***Bold and italic*** \
or you can use these symbol \
__bold__\
_italic_

# 6-bullet points/list
- Day1
- Day2
- Day3
- Day4
    - Day5a
        - subheading
    - Day5b
- Day6

>numbering of list
1. Day1
2. Day2
3. Day3
    1. Day3a
        1. subheading
    2. Day3b
4. Day4
> __using *or+__
* one
+ one

# 7-line breaks or pages breaks
This is page1.
***
___
---
This is page2.


# 8-links and hyperlinks


* <https://www.youtube.com/> 


* [The play list of python ka chilla is](https://www.youtube.com/playlist?list=PL9XvIvvVL50HVsu-Ao8NBr0UJSO8O6lBI)

[codanics]:https://www.youtube.com/playlist?list=PL9XvIvvVL50HVsu-Ao8NBr0UJSO8O6lBI

The hole course play list is [here][codanics].

# 9-images and figure with links.
To join this course pleas scane the QR code :

![QR](qr.png)



online picture

![codanics](https://www.google.com/search?q=codanics&rlz=1C1RLNS_enPK885PK885&sxsrf=ALiCzsYcZ2eyKH9oj3_OR-_KJzfs_Ujvrw:1659627245007&source=lnms&tbm=isch&sa=X&ved=2ahUKEwjyqJejwa35AhUXYPEDHfWnCwYQ_AUoAXoECAEQAw&biw=1366&bih=625&dpr=1#imgrc=GRjVtCcWAILqOM)



# 10-Adding code and code block

to print a string using `print("codanics")` \
`print("hello shoaib")`


```
x=5+6
y=6-3 
z=x+y
print(z)
```
>This code with show according to the python language syntex.
```python
x=5+6
y=6-3
z=x+y
print(z)
```
>This code with show according to the R language syntex.
```r
x=5+6
y=6-3
z=x+y
print(z)
```



# 11-Adding table

| species | petal_lenght | sepal_lenght |
| ------- | :------------: | :------------: |
|virginicas | 18.2 | 19.2 | 
| setosa | 15.1 | 17.2 |
| versicolo | 12.2 | 12.2 |



# 12-content

[1.Heading](#1-headings)\
[2.break-of-line](#2-break-of-line)\
[3.combine-two-things](#3-combine-two-things)\
[5.face-of-text](#5-face-of-text)\
[6.bullet-pointslist](#6-bullet-pointslist)



# 13-install extensions
### right click kr k ap hr library use kr skte ho

```

```
~~ ~~

Column A | Column B | Column C
---------|----------|---------
 A1 | B1 | C1
 A2 | B2 | C2
 A3 | B3 | C3

# how to change the colour

This text colour is normal


<span style="color:red">
This text colour is red
</span>

# hexcode color picker

# 15-Adding equection in MD

>inline_math

$This_{is}^{inline}$

>Math block

$$
/int_0^\infty \frac{x^3}{e^x-1}\,dx = \frac{\pi^4}{15}
$$
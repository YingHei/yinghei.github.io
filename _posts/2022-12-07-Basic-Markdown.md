---
layout: post
title: Basic Markdown 
subtitle: 
tags: [md]
categories: [Fundamentals]
comments: true
---

Markdown is very easy to learn and write. It is broadly used in websites, notes, documents, etc. 

In this article, we will go through some basic syntax of markdown to help you get started.

I strongly encourage you to take this [interactive tutorial](https://www.markdowntutorial.com/) from Markdown Tutorial. 

## Styling Text
Surround text with  
_one_ * or _ to make it *italic*  
__two__ * or _ to make it **bold**  
___three___ * or _ to make it ***italic and bold***, or you can __*mix*__ and **_match_** it  
~~two~~ ~ to ~~strikethrough~~ it  

``` markdown
Surround text with 
_one_ * or _ to make it *italic*
__two__ * or _ to make it **bold**
___three___ * or _ to make it ***italic and bold***, or you can __*mix*__ and **_match_** it
~~two~~ ~ to ~~strikethrough~~ it
```


## Headings
# Heading is very easy
## Just add # in front of the text
### There are 6 levels of headings in total
#### The more \# you add 
##### The smaller the heading
###### Heading 6 is so small...


```
# Heading is very easy
## Just add # in front of the text
### There are 6 levels of headings in total
#### The more # 
##### The smaller the heading
###### Heading 6 is so small...
```

To make a horizontal line / section, use 3 - or * or _
I usually use 

---
to make a horizontal line
```
To make a horizontal line / section, use 3 - or * or _
I usually use 

---
to make a horizontal line
```


## Links
The syntax for links are: `[text](link)`  
Surround text with [] to make it a link. Surround link with ().  

[This will bring you to Google.](https://www.google.com/)
```
[This will bring you to Google.](https://www.google.com/)
```


Another way to add links is using **reference link**.  
This is useful when you want to reference several text to the same [link][link-of-link], so you don't need to modify [one by one][link-of-link] when the [link][link-of-link] is updated or you want to change the [link][link-of-link]. 
All [links][link-of-link] in this paragraph are linked to the same link!

[link-of-link]: https://dictionary.cambridge.org/dictionary/english/link
```
Another way to add links is using **reference link**.  
This is useful when you want to reference several text to the same [link][link-of-link], so you don't need to modify [one by one][link-of-link] when the [link][link-of-link] is updated or you want to change the [link][link-of-link]. 
All [links][link-of-link] in this paragraph are linked to the same link!

[link-of-link]: https://dictionary.cambridge.org/dictionary/english/link
```

## Lists
1. This is an ordered list
2. just type the number with a dot and a space
3. then it turns into a ordered list

* This is an unordered list
- type * or - followed by a space
* then it turns into a unordered list


```
1. This is an ordered list
2. just type the number with a dot and a space
3. then it turns into a ordered list

* This is an unordered list
- type * or - followed by a space
* then it turns into a unordered list
```

## Check box
```
- [x] #739
- [ ] https://github.com/octo-org/octo-repo/issues/740
- [ ] Add delight to the experience when all tasks are complete :tada:
```
- [x] #739
- [ ] https://github.com/octo-org/octo-repo/issues/740
- [ ] Add delight to the experience when all tasks are complete :tada:

- [x] this is a complete item 
- [-] this is also a complete item (works with every character) 
- [?] this is also a complete item
- [ ] this is an incomplete item

## Tables

| Number | Next number | Previous number |
| :------ |:--- | :--- |
| Five | Six | Four |
| Ten | Eleven | Nine |
| Seven | Eight | Six |
| Two | Three | One |


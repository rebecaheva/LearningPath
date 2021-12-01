# **Rebeca's Markdown exercise**
This document contains Rebeca's Markdown exercises. In it you will find the following topics:
* [Hierarchy of Headings](#hierarchy)
* [Emphasis](#emphasis)
* [Blockquotes](#blockquotes)
* [Lists](#lists)
* [Code](#code)
* [Tables](#tables)
* [Links](#links)
* [Images](#images)
 
# **Hierarchy of Headings**
 
With Markdown you can use different types of headings, according to the hierachy of your document. This is a cheat sheet to format your document with Markdown.
 
> # h1 Heading
> ## h2 Heading
>### h3 Heading
>#### h4 Heading
>##### h5 Heading
>###### h6 Heading
 
# **Emphasis**
With Markdown you can format your text to show emphasis. This is the syntax you should use:
 
**This is bold text**
 
**This is bold text**
 
*This is italic text*
 
*This is italic text*
 
Combine both ***italic*** and ***bold***. 
 
 
# Blockquotes
 
With Markdown the blockquote element is used to indicate the quotation of a large section of text from another source.
 
>Blockquotes can also be nested...
>>...by using additional greater-than signs right next to each other...
>>>...or with spaces between arrows.
 
 
# Lists
 
With Markdown, unordered and ordered lists could help you write clear and understandable instructions.
 
## Unordered lists
Unordered lists are the perfect fit when sequence is not essential to complete a task. Lear how to write unordered lists in Markdown with these tips.
* Create a list by starting a line with +, -, or *.  Sub-lists are made by indenting 2 spaces: 
 * First item of first nested list:
   * First item of second nested list
 * Second item of second nested list.
   * Second item of first nested list
 
 
## Ordered
Ordered lists are the perfect fit when you need sequence in order to complete a task. Start every ordered list with the number one and a period. This is a sample of an ordered list: 
1. Lorem ipsum dolor sit amet
2. Consectetur adipiscing elit
3. Integer molestie lorem at massa
 
# Code
With Markdown you can give format to blocks of code or type code inside a pragraph. In this section you will find how to write code with Markdown.
 
`Inline code`. To denote a phrase or word as code, enclose it in backticks.
 
   Indented code. To indent code, indent every line with a tab or add four spaces.
 
// Some comments
* `line 1 of code`
* `line 2 of code`
* `line 3 of code`
 
 
## Block code
 
 
   Sample text here...
 
 
## Code snippet
 
```js
var foo = function (bar) {
 return bar++;
};
 
console.log(foo(5));
```
 
# Tables
With Markdown you can create tables for your data. Use two or more hyphens (––) to start a table and pipes (|) to separate the columns.
| Option|  Description|
|:--|:--:|
|data  | path to data files to supply the data that will be passed into templates. |
| engine | engine to be used for processing templates. Handlebars are the default. |
| ext  |  extension to be used for dest files. |
 
## Right aligned columns
To make right aligned columns, add a colon at the right side of the hyphens.
 
| Option|  Description|
|:--|:--|
|data  | path to data files to supply the data that will be passed into templates.
|engine | engine to be used for processing templates. Handlebars are the default.
|ext   |  extension to be used for dest files.
 
 
# Links
With Markdown you can also add links to your document. To add a link enclose the link text in brackets and then follow it immediately with the URL in parentheses. 
 
link [text](http://dev.nodeca.com)
 
 
# Images Title
With Markdown it is possible to add images to your document. To add an image, add an exclamation mark (!), followed by alt text in brackets, and the path or URL to the image asset in parentheses. You can optionally add a title after the URL in the parentheses.
 
 
![Dojocat](https://octodex.github.com/images/dojocat.jpg)



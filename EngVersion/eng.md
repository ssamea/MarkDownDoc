# Markdown Syntax Markdown Method
Markdown is a grammar that edits a form in a plain text document.<br><br>
Used to edit document forms with README files, online documents, or plain text editors.<br><br>
Documents created using markdown can be easily converted to other forms of document, such as HTML.<br><br>
John Gruber was born in 2004 in grammar with Aaron Schwartz (https://ko.wikipedia.org/wiki/%EC%97%90%EB%9F%B0_%EC%8A%A4%EC%9B%8C%EC%B8%A0).
Significant collaboration has created a mart-down language, allowing people to write using plain text formats that are easy to diary and write, while enabling selective conversion to structurally valid HTML.[John Gruber
(DaringFireball)](http://daringfireball.net/projects/markdown/syntax).
## Markdown Pros Markdown Advantages
* "It's easy to read."For sure, markdown is more readable than other markup languages. Grammar is simple, HTML is written and how it looks in the browser.
It's not easy to predict whether it's going to lose, but text using Markdown can easily imagine what's going to be shown in the browser.
* "Easy to learn."John Gruber wanted to use what people use a lot as markdown and what's complicated as HTML. So grammar is very simple. And when you write with markdown, it doesn't matter if you use HTML together, except for a few limited features.
* 'Mobile friendly."It's not easy to write on mobile using an editor, not just text. But with Markdown, it's much easier than an editor because it's easy to format with tags on mobile.
## Markdown Cons Markdown Disadvantages
* "The grammar is too simple.' The grammar is simple, and eventually you have to write HTML. There is a table sorting function, but there is no image sorting function, so you need to use the img tag in HTML. Because class assignment lights are not possible for tags, you must use HTML to specify classes or id.
* 'There is no standard, so each user may have a different grammar."As grammar is simple, extended grammar has been created to address this point, and sometimes Markdown documents that work in one place do not work well elsewhere.
## 1. Headers Header
* Text starting with '#'.
* One to six '#' can be used.
* The subject will scale down each time '#' is increased.
* H1 can also be made as '==='.
* H2 can also be made as '---'.
### How to Markdown on Syntax
This is an H1
===
This is an H2
---
# This is an H1
## This is an H2
### This is an H3
#### This is an H4
##### This is an H5
###### This is an H6
###Demonstration Execution Results
This is an H1<br>
===
This is an H2<br>
---
# This is an H1; used for parts <br>
## This is an H2; used in chapter <br>
###This is an H3; used in page sections <br>
####This is an H4; used for subsections <br>
##### This is an H5; used for subsections below subsections <br>
#####This is an H6; used in paragraph <br>

#2. Emphasis on Ephasis
* Tilt writing (italic): Text wrapped in '*' or '_'.
* Bold: Text wrapped in '**' or '__'.
* Cancellation line: Text wrapped with '~~'.
* Italics can be used in combination with thick.
### How to Markdown on Syntax
*This text will be italic*
_This will also be italic_
**This text will be bold**
__This will also be bold__
~~This is canceled~~
*You **can** combine them*
###Demonstration Execution Results
*This text will be italic*<br>
_This will also be italic_<br>
**This text will be bold**<br>
__This will also be bold__<br>
~~This is canceled~~<br>
*You **can** combine them*<br>

## 3. Quote Blockquotes
* Text starting with '>'.
* Up to three '>'s are possible.
* Quotes '1'.
* '2' is a quote in the quotation.
* '3' is a quote within a quote.
### How to Markdown on Syntax
As Grace Hopper said:
> I've always been more interested in the future than in the past.
> This is a first blockquote.
> > This is a second blockquote.
> > > This is a third blockquote.
###Demonstration Execution Results
As Grace Hopper said:
> I've always been more interested in the future than in the past.
> This is a first blockquote.
> > This is a second blockquote.
> > > This is a third blockquote.

## 4. Lists
###4.1. Unordered lists Unordered lists
* You can make an in-order list using '*', '+', and '-'.
* Indentation changes the appearance.
###4.2. Ordered list list with order
* Fill in the numbers to become an ordered list.
* Indentation changes the appearance.
### How to Markdown on Syntax
* Item 1
* Item 2
* Item 1
* Item 2
* Item 1
* Item 2
1. Item 1
2. Item 2
3. Item 3
1. Item 1
2. Item 2
3. Item 3
1. Item 1
2. Item 2
3. Item 3
###Demonstration Execution Results
* Item 1
* Item 2
* Item 1
* Item 2
* Item 1
* Item 2
1. Item 1
2. Item 2
3. Item 3
1. Item 1
2. Item 2
3. Item 3
1. Item 1
2. Item 2
3. Item 3
## 5. Backslash Escape Backslash Escape
* When expressing special characters, put '\' in front of the character to be displayed and write special characters.
* Attention is given to special characters after the backslash, with the front and back having the same format. "Wrapping is not a form.`
* Backslash can express the special characters below.
* \ backslash, \ backtick, * asterisk, _ underscore, {} curly braces, [] square brackets,
() parentheses, # hash mark, + plus sign, - minus sign (hyphen), . dot, ! exclamation mark
### How to Markdown on Syntax
\*literal asterisks\*
\#hash mark\#
\[squre brackets\]
###Demonstration Execution Results
\*literal asterisks\*<br>
\#hash mark\#<br>
\[squre brackets\]<br>

## 6. Images Image
* Converts to <img>.
* Similar to the link, but "!`가 붙습니다.
* Inline image \![alt text] (/test.png\)
* Link image \![alt text] (image_URL\)
* To change the size of the image, express it as '<img width="OOOpx" height="OOOpx"></img>'.
### How to Markdown on Syntax
![alt tomato] (/img/tomato.jpg)
![alt man](/img/man_laptop.jpg)
![alt Concrete Buildings](https://github.com/jinkyukim-me/markdown_ko/blob/master/img/concrete_building.jpg)
###Demonstration Execution Results
![alt tomato] (/img/tomato.jpg)
![alt man](/img/man_laptop.jpg)
![alt Concrete Buildings](https://github.com/jinkyukim-me/markdown_ko/blob/master/img/concrete_building.jpg)

## 7. Links (Anchor) Link
## 7.1. External Links External Links
Inline link: [Link] (http://example.com "Link Title")
url link: example.com, example@example.com; automatically use link without angle brackets
### How to Markdown on Syntax
[Google](http://www.google.com "구글")
[Naver] (http://www.naver.com "Naver")
[Github] (http://www.github.com "GitHub")
Google www.google.com; No angle
Naver <www.naver.com>; with angle
My mail <jinkyukim.dev@gmail.com>
###Demonstration Execution Results
[Google](http://www.google.com "구글")<br>
[Naver] (http://www.naver.com "Naver") <br>
[Github](http://www.github.com "GitHub")<br>
Google www.google.com <br>
Naver <www.naver.com> <br>
My mail <jinkyukim.dev@gmail.com><br>
## 7.2. Internal Links Internal Links
[Show] (#Head to move (title))
When writing a link in parentheses, space is linked to - and English is all in lowercase.
### How to Markdown on Syntax
[1. Headers Header] (#1-headers-headers)
[2. Emphasis] (#2-emphasis)
[3. Quote Blockquotes] (#3-blockquotes)
###Demonstration Execution Results
[1. Headers Header] (#1-headers-header)<br>
[2. Emphasis] (#2-emphasis-emphasis) <br>
[3. Blockquotes 인용](#3-blockquotes-인용)<br>

## 8. Fenced Code Blocks Code Blocks
* Simple inline code can cover the text back and forth with \` symbols.
* \`\`\` or ~~~~ code.
* Insert three Backquotes ( \` ) or waves ( ~ ) in the first and last lines.
* If multiple codes are shortened, you can add four spaces before the line.
* Specify a language next to \`\`\` to apply the syntax color.
### How to Markdown on Syntax
```
This is code blocks.
```
~~~
This is code blocks.
~~~
4 spaces
```javascript
function test() {
console.log("look ma', no spaces");
}
```
###Demonstration Execution Results
```
This is code blocks.
```
~~~
This is code blocks.
~~~
4 spaces
```javascript
function test() {
console.log("look ma', no spaces");
}
```

## 9. Task Lisk Checklist
* Display the completed list by writing '- [x]' in front of the line.
* Display incomplete list using '- [ ]' in front of line.
* In addition to highlighting, many functions are available within the check.
### How to Markdown on Syntax
- [x] this is a complete item
- [ ] this is an incomplete item
- [x] @mentions, #refs, [links](),
**formatting**, and <del>tags</del>
supported
- [x] list syntax required (any
unordered or ordered list
supported)
###Demonstration Execution Results
- [x] this is a complete item
- [ ] this is an incomplete item
- [x] @mentions, #refs, [links](),
**formatting**, and <del>tags</del>
supported
- [x] list syntax required (any
unordered or ordered list
supported)

## 10. Horizontal Rules Horizontal Lines
Create at least three * \- or * or _.
* However, if - is used, the previous line should be empty because it can be recognized as a header.
### How to Markdown on Syntax
* * *
***
*****
- - -
-------------------
###Demonstration Execution Results
* * *
***
*****
- - -
-------------------

## 11. Emoji emoticon
* Emoticons can be expressed using Markdown.
* GitHub is also applicable.
* Visit the site below for more listings.
* www.emoji-cheat-sheet.com
### How to Markdown on Syntax
GitHub supports emoji!
:+1: :sparkles: :camel: :tada:
:rocket: :metal: :octocat:
###Demonstration Execution Results
GitHub supports emoji!
:+1: :sparkles: :camel: :tada:
:rocket: :metal: :octocat:

##12. Table table
* At least three '-' (hyphen/dash) symbols are required to distinguish between headers and cells.
* You can sort the contents within the cell (column/column) with the symbol :(Colons) while separating the header cells.
* The leftmost and rightmost | (vertical bar) symbols may be omitted.
### How to Markdown on Syntax
Creating a table

Header1|Header2|Header3|Header4
---|---|---|---
Cell1|Cell2|Cell3|Cell4
Cell 5|Cell 6|Cell 7|Cell 8
Cell 9|Cell 10|Cell 11|Cell 12

Table Alignment

Header1|Header2|Header3
:---|:---:|---:
Left|Center|Right
1|2|3
4|5|6
7|8|9
###Demonstration Execution Results
Creating a table

Header1|Header2|Header3|Header4
---|---|---|---
Cell1|Cell2|Cell3|Cell4
Cell 5|Cell 6|Cell 7|Cell 8
Cell 9|Cell 10|Cell 11|Cell 12

Table Alignment

Header1|Header2|Header3
:---|:---:|---:
Left|Center|Right
1|2|3
4|5|6
7|8|9

#13. Line Breaks Wrap
* Line change can be made using '<br>'.
### How to Markdown on Syntax
Oh my my my oh my my my
You got me high so fast <br>
I want to be with you all.
Oh my my my oh my my my <br>
You got me fly so fast
Now I know a little bit.

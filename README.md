# Youthmappers Skill Lab 1 - Old git
Welcome to the first skills lab of the year! In this lab we are going to Git, GitHub and GitKraken. All the inforamtion on what Git, GitHub and GitKraken are, please see the slides that are also saved in this repo. 

For this exercise, we will be using a Glo Board, to copy my Glo Board, please use this link: https://app.gitkraken.com/glo/board/XkZPMA6McgARAvt9

## How to write on your .md file - basic writing and formatting

### In this README.md:
* [Introduction](#Introduction)
* [Headings](#Headings)
* [Styling text](#Styling-Text)
* [Quoting text](#Quoting-text)
* [Quoting code](#Quoting-code)
* [Links](#Links)
* [Lists](#Lists)
* [Task Lists](#Task-Lists)
* [Mentioning people](#Mentioning-people)
* [Paragraphs](#Paragraphs)
* [Ignoring Markdown formatting](#Ignoring-Markdown-formatting)
* [Creating a table](#Creating-a-table)
* [Images](#Images)
* [References](#References)

### [Introduction](#Introduction)
Markdown is a markup language designed to be simple enough to let anyone write structured documents without the need of a visual editor. Markdown is also lightweight and an easy-to-use syntax for styling all forms of writing on the GitHub platform. You control the display of the document; formatting words as bold or italic, adding images, and creating lists are just a few of the things we can do with Markdown. Mostly, Markdown is just regular text with a few non-alphabetic characters thrown in, like `#` or `*`. 


 ### [Headings](#Headings)
To create a heading, add one to six `#` symbols before your heading text. The number of `#` you use will determine the size of the heading.

```
# The largest heading
## The second largest heading
###### The smallest heading
```

# The largest heading
## The second largest heading
###### The smallest heading


### [Styling text](#Styling-Text)

You can indicate emphasis with bold, italic, or strikethrough text.

| Style | Syntax | Example | Output |
| ------| -------| ------- | ------ |
| Bold  | `** **`| `**This is bold text**` | **This is bold text**  |
| Italic | `* *` | `**This is italic text**` | *This is italic text*  |
| Strikethrough | `~~ ~~` | `~~This is wrong text~~` | ~~This is wrong text~~  |
| Bold and nested italic | `** **` and `_ _` | `**This is _really_ important text**` | **This is _really_ important text** |
| All bold and italic | `*** ***` |  `***All this text is important***` | ***All this text is important***  |


### [Quoting text](#Quoting-text)
You can quote text with a >.

In the words of Cameron Green:
> Stick with me, I'll make you famous


### [Quoting code](#Quoting-code)
You can call out code or a command within a sentence with single backticks. The text within the backticks will not be formatted.

```
Use `git status` to list all new or modified files that haven't yet been committed.
```
Use `git status` to list all new or modified files that haven't yet been committed.

To format code or text into its own distinct block, use triple backticks.

````
Some basic Git commands are:
```
git status
git add
git commit
```
````

Some basic Git commands are:
```
git status
git add
git commit
```


### [Links](#Links)
You can create an inline link by wrapping link text in brackets [ ], and then wrapping the URL in parentheses ( ).

`This site was built using [GitHub Help Pages](https://help.github.com/en/github/writing-on-github/basic-writing-and-formatting-syntax).`

This site was built using [GitHub Help Pages](https://help.github.com/en/github/writing-on-github/basic-writing-and-formatting-syntax).


### [Lists](#Lists)
You can make an unordered list by preceding one or more lines of text with `-` or `*`.

```
- Cameron Green 
- Victoria Rautenbach
- Azile Mdleleni
```
- Cameron Green 
- Victoria Rautenbach
- Azile Mdleleni

To order your list, precede each line with a number.

```
1. Cameron Green 
2. Victoria Rautenbach
3. Azile Mdleleni
```
1. Cameron Green 
2. Victoria Rautenbach
3. Azile Mdleleni

Nested Lists - You can create a nested list by indenting one or more list items below another item.

```
1. First list item
    - First nested item
        - Second nested list item
```
1. First list item
    - First nested item
        - Second nested list item


### [Task Lists](#Task-Lists)
To create a task list, preface list items with a regular space character followed by `[ ]`. To mark a task as complete, use `[x]`.

```
- [x] Finish my changes
- [ ] Push my commits to GitHub
- [ ] Open a pull request
```
- [x] Finish my changes
- [ ] Push my commits to GitHub
- [ ] Open a pull request


### [Mentioning people](#Mentioning-people)
You can mention a person or team on GitHub by typing `@` plus their username. This will trigger a notification and bring their attention to the conversation. People will also receive a notification if you edit a comment to mention their username.

`@vrautenbach how does this look?`

@vrautenbach how does this look?


### [Paragraphs](#Paragraphs)
You can create a new paragraph by leaving a blank line between lines of text.


### [Ignoring Markdown formatting](#Ignoring-Markdown-formatting)
You can tell GitHub to ignore (or escape) Markdown formatting by using `\` before the Markdown character.

`Let's rename \*our-new-project\* to \*our-old-project\*.`

Let's rename \*our-new-project\* to \*our-old-project\*

### [Creating a table](#Creating-a-table)
You can create tables with pipes `|` and hyphens `-`. Hyphens are used to create each column's header, while pipes separate each column. You must include a blank line before your table in order for it to correctly render.

```
| First Header  | Second Header |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |
```

| First Header  | Second Header |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |

Cells can vary in width and do not need to be perfectly aligned within columns. There must be at least three hyphens in each column of the header row.

```
| Command | Description |
| --- | --- |
| git status | List all new or modified files |
| git diff | Show file differences that haven't been staged |
```
| Command | Description |
| --- | --- |
| git status | List all new or modified files |
| git diff | Show file differences that haven't been staged |

### [Images](#Images)
The syntax for images is like the syntax for links, but with a `!` before:

`![image name](url to image)`

![code](https://www.economist.com/img/b/1000/563/85/sites/default/files/images/2015/09/blogs/economist-explains/code2.png)

### [References](#References)
* [Basic writing and formatting syntax](https://help.github.com/en/github/writing-on-github/basic-writing-and-formatting-syntax)
* [Organizing information with tables](https://help.github.com/en/github/writing-on-github/organizing-information-with-tables)
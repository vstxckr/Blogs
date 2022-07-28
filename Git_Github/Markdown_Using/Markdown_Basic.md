
# Basic Formatting Syntax

## Table Of Contents

- [Heading](#Heading)
- [Paragraph](#Paragraph)
- [Line Breaks](#Line-Breaks)
- [Styling Text](#Styling-Text)
	- [Bold](#Bold)
	- [Italic](#Italic)
	- [Italic and Bold](#Italic-and-Bold)
- [Block quotes](#Blockquotes)
	- [Blockquotes with Multiple Paragraph](#Blockquotes-with-Multiple-Paragraph)
	- [Nested Blockquotes](#Nested-Blockquotes)
	- [Blockquotes with Other Elements](#Blockquotes-with-Other-Elements)
- [Quoting Code](#Quoting-Code)
	- [Quoting a Sentence](#Quoting-a-Sentence)
	- [Quoting a Block](#Quoting-a-Block)
- [Supported Color Models](#Supported-Color-Models)
- [Links](#Links)
	- [URL](#URL)
	- [Relative Links](#Relative-Links)
- [Lists](#Lists)
	- [Ordered Lists](#Ordered-Lists)
	- [Unordered Lists](#Unordered-Lists)
	- [Adding Elements in Lists](#Adding-Elements-in-Lists)
	- [Nested Lists](#Nested-Lists)
- [Task Lists](#Task-Lists)


## Heading

| **Markdown & Description** | **Rendered Output** |
|  :----: | :----: |
| Heading level 1<br>`# Heading level 1` | # Heading level 1 |
| Heading level 2<br>`## Heading level 2` | ## Heading level 2 |
| Heading level 3<br>`### Heading level 3` | ### Heading level 3 |
| Heading level 4<br>`#### Heading level 4` | #### Heading level 4 |
| Heading level 5<br>`##### Heading level 5` | ##### Heading level 5 |
| Heading level 6<br>`###### Heading level 6` | ###### Heading level 6 |

When you use two or more heading Github automatically generates a table of contents which you can access by this way:

![image](/Git_Github/assets/heading/heading.png)

> ### Note: 
>
> 	- You should also put blank lines before and after a heading for compatibility 
> 	- You can also use ==== or --- after title to **assign Heading 1** or **Heading 2** to **that title**

## Paragraph

| **Markdown & Description** | **Rendered Output** |
| :---: |  :---: |
| Paragraph<br>`Just type normally and put blank line to seperate one or more lines of text` | Just type normally and put blank line<br>to seperate one or more lines of text |

## Line Breaks

| **Markdown & Description** | **Rendered Output** |
| :---: |  :---: |
| Line Breaks<br>`This line will break<br>oh yeah` | This line will break<br>oh yeah |

> ### Note:
>
> - You can add two or more spaces (commonly referred to as "trailing whitespace") for line breaks in nearly every Markdown application.
> - There are two other options, which you can read in this [link](https://www.markdownguide.org/basic-syntax/#line-breaks)

## Styling Text


| **Markdown, Description & Example** | **Rendered Output** |
| :---: |  :---: |
| Bold<br>`** ** or __ __`<br>`Love is **bold**` | Love is **bold** |
| Italic<br>`* * or _ _`<br>`*Cat* is italic` | *Cat* is italic | 
| Strikethrough<br>`~~ ~~`<br>`~~Oh yeah~~` | ~~This text was mistaken~~ |
| Bold and nested italic<br>`** ** and _ _`<br> `**This text is _extremely_ important***` | **This text is _extremely_ important** |
| All bold and italic<br>`*** ***`<br>`***All this text is important***` | ***All this text is important*** |
| Subscript<br>`<sub></sub>`<br>`<sub>this text is subscript</sub>` | <sub>this text is subscript</sub> |
| Superscript<br>`<sup></sup>`<br>`<sup>this text is superscript</sup>` | <sup>this text is superscript</sup> |

## Blockquotes

To create blockquote, add a ">" in front of paragraph.

<br>

`> Dorothy followed her through many of the beautifull rooms in her castle.`

<br>

The rendered output looks like this:

<br>

> Dorothy followed her through many of the beautifull rooms in her castle.

### Blockquotes with Multiple Paragraphs

Blockquotes can contain multiple paragraph. Add a ">" on the blank lines between the paragraphs.

<br>

	> Dorothy followed her through many of the beautifull rooms in her castle.
	>
	> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

<br>

The rendered output looks like this:

<br>

> Dorothy followed her through many of the beautifull rooms in her castle.
>
> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

### Nested Blockquotes

Blockquotes can be nested. Add a ">>" in front of the paragraphs you want to nest.

<br>

	> Dorothy followed her through many of the beautifull rooms in her castle.
	>
	>> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

<br>

The rendered output looks like this:

<br>

> Dorothy followed her through many of the beautifull rooms in her castle.
>                                                                                                   	
>> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

### Blockquotes with Other Elements

Blockquotes can contain other Markdown formatted elements. Not all elements can be used -- you'll need to experiment to see which one work.

<br>

	> #### The quarterly results look great!
	> 
	> - Revenue was off the chart.
	> - Profits were higher than ever.
	> 
	> *Everything* is going according to **plan**.

<br>

The rendered output looks like this:

> #### The quarterly results look great!
> 
> - Revenue was off the chart.
> - Profits were higher than ever.
> 
> *Everything* is going according to **plan**.

## Quoting Code

### Quoting a Sentence

You can call out code or a command within a sentence with single backticks. The text within the backticks will not be formatted.

``Use `git status` to list all new or modified files that haven't yet been committed. ``

The rendered output looks like this:

Use `git status` to list all new or modified files that haven't yet been committed. 

### Quoting a Block

To format code or text into its own distinct block, use triple backticks.

````
Some basic Git commands are:
```
git status
git add
git commit
```
````

The rendered output looks likes this:

Some basic Git commands are:
```
git status
git add
git commit
```

## Supported Color Models

In issues, pull requests, and discussions, you can call out colors within a sentence by using backticks. A supported color model within backticks will display a visualization of the color.

``The background color should be `#ffffff` for light mode and `#0d1117` for dark mode.``

The rendered output looks like this:

The background color should be `#ffffff` for light mode and `#0d1117` for dark mode.

Here are the currently supported color models.

| Color | Syntax | Example | Output |
|------|------|-----|-----|
| HEX | `#RRGGBB` | `#9069DA` | #9069DA |
| RGB | `rgb(R,G,B)` | `rgb(9, 105, 218)` | rgb(9, 105, 218) |
| HSL | `hsl(H,S,L)` | `hhsl(212, 92%, 45%)` | hhsl(212, 92%, 45%) |


## Links

### URL

You can create an inline link by wrapping link text in brackets `[ ]`, and then wrapping the URL in parentheses `( )`.

Example:

``This is my github [link](https://github.com/vstxckr).``

The rendered output looks like this:

This is my github [link](https://github.com/vstxckr).

### Relative Links

You can define relative links and image paths in your rendered files to help readers navigate to other files in your repository.

A relative link is a link that is relative to the current file. For example, I have README.md in root of my repository and another file in Git_Using/git_using.md, the relative link to Git_Using/git_using.md looks like this:

`[How to use git](/Git_Using/git_using.md)`

The rendered output looks like this:

[How to use git](/Git_Using/git_using.md)

## Image 

You can display an image by adding `!` and wrapping the alt text in `[ ]`. Then wrap the link for the image in parentheses `()`.

![This is an image](https://myoctocat.com/assets/images/base-octocat.svg)

![Another image](/Git_Github/assets/images/more_infomations.png)

## Lists

You can organize items into ordered and unordered lists.

### Ordered Lists

To create an ordered list, add line items with numbers followed by periods. The numbers don't have to be in numerical order, but the list should start with the number one.


| **Markdown & Description** | **Rendered Output** |
| :---: |  :---: |
| 1. first item<br>2. second item<br>3. third item<br>4. fourth item | 1. first item<br>2. second item<br>3. third item<br>4. fourth item  |
| 1. first item<br>1. second item<br>1. third item<br>1. fourth item | 1. first item<br>2. second item<br>3. third item<br>4. fourth item  |
| 1. first item<br>8. second item<br>3. third item<br>5. fourth item | 1. first item<br>2. second item<br>3. third item<br>4. fourth item  |

> #### Note: This will be modified

### Unordered Lists

| **Markdown & Description** | **Rendered Output** |
| :---: |  :---: |
| - first item<br>- second item<br>- third item<br>- fourth item | 1. first item<br>2. second item<br>3. third item<br>4. fourth item  |

> #### Note: This will be modified

### Adding Elements in Lists

To add another element in a list while preserving the continuity of the list, indent the element four spaces or one tab, as shown in the following examples.
<br>

#### Paragraphs

	- This is the first list item.
	- Here's the second list item.

		I need to add another paragraph below the second list item.

	- And here's the third list item.

<br>

The rendered output looks like this:

<br>

- This is the first list item.
- Here's the second list item.

	I need to add another paragraph below the second list item.

- And here's the third list item.

#### Blockquotes

- This is the first list item.
- Here's the second list item.

	> A blockquote would look great below the second list item.

- And here's the third list item.

### Nested Lists

You can create a nested list by indenting one or more list items below another item.

```
1. First list item
   - First nested list item
     - Second nested list item
```

The rendered output looks like this:

1. First list item
   - First nested list item
     - Second nested list item

## Task Lists

To create a task list, preface list items with a hyphen and space followed by `[ ]`. To mark a task as complete, use `[x]`.

```
- [x] Look at the sky :cyclone: :comet: :tornado:
- [ ] Kiss my girlfriend
- [ ] Add delight to the experience when all tasks are complete :tada:
```

The rendered output looks like this:

- [x] Look at the sky :cyclone: :comet: :tornado:
- [ ] Kiss my girlfriend
- [ ] Add delight to the experience when all tasks are complete :tada:

> ### Note:
>
> ![image](/Git_Github/assets/task_lists/note.png)

## Using Emoji

You can add emoji to your writing by typing `:EMOJICODE:`.

``:+1: This PR looks great - it's ready to merge! :shipit:``

The rendered output looks like this:

:+1: This PR looks great - it's ready to merge! :shipit:

Typing `:` will bring up a list of suggested emoji. The list will filter as you type, so once you find the emoji you're looking for, press **Tab** or **Enter** to complete the highlighted result.

For a full list of available emoji and codes, check out the [Emoji-Cheat-Sheet](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md).

## Footnotes

You can add footnotes to your content by using this bracket syntax:

```
Here is a simple footnote[^1].

A footnote can also have multiple lines[^2].  

You can also use words, to fit your writing style more closely[^note].

[^1]: My reference.
[^2]: Every new line should be prefixed with 2 spaces.  
  This allows you to have a footnote with multiple lines.
[^note]:
    Named footnotes will still render with numbers instead of the text but allow easier identification and linking.  
    This footnote also has been made with a different syntax using 4 spaces for new lines.
```

Here is a simple footnote[^1].

A footnote can also have multiple lines[^2].  

You can also use words, to fit your writing style more closely[^note].

[^1]: My reference.
[^2]: Every new line should be prefixed with 2 spaces.  
  This allows you to have a footnote with multiple lines.
[^note]:
    Named footnotes will still render with numbers instead of the text but allow easier identification and linking.  
    This footnote also has been made with a different syntax using 4 spaces for new lines.

## Hiding Content with Comments

You can tell GitHub to hide content from the rendered Markdown by placing the content in an HTML comment.

``<!-- This content will not appear in the rendered Markdown-->``


## Ignoring Markdown formatting

You can tell GitHub to ignore (or escape) Markdown formatting by using `\` before the Markdown character.

``Let's rename \*our-new-project\* to \*our-old-project\*.``

The rendered output looks like this:

Let's rename \*our-new-project\* to \*our-old-project\*.

## Disabling Markdown rendering

When viewing a Markdown file, you can click `<>` at the top of the file to disable Markdown rendering and view the file's source instead.

> ### Note:
>
> ![image](/Git_Github/assets/disabling_markdown_rendering/image.png)

Disabling Markdown rendering enables you to use source view features, such as line linking, which is not possible when viewing rendered Markdown files.
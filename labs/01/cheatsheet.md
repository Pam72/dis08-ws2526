# Markdown Cheat Sheet

This document provides an overview of Markdown elements with brief explanations, code examples, and rendered results.
Markdown is a simple markup language for formatting text on platforms like GitHub.
You can also see https://www.markdownguide.org/cheat-sheet/ for a quick overview

---

## 1. Basic Formatting

### Headings
Headings are created with one or more `#` characters at the beginning of a line.  
The more `#` you use, the smaller the heading. Don’t forget the space after the `#`.

**Example:**
# H1 - `# H1`
## H2 - `## H2`
### H3 - `### H3`  

### Paragraphs & Line Breaks
Paragraphs are separated by a blank line.  
Line breaks are created by adding two spaces at the end of a line.

**Example:**

First paragraph.

Second paragraph with a line break.  

### Bold
Bold text is created using double asterisks `**`
Bold text can also be created by using double underscores `__`.

**Example:**
**This text is bold**. If only **certain** words need to be **bold**, just put the `**` around single words.   

### Italic
Italic is created with one asteriks `*`. 
Italic text can also be created by using the single underscore `_`.

**Example:**
_This text is in italic_. If only _certain_ words need to be _italic_, just put the `_` around single words.  

## Bold & Italic
Text can be in italic and bold using three asterisks `***` or three underscore `___`.

**Example:**
***This text is bold and italic***  

### Strikethrough
Strikethrough text is created with double tildes `~~`.

**Example:**
~~This text is with strikethrough~~. If only ~~certain~~ words need to be ~~strikethrough~~, just put the `~~` around single words.  

## Inline Code
Inline code is created by wrapping text in single backticks `` ` ``.  
This prevents Markdown from interpreting formatting symbols inside.

**Example:**
Use the command `git status` to check your repository.  

## 2. Lists

### Unordered Lists
Unordered lists are created with `-`, `*`, or `+` followed by a space.  
All three work the same, but it’s good practice to stay consistent.

**Example:**
- First item
- Second item
- Third item

### Ordered Lists
Ordered lists are created by writing numbers followed by a dot and a space (`1. `, `2. `, etc.).  
The actual numbers you use don’t matter — Markdown automatically renders them in order.

**Example:**
1. First item
2. Second item
3. Third item

### Nested Lists
You can nest lists by adding two spaces or a tab before the sub-items.  
You can also mix ordered and unordered lists.

**Example:**
1. First item
   - Sub-item A
   - Sub-item B
2. Second item
   * Sub-item C
3. Third item

## 3. Links & Images

### Inline Links
Inline links are created with square brackets for the text and parentheses for the URL:  
`[link text](URL)`

**Example:**
[OpenAI](https://openai.com) - `[OpenAI](https://openai.com)`

### Reference-Style Links
Reference-style links let you define your URLs elsewhere in the document for better readability.  
They are especially useful when you have the same link multiple times.

**Example:**
This is a [reference link][1] example.  
[1]: https://openai.com

### Images
Images use a similar syntax as links but start with an exclamation mark `!`.

**Example:**
![Placeholder image](https://via.placeholder.com/150)

### Image + Link Combination
You can make an image clickable by wrapping it inside a link.

**Example:**
[![Placeholder image](https://via.placeholder.com/100)](https://openai.com)

## 4. Code & Technical Content

### Inline Code
Inline code is created by wrapping text in single backticks `` ` ``.  
This is useful for short commands, filenames, or code references inside a sentence.

**Example:**
Use the command `git status` to check your repository.

### Fenced Code Blocks
To display larger code snippets, use three backticks (```` ``` ````) before and after the code block.  
This preserves formatting and indentation.

**Example:**

### Syntax Highlighting
To enable syntax highlighting, specify the programming language right after the opening backticks.  

**Example (Python):**
<pre>
```python
def greet(name):
    print(f"Hello, {name}!")

--- 
# ToDo



## 4. Code & Technical Content
Inline code
Fenced code blocks
Syntax highlighting (languages like Python, R, HTML, etc.)

## 5. Quotes & Notes
Blockquotes
Nested blockquotes
Blockquotes with formatting

## 6. Tables
Basic tables
Alignment
Complex tables

## 7. Task Lists
Checkboxes

## 8. Dividers & Layout
Horizontal rules
Line breaks

## 9. Online and collaborative editors
Markdown-based editors

## 10. Platform/Tool Specific: GitHub
Task lists
Mentioning users (@username)
Automatic linking of issues/PRs
Emoji shortcodes

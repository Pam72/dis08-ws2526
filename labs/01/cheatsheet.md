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

### Bold & Italic
Text can be in italic and bold using three asterisks `***` or three underscore `___`.

**Example:**
***This text is bold and italic***  

### Strikethrough
Strikethrough text is created with double tildes `~~`.

**Example:**
~~This text is with strikethrough~~. If only ~~certain~~ words need to be ~~strikethrough~~, just put the `~~` around single words.  

### Inline Code
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

**Example:**

## 5. Quotes & Notes

### Blockquotes
Blockquotes are created using the `>` character at the beginning of a line.  
They are typically used to highlight quotes, notes, or tips.

**Example:**
> This is a simple blockquote.

### Nested Blockquotes
To nest blockquotes, add another `>` in front of the lines.  
Each level adds one more `>` symbol.

**Example:**
> This is the first level.  
>> This is a nested (second-level) quote.

### Blockquotes with formatting
You can use **bold**, *italic*, `inline code`, and even lists inside blockquotes.

**Example:**
> **Note:** You can use *Markdown* formatting  
> inside blockquotes, including `inline code`.
>
> - Item 1  
> - Item 2

## 6. Tables
Tables are useful for presenting structured information such as comparisons, data, or summaries.  
They are created using `|` (vertical bars) and `-` (dashes).

### Basic Tables
A table needs at least three columns separated by vertical bars (`|`) and a header separator row made of dashes (`---`).

**Example:**
| Name | Age | City |
|------|-----|------|
| Nadja | 24 | Berlin |
| Alessandro | 30 | London |
| Arty | 28 | Paris |

### Alignment
You can align text in columns by adding colons `:` in the separator row:

- `:---` → Left-aligned  
- `:---:` → Centered  
- `---:` → Right-aligned

**Example:**
| Left | Center | Right |
|:-----|:------:|------:|
| a    |   b    |     c |
| d    |   e    |     f |

### Complex Tables
You can include **inline formatting**, **links**, and **images** inside table cells.

**Example:**
| Name | Info | Link |
|------|------|------|
| **Billy** | *Designer* | [Portfolio](https://example.com) |
| **Bob** | ![Icon](https://via.placeholder.com/15) Developer | [GitHub](https://github.com) |

## 7. Task Lists
Task lists are a GitHub-specific Markdown feature that allows you to create checkboxes for tracking tasks.  
They are especially useful in issues, pull requests, or README files.

### Creating Task Lists
Use `- [ ]` for an unchecked box and `- [x]` for a checked box.  
Make sure there is a space after the brackets.

**Example:**
- [ ] Learn Markdown basics
- [x] Create cheat sheet
- [ ] Push changes to GitHub

## 8. Dividers & Layout
Markdown allows to separate sections visually or control line breaks.  
This improves readability, especially in long documents.

### Horizontal Rules
Horizontal rules create a visual divider.  
They are created with three or more dashes `---`, asterisks `***`, or underscores `___` on a line by themselves.

**Example:**
`---` ---
`***` ***
`___` ___

### Line Breaks
To create a line break (a new line without starting a new paragraph), add two or more spaces at the end of a line.

**Example:**
This is the first line.  
This is the second line.

> Note: Just pressing Enter once does **not** create a line break in Markdown.

### Combining Dividers with Headings
You can use horizontal rules to separate sections in combination with headings.

**Example:**
## Section 1
Content of section 1.

## 10. Platform/Tool Specific: GitHub
GitHub supports standard Markdown plus some **additional features** that are useful for collaboration and project management.

---

### Task Lists
GitHub allows interactive task lists in issues, pull requests, and README files.  
Use `- [ ]` for unchecked and `- [x]` for checked boxes.

**Example:**
- [x] Complete README
- [ ] Add cheat sheet
- [ ] Push changes

### Mentioning Users
You can mention GitHub users in comments or Markdown by using `@username`.  
This will send a notification to that user.

**Example:**
@lassagna Please review this section.

### Automatic Linking of Issues / Pull Requests
Use `#` followed by the issue or pull request number to automatically link it.

**Example:**
Fixed in #42

### Emoji Shortcodes
GitHub supports emoji shortcodes.  
Use `:shortcode:` to display emojis.

**Example:**
These are my favorite ones
:smiley: :star_struck: :sunglasses: :see_no_evil: :rocket:

--- 
# ToDo

## 4. Code & Technical Content
Fenced code blocks - find example
Syntax highlighting (languages like Python, R, HTML, etc.) - find example

## 9. Online and collaborative editors
Markdown-based editors

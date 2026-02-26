<p align="center">
  
  <img src="https://readme-typing-svg.demolab.com?font=Press+Start+2P&size=30&letterSpacing=&duration=2000&pause=1000&color=F74E12&center=true&vCenter=true&repeat=false&width=435&height=50&lines=MARKDOWN+GUIDE" alt="Typing SVG" />
  
</p>

<p align = center>
    <a href="LICENSE">
      <img src="https://img.shields.io/badge/license-MIT-blue?style=for-the-badge&logo=ReadMe&logoColor=white" alt="License: MIT" />
    </a>
    <a href="CONTRIBUTING.md">
      <img src="https://img.shields.io/badge/Contributions-Welcome-green?style=for-the-badge&logo=github&logoColor=white" alt="PRs Welcome" />
    </a>
    <a href="https://github.com/d3vdebug/markdown/stargazers">
      <img src="https://img.shields.io/github/stars/d3vdebug/markdown?style=for-the-badge&logo=github&color=red" alt="GitHub stars" />
    </a>
    <a href="https://github.com/wesleyscholl/credly-badge/network/members">
      <img src="https://img.shields.io/github/forks/d3vdebug/markdown?style=for-the-badge&logo=github&color=orange" alt="GitHub forks" />
    </a>
  </p>
  
<p align="center"> A clean, complete guide for anyone writing better README files. </p>



> <p align = 'center' font="40px"> Table of Contents</p>

> - [What is Markdown?](#what-is-markdown)
> - [Heading](#usage)
> - [Text Formatting](#usage)
> - [Lists](#usage)
> - [Usage](#usage)
> - [Usage](#usage)
> - [Usage](#usage)
> - [Usage](#usage)
> - [Usage](#usage)
> - [Usage](#usage) 



## What is Markdown?
> Markdown is a lightweight markup language that lets you format text using simple symbols.
> It’s widely used in GitHub READMEs, documentation, wikis, blogs, and notes.
<br>

<!-- Heading -->
# Headings
Headings help structure your README into clear, readable sections. Simply it makes the document easy to scan.

> # This is a Heading
> ```md
> # This is a Heading
> ```
> ## This is a Heading
> ```md
> ## This is a Heading
> ```
> ### This is a Heading
> ```md
> ### This is a Heading
> ```

<!-- Text Formatting -->
# Text Formatting
Formatting helps you highlight important info, emphasize details, or organize explanations. It makes your README clearer, more readable, and more professional.

**Bold Text**
```md
**Bold Text** or __Bold Text__
```

*Italic Text*
```md
*Italic Text* or _Italic Text_
```

***Bold + Italic***
```md
***Bold + Italic***
```

~Strikethrough~
```md
`~~Strikethrough~~` or `~Strikethrough~`
```

<ins>Underline<ins>
```md
<ins>Underline<ins>
```

Here's is a <sub>subscript<sub>
```md
<sub>subscript<sub>
```

Here's is a <sup>superscript<sup>
```md
<sup>superscript<sup>
```

`inline code`
```md
`inline code`
```

<!-- Lists -->

# Lists
Lists help you present information cleanly and quickly, making complex steps or features easy to digest.

> ## Unordered List
> - Item 1
> - Item 2
> ```md
> - Item 1
> - Item 2
> ```


> ## Ordered List
> 1. Item 1
> 2. Item 2
> ```md
> 1. Item 1
> 2. Item 2
> ```

> ## Nested Lists
> - Item 1
>   - Sub Item 1
>     - Sub item a
> ```md
> - Item 1
>   - Sub Item 1
>     - Sub item a
> ```


> ## Task List
> - [x] Completed task
> - [ ] Pending task
> ```md
> - [x] Completed task
> - [ ] Pending task
> ```

<!-- Code -->
# Code Blocks
Code blocks make your README **developer‑friendly**, giving users clean, formatted examples they can copy and run.

### Inline Code
Use `npm install` to install packages.
```
`npm install`
```
### Code Block
```python
print("Hello World")
```

````
```python
print("Hello World")
```
````
Syntax highlighting available for Python, JavaScript, Java, Bash, JSON, YAML etc.
````
```<syntax>
<code>
```
````

# Mermaid Diagrams
GitHub supports Mermaid for diagrams. Very useful for architecture diagrams, flowcharts, and explaining project structure: essential for technical documentation.


```mermaid
flowchart TD
    A --> B
```
Syntax:
````
```mermaid
flowchart TD
    A --> B
```
````


<!-- Tables -->
# Tables
Tables allow you to show structured information such as configurations, comparisons, or fields. It turns messy text into a clean, organized layout, especially useful for feature lists, API data, and documentation.

| Name   | Role      | Level  |
|--------|-----------|--------|
| John   | Developer | Senior |
| Bob    | Tester    | Junior |

```md
| Name   | Role      | Level  |
|--------|-----------|--------|
| John   | Developer | Senior |
| Bob    | Tester    | Junior |
```
or
```md
|Name|Role|Level|
|-|-|-|
|John|Developer|Senior|
|Bob|Tester|Junior|
```

<!-- Blockquotes -->
# Blockquotes
Used for notes, warnings, tips, or important messages.

> This is a quoted line.
>> Nested quote
```md
> This is a quoted line.
>> Nested quote
```

# Horizontal Line

---
```md
---
```

# Links
Links lets us connect users to installation guides, docs, external pages, or related repositories.

[GitHub](https://github.com)

Syntax:
```
[GitHub](https://github.com)
```
# Images
Images help make your README visually appealing, making your README more engaging and easier to understand.

Syntax:
```
![Alt text](image_url)
````
![cat](https://github.com/user-attachments/assets/ba594416-cd49-4231-837b-fc4b742b876f)

```
![cat](https://github.com/user-attachments/assets/ba594416-cd49-4231-837b-fc4b742b876f)
```



<!-- HTML -->
# Alerts
Alerts are use to emphasize critical information. On GitHub, they are displayed with distinctive colors and icons to indicate the significance of the content.

### NOTE
> [!NOTE]
> Useful information that users should know, even when skimming content.
```
> [!NOTE]
> Useful information that users should know, even when skimming content.
```

> [!TIP]
> Helpful advice for doing things better or more easily.
```
> [!TIP]
> Helpful advice for doing things better or more easily.
```

> [!IMPORTANT]
> Key information users need to know to achieve their goal.
```
> [!IMPORTANT]
> Key information users need to know to achieve their goal.
```

> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.
```
> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.
```

> [!CAUTION]
> Advises about risks or negative outcomes of certain actions.
```
> [!CAUTION]
> Advises about risks or negative outcomes of certain actions.
```
# HTML in Markdown
Markdown is powerful, but it has limits. GitHub supports HTML inside Markdown, letting you do layout tricks that plain Markdown cannot achieve. Below is the full detailed explanation of how HTML can enhance Markdown.

## HTML Headings
Markdown headings are good, but HTML headings gives more control. Useful when you want alignment or mixed layout at the top.

> <h1>Heading 1</h1>
> <h2>Heading 2</h2>
> <h3>Heading 3</h3>
```md
<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
```

> <h2 align="left">Left Aligned</h1>
> <h2 align="center">Centered</h2>
> <h2 align="right">Right Aligned</h3>
```md
<h2 align="left">Left Aligned</h1>
<h2 align="center">Centered</h2>
<h2 align="right">Right Aligned</h3>
```

## Paragraphs & Line Breaks
Markdown sometimes collapses line breaks. HTML fixes that.

### Paragraph
<p>This is a paragraph with controlled spacing.</p>

```md
<p>This is a paragraph with controlled spacing.</p>
```

### Line Break
Line 1 <br>
Line 2

```md
Line 1 <br>
Line 2
```

## Comments
Comments are notes that won't render on the markdown, useful in add info without showing them publicly.
```md
<!-- This is a Comment -->

<!--
This is
also a
Comment
-->
```

## Alignment and Centered Sections
We can tweak the alignment of elements using the 'align' attribute on some tags. It is very useful to get a clean professional look for README's top section.


> <div align="center">
>   <img src="assets/devdebug.png" alt="Logo" width="120" />
>   <h1>Project Name</h1>
>   <p>A short one‑line description of what your project does.</p>
> </div>
code
> ```md
> <div align="center">
>   <img src="assets/logo.png" alt="Logo" width="120" />
>   <h1>Project Name</h1>
>   <p>A short one‑line description of what your project does.</p>
> </div>
> ```

## Links
Using `<a>` tag we can add links inside centered blocks, badge rows, or custom layouts where Markdown links get messy.

<a href="https://example.com" title="Example">Example Site</a>

```md
<a href="https://example.com" title="Example">Example Site</a>
```

## Lists
Markdown lists are usually enough, but HTML lists help when you’re mixing complex blocks or alignment. We use `<ul>` ` <li>` for unordered lists, `<ol>` `<li>` for ordered lists.

<ul>
  <li>list 1</li>
  <li>list 2</li>
</ul>

```md
<ul>
  <li>list 1</li>
  <li>list 2</li>
</ul>
```

<ol>
  <li>list 1</li>
  <li>list 2</li>
</ol>

```md
<ol>
  <li>list 1</li>
  <li>list 2</li>
</ol>
```


## Tables
HTML tables are more flexible than Markdown tables. These are great for side‑by‑side layouts and for content that breaks Markdown table formatting.




## Collapsible sections
Within our README we can use  `<details>` and  `summary>` tag to create expandable sections. These collapsible sections are perfect for FAQ, advanced setup, more screenshots, or extended configuration without making the README huge.

<details>
<summary>Show advanced setup</summary>
  
- Step 1: Do this  
- Step 2: Do that
</details>

```md
<details>
  <summary>Show advanced setup</summary>
  - Step 1: Do this  
  - Step 2: Do that  
</details>
```


# Anchors
Anchors helps navigation in long READMEs. GitHub supports TOC linking behavior as part of common README practice.


# Keyboard keys
We can use `<kbd>` to display keyboard keys nicely. It is useful for shortcuts or commands in guides.

> Press <kbd>Ctrl</kbd> + <kbd>C</kbd> to Copy.
> Press <kbd>Ctrl</kbd> + <kbd>V</kbd> to Paste.
> ```md
> Press <kbd>Ctrl</kbd> + <kbd>C</kbd> to Copy.
> Press <kbd>Ctrl</kbd> + <kbd>V</kbd> to Paste.
> ```



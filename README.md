# Markdown Guide — Basics to Advanced
<p> A clean, complete guide for anyone writing better README files. </p>

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




<!-- HTML -->
# HTML in Markdown
<span style="color:yellow">Yellow text</span>

# Collapsible Sections



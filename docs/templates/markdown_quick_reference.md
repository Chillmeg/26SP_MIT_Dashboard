# Markdown quick reference for GitHub and VS Code

## Headings
```md
# Title
## Section
### Subsection
#### Smaller subsection
```

## Emphasis and inline code
```md
**bold**
*italic*
***bold italic***
`inline code`
```

## Line breaks and paragraphs
A blank line creates a new paragraph.

To force a line break without a blank line, end the line with two spaces.
```md
Line one.··
Line two.
```
Replace the two middle dots with two real spaces.

## Lists

### Unordered list
```md
* item
* item
  * sub item
  * sub item
```

### Ordered list
```md
1. first
2. second
   1. nested first
   2. nested second
```

### Checklist
```md
* [ ] todo
* [x] done
* [ ] another task
```

## Links

### Link to a website
```md
[link text](https://example.com)
```

### Link to a file in your repo
```md
[Notes index](notes/index.md)
```

### Link to a heading in the same file
```md
[Jump to Quotes](#quotes)
```

## Images
Relative paths work well in repos.
```md
![alt text](assets/figure1.png)
```

## Code blocks

### Fenced code block with language
```md
```python
print("hi")
```
```

### Fenced code block without language
```md
```
some text
```
```

## Quotes
```md
> This is a quote.
> This is still part of the quote.
```

Nested quote
```md
> Outer quote
>> Inner quote
```

## Separator
Asterisks work across renderers.
```md
***
```

## Collapsible section
Works on GitHub.
```md
<details>
<summary>Click to expand</summary>

Text inside.

```python
code inside
```

</details>
```

## Tables
GitHub tables typically need a header separator line that uses a character you might not want. Use an HTML table instead.

```md
<table>
  <tr>
    <th>Col A</th>
    <th>Col B</th>
  </tr>
  <tr>
    <td>a</td>
    <td>b</td>
  </tr>
  <tr>
    <td>c</td>
    <td>d</td>
  </tr>
</table>
```

## Footnotes
Footnotes work in many Markdown renderers.

```md
This is a claim.[^1]

[^1]: Source or note.
```

## Escaping Markdown characters
Use a backslash to show literal characters.

```md
\* not a list item
\# not a heading
```

## Suggested lecture note template
```md
# Lecture: Topic

Date: 2026 02 17
Notion:

## Summary
Write 3 to 6 sentences.

## Key points
1.
2.
3.

## Terms
1. term: definition
2. term: definition

## Questions
1.
2.

## Action items
* [ ]
* [ ]
```

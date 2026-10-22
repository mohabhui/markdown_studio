# Markdown Formatting Examples

*A sample Markdown document for testing Markdown editors and previewers.*

> **Tip:** Open this file in your Markdown editor and switch between Source and Preview to see how the syntax is rendered.

---

## 1. Normal Paragraphs

This is a normal paragraph. Markdown is a lightweight markup language used to format documents with plain text. Paragraphs wrap naturally based on the width of the viewer.

This is a second paragraph. Leave one blank line between paragraphs to keep them separate.

To force a line break without creating a new paragraph, end the line with two spaces.  
This sentence appears on the next line in the same paragraph.

## 2. Headings

# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6

## 3. Text Formatting

- **Bold text**
- *Italic text*
- ***Bold and italic text***
- ~~Strikethrough text~~
- `Inline code`
- <u>Underlined text (HTML)</u>
- <mark>Highlighted text (HTML; viewer support varies)</mark>
- Superscript: X<sup>2</sup>; subscript: H<sub>2</sub>O (HTML)
- Escaped formatting characters: \*not italic\* and \# not a heading

You can use formatting **within a normal paragraph**, mix *italic* with **bold**, and refer to a command like `pip install requests`.

## 4. Lists

### Unordered List

- Apples
- Bananas
  - Yellow bananas
  - Green bananas
- Oranges

### Ordered List

1. Open your Markdown file.
2. Edit the source text.
3. Save it.
4. Preview the formatted document.

### Task / Checklist

- [x] Create Markdown file
- [x] Add formatting examples
- [ ] Insert your own content
- [ ] Share the document

## 5. Blockquotes

> This is a blockquote. It is useful for quotations, notes, or highlighted information.
>
> **Important:** You can use bold text and other Markdown inside a blockquote.

> A nested quotation:
> > This is a second-level blockquote.

## 6. Code Examples

### Inline Code

Use `print("Hello, Markdown!")` to print a message in Python.

### Python Code Block

```python
from datetime import datetime

def greet(name: str) -> str:
    """Return a personalized greeting."""
    return f"Hello, {name}! Today is {datetime.now():%Y-%m-%d}."

if __name__ == "__main__":
    print(greet("World"))
```

### JavaScript Code Block

```javascript
const numbers = [1, 2, 3, 4];
const squares = numbers.map(n => n * n);
console.log(squares);
```

### SQL Code Block

```sql
SELECT employee_id, employee_name, department
FROM employees
WHERE active = 1
ORDER BY employee_name;
```

### Plain Text Code Block

```text
Project/
├── README.md
├── sample_image.png
└── src/
    └── app.py
```

## 7. Web Links

A normal web link: [Python Official Website](https://www.python.org/)

A link with a title: [GitHub](https://github.com/ "Visit GitHub")

An automatic URL: <https://www.wikipedia.org/>

An email link: [Email the team](mailto:team@example.com)

## 8. Images

### Image Stored Alongside This Markdown File

The following image is included in the ZIP package. Keep it in the same folder as this `.md` file:

![Markdown formatting illustration](sample_image.png "Local sample image")

### Online Image Example

This image is loaded from the web (internet access required):

![Placeholder banner from placehold.co](https://placehold.co/700x160/png?text=Online+Markdown+Image "Online image example")

### Clickable Image

[![Click to visit Python](https://placehold.co/300x90/png?text=Visit+Python)](https://www.python.org/)

## 9. Tables

| ID | Employee | Department | Salary (CAD) | Status |
|:---|:---------|:----------:|-------------:|:------:|
| 101 | Alice Brown | QA | $82,000 | Active |
| 102 | Bob Smith | Development | $95,500 | Active |
| 103 | Carol Lee | Support | $73,000 | On Leave |
| 104 | David Chen | DevOps | $102,000 | Active |

Alignment: `:---` aligns left, `:---:` centers, and `---:` aligns right.

## 10. Horizontal Rules

The lines below create horizontal separators:

---

***

## 11. Special Characters and Symbols

- Check mark: ✓
- Cross mark: ✗
- Right arrow: →
- Copyright symbol: ©
- Emoji: 📘 🧪 🚀

## 12. Footnotes (Supported in Some Markdown Renderers)

Markdown is a popular format for technical documentation.[^markdown-note]

[^markdown-note]: Footnote support depends on the Markdown implementation (for example, GitHub Flavored Markdown supports it).

## 13. Collapsible Section (HTML; Support Varies)

<details>
<summary>Click to expand additional information</summary>

This paragraph is visible when the section is expanded in a renderer that supports HTML `<details>` elements.

</details>

## 14. Raw Markdown Source Example

The code block below shows Markdown syntax **without** rendering it as formatting:

````markdown
# My Heading

This is **bold**, *italic*, and `inline code`.

- Item one
- Item two

[Open a website](https://example.com)

![Image description](image.png)
````

---

**End of Markdown examples.**

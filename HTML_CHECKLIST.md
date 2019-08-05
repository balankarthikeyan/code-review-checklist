## <h1>MARKUP<h1>

Note:

```
http://webdevchecklist.com
Write the code properly formatted in terms of white space and syntax conventions
```

---

<h3>Tags / Attributes</h3>

> 1. Dont use inline style attributes.
> 2. Use proper attributes for images and links. <br>`(Example: <DIV> – Bad, <div> – Better)`
> 3. Omit the values on Boolean attributes. <br>`(Example: <input type=”text” name=” fname“ disabled= disabled”> – Bad, <input type=”text” name=”fname” disabled> – Better)`
> 4. `<image>` elements must have an "alt" attribute? Decorative images should have an empty value.
> 5. Use one time ID attribute
> 6. Use class name in UI related names
> 7. Do all input fields have explicit `<label>`elements? <br>All form elements should ensure proper association with "for" and "id" attributes.

---

<h3>Semantics</h3>

> 1. Don't use Heading Content in `<div>` and `<span>` elements unless necessary. Use it h1-h6 tags
> 2. Use Proper tags as per UI depend
> 3. Use all latest html 5 tags

_Semantic HTML Tags_

| Syntax         | Description                           |
| -------------- | ------------------------------------- |
| `<abbr>`       | Abbreviation                          |
| `<acronym>`    | Acronym                               |
| `<blockquote>` | Long quotation                        |
| `<dfn>`        | Definition                            |
| `<address>`    | Address for author(s) of the document |
| `<cite>`       | Citation                              |
| `<code>`       | Code reference                        |
| `<tt>`         | Teletype text                         |
| `<div>`        | Logical division                      |
| `<span>`       | Generic inline style container        |
| `<del>`        | Deleted text                          |
| `<ins>`        | Inserted text                         |
| `<em>`         | Emphasis                              |
| `<strong>`     | Strong emphasis                       |
| `<p>`          | paragraph                             |
| `<h1>`         | First-level headline                  |
| `<h2>`         | Second-level headline                 |
| `<h3>`         | Third-level headline                  |
| `<h4>`         | Fourth-level headline                 |
| `<h5>`         | Fifth-level headline                  |
| `<h6>`         | Sixth-level headline                  |
| `<hr>`         | Thematic break                        |
| `<kbd>`        | Text to be entered by the user        |
| `<pre>`        | Pre-formatted text                    |
| `<q>`          | Short inline quotation                |
| `<samp>`       | Sample output                         |
| `<sub>`        | Subscript                             |
| `<sup>`        | Superscript                           |
| `<var>`        | Variable or user defined text         |

---

---

<h3>SEO</h3>

---

<h3>Accessibility / WCAG</h3>

> 1. Page has a proper outline (H1-H6 order)
> 2. Alt attributes exist on all `<img >` elements
> 3. Video is accompanied by a transcript and closed captioning
> 4. Code validates against WCAG priority level 1 and 2
> 5. Events and styles applied to :hover are also applied to :focus
> 6. Tabindex order is logical and intuitive
> 7. Are appropriate ARIA landmark roles being used? Is there one "main", "banner", "contentinfo", and 3 or less "navigation" roles?

---

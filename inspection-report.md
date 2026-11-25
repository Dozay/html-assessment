# HTML validation assessment — manual inspection

The original broken.html is preserved. Line numbers below refer to that original. The corrected document is fixed.html. The product image and destination pages are included.

| Problem | Location | Fix | Why it matters |
|---|---|---|---|
| Missing document language | 2 | Add lang="en" | Helps assistive technology pronounce text correctly. |
| Missing title | 3–5 | Add descriptive title | Identifies the page in tabs and assistive technology. |
| Skipped heading level | 8 | Change h3 to h2 | Preserves logical document structure. |
| Omitted paragraph end tag | 10 | Add closing p tag | Improves readability; this particular omission is permitted by HTML before another p. |
| Incorrect nesting | 11 | Close em before strong | Prevents parser repair and ambiguous structure. |
| Missing image alternative | 12 | Add descriptive alt text | Communicates meaningful image content to screen-reader users. |
| Duplicate ID | 9, 14 | Rename second ID to stock | Ensures unique element identification. |
| Broken relative product link | 15 | Link to included product.html | Allows navigation to an existing resource. |
| Broken relative contact link | 16 | Link to included contact.html | Allows navigation to an existing resource. |
| Incorrect label association | 19–20 | Change for to name | Connects label to its input. |
| Missing email label | 21 | Add label for email | Gives the input an accessible name. |
| Missing section closing tag | 24–27 | Add closing section tag | Corrects unclosed structural element. |

## Validation evidence (pending)
The online W3C Nu HTML Checker could not be reached from the creation environment. No validator output or screenshots have been fabricated. Validate both complete files at https://validator.w3.org/nu/ using file upload. Save the original errors as screenshots/initial-validation.png and the corrected result as screenshots/final-validation.png. If errors remain, correct fixed.html and revalidate. The checker does not verify every accessibility or broken-link issue; these were inspected manually.

## Public project link (pending)
Upload the project contents to a public GitHub repository or static hosting service. Enable GitHub Pages if using GitHub. Include the actual repository and live page links in your submission. Do not upload credentials or private files.

# markdown-cheat-sheet
Because I feel like I'm learning and forgetting things I can do in markdown constantly

## Code and syntax highlighting

### Inline code
```markdown
Inline code will just have single back-ticks around the code. For example: `import requests`
```
Inline code will just have single back-ticks around the code. For example: `import requests`

### Code blocks
Blocks of code have 3 back-ticks. Not all markdown renderer's will support syntax highlighting

<pre>
```python
import requests
r = requests.get("https://www.google.com")
print(r.status_code)
```
</pre>

```python
import requests
r = requests.get("https://www.google.com")
print(r.status_code)
```

## Footnotes
This one doesn't really work in Github's markdown renderer, but works pretty with VSCode (provided you're using the [Markdown Preview Enhanced](https://marketplace.visualstudio.com/items?itemName=shd101wyy.markdown-preview-enhanced) extension, doesn't work with the native markdown preview)
```markdown
Mediawiki and Wikipedia articles use this a lot to cite sources [^1]

[^1]: https://www.wikipedia.org
```

Mediawiki and Wikipedia articles use this a lot to cite sources [^1]

[^1]: https://www.wikipedia.org

## Abbreviations
This one doesn't really work in Github's markdown renderer, but works pretty with VSCode (provided you're using the [Markdown Preview Enhanced](https://marketplace.visualstudio.com/items?itemName=shd101wyy.markdown-preview-enhanced) extension, doesn't work with the native markdown preview)
```markdown
Here, we're talking about HTML

*[HTML]: HyperText Markup Language
```
Here, we're talking about HTML

*[HTML]: HyperText Markup Language

## Sources and references
1. https://wordpress.com/support/markdown-quick-reference/
2. https://github.com/adam-p/markdown-here/wiki/Markdown-Here-Cheatsheet

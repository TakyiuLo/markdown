# Using Markdown as Notes Toker with Atom 
My setup for using atom as note taker

##### Install:
  - `markdown-writer`
  - `language-markdown`
  - `linter-markdown`
  - `tool-bar`
  - `tool-bar-markdown-writer`
  - `markdown-table-editor`

##### Change Settings
- `markdown-writer`
  - File extension: change from `.markdown` to `.md`
  - New Post File Name: change from `{year}-{month}-{day}-{slug}{extension}` to `{slug}{extension}`
  - Check `Table Extra Pipes`
- `tool-bar-markdown-writer`
  - `Visibility` select `showToolbarOnMarkdown`
- (Optional) `markdown-table-editor`
  - Check `Format on Save`

### Example
```js
class ClassName {
  constructor() {
    
  }
}
```

### Dark Mode
```
<style>
.markdown-preview {
  background: #1d252c !important;
  color: #aaa !important;
}
.markdown-preview code {
  background: #000 !important;
  /* box-shadow: 0 0px 2px #fff !important; */
  color: #0aa !important;
}
</style>
```

### Reference
- Read GA WDI's Markdown Repo
- [Markdown Cheat Sheet][72f0c6fb]
- [Pandoc][6267ccf8]

[72f0c6fb]: https://www.markdownguide.org/cheat-sheet "Markdown Cheat Sheet"
[6267ccf8]: https://pandoc.org/index.html "Pandoc"

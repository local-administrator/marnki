# Marnki - Markdown Anki Templates

Beautiful Anki card templates with full Markdown support and terminal-inspired design.

## Features

- ✨ **Full Markdown Support** - Write your cards in Markdown with live rendering
- 🎨 **Two Beautiful Themes** - Choose between Catppuccin Mocha and Nord themes
- 💻 **Terminal-Inspired Design** - Clean, developer-friendly interface
- 🔧 **Syntax Highlighting** - Language-specific code highlighting for multiple languages
- 📱 **Responsive Layout** - Works great on desktop and mobile

## What's Included

- `anki_front_template.html` - Front card template with embedded Markdown parser
- `anki_back_template.html` - Back card template showing question, answer, and tags
- `anki_styles_catppuccin.css` - Catppuccin Mocha dark theme
- `anki_styles_nord.css` - Nord theme

## Quick Setup

1. **Import the template** into Anki:
   - Go to Tools → Manage Note Types
   - Add a new note type or edit an existing one
   - Copy the contents of `anki_front_template.html` into the Front Template
   - Copy the contents of `anki_back_template.html` into the Back Template

2. **Choose your theme** by copying one of the CSS files into the Styling section:
   - For dark theme: Use `anki_styles_catppuccin.css`
   - For light/blue theme: Use `anki_styles_nord.css`

3. **Create cards** using Markdown syntax in your Front and Back fields

## Markdown Support

Write your cards using standard Markdown syntax:

### Text Formatting
```markdown
**Bold text** and *italic text*
~~Strikethrough text~~
`inline code`
```

### Headers
```markdown
# Heading 1
## Heading 2  
### Heading 3
```

### Code Blocks
```markdown
```python
def hello_world():
    print("Hello, World!")
```
```

### Lists
```markdown
- Unordered list item
- Another item

1. Ordered list item
2. Another numbered item
```

### Links and More
```markdown
[Link text](https://example.com)

> Blockquote text

| Table | Header |
|-------|--------|
| Cell  | Data   |
```

## Supported Languages for Syntax Highlighting

- JavaScript/JS
- Python
- HTML/XML
- CSS
- Bash/Shell
- JSON
- Rust
- Go
- Java
- C/C++

## Card Structure

**Front Card:**
- Clean terminal-style header with colored dots
- Centered question content
- Full Markdown rendering

**Back Card:**
- Same terminal header design
- Question section (repeated from front)
- Answer section
- Tags section (if tags are present)
- Visual separators between sections

## Themes

### Catppuccin Mocha
- Dark theme with purple/pink accents
- Warm, comfortable color palette
- Great for extended study sessions

### Nord
- Cool blue/teal color scheme
- Clean, minimalist design
- Easy on the eyes

## Customization

You can customize the appearance by modifying the CSS files:

- Colors are defined as CSS variables at the top of each file
- Font families, sizes, and spacing can be adjusted
- The terminal header can be customized or hidden
- Section borders and backgrounds are easily modifiable

## Requirements

- Anki desktop or AnkiWeb
- No additional plugins required - everything is embedded

## Tips

1. **Preview your cards** - The Markdown renders immediately, so you can see how your cards will look while editing
2. **Use code blocks** for technical content - The syntax highlighting makes code much more readable
3. **Organize with headers** - Use different header levels to structure complex information
4. **Tag your cards** - Tags will appear in a dedicated section at the bottom of the back card

## Contributing

Feel free to submit issues or pull requests to improve these templates!

## License

This template is provided as-is for educational use. Feel free to modify and distribute.
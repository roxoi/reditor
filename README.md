# Enhanced Dark Code Editor

A lightweight, feature-rich browser-based code editor with syntax highlighting, auto-save, and real-time statistics. No installation required - runs entirely in your browser!

![License](https://img.shields.io/badge/license-MIT-green)
![HTML5](https://img.shields.io/badge/HTML5-E34C26?style=flat&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

## ✨ Features

### Core Editing
- **Syntax Highlighting** - 10 language modes (JavaScript, Python, HTML, CSS, SQL, Shell, C/C++, XML, Markdown, Plain Text)
- **Line Numbers** - Easy code navigation
- **Auto-closing Brackets** - Bracket pairing for faster coding
- **Line Wrapping** - Toggle between wrapped and unwrapped text
- **Undo/Redo** - Full undo/redo support with keyboard shortcuts

### Toolbar Features
- **Paste** - Paste code directly from your clipboard
- **Copy** - Copy all code to clipboard with one click
- **Download** - Save your code as a `.txt` file
- **Search** - Find text within your code
- **Font Size** - Adjust text size (10-24px)
- **Statistics** - View real-time code metrics
- **Undo/Redo** - Navigate through edit history
- **Clear** - Clear all code (with confirmation)

### Statistics & Analytics
- **Line Count** - Total number of lines
- **Word Count** - Total words in code
- **Character Count** - Total characters (excluding whitespace)
- **Read Time** - Estimated reading time
- **Cursor Position** - Real-time line and column indicator

### Smart Storage
- **Auto-Save** - Automatically saves your code to browser storage every second
- **LocalStorage** - Persists code even after closing the browser
- **Visual Feedback** - Save indicator shows "Saving..." then "✓ Saved"

### UI/UX
- **Dark Theme (Dracula)** - Easy on the eyes, perfect for long coding sessions
- **Responsive Design** - Works on desktop browsers
- **Real-time Status Bar** - See stats, mode, and cursor position at a glance
- **Success Messages** - Toast notifications for copy/paste/download actions
- **Smooth Animations** - Polished transitions and visual feedback

## Quick Start

### Option 1: Open Online
Just click and use - no setup needed!
```
https://roxoi.github.io/reditor
```

### Option 2: Use Data URI
Paste this directly into your browser address bar:
```
data:text/html,<full-html-content>
```

### Option 3: Download & Run Locally
1. Download `index.html`
2. Open the file in any modern web browser
3. Start coding!

## How to Use

### Basic Operations
```
Write Code         → Start typing or paste code
Change Language    → Select from Language dropdown
Adjust Font Size   → Use the Font slider (10-24px)
Search Code        → Click Search, type text, click Next
```

### Keyboard Shortcuts
```
Ctrl/Cmd + Z       → Undo
Ctrl/Cmd + Shift + Z → Redo
Ctrl/Cmd + /       → Toggle comment
Tab                → Indent
Shift + Tab        → Unindent
```

### Save & Share
```
Auto-Save          → Automatic every second
Copy Code          → 📋 Copy button
Download Code      → ⬇️ Download button
Paste Code         → 📋 Paste button
```

## Deploy to GitHub Pages

### Step 1: Create a GitHub Repository

1. Go to [github.com/new](https://github.com/new)
2. Repository name: **editor** (important for the URL structure)
3. Add description: "Enhanced Dark Code Editor"
4. Click "Create repository"

### Step 2: Clone & Setup

```bash
# Clone the repository
git clone https://github.com/YOUR-USERNAME/editor.git

# Navigate to folder
cd editor

# Create index.html (copy the editor code)
# Copy the enhanced-code-editor.html content to index.html
```

### Step 3: Push to GitHub

```bash
# Add files
git add .

# Commit
git commit -m "Initial commit: Add enhanced code editor"

# Push to GitHub
git push -u origin main
```

### Step 4: Enable GitHub Pages

1. Go to your repository settings
2. Scroll down to **GitHub Pages**
3. Select **main** branch as source
4. Click **Save**
5. Wait 1-2 minutes for deployment

### Access Your Editor

Your editor will be available at:
```
https://YOUR-USERNAME.github.io/editor
```

**Example:**
```
https://roxoi.github.io/editor
```

## Repository Structure

```
editor/
├── index.html           # Main editor file
├── README.md           # This file
├── LICENSE             # MIT License
└── .gitignore          # Git ignore file
```

## Technologies Used

- **CodeMirror 5.65.16** - Syntax highlighting & editing
- **Dracula Theme** - Dark color scheme
- **Vanilla JavaScript** - No dependencies required
- **HTML5 & CSS3** - Modern web standards

## Supported Languages

| Language | Code |
|----------|------|
| JavaScript | `javascript` |
| HTML | `htmlmixed` |
| CSS | `css` |
| Python | `python` |
| XML/SVG | `xml` |
| Markdown | `markdown` |
| SQL | `sql` |
| Shell/Bash | `shell` |
| C/C++/Java | `clike` |
| Plain Text | `null` |

## Tips & Tricks

### Pro Tips
1. **Code Persistence** - Your code is saved automatically. Refresh the page and it's still there!
2. **Fast Copying** - Use Copy button to quickly share code snippets
3. **Language Switching** - Change language on the fly - syntax highlighting updates instantly
4. **Search Feature** - Use Ctrl+F to search within your code
5. **Font Adjustment** - Increase font size for presentations or reduce for more content

### Keyboard Shortcuts
- `Ctrl+Z` - Undo
- `Ctrl+Shift+Z` - Redo
- `Ctrl+A` - Select all
- `Tab` - Indent
- `Shift+Tab` - Dedent

## Use Cases

- Quick code snippets  
- Live coding tutorials  
- Temporary code storage  
- Learning programming  
- Code review & sharing  
- Take code notes  
- Practice coding problems  

## Browser Compatibility

| Browser | Support |
|---------|---------|
| Chrome/Edge | Full |
| Firefox | Full |
| Safari | Full |
| Mobile Browsers | Partial |

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contributing

Found a bug or have a feature request? Feel free to open an issue or submit a pull request!

### How to Contribute

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## Contact & Social

- **Email** - roxoi0x01@gmail.com
- **GitHub** - [@roxoi](https://github.com/roxoi)
- **Portfolio** - [roxoi.vercel.app](https://roxoi.github.io)

## Acknowledgments

- **CodeMirror** - For the amazing code editor library
- **Dracula Theme** - For the beautiful dark theme
- **CDN Providers** - CloudFlare, JSDelivr for reliable CDN hosting

## Project Stats

- Lines of Code: ~500
- Supported Languages: 10
- Load Time: < 2 seconds
- ile Size: ~25KB (minified)

---

**Made with ❤️ by [Roxoi](https://github.com/roxoi)**

> "Code with passion, ship with purpose."

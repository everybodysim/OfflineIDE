# CodeStudio - Offline IDE

CodeStudio is a lightweight, fully functional integrated development environment (IDE) that runs entirely in your browser through a single HTML file. No internet connection, server, or installation is required—just open `OfflineIDE.html` in any modern web browser to start coding.

## Features

- **Single-File Portability:** The entire IDE is contained within `OfflineIDE.html`, making it incredibly easy to share and run anywhere.
- **File Management:** Create, delete, and organize files and folders within the IDE's virtual file system.
- **Rich Code Editor:** Powered by CodeMirror, featuring syntax highlighting, line numbers, and intelligent auto-indentation.
- **Multi-Language Support:** Recognizes and provides syntax highlighting for a wide variety of programming languages (HTML, CSS, JS, Python, C++, Java, Go, Rust, and many more).
- **Live Preview:** Instantly preview web projects (HTML/CSS/JS) and other supported formats directly within the IDE via the split-pane live preview.
- **Export to ZIP:** Easily export your entire workspace as a ZIP file to back up your code or share it with others.
- **Modern UI/UX:** A sleek, dark-themed interface with smooth animations, file search/filtering, and an informative status bar.
- **Offline First:** All files are stored locally in your browser.

## Getting Started

1. Download or clone this repository.
2. Double-click `OfflineIDE.html` to open it in your web browser (Chrome, Firefox, Edge, Safari, etc.).
3. Click the **+** button in the sidebar to create a new file (e.g., `index.html` or `src/main.js`).
4. Start typing in the editor.
5. Use the Live Preview panel to see your web pages render in real-time.
6. When you're done, click the **↓** (Export as ZIP) button to download your project files.

## Project Structure

- `OfflineIDE.html`: The core IDE file containing all HTML, CSS, and JavaScript logic.

## Supported File Types for Live Preview

The built-in Live Preview pane currently supports the following extensions:
- `.html`
- `.css`
- `.js`
- `.md` (Markdown)
- `.py` (Python)

## Technologies Used

- **HTML5/CSS3/JavaScript (ES6+)** for the core logic and interface.
- **[CodeMirror](https://codemirror.net/)** for the code editing experience.
- **[Devicons](https://devicon.dev/)** and **[Boxicons](https://boxicons.com/)** for UI and file type icons.

## License

This project is open-source. Feel free to modify and adapt it to your needs!

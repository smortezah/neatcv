# NeatCV

A clean, professional CV template built with Typst. This single-file template is easy to customize, ATS-friendly, and perfect for AI-assisted modifications based on specific job descriptions.

## Installation

### Windows

1. **Using winget (recommended):**

   ```bash
   winget install --id Typst.Typst
   ```

2. **Manual installation:**
   - Download the latest release from [Typst releases](https://github.com/typst/typst/releases)
   - Extract the archive and add the `typst.exe` to your PATH

### Linux/macOS

1. **Using Homebrew (macOS/Linux):**

   ```bash
   brew install typst
   ```

2. **Manual installation (Linux):**
   - Download the latest release from [Typst releases](https://github.com/typst/typst/releases)
   - Extract and move the binary to `/usr/local/bin/`:
     ```bash
     sudo mv typst /usr/local/bin/
     sudo chmod +x /usr/local/bin/typst
     ```

## Usage

### Compile your CV

To compile the CV to PDF:

```bash
typst compile cv.typ
```

This will generate `cv.pdf` in the same directory.

### Watch mode (auto-compile on changes)

For real-time preview while editing:

```bash
typst watch cv.typ
```

The PDF will automatically update whenever you save changes to the file.

## Customization

The `cv.typ` file is designed to be easily customizable:

- **Single-file design**: All your CV content and formatting is in one file
- **Text-based format**: Easy to edit in any text editor
- **Simple syntax**: Modify personal information, sections, and content directly in the file
- **ATS-friendly**: Clean structure ensures compatibility with Applicant Tracking Systems
- **AI-friendly**: The text-based nature makes it perfect for AI agents to modify and tailor your CV based on specific job descriptions

Simply open `cv.typ` in your favorite text editor and update the content. The Typst syntax is intuitive and well-documented at [typst.app/docs](https://typst.app/docs).

## Tips

- Use the [Typst web app](https://typst.app/) for online editing with live preview
- Check the [official documentation](https://typst.app/docs) for advanced formatting options
- The single-file approach keeps everything organized and version-control friendly

## License

This template is provided as-is for personal and professional use.

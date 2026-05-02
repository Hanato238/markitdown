# MarkItDown Gemini Extension

This extension provides tools to convert various file formats (PDF, DOCX, XLSX, images, etc.) to Markdown using Microsoft's MarkItDown library.

## Available Tools

- `convert_to_markdown`: Converts a local file or URL to Markdown.

## Requirements

- Python 3.10+ (Recommended: 3.13)
- `uv` (Fast Python package manager)

## Implementation Details

The extension uses the `markitdown-mcp` package included in the repository and runs it using `uv` to ensure all dependencies (including OCR and media processing) are correctly isolated and installed.

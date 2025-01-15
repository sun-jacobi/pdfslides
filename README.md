# PDF to PPTX Converter

## Installation

```bash
pip install pdfslides
```

## Usage

Run the script using the command-line interface:

```bash
pdfslides --pdf input.pdf --output output.pptx --dpi 300
```

### Arguments
- `--pdf` (required): Path to the input PDF file.
- `--output` (required): Path to save the generated PPTX file.
- `--dpi` (optional): Resolution for rendering PDF pages (default: 300).

### Example
Convert a file named `example.pdf` to `example.pptx` with a DPI of 200:
```bash
pdfslides --pdf example.pdf --output example.pptx --dpi 200
```


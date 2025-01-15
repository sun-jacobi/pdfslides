# PDF to PPTX Converter

## Installation

### Prerequisites
- Python 3.6 or higher
- Required Python libraries:
  - `pymupdf`
  - `python-pptx`

Install the dependencies using:
```bash
pip install pymupdf python-pptx
```

## Usage

Run the script using the command-line interface:

```bash
python script_name.py --pdf input.pdf --output output.pptx --dpi 300
```

### Arguments
- `--pdf` (required): Path to the input PDF file.
- `--output` (required): Path to save the generated PPTX file.
- `--dpi` (optional): Resolution for rendering PDF pages (default: 300).

### Example
Convert a file named `example.pdf` to `example.pptx` with a DPI of 200:
```bash
python script_name.py --pdf example.pdf --output example.pptx --dpi 200
```


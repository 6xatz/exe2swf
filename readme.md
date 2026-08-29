# EXE to SWF Extractor

A simple browser-based tool for extracting embedded SWF files from Adobe Flash Projector `.exe` files.

## Features

- Runs entirely in the browser
- No file upload or server required
- Extracts embedded SWF from Flash Projector executables
- Automatically downloads the extracted `.swf` file
- Displays extraction status and logs

## Usage

1. Open the HTML file in a modern web browser.
2. Select an Adobe Flash Projector `.exe` file.
3. The tool will automatically extract the embedded SWF.
4. The extracted SWF will be downloaded automatically.

## How It Works

The extractor checks for the Flash Projector footer signature `0xFA123456`, reads the stored SWF length, and extracts the SWF data located immediately before the 8-byte footer.

## License

MIT LICENSE
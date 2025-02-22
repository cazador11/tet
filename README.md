# Text to PDF Converter

A modern, user-friendly web application that converts text files (.txt) to PDF documents. Built with vanilla JavaScript and features a responsive design with light/dark theme support.

## Features

- **Text to PDF Conversion**: Convert any text content to a well-formatted PDF document
- **File Upload**: Support for .txt file uploads
- **Clipboard Support**: Paste text directly from clipboard
- **Theme Support**: Toggle between light and dark themes
- **Responsive Design**: Works seamlessly on both desktop and mobile devices
- **Error Handling**: Clear error messages and visual feedback
- **Custom Formatting**: Automatic page breaks and margin handling

## Installation

1. Clone this repository or download the files
2. No build process required - it's ready to use!
3. Open `index.html` in your web browser

## Usage

1. **Upload a Text File**:
   - Click "Choose TXT File" button
   - Select a .txt file from your computer

2. **Paste Text**:
   - Click "Paste from Clipboard" button, or
   - Directly type or paste text into the text area

3. **Convert to PDF**:
   - Click "Convert to PDF" button
   - The PDF will be automatically downloaded

## Dependencies

- [jsPDF](https://github.com/parallax/jsPDF) (2.5.1) - For PDF generation
- Google Fonts (Inter) - For typography

## Browser Support

Works in all modern browsers that support:
- File API
- Clipboard API
- Local Storage (for theme preference)

## License

MIT License - feel free to use and modify for your own projects!

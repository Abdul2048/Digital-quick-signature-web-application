# QuickSign 


A simple, lightweight digital signature application built with HTML5 Canvas and vanilla JavaScript. Create, customize, and save your digital signatures directly in your browser.

## Features

- **Digital Drawing**: Draw signatures using your mouse or touchpad
- **Customizable Colors**: Choose text color and background color
- **Adjustable Stroke Width**: Select from multiple font/stroke sizes (5px to 50px)
- **Save & Download**: Save signatures as PNG files
- **Local Storage**: Store and retrieve your signatures locally
- **Responsive Design**: Clean, centered interface with Bootstrap styling

## Demo
![alt text](<image.jpg>)


## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- No additional software installation required

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/quicksign.git
```

2. Navigate to the project directory:
```bash
cd quicksign
```

3. Open `index.html` in your web browser:
```bash
open index.html
```

Or simply double-click the `index.html` file to open it in your default browser.

## Usage

1. **Drawing**: Click and drag on the canvas to draw your signature
2. **Customize Colors**: 
   - Use the "Text color" picker to change stroke color
   - Use the "Background" picker to change canvas background
3. **Adjust Stroke Size**: Select font size from the dropdown (5px-50px)
4. **Clear Canvas**: Click "Clear" to start over
5. **Save Signature**: Click "Save and Download" to save as PNG and store locally
6. **Retrieve Signature**: Click "Retrieve saved signature" to load your last saved signature

## File Structure

```
quicksign/
├── index.html          # Main HTML structure
├── style.css           # CSS styling
├── script.js           # JavaScript functionality
└── README.md          # This file
```

## Technologies Used

- **HTML5 Canvas** - For drawing functionality
- **Vanilla JavaScript** - Core application logic
- **Bootstrap 4** - UI styling and components
- **Local Storage API** - For saving/retrieving signatures

## Browser Compatibility

- Chrome 50+
- Firefox 45+
- Safari 10+
- Edge 12+


## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/new-feature`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature/new-feature`)
5. Create a Pull Request

## Known Issues

- Touch support for mobile devices could be improved
- No undo/redo functionality currently available
- Limited to single signature storage in local storage

## Future Enhancements

- Mobile touch support
- Multiple signature storage
- Undo/Redo functionality
- Different brush types
- Export to different formats (SVG, PDF)
- Signature templates


## Support

If you encounter any issues or have questions, please [open an issue](https://github.com/Abdul2048/quicksign/issues) on GitHub.

---

**Made with ❤️ for digital signatures**
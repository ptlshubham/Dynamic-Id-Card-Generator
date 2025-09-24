# Dynamic ID Card Generator

A modern, web-based ID card generator that allows you to create professional ID cards dynamically using CSV data and customizable templates. Perfect for organizations, schools, companies, and events that need to generate multiple ID cards efficiently.

## 🌟 Features

### Core Functionality
- **Dynamic Card Generation**: Generate multiple ID cards from CSV data
- **Custom Templates**: Upload your own ID card templates (images)
- **Flexible Layout System**: Drag-and-drop positioning of elements
- **Real-time Preview**: See changes instantly as you design
- **Batch Processing**: Generate hundreds of cards at once

### Supported Elements
- **Photos**: Upload and position profile photos with automatic resizing
- **Text Fields**: Add any text data from your CSV (names, IDs, departments, etc.)
- **Barcodes**: Generate barcodes automatically from data fields
- **Custom Styling**: Fonts, colors, sizes, and alignment options

### Advanced Features
- **Custom Fonts**: Upload and use your own font files (.ttf, .otf, .woff, .woff2)
- **Font URLs**: Load fonts from web URLs
- **Overlay Controls**: Visual guides for precise element positioning
- **Grid Snapping**: Align elements perfectly with snap-to-grid
- **Layout Export/Import**: Save and reuse your card layouts
- **Bulk Download**: Download all generated cards as a ZIP file
- **Progress Tracking**: Real-time progress bars for batch operations

## 🚀 Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- No installation required - runs entirely in the browser

### Quick Start
1. Open `index.html` in your web browser
2. Upload your ID card template image
3. Upload a CSV file with your data
4. Position elements on the card using the visual editor
5. Generate and download your ID cards

## 📋 CSV Data Format

Your CSV file should contain headers that match the fields you want to display on the ID cards. Common examples:

```csv
name,employee_id,department,email,phone,photo_url
John Doe,EMP001,Engineering,john@company.com,+1234567890,photos/john.jpg
Jane Smith,EMP002,Marketing,jane@company.com,+1234567891,photos/jane.jpg
```

### Supported Data Types
- **Text Fields**: Any text data (names, IDs, titles, etc.)
- **Photo URLs**: Local or web URLs to profile photos
- **Barcode Data**: Any field can be used for barcode generation

## 🎨 Customization Options

### Layout Configuration
- **Element Positioning**: Drag elements or use precise coordinates
- **Size Adjustments**: Resize photos and text areas
- **Alignment Options**: Left, center, right alignment for text
- **Font Styling**: Size, weight, color, and family

### Template Support
- **Image Formats**: JPG, PNG, GIF, WebP
- **Any Size**: Automatic scaling to fit the canvas
- **High Resolution**: Maintains quality for printing

### Font Management
- **Web Fonts**: Google Fonts and other web font services
- **Custom Fonts**: Upload your own font files
- **Font Families**: Support for all standard font properties

## 🔧 Usage Instructions

### Step 1: Upload Template
1. Click "Select Template Image"
2. Choose your ID card background/template
3. The template will appear in the preview area

### Step 2: Upload Data
1. Click "Select CSV File"
2. Choose your CSV file with card data
3. Headers will be automatically detected

### Step 3: Design Layout
1. Select elements from the left panel (Photo, Name, ID, etc.)
2. Click on the preview to position elements
3. Use the coordinate inputs for precise positioning
4. Adjust styling options (font, color, size)

### Step 4: Generate Cards
1. Click "Live Preview" to see a sample card
2. Use "Generate All" to create all cards
3. Download individual cards or use "Download All (ZIP)"

## 📁 File Structure

```
Dynamic-Id-Card-Generator/
├── index.html              # Main application file
├── README.md               # This file
├── VHK.json               # Sample layout configuration
├── idcard-layout.json # Another sample layout
└── photo/        # Sample photos directory
    └── sample.jpg              # Sample photo
```

## 🛠️ Technical Details

### Built With
- **Pure HTML/CSS/JavaScript** - No framework dependencies
- **Canvas API** - For high-quality card rendering
- **File API** - For drag-and-drop file handling
- **Web Fonts API** - For custom font loading

### External Libraries
- **PapaParse** - CSV parsing
- **JSZip** - ZIP file creation
- **FileSaver.js** - File download functionality
- **JsBarcode** - Barcode generation

### Browser Compatibility
- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## 🎯 Use Cases

### Educational Institutions
- Student ID cards
- Staff identification
- Event badges
- Library cards

### Corporate Organizations
- Employee ID badges
- Visitor passes
- Conference badges
- Access cards

### Events & Conferences
- Attendee badges
- Speaker cards
- VIP passes
- Name tags

### Healthcare
- Patient wristbands
- Staff identification
- Visitor badges

## 📖 Examples

### Basic Employee ID Card
```csv
name,employee_id,department,position,photo
John Doe,EMP001,IT,Developer,photos/john.jpg
Jane Smith,EMP002,HR,Manager,photos/jane.jpg
```

### Student ID Card
```csv
student_name,student_id,grade,class,photo
Alice Johnson,STU001,10,10-A,photos/alice.jpg
Bob Wilson,STU002,11,11-B,photos/bob.jpg
```

## 🔐 Privacy & Security

- **Local Processing**: All data processing happens in your browser
- **No Server Upload**: Your data never leaves your computer
- **Privacy First**: No tracking or data collection
- **Secure**: Works offline after initial load

## 🤝 Contributing

This is an open-source project. Contributions are welcome!

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## 📞 Support

For issues, questions, or feature requests:
- Create an issue on GitHub
- Check existing documentation
- Review the code for implementation details

## 📄 License

This project is open source. Please check the repository for license details.

## 🔄 Version History

- **v1.0** - Initial release with core functionality
- Dynamic element placement
- CSV data import
- Batch card generation
- Custom font support
- Layout save/load functionality

---

**Made with ❤️ for efficient ID card generation**
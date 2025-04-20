# Local File Share

A modern, user-friendly web application for local file sharing and management built with Flask. This application allows users to easily upload, store, and download files within a local network.

## Features

- 📤 Simple drag-and-drop file upload interface
- 📥 Easy file downloading
- 🎨 Modern, responsive UI with animations
- 🔒 File type validation
- 📱 Mobile-friendly design
- 🌈 Beautiful gradient design elements

## Supported File Types

- Images (PNG, JPG, JPEG, GIF)
- Documents (PDF, TXT, CSV)
- Archives (ZIP, RAR)
- Media (MP4)
- Applications (APK)

## Requirements

- Python 3.x
- Flask

## Installation

1. Clone this repository:
```bash
git clone [repository-url]
```

2. Install the required dependencies:
```bash
pip install flask
```

3. Run the application:
```bash
python app.py
```

4. Access the application in your web browser at:
```
http://localhost:5000
```

## Usage

1. **Uploading Files**:
   - Click the upload button or drag and drop files into the upload area
   - Select your file(s)
   - The file will be automatically uploaded and appear in the file list

2. **Downloading Files**:
   - Click on any file in the list to download it

## Directory Structure

```
.
├── app.py              # Main application file
├── templates/          # HTML templates
│   └── index.html     # Main page template
├── uploads/           # Directory for uploaded files
└── README.md          # This file
```

## Security Note

This application is designed for local network use. It's recommended not to expose it directly to the internet without implementing proper security measures.

## License

See the [LICENSE](LICENSE) file for details.

---
Made with ❤️ for easy local file sharing

# YouTube Video Downloader

A React-based web application that allows users to download YouTube videos and music in various formats and qualities. The application is powered by a Node.js backend using `ytdl-core`.

## Features

- **Download Music**: Convert and download YouTube videos as MP3 files.
- **Download Video**: Download YouTube videos as MP4 files.
- **Format Selection**: Choose between different formats (MP4, MP3).
- **Quality Selection**: Select the desired quality (Highest, Lowest, etc.).
- **Web Interface**: User-friendly interface for entering URLs and selecting download options.

## File Structure

```
/youtube-downloader
|-- /backend
|   |-- server.js
|-- /frontend
|   |-- /public
|   |-- /src
|   |   |-- App.js
|   |   |-- index.js
|   |-- package.json
|-- package.json
```

## Getting Started

### Prerequisites

- Node.js
- npm

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/coderooz/react-youtube-downloader.git
   cd react-youtube-downloader
   ```

2. **Install backend dependencies:**
   ```bash
    cd backend
    npm install
   ```

3. **Install frontend dependencies:**
   ```bash
    cd ../frontend
    npm install
   ```

### Running the Application

1. **Start the backend server:**
   ```bash
    cd backend
    node server.js
   ```

2. **Start the frontend development server:**
   ```bash
    cd ../frontend
    npm start
   ```

3. Open your browser and navigate to `http://localhost:3000` to use the application.

## Usage

1. Enter a valid YouTube URL in the input field.
2. Select the desired format (MP4, MP3).
3. Choose the quality of the download (Highest, Lowest).
4. Click the "Download" button to start the download process.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Please see the [CONTRIBUTING](CONTRIBUTING.md) guidelines for more information.

## Code of Conduct

Please read the [CODE_OF_CONDUCT](CODE_OF_CONDUCT.md) to understand the expected behavior in our community.

## Author

**Ranit Saha**  
GitHub: [coderooz](https://github.com/coderooz)

# Background Remover Web App

A web application that removes backgrounds from images using the Remove.bg API. Built with Flask and modern web technologies.

## Features

- Modern, responsive web interface
- Drag and drop image upload
- Camera capture support (mobile and desktop)
- Real-time background removal
- Download processed images
- Support for multiple image formats (PNG, JPG, JPEG)
- Front/back camera switching on mobile devices

## Technologies Used

- Python 3.7+
- Flask
- Remove.bg API
- HTML5/CSS3
- JavaScript (ES6+)
- WebRTC for camera access

## Setup

1. Clone the repository:
```bash
git clone https://github.com/psycho-8/bgrem.git
cd background-remover
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Create a `.env` file in the root directory and add your Remove.bg API key:
```
REMOVE_BG_API_KEY=your_api_key_here
```

4. Run the application:
```bash
python app.py
```

5. Open your browser and navigate to `http://localhost:5000`

## Usage

1. Upload an image using the "Gallery" button or drag and drop
2. Or capture an image using your camera with the "Camera" button
3. Click "Remove BG" to process the image
4. Download the processed image using the "Download" button

## API Key

You'll need an API key from [Remove.bg](https://www.remove.bg/api) to use this application. The free tier includes 50 API calls per month.

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details. 
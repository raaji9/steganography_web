# Steganography Web Project

The **Steganography Web Project** is a web-based application that allows users to hide secret messages within digital images using the **Least Significant Bit (LSB)** technique. This project ensures secure communication by embedding data in a way that is imperceptible to the human eye, without altering the quality of the image.

## Features
- **Encode Messages**: Hide secret messages within an image.
- **Decode Messages**: Extract hidden messages from an encoded image.
- **User-Friendly Interface**: Simple and intuitive web interface.
- **Secure Communication**: Messages are securely embedded and extracted using LSB steganography.

## How It Works
Steganography works by modifying the least significant bits of the pixel values in an image to store secret data. These changes are so minor that they are invisible to the human eye, making the image appear unchanged.

### Encoding Process
1. The user uploads an image and enters a secret message.
2. The message is converted into binary format.
3. The binary message is embedded into the least significant bits of the image's pixel values.
4. The encoded image is saved and can be downloaded.

### Decoding Process
1. The user uploads an encoded image.
2. The least significant bits of the image's pixel values are extracted.
3. The binary data is converted back into the original message.
4. The decoded message is displayed to the user.

---

## Getting Started

### Prerequisites
- Python 3.x
- Flask (`pip install flask`)
- Pillow (`pip install pillow`)
- NumPy (`pip install numpy`)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/steganography_web.git
   cd steganography_web
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Flask application:
   ```bash
   python app.py
   ```

4. Open your browser and navigate to:
   ```
   http://127.0.0.1:5000/
   ```

---

## Usage

### Encoding a Message
1. **Choose "Encode Message"** from the dropdown menu.
2. **Upload an image** (e.g., a PNG or JPEG file).
3. **Enter your secret message** in the text box.
4. Click **Submit**.
5. The encoded image will be displayed. You can **download the image** by clicking the "Download Image" button.

### Decoding a Message
1. **Choose "Decode Message"** from the dropdown menu.
2. **Upload the encoded image**.
3. Click **Submit**.
4. The decoded message will be displayed below the form.

---

## Tutorial

### Step-by-Step Guide
1. **Encoding a Message**:
   - Select "Encode Message" from the dropdown.
   - Upload an image and enter your secret message.
   - Click "Submit" to generate the encoded image.
   - Download the encoded image to share it securely.

2. **Decoding a Message**:
   - Select "Decode Message" from the dropdown.
   - Upload the encoded image.
   - Click "Submit" to extract the hidden message.
   - The decoded message will appear below the form.

---

## Screenshots

### Home Page
![Home Page](screenshots/home.png)

### Encoding a Message
![Encoding](screenshots/encode.png)

### Decoding a Message
![Decoding](screenshots/decode.png)

---

## Folder Structure
```
steganography_web/
│
├── app.py                  # Flask application
├── requirements.txt        # Dependencies
├── static/                 # Static files (CSS, images, etc.)
│   ├── assets/             # Logo and background images
│   ├── uploads/            # Uploaded and encoded images
│   └── styles.css          # CSS styles
├── templates/              # HTML templates
│   └── index.html          # Main page
└── README.md               # Project documentation
```

---

## Contributing
Contributions are welcome! If you'd like to contribute, please follow these steps:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeatureName`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/YourFeatureName`).
5. Open a pull request.

---

## License
This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---

## Acknowledgments
- **Flask**: For providing a lightweight web framework.
- **Pillow**: For image processing capabilities.
- **NumPy**: For efficient numerical operations.

---

## Contact
For questions or feedback, feel free to reach out:
- **Email**: shapritik@gmail.com
- **GitHub**: [pritik](https://github.com/Pritiksha20)

---

Enjoy hiding and revealing your secret messages with the **Steganography Web Project**! 🕵️‍♂️🔐

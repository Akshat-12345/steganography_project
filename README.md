# Steganography Project

## Introduction
This project implements steganography techniques to hide secret messages within digital images. Steganography is the practice of concealing information within non-secret data to avoid detection. The project provides encoding and decoding functionalities using image processing.

## Features
- Encode messages into images without noticeable changes.
- Decode hidden messages from stego-images.
- Support for various image formats (PNG, BMP, etc.).
- User-friendly command-line interface.
- Error handling and validation for reliable encoding/decoding.

## Technologies Used
- Programming Language: Python
- Libraries: OpenCV, NumPy, Pillow

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/steganography-project.git
   cd steganography-project
   ```
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
### Encoding a Message
```bash
python encode.py -i input_image.png -m "Your secret message" -o output_image.png
```

### Decoding a Message
```bash
python decode.py -i output_image.png
```

## Example
1. Original Image: `input_image.png`
2. Hidden Message: "Hello, World!"
3. Encoded Image: `output_image.png`
4. Decoded Message: "Hello, World!"

## Contributing
Contributions are welcome! Feel free to submit issues or pull requests.

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

## Contact
For any inquiries, reach out to [akshatbajpai2020@gmail.com] or open an issue on GitHub.


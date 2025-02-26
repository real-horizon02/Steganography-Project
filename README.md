# Steganography-Project

📌 Project Overview

This project implements Image Steganography using the Least Significant Bit (LSB) technique to securely hide and extract data within an image. The project is developed in Python using the OpenCV (cv2) library and other supporting libraries.

🚀 Features

Secure Data Hiding: Embeds text messages into images without visible changes.

Data Extraction: Retrieves the hidden data from an image.

Lossless Data Storage: Ensures minimal distortion in the stego image.

🛠️ Technologies Used

Programming Language: Python

Libraries:

OpenCV (cv2) – for image processing

NumPy – for numerical operations


🖥️ Installation and Usage

1️⃣ Prerequisites

Ensure Python is installed on your system. You can download it from Python Official Site.

2️⃣ Clone the Repository

 git clone https://github.com/yourusername/secure-image-steganography.git
 cd secure-image-steganography

3️⃣ Install Dependencies

 pip install -r requirements.txt

4️⃣ Encoding Data into an Image

Run the following command to hide a message inside an image:

 python src/encode.py --input image.png --output stego_image.png --message "Your Secret Message"

5️⃣ Decoding Hidden Data from an Image

Extract the hidden message using:

 python src/decode.py --input stego_image.png


🔐 Security & Limitations

This method is effective against casual inspection but may not withstand advanced steganalysis attacks.

The image should not be heavily compressed after embedding the message, as compression may distort hidden data.


🤝 Contributing

Contributions are welcome! Feel free to fork this repository and submit pull requests.

📞 Contact

For any questions or suggestions, reach out via:

Email: kshitijchandel02@gmail.com

GitHub: real-horizon02

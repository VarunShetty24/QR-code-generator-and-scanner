# QR Code Generator & Scanner

A simple and user-friendly **QR Code Generator & Scanner** built with **Python** and **Tkinter**. This application allows users to generate QR codes from text or URLs, scan QR codes using a webcam or image file, and save generated QR codes locally.

---

##  Features

###  QR Code Generator

* Generate QR codes from text
* Generate QR codes from URLs
* Save QR codes as PNG images
* Clear input fields
* Preview generated QR codes

### 📷 QR Code Scanner

* Scan QR codes using a webcam
* Scan QR codes from image files
* Display scanned text or URL
* Open scanned URLs in the default browser
* Copy scanned text to the clipboard

###  History

* Save generated QR codes
* Save scanned results
* View scan history
* Clear history

---

##  Technologies Used

* Python 3
* Tkinter
* OpenCV
* qrcode
* Pillow (PIL)
* pyzbar
* JSON

---

##  Project Structure

```text
QR-Code-Generator-Scanner/
│
├── main.py
├── qr_generator.py
├── qr_scanner.py
├── history.py
├── utils.py
├── history.json
├── requirements.txt
├── README.md
├── LICENSE
├── .gitignore
├── .gitattributes
│
├── generated/
│   └── qr_codes/
│
└── assets/
    ├── icon.ico
    └── screenshots/
```

---

##  Installation

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/QR-Code-Generator-Scanner.git
```

### 2. Open the Project Folder

```bash
cd QR-Code-Generator-Scanner
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the Application

```bash
python main.py
```

---

##  Required Libraries

Install the following libraries if you are not using `requirements.txt`:

```bash
pip install qrcode
pip install pillow
pip install opencv-python
pip install pyzbar
```

---

##  How to Use

### Generate QR Code

1. Open the application.
2. Enter text or a URL.
3. Click **Generate QR**.
4. Preview the generated QR code.
5. Click **Save** to store it.

### Scan QR Code

1. Click **Open Camera** to scan using your webcam.
2. Or click **Scan Image** to decode a QR code from an image.
3. The decoded content will be displayed automatically.
4. Copy or open the scanned URL directly.

---


##  Future Enhancements

*  Dark Mode
*  Wi-Fi QR Code Generator
*  Contact (vCard) QR Generator
*  PDF Export
*  QR Code Analytics
*  Cloud Backup
*  Custom QR Colors
*  Logo Embedded QR Codes
*  Mobile Version
*  Multi-language Support

---

##  Contributing

Contributions are welcome!

1. Fork this repository.
2. Create a feature branch.

```bash
git checkout -b feature-name
```

3. Commit your changes.

```bash
git commit -m "Add new feature"
```

4. Push your branch.

```bash
git push origin feature-name
```

5. Open a Pull Request.

---

##  License

This project is licensed under the **MIT License**.

---

##  Author

**Varun Shetty**

*  Computer Science & Engineering Student
*  Python | C | C++ Programmer
*  Passionate about Software Development and Open Source

---

##  Support

If you found this project helpful, please give it a ⭐ on GitHub.

Happy Coding! 

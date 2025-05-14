This Python project generates a QR code that links to a YouTube video and embeds the CSUMB logo in the center. The resulting image is saved and displayed to the user. This is useful for branding QR codes with a recognizable logo while maintaining scan accuracy through high error correction.

Libraries Used:
- qrcode (to generate the QR code)
- PIL / Pillow (to manipulate and embed the logo image)

Features:
- Custom URL embedded in the QR code
- CSUMB logo added at the center of the QR code
- High error correction level to ensure scannability despite the embedded image

Note:
- Ensure that the logo image file `csumb.jpg` exists in the same directory as the script.
- The generated QR code is saved as `QRnew.png` and then displayed.

Forensics software.

For QRcodechecker.py , install everything into source ~/.venv/bin/activate first pip install --upgrade pip pip install pyzbar opencv-python-headless Pillow numpy qrcode qreader pyzxing
python-barcode yara-python requests python-magic-bin scikit-image imageio
scipy tldextract cryptography colorama termcolor segno

Essential QR/Image Processing
pip3 install pyzbar opencv-python-headless Pillow qrcode qreader

Additional decoders
pip3 install pyzxing python-barcode segno

Analysis tools
pip3 install yara-python requests python-magic-bin

Scientific/Image processing
pip3 install scikit-image imageio scipy

Network/Security
pip3 install tldextract cryptography

Optional but useful
pip3 install colorama termcolor

brew install zbar

Install libdmtx for DataMatrix codes
brew install libdmtx dmtx-utils

Install other tools the script references
brew install imagemagick tesseract qrencode

and run the software with source ~/.venv/bin/activate Enter: source ~/.venv/bin/activate then Enter: bash ~/desktop/QRcodechecker.sh ~/Desktop/(QRCODE.jpg/.jpeg/etc)

All are drafts, all are pretty straight forward.

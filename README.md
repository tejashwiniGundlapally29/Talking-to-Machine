# Shopping Assistance for Visually-Impaired

A simple but powerful tool to help visually-impaired users shop more independently.  
Using a smartphone camera, the app scans a product barcode, looks up product details,  
and speaks the information aloud.

---

## ✨ Features
- **Barcode Scanning** – Detects and decodes product barcodes using Python libraries.
- **Product Database Lookup** – Fetches product details from a local/remote database.
- **Text-to-Speech** – Reads product name and details for hands-free use.
- **Accessible UI** – Minimal interaction needed; designed for visually-impaired users.

---

## 🛠️ Tech Stack
- **Language:** Python  
- **Libraries:** OpenCV / Pillow (image capture & processing), `pyzbar` or `zxing` (barcode decoding),  
  SQLite or other database for product info, `pyttsx3` or `gTTS` for text-to-speech.

---

## 🚀 Getting Started
### Prerequisites
- Python 3.8+
- Camera-equipped computer or smartphone

### Installation
```bash
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>
pip install -r requirements.txt

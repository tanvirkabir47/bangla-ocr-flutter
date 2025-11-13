# 📷 Bangla OCR App

A modern **Flutter** application that uses **Tesseract OCR** to extract Bangla text from images captured via the camera or selected from the gallery.

![App Icon](https://github.com/tanvirkabir47/bangla-ocr-flutter/blob/main/assets/icon/icon.png)

---

## 🚀 Features

✅ **Bangla OCR Support** – Extract text from printed or handwritten Bangla images  
✅ **Camera & Gallery Integration** – Pick an image or take a new one instantly  
✅ **Modern UI/UX** – Clean, smooth, and user-friendly design  
✅ **Progress Indicator** – Shows live extraction progress  
✅ **Copy or Clear Extracted Text** (optional for extension)  

---

## 🧠 How It Works

1. Choose an image from the gallery or take a photo with the camera.  
2. The app automatically processes the image using **Tesseract OCR**.  
3. Extracted Bangla text is displayed on screen.  
4. You can copy or clear the text easily.

---

## 🧩 Tech Stack

- **Flutter** (Dart)  
- **Tesseract OCR Plugin** (`tesseract_ocr`)  
- **Image Picker** (`image_picker`)  
- **Material 3 UI Design**  

---

## 📸 Screenshots

| Home Screen | OCR Processing | Extracted Text |
|--------------|----------------|----------------|
| ![Home](https://github.com/tanvirkabir47/bangla-ocr-flutter/blob/main/assets/image/home.jpg) | ![Loading](https://github.com/tanvirkabir47/bangla-ocr-flutter/blob/main/assets/image/loading.jpg) | ![Result](https://github.com/tanvirkabir47/bangla-ocr-flutter/blob/main/assets/image/result.jpg) |

---

## ⚙️ Installation

### 1️⃣ Clone the repository
```bash
git clone https://github.com/<your-username>/bangla-ocr-app.git
cd bangla-ocr-app
2️⃣ Install dependencies
bash
Copy code
flutter pub get
3️⃣ Run the app
bash
Copy code
flutter run
⚠️ Make sure your device or emulator has a working camera if you want to test image capture.

🧩 Dependencies
Add these in your pubspec.yaml (already included):

yaml
Copy code
dependencies:
  flutter:
    sdk: flutter
  image_picker: ^1.1.2
  tesseract_ocr: ^0.3.0
🧰 App Icon Setup
Place your app icon (e.g., app_icon.png) in assets/icon.png and run:

bash
Copy code
flutter pub run flutter_launcher_icons
Update your pubspec.yaml:

yaml
Copy code
flutter_launcher_icons:
  android: true
  ios: true
  image_path: "assets/icon.png"
📄 Folder Structure
bash
Copy code
lib/
 ├── main.dart          # App entry point
 ├── widgets/           # (Optional) UI components
assets/
 ├── icon.png           # App icon
 ├── screenshots/       # UI screenshots
🧑‍💻 Author
Tanvir Kabir
📧 tanvirkabir47@gmail.com
🌐 tanvirkabir47.netlify.app

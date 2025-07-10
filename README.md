
# 🐶🐱 Dog vs Cat Classifier App

A smart Flutter application that can identify whether an image contains a **dog** or a **cat**, using on-device machine learning with TensorFlow Lite.

---

## 🔍 What It Does

- 📸 Pick an image from camera or gallery  
- 🤖 Classify the image as **Dog** or **Cat**  
- 💬 Show confidence percentage  
- 🧠 (Optional) Use bounding boxes if detection is enabled

---

## 🧠 Use Cases

- Pet identification  
- Beginner ML demos  
- Fun classification games

---

## 📸 Sample Screenshots

<div align="center">

<table>
  <tr>
    <td><img src="assets/WhatsApp Image 2025-07-10 at 03.15.49_3a8090ce.jpg" width="220"/></td>
    <td><img src="assets/WhatsApp Image 2025-07-10 at 03.15.49_d726141e.jpg" width="220"/></td>
    <td><img src="assets/WhatsApp Image 2025-07-10 at 03.15.50_5b3a91b4.jpg" width="220"/></td>
  </tr>
  <tr>
    <td><b>Image 1</b></td>
    <td><b>Image 2</b></td>
    <td><b>Image 3</b></td>
  </tr>
</table>

<br/>

<table>
  <tr>
    <td><img src="assets/WhatsApp Image 2025-07-10 at 03.15.50_b22f6536.jpg" width="220"/></td>
    <td><img src="assets/WhatsApp Image 2025-07-10 at 03.15.50_cf3c051e.jpg" width="220"/></td>
  </tr>
  <tr>
    <td><b>Image 4</b></td>
    <td><b>Image 5</b></td>
  </tr>
</table>

</div>


---

## 🛠️ Tech Stack

- **Flutter**
- **Dart**
- **tflite_flutter** or **google_mlkit_image_labeling**
- **image_picker**
- **TensorFlow Lite Model** (dog-vs-cat.tflite)
- Clean UI + State management (Cubit/BLoC/etc.)

---

## 🧪 How It Works

1. Load TFLite model  
2. Pick an image  
3. Preprocess image  
4. Run classification  
5. Show results with label and confidence

---

## ▶️ Getting Started

```bash
git clone https://github.com/yourusername/dog_cat_classifier.git
cd dog_cat_classifier
flutter pub get
flutter run
````

---


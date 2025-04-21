# 📄 Documents.md

## 🔧 Task: Image Patch Extraction

This project processes untrained images using a YOLOv4 model to detect objects (stamps or regions of interest), extracts patches (bounding boxes), and saves them to corresponding directories. It also logs images where patches were not detected.

---

## 🗂️ Project Files

- `extract_patches.py` – Main script to process images and save patches.
- `images_without_patches.txt` – Log file containing names of images with no detected patches.
- `Documents.md` – Project documentation.
- `README.md` – Project summary and usage.

---

## 📦 Dataset Processed

- **Total Images Processed:** ~9000 images
- **Source:** `not_trained_images` directory (local SignDesk path)
- **Output:** Cropped image patches saved under:


---

## 🧠 Model Used

- YOLOv4 (with custom trained weights)
- Custom post-processing layers for bounding boxes
- Inference performed using TensorFlow Keras model loading

---

## 📝 Output Generated

- Extracted patches organized by `stamp_type`
- Log file for images without detections
- Future ready for annotation or retraining

---

## ✨ Contributor

- **Name:** Shahabaz
- **Assisted on:** APIT Project (Rice annotation – 14 images)
- **Tools Used:** Python, OpenCV, TensorFlow, Git, VS Code

---

## 📌 Notes

This task is part of model pipeline preparation and aids in building datasets for further training or validation in object detection tasks.


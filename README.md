# 🛡️ AI Wireless Surveillance System
Acest proiect transformă un smartphone într-o cameră de supraveghere inteligentă cu detecție de obiecte în timp real.

### 🚀 Caracteristici:
**Integrare Hardware:** Folosește telefonul mobil ca senzor video via Iriun Webcam.
* **Computer Vision:** Implementare YOLOv8 pentru detecția persoanelor și obiectelor.
* **Procesare Real-Time:** Flux video wireless procesat local în Python.

### 🛠️ Tehnologii:
* Python 3.11.9
* YOLOv8 (Ultralytics)
* OpenCV
* Iriun Webcam Integration

### 📋 Cum funcționează:
1. Conectează telefonul la PC folosind aplicația Iriun.
2. Rulează scriptul: modelul YOLO va detecta automat persoanele din cadru și va afișa bounding boxes.

# PPE Detection using YOLOv11

Proyek ini bertujuan mengembangkan sistem **deteksi Alat Pelindung Diri (Personal Protective Equipment / PPE)** seperti helm dan rompi keselamatan menggunakan **YOLOv11** dengan dataset custom dari **Roboflow**.

## 🚀 Fitur
- Training model YOLOv11 dengan dataset custom PPE.
- Fine-tuning model dengan 50 epoch untuk hasil optimal.
- Evaluasi performa model menggunakan metrik: Precision, Recall, F1-score.
- Visualisasi hasil training: PR Curve, F1 Curve, Confusion Matrix.
- Prediksi contoh gambar untuk validasi model.

## 🛠️ Teknologi
- Python 3.10+
- [Ultralytics YOLOv11](https://github.com/ultralytics/ultralytics)
- [Roboflow](https://roboflow.com/)
- NumPy, Pandas, Matplotlib

## 📂 Struktur
- `PPE_Detection.ipynb` : Notebook utama untuk training dan evaluasi model.
- `runs/detect/train/` : Hasil training (grafik evaluasi, confusion matrix, hasil prediksi).

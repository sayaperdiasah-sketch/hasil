# Evaluasi Kombinasi Fitur MFCC dan ZCR pada Klasifikasi Suara Pernapasan

Repositori ini berisi hasil eksperimen dan artefak pendukung untuk penelitian:
**"Evaluasi Kombinasi Fitur MFCC dan Zero Crossing Rate dengan GroupKFold pada Klasifikasi Suara Pernapasan"**

## Ringkasan Dataset
- **Sumber**: ICBHI 2017
- **Total Siklus**: 6898
- **Total Pasien**: 126
- **Dimensi Fitur**: 14 (13 MFCC + 1 ZCR)

## Hasil Utama (Random Forest, MFCC+ZCR)
- **Accuracy**: 0.5135
- **F1-Macro**: 0.2655

## Struktur File Hasil
- `final_dataset_summary.csv`: Distribusi kelas siklus pernapasan.
- `final_model_performance.csv`: Hasil lengkap 5-fold GroupKFold (Tabel 1).
- `final_per_class_metrics.csv`: Metrik Precision, Recall, F1 per kelas (Tabel 2).
- `final_statistical_tests.csv`: Hasil uji Wilcoxon signed-rank untuk perbandingan MFCC vs MFCC+ZCR.
- `experiment_environment.txt`: Spesifikasi perangkat dan versi library yang digunakan.

## Cara Reproduksi
Kode sumber lengkap (ekstraksi fitur, pelatihan, evaluasi) tersedia di dalam folder `src/` pada repositori ini.

![image](https://github.com/user-attachments/assets/bf908cd7-869b-4c1b-8fab-e29f18d1a209)

Hasil evaluasi AutoML dengan FLAML menunjukkan performa yang sangat baik pada kedua tugas, yaitu regresi dan klasifikasi. Pada tugas regresi, model terbaik yang dipilih adalah xgb_limitdepth, dengan konfigurasi optimal yang mencakup parameter seperti n_estimators=346, max_depth=2, dan learning_rate=0.181. Model ini berhasil mencapai skor R² sebesar 0.997, yang menunjukkan bahwa model mampu menjelaskan hampir seluruh variansi data target. Nilai MSE sebesar 192.9 juta juga tergolong rendah, menandakan bahwa selisih antara prediksi dan nilai aktual sangat kecil.

Sementara itu, pada tugas klasifikasi, FLAML juga memilih xgb_limitdepth sebagai model terbaik dengan parameter berbeda. Model ini mencapai akurasi sebesar 98.1% dan F1-score sebesar 0.9847, yang menunjukkan performa klasifikasi yang sangat andal dan seimbang, baik untuk kelas mayoritas maupun minoritas. Parameter optimal yang ditemukan mencakup n_estimators=10, max_depth=6, dan learning_rate=0.777, dengan nilai regularisasi yang disesuaikan secara otomatis.

Kedua hasil tersebut memperkuat efektivitas FLAML dalam menemukan konfigurasi model terbaik tanpa campur tangan manual, sehingga sangat efisien untuk eksperimen cepat dan pemodelan dengan performa tinggi.

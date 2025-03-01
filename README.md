# Proyek Akhir: Menyelesaikan Permasalahan Institusi Pendidikan

## Business Understanding
Perusahaan Edutech "Jaya Jaya Institut" menghadapi tantangan dalam meningkatkan tingkat kelulusan siswa dan mengurangi tingkat dropout. Banyak siswa mengalami kesulitan akademik dan finansial yang berdampak pada keberlanjutan studi mereka. Oleh karena itu, diperlukan sistem prediksi dropout yang dapat membantu institusi dalam mengidentifikasi siswa yang berisiko tinggi dan mengambil tindakan pencegahan lebih awal.

### Permasalahan Bisnis
1. Tingginya tingkat dropout siswa yang berdampak pada reputasi institusi.
2. Tidak adanya sistem pemantauan faktor utama yang menyebabkan siswa dropout.
3. Keterbatasan dalam mengidentifikasi siswa yang memerlukan intervensi lebih awal.
4. Kurangnya wawasan tentang bagaimana faktor ekonomi eksternal seperti GDP, inflasi, dan tingkat pengangguran mempengaruhi status akademik siswa.

### Cakupan Proyek
1. Mengembangkan model machine learning untuk memprediksi kemungkinan dropout siswa.
2. Membuat dashboard interaktif untuk memvisualisasikan faktor utama yang mempengaruhi dropout.
3. Mengembangkan sistem berbasis Streamlit untuk mengimplementasikan model prediksi secara real-time.
4. Menganalisis hubungan antara faktor ekonomi dengan status akademik siswa.

### Persiapan

Sumber data: https://github.com/dicodingacademy/dicoding_dataset/blob/main/students_performance

### 1. Install Dependencies (Library)
Sebelum menjalankan proyek ini, pastikan Anda memiliki Python 3.9 atau lebih baru.

## Setup Environment - Anaconda
```
conda create --name myenv python=3.9
conda activate myenv
pip install -r requirements.txt
```
## Setup Environment - Virtual environment biasa
```
python -m venv env
source env/bin/activate  # Untuk Linux/macOS
env\Scripts\activate  # Untuk Windows
pip install -r requirements.txt
```
### 2. Menjalankan jupyter notebook
### 3. Membuka app.py
```
streamlit run app.py
```
### 4. Menginput data yang ingin diprediksi sesuai dengan label yang tertera pada website.
### 5. Mengisi semua data yang diperlukan dan tunggu hingga hasil prediksi keluar.

## Business Dashboard
Dashboard dibuat menggunakan Tableau Public untuk memberikan wawasan mengenai faktor utama yang mempengaruhi dropout. Fitur utama dalam dashboard:
1. Distribusi Status Siswa: Menunjukkan jumlah siswa yang Dropout, Enrolled, dan Graduate.
2. Faktor Utama Penyebab Dropout: Menggunakan Horizontal Bar Chart untuk menampilkan fitur yang paling berkontribusi.
3. Tren Dropout Berdasarkan Waktu: Menampilkan tren dropout siswa dari tahun ke tahun menggunakan Line Chart.
4. Hubungan Faktor Ekonomi dengan Status Siswa: Menggunakan Scatter Plot untuk menunjukkan hubungan antara GDP, tingkat pengangguran, dan inflasi dengan dropout.
🔗 Link Tableau Dashboard: https://public.tableau.com/views/StudentDropout_17408395158730/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

## Menjalankan Sistem Machine Learning
Bisa langsung mengakses streamlit ke sini : https://app-finalprojectdatascience-cjjky7ismjzvinaevtrvsw.streamlit.app/
<img width="677" alt="image" src="https://github.com/user-attachments/assets/6159b4ad-03aa-4c8c-acde-3a3aba6e5d0a" />

### 1. Install Dependencies (Library)
Sebelum menjalankan proyek ini, pastikan Anda memiliki Python 3.9 atau lebih baru.

## Setup Environment - Anaconda
```
conda create --name myenv python=3.9
conda activate myenv
pip install -r requirements.txt
```
## Setup Environment - Virtual environment biasa
```
python -m venv env
source env/bin/activate  # Untuk Linux/macOS
env\Scripts\activate  # Untuk Windows
pip install -r requirements.txt
```
### 2. Menjalankan jupyter notebook
### 3. Membuka app.py
```
streamlit run app.py
```
### 4. Menginput data yang ingin diprediksi sesuai dengan label yang tertera pada website.
### 5. Mengisi semua data yang diperlukan dan tunggu hingga hasil prediksi keluar.

## Conclusion
Proyek ini berhasil mengembangkan sistem prediksi dropout yang dapat membantu institusi pendidikan dalam mengidentifikasi siswa berisiko tinggi. Dengan adanya dashboard bisnis, pihak akademik dapat memahami faktor utama yang mempengaruhi dropout serta hubungan antara kondisi ekonomi dengan status akademik siswa. Sistem ini juga dapat digunakan sebagai alat bantu dalam pengambilan keputusan strategis untuk meningkatkan tingkat kelulusan.

### Rekomendasi Action Items
1. Menggunakan model prediksi secara proaktif untuk mengidentifikasi siswa yang berisiko dropout dan memberikan intervensi yang sesuai.
2. Meningkatkan dukungan finansial bagi siswa yang mengalami kesulitan membayar tuition fees.
3. Meningkatkan layanan akademik dan bimbingan bagi siswa dengan nilai akademik rendah.
4. Melakukan analisis lanjutan terkait hubungan antara faktor ekonomi makro dengan tingkat dropout untuk perencanaan kebijakan pendidikan yang lebih baik.

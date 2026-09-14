# DKA3223_PKV0125KA014
tugasan projek kumpulan (nabilah &amp; syasya)
Projek Aplikasi Computer Vision: Sistem Pengesanan & Klasifikasi

1. Pengenalan Projek (Project Introduction)

Projek ini merupakan sebuah aplikasi Computer Vision (Penglihatan Komputer) yang direkabentuk untuk menganalisis, mengesan, dan mengklasifikasikan objek/imej secara automatik dan masa nyata (real-time).

Objetik Utama:

Membangunkan model Computer Vision yang berprestasi tinggi dan tepat bagi membantu dalam tugasan pengesanan imej.

Menerapkan prinsip etika kepintaran buatan (AI Ethics) dalam keseluruhan kitaran hayat pembangunan model, bermula dari pemprosesan data sehingga penyebaran model (deployment).

Ciri-ciri Utama:

Pengesanan Objek / Pengcaman Imej: Memproses input imej atau strim video secara masa nyata.

Pra-pemprosesan Data: Pembersihan imej, data augmentation, dan normalisasi imej.

Sistem Penilaian: Menjana metrik prestasi seperti Accuracy, Precision, Recall, dan F1-Score.

2. Harta Intelek & Kredit (Attribution & Intellectual Property)

Pembangunan projek ini menghormati dan mematuhi undang-undang harta intelek. Projek ini dibina dengan merujuk kepada sumber terbuka (open-source) dan set data awam berikut:

A. Kod Rujukan & Senibina Model (Reference Code & Architecture)

YOLO / OpenCV / PyTorch Framework: Kod asas dan senibina model diadaptasi daripada repositori rasmi dengan lesen pematuhan.

Sumber: [Ultralytics YOLO / OpenCV / PyTorch GitHub Repository]

Pelesenan: Di bawah lesen kualiti terbuka yang dibenarkan untuk tujuan penyelidikan dan pembangunan.

B. Set Data (Dataset Attribution)

Set data yang digunakan dalam latihan model ini diperoleh daripada sumber awam bersyarat:

Nama Dataset: [Masukkan Nama Dataset, contoh: COCO / Roboflow / Kaggle Dataset]

Penyedia / Pengarang: [Masukkan Nama Pencipta / Organisasi]

Pautan Dataset: [Masukkan URL Dataset]

Lesen Dataset: [Contoh: CC BY 4.0 / Public Domain]

Nota Hak Cipta: Semua hak cipta bagi kod asal, pustaka (libraries), dan set data latihan adalah kekal milik pengarang dan penyedia asal masing-masing. Projek ini memberikan penghargaan sepenuhnya (full attribution) kepada mereka.

3. Etika AI, Limitasi Model, dan Tanggungjawab Pengguna

A. Etika AI (AI Ethics)

Ketelusan (Transparency): Keputusan yang dihasilkan oleh model berasaskan kebarangkalian statistik dan tidak boleh dianggap sebagai kebenaran mutlak tanpa pengesahan manusia (Human-in-the-loop).

Keadilan & Bias (Fairness & Bias): Set data telah disaring bagi mengurangkan kecondongan (bias). Walau bagaimanapun, kecondongan yang wujud dalam set data asal mungkin mempengaruhi hasil pengesanan pada keadaan tertentu.

Privasi Data (Data Privacy): Aplikasi ini tidak menyimpan atau mengumpul maklumat peribadi boleh kenal pasti (Personally Identifiable Information - PII) daripada imej atau video yang diproses tanpa kebenaran pengguna.

B. Limitasi Model (Model Limitations)

Faktor Persekitaran: Prestasi pengesanan mungkin merosot dalam keadaan pencahayaan yang amat gelap, imej kabur (motion blur), atau apabila objek terhalang (occlusion).

Domain Terhad: Model ini dilatih khas untuk kategori objek tertentu sahaja. Pengesanan di luar domain data latihan boleh menghasilkan false positive atau false negative.

Keperluan GPU/CPU: Kelajuan pemprosesan bergantung pada spesifikasi peranti keras yang digunakan.

C. Tanggungjawab Pengguna (User Responsibilities)

Penggunaan Beretika: Pengguna dilarang menggunakan aplikasi ini untuk tujuan penyeliaan tanpa kebenaran (unauthorized surveillance), pencabulan privasi, atau sebarang aktiviti yang melanggar undang-undang tempatan.

Pemeriksaan Manuai: Pengguna bertanggungjawab membuat semakan manual bagi sebarang keputusan kritikal (terutamanya dalam bidang keselamatan, perubatan, atau perundangan).

Penafian (Disclaimer): Pembangun projek ini tidak bertanggungjawab atas sebarang kerugian, kerosakan, atau tindakan undang-undang yang timbul akibat penyalahgunaan aplikasi atau kebergantungan sepenuhnya kepada hasil pengeluaran model AI ini.

4. Cara Penggunaan & Pemasangan (Setup & Installation)

# 1. Clone repositori ini
git clone https://github.com/username/project-cv.git

# 2. Masuk ke direktori projek
cd project-cv

# 3. Pasang persekitaran maya & kebolehan pustaka
python -m venv venv
source venv/bin/activate  # Untuk Linux/macOS
# venv\Scripts\activate   # Untuk Windows

# 4. Pasang keperluan (requirements)
pip install -r requirements.txt

# 5. Jalankan aplikasi
python main.py


5. Lesen (License)

Projek ini dilesenkan di bawah MIT License - lihat fail LICENSE untuk maklumat lanjut.

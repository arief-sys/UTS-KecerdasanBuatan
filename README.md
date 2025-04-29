#  Sistem Pakar Diagnosa Hama Tanaman

Sistem ini membantu petani mendiagnosis jenis hama tanaman berdasarkan gejala yang diamati menggunakan metode **logika berbasis aturan**.

---

##  Penjelasan Sistem

- **Input:** Gejala tanaman (daun menguning, bercak hitam, daun berlubang, tanaman layu).
- **Proses:** Sistem mencocokkan kombinasi gejala dengan aturan logika proposisional.
- **Output:** Diagnosis jenis hama tanaman.

---

##  Aturan Diagnosa

- Daun menguning + Bercak hitam → **Hama Jamur**
- Daun berlubang → **Hama Ulat**
- Daun menguning + Tanaman layu → **Hama Kutu Daun**
- Bercak hitam + Tanaman layu → **Hama Bakteri**

---

##  Contoh Kasus

**Input:**  
✅ Daun menguning  
✅ Tanaman layu  
❌ Bercak hitam  
❌ Daun berlubang  

**Output:**  
➡️ **Hama Kutu Daun**

---

##  Ide Pengembangan

- Integrasi sensor IoT untuk deteksi otomatis.
- Visualisasi diagnosis berbasis web atau mobile.
- Sistem rekomendasi tindakan pengendalian hama.

---




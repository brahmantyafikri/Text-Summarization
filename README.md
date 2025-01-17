# Pengembangan Model Consumer Health Question Summarization

Proyek ini bertujuan untuk mengembangkan model otomatis untuk merangkum pertanyaan kesehatan konsumen dalam bahasa Indonesia menggunakan teknologi *transfer learning*. Dengan memanfaatkan model UnifiedQA-T5, proyek ini menghasilkan ringkasan pertanyaan yang lebih ringkas, relevan, dan terstruktur, untuk mendukung efisiensi sistem *question-answering* di platform telemedicine.

---

## Fitur Utama

1. **Model UnifiedQA-T5**: Menggunakan teknologi *transfer learning* untuk merangkum pertanyaan kesehatan secara otomatis.
2. **Dataset Khusus Bahasa Indonesia**: Dataset diperoleh dari platform telemedicine seperti Alodokter.
3. **Evaluasi Kinerja Model**: Menggunakan metrik ROUGE dan BLEU untuk mengukur relevansi dan akurasi ringkasan.
4. **Preprocessing Data**: Meliputi pembersihan teks, normalisasi, dan penghapusan stopword.
5. **Aplikasi Telemedicine**: Mendukung efisiensi sistem *question-answering* dalam platform kesehatan.

---

## Dataset

Dataset terdiri dari kumpulan pertanyaan kesehatan konsumen dalam bahasa Indonesia yang mencakup:
- Pertanyaan panjang dari pengguna.
- Ringkasan singkat yang relevan dan terstruktur.

Dataset diolah melalui proses berikut:
- **Pembersihan Teks**: Menghapus simbol, tanda baca yang tidak relevan, dan *stopwords*.
- **Normalisasi**: Menstandarkan penulisan teks.
- **Tokenisasi**: Memecah teks menjadi unit-unit yang lebih kecil.

---

## Metodologi

1. **Transfer Learning**: Model UnifiedQA-T5 di-*fine-tune* menggunakan dataset berbahasa Indonesia.
2. **Evaluasi**: Model dievaluasi menggunakan metrik ROUGE-1, ROUGE-2, ROUGE-L, dan BLEU untuk mengukur performanya.
3. **Perbandingan Model**: Melibatkan analisis terhadap performa UnifiedQA-T5 dibandingkan dengan model lain seperti mBart-L dan Seq2Seq.

---

## Hasil Utama

- **Model Terbaik**: UnifiedQA-T5 menunjukkan performa tertinggi dengan akurasi yang diukur menggunakan metrik ROUGE dan BLEU.
- **Aplikasi**: Model dapat diimplementasikan pada sistem telemedicine untuk mempermudah dan menyederhanakan interaksi tanya jawab.

---

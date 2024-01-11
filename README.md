Pengenalan:
Aplikasi Obrolan MultiPDF adalah aplikasi Python yang memungkinkan Anda mengobrol dengan beberapa dokumen PDF. Anda dapat mengajukan pertanyaan tentang PDF menggunakan bahasa alami, dan aplikasi ini akan memberikan tanggapan yang relevan berdasarkan konten dokumen. 
Aplikasi ini menggunakan model bahasa untuk menghasilkan jawaban yang akurat atas pertanyaan Anda. Harap diperhatikan bahwa aplikasi ini hanya akan menjawab pertanyaan yang terkait dengan PDF yang dimuat.

Bagaimana Aplikasi Bekerja:
Aplikasi ini mengikuti langkah-langkah berikut untuk memberikan jawaban atas pertanyaan Anda:

1. Memuat PDF: Aplikasi ini membaca beberapa dokumen PDF dan mengekstrak konten teksnya.

2. Pemenggalan Teks: Teks yang diekstrak dibagi menjadi potongan-potongan kecil yang dapat diproses secara efektif.

3. Model Bahasa: Aplikasi ini menggunakan model bahasa untuk menghasilkan representasi vektor (penyematan) dari potongan-potongan teks.

4. Pencocokan Kemiripan: Ketika Anda mengajukan pertanyaan, aplikasi membandingkannya dengan potongan teks dan mengidentifikasi yang paling mirip secara semantik.

5. Pembuatan Tanggapan: Potongan yang dipilih diteruskan ke model bahasa, yang menghasilkan respons berdasarkan konten PDF yang relevan.


CATATAN: 
Jika ingin run aplikasi ganti API OPENAI TOKEN di file .env menjadi = 
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

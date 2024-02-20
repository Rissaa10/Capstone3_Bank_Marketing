# **BANK MARKETING CAMPAIGN**
## **BUSINESS UNDERSTANDING**

Context
Jenis produk keuangan yang digunakan masyarakat semakin bervariasi. Salah satu produk keuangan yang banyak dikenal masyarakat adalah deposito berjangka. Mekanisme deposito berjangka adalah nasabah menyetorkan sejumlah uangnya ke bank atau lembaga keuangan, dan uang tersebut baru dapat ditarik setelah jangka waktu tertentu. Sebagai imbalannya, nasabah akan diberikan bunga tetap sesuai dengan jumlah nominal uang yang disetorkan.

Meski demikian, sebagai badan usaha yang memiliki produk keuangan dan nasabah masing-masing, bank tetap harus bersaing agar tidak kehilangan nasabah. Salah satu cara untuk mendapatkan pelanggan baru adalah dengan melakukan kampanye pemasaran. Target :

0 : Tidak deposit

1 : Deposit

Problem Statement

Proses campaign penawaran deposit memakan waktu dan biaya, Bank ingin melakukan efisiensi proses campaign dengan menargetkan ke calon nasabah yang memiliki potensi untuk menaruh deposit.

Goals

Berdasarkan problem tersebut, bank ingin memiliki kemampuan untuk memprediksi kemungkinan kandidat nasabah untuk yang ingin melakukan deposit atau tidak, sehingga dapat menargetkan campaign pada kandidat yang memiliki potensial melakukan deposit

Analytic Approach

Kita akan menganalisis data untuk menemukan pola yang membedakan kandidat nasabah yang akan melakukan deposit atau tidak.

Kemudian, dilanjutkan dengan membangun model klasifikasi yang akan membantu bank untuk dapat memprediksi probabilitas seorang kandidat nasabah akan/ingin melakukan deposit atau tidak.

Evaluation Metric

Type 1 error : False Positive
Konsekuensi: membuang waktu dan biaya campaign untuk nasabah yang tidak berpotensial menaruh deposit

Type 2 error : False Negative
Konsekuensi: kehilangan kandidat nasabah potensial

Berdasarkan konsekuensinya, maka sebisa mungkin akan dibuat model yang dapat mengurangi cost campaign dari bank, tetapi tanpa membuat menjadi kurangnya kandidat nasabah potensial yang dicari oleh bank. Jadi kita ingin sebanyak mungkin prediksi kelas positif yang benar, dengan sesedikit mungkin prediksi false positive. Sehingga yang akan kita gunakan adalah F1 Score.

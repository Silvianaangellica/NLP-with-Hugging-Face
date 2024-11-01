<p align="center">
    <h1>NLP With HuggingFace Transformers</h1>
</p>

Berisikan mengenai pipeline menggunakan library `Transformers` untuk keperluan pemodelan, seperti:

- Zero-Shot-Classification
- Text-Generation
- Fill-Mask
- Named Entity Recognition (NER)
- Question Answering
- Sentiment Analysis
- Summarizer
- Translated Text


## Bahasa yang digunakan :
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)


## Tools yang digunakan :
![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)


---

## <p align="center">Analisis Berdasarkan Kode.ipynb</p>

Menurut saya, **Zero-Shot-Classification** adalah salah satu versi terbaik karena memungkinkan pengguna untuk menginput teks dan label secara manual, tanpa harus memodifikasi kode awal. Setelah kode di-run, pengguna hanya perlu memasukkan teks dan label yang diinginkan.

Selain itu, **Question Answering** juga sangat fleksibel. Dalam versi ini, pengguna dapat memasukkan konteks manual, seperti cerita atau biodata, dan setelahnya dapat menginput pertanyaan secara manual. Proses dapat dilanjutkan beberapa kali hingga selesai dengan hanya memasukkan "exit" tanpa perlu menjalankan ulang kode.

---

### Zero-Shot-Classification

Zero-Shot-Classification adalah tugas di mana model diminta untuk mengklasifikasikan teks ke dalam kategori yang belum dilatih secara eksplisit selama fase pelatihan awal. Model menganalisis teks dan membandingkan makna teks input dengan makna label kandidat yang disediakan. Serta termasuk klasifikasi seluruh kalimat.

### Text-Generation

Text-Generation adalah tugas untuk membuat konten teks baru secara otomatis dengan bantuan model AI. Model `distilgpt2` digunakan sebagai model bahasa serba guna yang dilatih pada berbagai teks dan kode yang sangat beragam. Serta termasuk membuat konten teks otomatis.

### Fill-Mask

Fill-Mask menggunakan model bahasa yang telah dilatih sebelumnya untuk memprediksi kata-kata yang hilang dalam kalimat. Model menerima kalimat dengan spasi kosong dan memprediksi kata yang paling mungkin untuk diisi. Serta termasuk membuat konten teks otomatis.

### Named Entity Recognition (NER)

NER (Named Entity Recognition) adalah tugas yang melibatkan identifikasi dan klasifikasi entitas tertentu dalam teks, seperti nama orang, lokasi, dan lainnya. Serta termasuk klasifikasi setiap kata.

### Question Answering

Question Answering adalah tugas di mana sistem diberi pertanyaan dan konteks untuk menemukan jawaban di dalam teks. Model menggunakan loop untuk menghasilkan jawaban; jika "exit" dimasukkan, maka loop berhenti.Serta termasuk ekstraksi jawaban dari teks.

### Sentiment Analysis

Sentiment Analysis digunakan untuk menentukan nada emosional di balik suatu teks. Termasuk klasifikasi seluruh kalimat.

### Summarizer

Summarizer adalah proses merangkum teks menggunakan pustaka `Transformers`, menciptakan kalimat baru yang lebih ringkas dari teks masukan. Termasuk membuat ringkasan dari teks input.

### Translated Text

Translated Text adalah fungsi yang melakukan penerjemahan, seperti dari bahasa Jepang ke bahasa Italia. Termasuk membuat teks baru dari teks input dalam bahasa berbeda
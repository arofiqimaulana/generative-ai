
# 📘 Generative AI Overview

Generative AI adalah cabang dari kecerdasan buatan yang bertujuan untuk menciptakan data baru yang mirip dengan data asli berdasarkan pola yang dipelajari dari data tersebut. Teknologi ini telah digunakan dalam berbagai aplikasi seperti pembuatan gambar, video, musik, dan teks. Generative AI memungkinkan mesin untuk tidak hanya memahami data tetapi juga untuk menciptakan sesuatu yang baru dan kreatif.

## Bahan Ajar

## 🔍 Daftar Algoritma Generative AI

### 📌 Generative Adversarial Networks (GAN)
Generative Adversarial Networks (GAN) adalah jenis model generatif yang melibatkan dua jaringan saraf: generator dan discriminator. Generator mencoba membuat data yang menyerupai data asli, sementara discriminator mencoba membedakan antara data asli dan data yang dihasilkan oleh generator. Proses ini terjadi secara bersaing, sehingga keduanya saling meningkatkan kemampuan mereka.
- **Variasi:** DCGAN, CycleGAN, StyleGAN

### 📌 Variational Autoencoders (VAE)
Variational Autoencoders (VAE) adalah jenis autoencoder yang menggunakan teknik probabilistik untuk menghasilkan data baru. VAE bekerja dengan mempelajari distribusi data dan menghasilkan sampel baru dari distribusi tersebut. Ini memungkinkan pembuatan data yang lebih bervariasi dibandingkan dengan autoencoder standar.
- **Aplikasi:** Generasi gambar, rekonstruksi data

### 📌 Transformer-based Models (GPT, BERT)
Model berbasis Transformer seperti GPT (Generative Pretrained Transformer) dan BERT (Bidirectional Encoder Representations from Transformers) telah merevolusi bidang pemrosesan bahasa alami (NLP). Model-model ini dapat menghasilkan teks yang sangat realistis berdasarkan input yang diberikan, dan juga digunakan untuk berbagai aplikasi seperti pembuatan konten otomatis dan pemahaman bahasa.
- **GPT** (seperti GPT-3) adalah model autoregresif yang menghasilkan teks dengan cara melengkapi atau melanjutkan teks yang dimulai oleh pengguna.
- **BERT** digunakan lebih banyak untuk pemahaman bahasa dan bukan untuk generasi, namun variasi seperti T5 (Text-to-Text Transfer Transformer) dan GPT-3 digunakan untuk generasi teks.

### 📌 Recurrent Neural Networks (RNN) dan LSTM
RNN dan LSTM (Long Short-Term Memory) dapat digunakan untuk generasi urutan data seperti teks atau musik. RNN mengingat informasi dari urutan sebelumnya dan menghasilkan data berdasarkan urutan tersebut. LSTM, sebagai perbaikan dari RNN, lebih efektif dalam menangani masalah *vanishing gradient*, membuatnya lebih cocok untuk generasi data yang lebih panjang atau kompleks.
- **Aplikasi:** Generasi teks, musik, dan urutan waktu

### 📌 Diffusion Models
Diffusion models adalah algoritma generatif yang melibatkan pengenalan proses difusi probabilistik untuk menghasilkan data. Mereka bekerja dengan memulai dari data noise yang kemudian diubah secara bertahap untuk menghasilkan data yang lebih terstruktur, mirip dengan data asli. Diffusion models telah menunjukkan hasil yang mengesankan dalam menghasilkan gambar realistis.
- **Aplikasi:** Generasi gambar dan suara

### 📌 Neural Style Transfer
Neural Style Transfer adalah teknik yang memungkinkan kita untuk mengubah gaya gambar dengan memadukan konten dari satu gambar dengan gaya dari gambar lain. Ini menggunakan convolutional neural networks (CNNs) untuk mengekstraksi fitur dari kedua gambar dan menghasilkan gambar baru yang menggabungkan keduanya.
- **Aplikasi:** Pengolahan gambar, seni digital

### 📌 Flow-based Models
Flow-based models menggunakan transformasi yang dapat dibalik untuk menghasilkan data. Berbeda dengan GAN dan VAE, yang menggunakan pendekatan probabilistik, flow-based models menghasilkan data dengan cara yang lebih deterministik. Model-model ini memungkinkan pemodelan distribusi data secara eksplisit dan dapat menghasilkan sampel dari distribusi tersebut.
- **Aplikasi:** Generasi data dan kompresi

### 📌 Deep Dream
Deep Dream adalah algoritma generatif yang dikembangkan oleh Google untuk menghasilkan gambar yang menarik atau surreal dengan cara meningkatkan pola yang dikenali oleh jaringan saraf. Deep Dream bekerja dengan memodifikasi gambar untuk menonjolkan fitur-fitur tertentu, menciptakan efek visual yang unik dan aneh.
- **Aplikasi:** Seni generatif, eksperimen visual

## 🛠️ Tools dan Library Populer untuk Generative AI

- **TensorFlow** – Framework deep learning untuk membangun model generatif.
- **PyTorch** – Framework deep learning yang banyak digunakan untuk penelitian dan pengembangan model generatif.
- **OpenAI GPT** – API untuk menghasilkan teks, kode, dan bahkan gambar dengan menggunakan model GPT-3.
- **Hugging Face** – Platform dengan berbagai model pre-trained seperti GPT-2, BERT, T5 untuk generasi teks dan pemrosesan bahasa alami.
- **NVIDIA StyleGAN** – Framework untuk generasi gambar dengan menggunakan GANs.

## 📚 My Notes
- [Attention In Transformers](https://www.canva.com/design/DAGthEqvgFA/7Oy0t6uQ5mlSXuwBWbBS_A/edit)

## 📚 Referensi Belajar
- [Generative Deep Learning by David Foster](https://www.oreilly.com/library/view/generative-deep-learning/9781492041914/)
- [Hugging Face Documentation](https://huggingface.co/docs)
- [OpenAI GPT-3](https://beta.openai.com/docs/)
- [DeepAI - Generative Models](https://deepai.org/machine-learning-model/generative-models)
- [NVIDIA GAN](https://developer.nvidia.com/generative-adversarial-networks)


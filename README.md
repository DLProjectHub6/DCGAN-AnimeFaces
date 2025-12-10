<h1 align="center">👋 Welcome to DCGAN AnimeFaces</h1>

<p align="center">
  <img src="outputs/logo.png" alt="DCGAN AnimeFaces Logo" width="180">
</p>

<h2 align="center">🎨 Generate Anime Faces with Deep Convolutional GAN (DCGAN)</h2>

<p align="center">
  <img src="outputs/sample_banner.png" alt="DCGAN AnimeFaces Banner" width="85%">
</p>

<p align="center">
  <b>DCGAN AnimeFaces</b> adalah proyek Deep Learning yang memanfaatkan 
  <b>Deep Convolutional Generative Adversarial Network (DCGAN)</b> untuk 
  menghasilkan wajah anime baru secara otomatis.  
  <br><br>
  Proyek ini juga dilengkapi dengan <b>Random Search Hyperparameter Optimization</b> 
  guna menemukan konfigurasi training terbaik sehingga model lebih stabil dan 
  mampu menghasilkan gambar berkualitas.
</p>

---

## ✨ Key Features

### 🔹 1. Anime Face Generation (DCGAN)
Model menghasilkan gambar wajah anime beresolusi **64×64 px** dari latent noise acak menggunakan arsitektur DCGAN yang telah dioptimalkan.

---

### 🔹 2. Random Search Hyperparameter Optimization
Mencari kombinasi hyperparameter terbaik untuk meningkatkan kualitas generasi gambar, meliputi:

- Learning Rate  
- Optimizer β1  
- Latent Dimension  

Pendekatan ini membantu model mencapai proses pelatihan yang lebih stabil serta mengurangi risiko **mode collapse**.

---

### 🔹 3. Stable Training Pipeline
Proyek menyediakan pipeline pelatihan yang rapi dan terstruktur, mencakup:

- Visualisasi tren loss  
- Auto-checkpoint  
- Grid sampling otomatis  
- Pembuatan GIF progres training  

---

### 🔹 4. Clean, Modular, Beginner-Friendly Notebook
Notebook dirancang agar mudah dipahami dan dipelajari.

---

# 👋 Welcome To DCGAN AnimeFaces
## 🎨 Generate Anime Faces With Deep Convolutional Generative Adversarial Network (DCGAN)

DCGAN AnimeFaces adalah proyek Deep Learning yang memanfaatkan  
**Deep Convolutional Generative Adversarial Network (DCGAN)**  
untuk menghasilkan wajah anime baru secara otomatis.

Proyek ini juga dilengkapi dengan  
**Random Search Hyperparameter Optimization**  
untuk menemukan konfigurasi training terbaik sehingga model lebih stabil  
dan mampu menghasilkan gambar berkualitas.

---

## 👥 Kelompok 6 Mata Kuliah Deep Learning

| **Nama**                                | **NPM**           |
|:---------------------------------------:|:-----------------:|
| Reza Putri Angga                        | 22083010006       |
| Larasati                                | 22083010018       |
| Muhammad Azkiya Akmal                   | 22083010084       |
| Vira Amalia Zahrani                     | 22083010098       |
| R. Taufik Utomo Iswanindra Kusuma       | 22083010108       |

---

## ✨ Key Features

### 🔹 1. Anime Face Generation (DCGAN)
Model menghasilkan gambar wajah anime beresolusi **64×64 px** dari latent noise acak menggunakan arsitektur DCGAN yang telah dioptimalkan.

### 🔹 2. Random Search Hyperparameter Optimization
Mencari kombinasi hyperparameter terbaik untuk meningkatkan kualitas generasi gambar, meliputi:

- Learning Rate  
- Optimizer β1  
- Latent Dimension  

Pendekatan ini membantu model mencapai proses pelatihan yang lebih stabil serta mengurangi risiko **mode collapse**.


### 🔹 3. Stable Training Pipeline
Proyek menyediakan pipeline pelatihan yang rapi dan terstruktur, mencakup:

- Visualisasi tren loss  
- Auto-checkpoint  
- Grid sampling otomatis  
- Pembuatan GIF progres training  

### 🔹 4. Clean, Modular, Beginner-Friendly Notebook
Notebook dirancang agar mudah dipahami dan dipelajari.

---
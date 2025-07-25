# Brain Activity Image Reconstruction

This project explores the use of deep learning to reconstruct visual images directly from brain activity data (fMRI). It was completed as part of the *Deep Learning and Neural Networks* module at Sheffield Hallam University.

---

## 📌 Objectives

- Build an autoencoder to compress and reconstruct visual images
- Design a brain decoder to map fMRI signals to the image feature space
- Train both models on the Algonauts 2023 dataset
- Evaluate the quality of image reconstructions using quantitative and visual metrics

---

## 🛠️ Tools & Libraries

- Python
- TensorFlow, Keras
- NumPy, Pandas, SciPy
- Matplotlib, Seaborn
- Scikit-learn
- Nibabel (for neuroimaging data)

---

## 🧠 Model Architecture

1. **Autoencoder**
   - Encoder: CNN layers → ReLU activations
   - Decoder: Transposed convolutions for reconstruction
   - Loss Function: Mean Squared Error (MSE)

2. **Brain Decoder**
   - Maps fMRI data to the autoencoder’s latent space
   - Loss Function: Cosine Embedding Loss (CEL)
   - Enables generation of images directly from brain signals

---

## 📈 Evaluation Metrics

- Mean Squared Error (MSE)
- Structural Similarity Index (SSIM)
- Visual comparison between original and reconstructed images
- Latent space interpretation

---

## 📂 How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/your-username/brain-image-reconstruction-dnn.git
   cd brain-image-reconstruction-dnn
   
2.Install dependencies:
  pip install -r requirements.txt

3.Open the notebook:
  jupyter notebook DNN_33085799-2.ipynb

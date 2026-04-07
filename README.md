# Gen-Ai-Challenge

This is a three-part generative AI framework exploring the intersection of structural architecture and neural fashion synthesis.

---

## 📂 Project Structure & Challenges

### Challenge 1: Foundation and Environment
* **Objective:** Environment configuration and initial data exploration.
* **Technical Focus:** Setting up high-performance compute (GPU T4 x2) and establishing a robust data pipeline for large-scale image processing and augmentation.

### Challenge 2: Neural Fashion Collection
* **Objective:** Synthesizing a 5-look cohesive garment collection using custom deep learning models.
* **Methodology:** * Developed a **Deep Convolutional GAN (DCGAN)** and a **Variational Autoencoder (VAE)** from scratch using TensorFlow/Keras.
    * Implemented structural grayscale preprocessing to eliminate color noise and force the models to learn geometric silhouettes.
    * Utilized **Latent Space Interpolation** to ensure "DNA consistency" and morphological transitions across the generated fashion looks.
* **Result:** A mathematically unified digital capsule collection that prioritizes architectural form over fast-fashion trends.

### Challenge 3: AI-Driven Media Design
* **Objective:** Designing a professional promotional poster for an exclusive runway event.
* **Tools:** `Stable Diffusion v1.5` for base visual generation; **Python (PIL)** for programmatic graphic design and refinement.
* **Design Strategy:**
    * Generated architectural backgrounds to match the brutalist aesthetic established in Challenge 2.
    * Applied automated image refinement (luminance grading and editorial framing) via custom Python scripts.
    * Programmed a hierarchical typographic layout to produce a high-fidelity, market-ready final asset.

---

## 🛠️ Technical Stack

| Category | Tools & Libraries |
| :--- | :--- |
| **Deep Learning** | TensorFlow, Keras, PyTorch, Hugging Face Diffusers |
| **Generative Models** | DCGAN, VAE, Stable Diffusion v1.5 |
| **Image Processing** | OpenCV, PIL (Pillow) |
| **Data & Visualization** | NumPy, Matplotlib |
| **Compute Environment** | Kaggle GPU T4 x2 / Linux |

---

## 🧠 Approach & Methodology

1. **Strategic Data Constraint:** By limiting the visual palette to high-contrast grayscale, the models prioritized structural integrity over color-mapping, creating a unique "Brutalist Noir" brand identity.
2. **Adversarial Optimization:** Utilizing DCGANs allowed for significantly higher edge-fidelity in garment generation compared to standard generative approaches.
3. **Reproducible Design:** The final poster was rendered entirely via Python code rather than traditional GUI tools. This ensures the entire creative workflow is reproducible, version-controlled, and scalable.

---

## 🏁 Final Deliverables

* **Fashion Collection:** Located in the `outputs/collection/` directory.
* **Event Poster:** Standalone high-resolution file: `Final_AI_Poster.png`.
* **Source Code:** Fully documented `.ipynb` notebooks for both the GAN training and the Poster Design pipeline.

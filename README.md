# UIA-Erasmus
## Erasmus @ UiA — Master’s in Computer Science (Aug–Dec 2024)

Notes, assignments, mini-projects, and study materials from my Erasmus semester at  
**University of Agder (UiA), Grimstad, Norway** — Master’s in **Computer Science**.

> 📅 **Timeline:** August 2024 → December 2024  
> 🏫 **Campus:** UiA Grimstad  
> 🗣️ **Language:** English

---

## Repository Structure

This repo hosts content for three courses I took at UiA. Each folder contains lab work and project material.


There was also a fourth course with its own dedicated repository:

- **Programming and Software Development** → 👉 [Link to the separate repository](https://github.com/ZattiAndrea/Sloot_Zatti_MAS417)

---

## Courses

### 1) AI-Mathematics
A collection of worked notes and mini-reports that connect core math to practical ML.
- Survey and hands-on comparisons of **Gradient Descent variants** (SGD, Mini-Batch, Momentum, RMSProp, Adam) with discussion of convergence, robustness, and scalability. :contentReference[oaicite:0]{index=0}
- Applied **convex optimization** case study: proactive thermal/frequency control for MPSoCs (“Pro-Temp”) with constraints and objective formulation, plus takeaways from the experimental results. :contentReference[oaicite:1]{index=1}
- **Missing data** strategies in longitudinal studies: MCAR/MAR/MNAR, with **Expectation-Maximization** and **Multiple Imputation** as preferred methods. :contentReference[oaicite:2]{index=2}
- **Linear algebra refreshers**: eigenvalues/eigenvectors proofs with worked examples. :contentReference[oaicite:3]{index=3}

📂 See: [`/AI-Mathematics`](./AI-Mathematics)

---

### 2) Deep Neural Network
Assignments spanning classical ML, modern deep learning, and a final project.
- Implemented **KNN from scratch** on the Pima Indians Diabetes dataset, including scaling, tie-handling discussion, and **k** selection via multiple metrics. :contentReference[oaicite:4]{index=4}
- Built a custom **MLP** (and PyTorch version) for E. coli class classification; ~**100% accuracy** with Sigmoid activations and momentum. :contentReference[oaicite:5]{index=5}
- **CNN image classification** on Food-11; baseline vs. transfer learning:
  - **ResNet18** with augmentation reached ~**83% test accuracy**; VGG16 and a small custom CNN (“FoodNet”) lagged (~15%). Early stopping implemented. :contentReference[oaicite:6]{index=6}
- **Object detection & instance segmentation** with **Faster R-CNN/Mask R-CNN** on the Balloon dataset; reported **precision 0.82**, **recall 0.86**, **F1 0.81**. :contentReference[oaicite:7]{index=7}
- **RNN/LSTM** tag classifier on Stack Overflow Q&A (top-40 tags), including heavy class imbalance; achieved **accuracy 0.57**, **precision 0.82**, **recall 0.72**, **F1 0.74**. :contentReference[oaicite:8]{index=8}
- **Denoising task**: remove synthetic “date-stamp” noise using an **Autoencoder**, a **GAN** (generator/discriminator design), and a **Diffusion** approach; includes data pipeline and qualitative comparisons. :contentReference[oaicite:9]{index=9}
- **Final project (audio)**: experiments with **Wav2Vec2.0** and a **CNN (EfficientNetV2)**; training setups and comparative evaluations are documented. :contentReference[oaicite:10]{index=10}

📂 See: [`/DeepNeuralNetwork`](./DeepNeuralNetwork)

---

### 3) Generative Programming
A DSL project for **Petri Nets** using **JetBrains MPS**.
- Language supports **places, transitions, tokens**, and arc connections; editor syntax for line-based modeling. :contentReference[oaicite:11]{index=11}
- New features: **inline line comments** (with constraint override), **test suite fixes + new tests** for comment handling, and **documentation overhaul** (README/manual migrated to GitHub Issues workflow). :contentReference[oaicite:12]{index=12}
- **External visualization export**: text generation to `.apt` for an online Petri-net tool; pipeline from model → file → rendered graph. :contentReference[oaicite:13]{index=13}
- **Runtime attempt**: MPS plugin to “Run Petrinet”; core logic works but **initialization issues** prevent full execution—next steps and limitations are discussed. :contentReference[oaicite:14]{index=14}

📂 See: [`/GenerativeProgramming`](./GenerativeProgramming)

---


## Academic Notes

- Material reflects **my personal learning** during the Erasmus period at UiA (Aug–Dec 2024).
- Course names and folder names match UiA’s topics taken on campus in **Grimstad**.

---

## License

Unless otherwise noted, content in this repository is released under the **MIT License**.  
If you reuse material, please include attribution.

---

## Acknowledgements

Thanks to the **University of Agder (UiA)** faculty and classmates in the Computer Science master’s program for the guidance and collaboration throughout the semester.

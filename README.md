# PhD Research Portfolio: NIR Spectroscopy & Deep Learning in AgTech

Welcome to my doctoral research repository. This space showcases the software frameworks, preprocessing optimization pipelines, and hybrid deep learning models developed during my PhD at Aliah University, Kolkata, focused on automated food safety and agricultural diagnostics.

---

## 📄 Core Publications & Architectural Implementations

### 1. AdBand-CTNet: A Hybrid Convolution Transformer Framework for Precise NIR-Based Determination of 1,8-Cineole in Large Cardamom
* **Journal:** Journal of Chemometrics (Published)
* **Core Contribution:** Developed a novel, hybrid 1D Convolution-Transformer network featuring a differentiable adaptive band selection (ABS) module that optimizes wavelength selection via gradient descent.
* **Framework Status:** Code optimization and model weights are currently undergoing documentation cleanup for open-source release.

### 2. Regression-Based Prediction of Piperine Content in Black Pepper Using Near Infrared Spectroscopy
* **Journal:** Journal of Near Infrared Spectroscopy (Published)
* **Core Contribution:** Implemented standard scatter corrections (SNV/MSC) paired with machine learning regression (SVR, XGBoost, Random Forest) to non-destructively predict chemical concentrations, benchmarked against gold-standard RP-HPLC data.

### 3. Prediction of Tartrazine Adulteration in Turmeric Powder Using NIR Spectroscopy and Machine Learning Algorithms
* **Conference:** IEEE Presentation (Published)
* **Core Contribution:** Fused Principal Component Analysis (PCA) for matrix dimensionality reduction with Linear Discriminant Analysis (LDA) to classify toxic dye contamination thresholds.

### 4. Regression Based Prediction of 1,8-Cineole Concentration in Large Indian Cardamom Using Near Infrared Spectroscopy
* **Book Chapter:** Springer Publication (Published)
* **Core Contribution:** Evaluated dataset uniformity techniques using jitter-based augmentation and z-score scaling across samples harvested from six distinct agro-climatic zones.

---

## 🛠️ Software Pipeline & Preprocessing Modules
The upcoming code release provides standardized Python classes for the following spectral treatment pipelines:
* **Scatter Adjustment:** Standard Normal Variate (SNV) & Multiplicative Scatter Correction (MSC).
* **Smoothing & Numerical Differentiation:** Savitzky–Golay filters (1st and 2nd order derivatives).
* **Dimensionality Reduction:** Principal Component Analysis (PCA) & Unsupervised K-Means clustering.

---

## ⚠️ Codebase Release Status
The underlying production scripts are currently being cleaned, heavily commented, and checked for formatting under institutional publication guidelines. Fully functional code files, example CSV datasets, and Jupyter notebook tutorials will be populated directly into this repository shortly.

## 📬 Contact
* **Author:** Sk Habibur Rahaman (Assistant Professor & PhD Scholar)
* **Email:** skhabiburrahaman27@gmail.com

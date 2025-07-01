# 🔬 Acoustic Data-based Characterization of Incipient Boiling for Space Applications

**Authors:** Andrew Martinez, Krishnanshu Gupta, James Lamkin, Zachary Weinfeld  
**Affiliation:** Cal Poly San Luis Obispo – Data Science Department  
**In Collaboration With:** NASA  
**Presented at:** SDSS (Symposium on Data Science & Statistics)

## 📄 Paper
[Click here to view the full paper (PDF)](./AcousticSpaceBoilingPaper.pdf)

## 📘 Abstract
In partnership with NASA, this research develops a machine learning framework to detect early-stage boiling in cryogenic fuel tanks based on **acoustic data**. By identifying unique boiling signatures using unsupervised learning techniques and signal processing, the system improves on the responsiveness of existing thermal sensor-based methods, which often fail to detect incipient boiling in microgravity.

## 🛠️ Methods & Technologies
- **Signal Processing:** Time-domain peak detection using dynamic thresholding
- **Feature Engineering:** Derived 15+ features from both time and spectral domains
- **ML Pipeline:** 
  - Dimensionality Reduction (PCA)
  - Unsupervised Learning (KMeans Clustering)
- **Spectral Analysis:** FFT, Butterworth filters, and Welch’s method
- **Visualization:** Web application with interactive 2D/3D scatter plots and time-domain comparisons

## 🧠 Key Contributions
- Built a feature-rich acoustic pipeline to detect boiling regimes in microgravity.
- Achieved improved classification of **quasi-homogeneous** vs. **heterogeneous** boiling behavior.
- Developed a user-facing web app that enables NASA researchers to:
  - Visualize PCA results and clusters interactively
  - Compare time-series waveforms between clusters
- Proposed future extensions including Poisson mixture models to detect overlapping regimes.

## 🛰️ Why This Matters
Current methods in spacecraft rely heavily on thermal sensors, which lack precision in early boiling detection. This work provides a **real-time, non-intrusive alternative** that enhances cryogenic fluid safety and stability—crucial for long-duration spaceflight.

## 📈 Visuals
- See [Page 2](./AcousticSpaceBoilingPaper.pdf) for experimental setup diagram
- See [Page 4](./AcousticSpaceBoilingPaper.pdf) for PCA scree plot
- See [Page 6](./AcousticSpaceBoilingPaper.pdf) for 3D clustering visualizations

## 🧪 Technologies Used
- Python (SciPy, NumPy, scikit-learn, matplotlib)
- MATLAB (signal processing)
- Dash (web visualization)
- Docker

---

📫 For questions or collaboration inquiries, feel free to reach out:  
**Andrew Martinez** – amart531@calpoly.edu

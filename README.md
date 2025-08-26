
# Stats4Cosmology

A curated collection of **Jupyter notebooks** introducing and applying statistical 
methods to problems in **cosmology**.  

The aim of this repository is to provide practical, hands-on examples for students 
and researchers who want to learn how to use statistics in the context of cosmological 
data analysis, model comparison, and forecasting.

---

## ✨ Contents

- **Probability & Statistics Refresher**  
  Basics of probability distributions, likelihoods, and Bayes' theorem.  

- **Bayesian Inference in Cosmology**  
  MCMC, nested sampling, and posterior exploration applied to toy cosmological models.  

- **Fisher Forecasting**  
  Deriving Fisher matrices and using them to forecast cosmological parameter constraints.  

- **Likelihoods for Cosmology**  
  Building Gaussian and non-Gaussian likelihoods, connecting with cosmological data vectors.  

- **Applications**  
  - Toy CMB & LSS parameter estimation  
  - Combining multiple probes  
  - Impact of priors and parameter degeneracies  

---

## 🚀 Getting Started

Fork this repository:

```bash
git clone https://github.com/your-username/Stats4Cosmology.git
cd Stats4Cosmology
```

Launch Jupyter Lab or Notebook:

```bash
jupyter lab
```

Open any notebook under the `tutorials/` folder and start exploring.

---

## 📚 Typical Dependencies

The notebooks rely on standard scientific Python libraries widely used in astronomy and cosmology:

- [`numpy`](https://numpy.org/) – numerical computing and arrays  
- [`scipy`](https://scipy.org/) – scientific routines (optimization, integration, stats)  
- [`astropy`](https://www.astropy.org/) – astronomy & cosmology utilities (units, constants, cosmology tools)  
- [`seaborn`](https://seaborn.pydata.org/) – statistical visualization  
- [`matplotlib`](https://matplotlib.org/) – plotting  
- [`jupyter`](https://jupyter.org/) – interactive notebooks  
- [`emcee`](https://emcee.readthedocs.io/) or [`ultranest`](https://johannesbuchner.github.io/UltraNest/) – Bayesian inference (optional, for MCMC examples)  


---

## 🧑‍🏫 Who Is This For?

- **Students** in astrophysics, physics, or statistics who want to learn 
  about cosmological inference.  
- **Researchers** looking for ready-to-use templates for teaching, 
  lectures, or quick experimentation.  
- **Educators** who want examples for cosmology and data science courses.  

---

## 👩‍🚀 Author

Developed and maintained by **Guadalupe Cañas-Herrera**, with inspiration from real-world cosmological pipelines in the era of **Euclid**, **LSST**, and **CMB-S4**.  

---

## 📄 License

This project is licensed under the MIT License.  
See the [LICENSE](LICENSE) file for details.

---

## ⭐ Citation

If you find these notebooks useful in your research or teaching, please cite:

```bibtex
@misc{stats4cosmology,
  author       = {Cañas Herrera, Guadalupe},
  title        = {Stats4Cosmology: Jupyter notebooks for statistical methods in cosmology},
  year         = {2025},
  howpublished = {\url{https://github.com/gcanasherrera/Stats4Cosmology}}
}
```

# IO_decorrelation_paper

**Welcome to the IO_decorrelation_paper repo.**  
Here you'll find the core analysis code and data supporting our study on how input and output representations in the olfactory bulb are transformed to support odour decorrelation and improved discriminability.

**Decorrelation by gain control in the mouse olfactory bulb**  
([preprint link])

---

## 🔎 The story

How does the olfactory bulb transform sensory input from olfactory sensory neurons into a more informative representation?  
In this study, we compared input and output activity patterns across matched glomerular fields to reveal how the bulb reshapes odour representations.

To do this, we combined:

- **Two-photon calcium imaging** of OSN input (OMP-GCaMP6f) and mitral/tufted cell output (Tbet-GCaMP6f) across matched dorsal OB fields,  
- **A computational model** of the OB input–output transformation to explore candidate circuit motifs,  
- **Comparative analysis** of correlation structures and decoding performance across representations.

### Key findings

- 📉 **Output representations are decorrelated** relative to inputs, enhancing odour discriminability.  
- 🧩 This decorrelation arises primarily from **diagonal gain adjustments**, not broad lateral inhibition.  
- 🧠 Recordings from MTC somata confirmed that decorrelation is **preserved across layers and independent of brain state**.  
- 🧮 A simple linear model with **inference-like diagonal structure** reproduces the observed transformations.  

Together, these results suggest that the olfactory bulb implements efficient inference-like computations to shape odour representations.

---

## 👩‍💻 Getting started

Clone this repository:

```bash
git clone https://github.com/ackels-lab/IO_decorrelation_paper.git
```

Download datasets from our Zenodo archive:
👉 https://zenodo.org/records/XXXXX

Create a conda environment with the required dependencies:
conda create -n ob_io_env python=3.9 numpy pandas scipy matplotlib seaborn jupyter scikit-learn
conda activate ob_io_env

Update file paths in scripts/analysis_main.py according to your local directory structure.

Run the main analysis notebook to reproduce the results for key panels of the main figures.
(Additional scripts and figure panels will be released after peer review.)


🙌 Acknowledgements

This work was supported by the Francis Crick Institute, University College London, and the University of Bonn, and benefited from discussions with colleagues in physiology, systems neuroscience, and computational modeling.
Please refer to the manuscript for full author contributions and funding details.

☎️ Contact

For questions, data access, or collaboration inquiries, contact:

Tobias Ackels – tobias.ackels@ukbonn.de

Andreas T. Schaefer – andreas.schaefer@crick.ac.uk

Sina Tootoonian – sina.tootoonian@crick.ac.uk

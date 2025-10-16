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

Set up the environment using the provided environment.yml file:
```bash
conda env create -f environment.yml
conda activate ob_io_env
```

Start Jupyter Notebook: 
```bash
jupyter notebook
```

Then open and run the main notebook:
```bash
notebooks/IO_main_figures.ipynb
```
This will reproduce the key panels of the main figures.
(Additional scripts and figure panels will be released after peer review.)


**Raw data (.h5)** is downloaded via the notebook and is hosted on Zenodo: [10.5281/zenodo.17359151](https://doi.org/10.5281/zenodo.17359151)

- `glom_omp_data.h5` — direct link: https://zenodo.org/record/17359151/files/glom_omp_data.h5
- `glom_tbet_data.h5` — direct link: https://zenodo.org/record/17359151/files/glom_tbet_data.h5
- `processed_data.h5` — direct link: https://zenodo.org/record/17359151/files/processed_data.h5

🙌 Acknowledgements

This work was supported by the Francis Crick Institute, University College London, and the University of Bonn, and benefited from discussions with colleagues in physiology, systems neuroscience, and computational modeling.
Please refer to the manuscript for full author contributions and funding details.

☎️ Contact

For questions, data access, or collaboration inquiries, contact:

Tobias Ackels – tobias.ackels@ukbonn.de

Andreas T. Schaefer – andreas.schaefer@crick.ac.uk

Sina Tootoonian – sina.tootoonian@crick.ac.uk

# IPRF

We provide examples for both simulation and real data analysis. The simulation jupyter notebook is `Code/Simulation Pipeline - Public.ipynb`.
The simulation pipleline includes data generation, model fitting, and some visualizations.
The real data analysis code is `Code/Feature Coupling Model - session 757216464.ipynb`.
Prior to analysing the real data, you need to install `allensdk` and download the Neuropixels dataset. 
Please follow the instructions to install allensdk and its dependencies: `https://allensdk.readthedocs.io/en/latest/install.html`.
You can follow `https://allensdk.readthedocs.io/en/latest/_static/examples/nb/ecephys_data_access.html` or use our code `Code/session_downloader.ipynb` for data downloading.
If the data can not be downloaded in a very short time, it can hit timeout issue. Check `Code/Copy these files to AllenSDK packages/` for our temporal solution (this applies to allensdk 2.2.0 at least).
We offer scripts to explore the Neuropixels dataset `Code/session_exploration.ipynb` and `Code/Condition Exploration.ipynb`, such as properties of visual stimuli, animals, neurons, brain regions, etc. If you are not familiar with the datastructure, it is highly recommended to explore the data first. Of course the official website is informative as well: `https://allensdk.readthedocs.io/en/latest/visual_coding_neuropixels.html`

Reference <br>
Chen, Y., Douglas, H., Medina, B. J., Olarinre, M., Siegle, J. H., & Kass, R. E. (2022). Population Burst Propagation Across Interacting Areas of the Brain. Journal of Neurophysiology. <br>
Main text: https://journals.physiology.org/doi/full/10.1152/jn.00066.2022 <br>
Supplementary document: https://zenodo.org/record/7024023#.Y6XHkXZOmUk

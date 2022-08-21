# IPRF

We provide examples for both simulation and real data analysis. The simulation jupyter notebook is `Code/Simulation Pipeline - Public.ipynb`.
The simulation pipleline includes data generation, model fitting, and some visualizations.
The real data analysis code is `Code/Feature Coupling Model - session 757216464.ipynb`.
Prior to analysing the real data, you need to download the Neuropixels dataset. You can use `Code/session_downloader.ipynb`.
If the data can not be downloaded in a very short time, it can hit timeout issue. Check `Code/Copy these files to AllenSDK packages/` for our temporal solution (this applies to allensdk 2.2.0 at least).
We offer scripts to explore the Neuropixels dataset `Code/session_exploration.ipynb` and `Code/Condition Exploration.ipynb`, such as properties of visual stimuli, animals, neurons, brain regions, etc. If you are not familiar with the datastructure, it is highly recommended to explore the data first. Of course the official website is informative as well: `https://allensdk.readthedocs.io/en/latest/visual_coding_neuropixels.html`
For the dependent packages and versions, please refer to `example_requirments.txt`, some of these are redundant.

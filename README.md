# FINAL_PROJECT_1825373_ShuangLi_XJTLU
# Counterfactual Explainations on Benign and Malignant Tumor Ultrasound Image Classification Based on Vision Transformer and Graph Neural Network
This is the implementation of combined vision transformer and graph neural network with counterfactual explainations on medical ultrasound images classification

1.	Put the data set in the data folder.
Note that the right for using the medical images with patients’ privacy in this paper is sensitive and limited, so users should employ your own datasets. Therefore, in the sample implementation in the attached video adopted an insensitive and public image.
2.	Install the following python environment packages using pip and conda 
conda create --name graph mlpmixer python=3.8
conda activate graph mlpmixer
conda install pytorch=1.12.1 torchvision=-0.13.1 torchaudio==0.12.1 cudatoolkit-11.3 -c pytorch
conda install -c pyg pytorch-sparse
conda install -c pyg pytorch-scatter
conda install -c pyg pytorch-cluster
conda install -c pyg pyg
pip install ogb
conda install -c conda-forge rdkit
pip install  yacs
pip install tensorboard
pip install network
pip install einops
# METIS
conda install -c conda-forge metis
pip install metis
3.	Open the entire code folder with jupyter notebook
4.	Run the final file



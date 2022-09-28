# LHGNN: Link Prediction on Latent Heterogeneous Graphs
We provide the code (in pytorch) and datasets for our work: "Link Prediction on Latent Heterogeneous Graphs".


## 1. Desription
The repository is organised as follows:

* dataset/: contains the 3 benchmark datasets: fb15k-237, wn18rr and dblp (ogb-mag is too large so we didn't upload). All datasets will be processed on the fly. Please extract the compressed file of each dataset before running.

* codes/: contains our model and processing functions.



## 2. Requirements
To install required packages
- pip install -r requirements.txt


## 3. Running experiments
To run our model, please run these commands regarding to specific dataset:

cd codes/
- python main.py --dataset=fb15k-237 
- python main.py --dataset=wn18rr --max_l=5 --lr=1e-4
- python main.py --dataset=dblp --max_l=3 --gamma=0.3



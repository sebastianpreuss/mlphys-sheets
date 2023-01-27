## Machine Learning and Physics, Sheet 11 

### Setup
Disclaimer: This is currently not working for me, I will figure it out tomorrow and update the environment setup. You can do task one with the previous environment

For this sheet we set up a new conda environment, that includes https://github.com/hci-unihd/celltype-graph-benchmark.

Clone this repo and navigate into it:
```bash
git clone https://github.com/hci-unihd/mlph_sheet11.git
cd mlph_sheet11
```
Install and activate the conda environment:
```bash
conda create -n ctg -c rusty1s -c pytorch -c conda-forge -c lcerrone ctg-benchmark torchmetrics=0.8.0 cpuonly jupyter matplotlib
conda activate ctg
```
Then you can start jupyter (run `jupyter notebook`) and open sheet11.ipynb, 
which you should use as the basis for the solution of the practical excercises.


### Hand in
 Hand in both your jupyter notebook, and an exported pdf (File -> Download as -> pdf). 
 If you encounter problems exporting the pdf like this, please print your notebook to pdf and hand this in.

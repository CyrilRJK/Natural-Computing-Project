# Natural-Computing-Project

* To run Differential Evolution with Novel Parameter Control \[1], run the 
DE_NPC_EvolveX_YZ.ipynb notebook where X=dataset, Y=model and Z={"","\_SSIM"}. Z is the indicator of whether SSIM was used in the fitness function and Y is the model which adversarial examples are generated against.
* To run the modified version of the Genetic Algorithm on CIFAR10 dataset, go to the "ImprovedGA" folder and then the folder having the name of wanted crossover technique. 
* Runs with different seeds are included in different notebooks. When you see "\_seed1" indication, it means seed=1 was used. Otherwise seed=0 is used. For modified Genetic Algorithm on MNIST dataset, run with different seeds are organized in "seed0" and "seed1" folders. Naming convention of which technique and model is used is straightforward from then on.
* The files are all Python Notebooks. You can download them to your local, connect to a kernel and run all cells. The subset files required for execution are in the folder "Subsets" and the models are in the "Models" folder. Include them in your working directory before running the notebooks.

\[1] Zhenyu Meng, Yuxin Chen, and Xiaoqing Li. 2020. Enhancing Differ-ential Evolution With Novel Parameter Control.IEEE Access8 (2020),51145–51167


# local-envs-zip
local built envs


## tf202105

conda config --add envs_dirs C:\ML\envs
conda config --show
conda env remove --name tf202105
conda create -n tf202105
conda info --envs
conda activate tf202105
conda install python=3.7.10

pip install -i https://pypi.tuna.tsinghua.edu.cn/simple tfx

pip install -i https://pypi.tuna.tsinghua.edu.cn/simple tensorflow-datasets tf-agents matplotlib pandas scikit-learn scikit-image ipython jupyter keras gym lxml xlrd openpyxl sqlalchemy jupyterlab seaborn tabulate pydot pydotplus tensorflow-model-remediation

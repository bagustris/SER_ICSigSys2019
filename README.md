### Speech emotion recognition using voiced speech and BLSTM with attention model  

This repository contains code for the following paper: "Speech emotion recognition based on voiced speech using LSTM with attention model", prepared to be submitted on ICSygSys 2019. The main code (jupyter-noteboook) is [ICSigSys4.ipynb](https://github.com/bagustris/SER_ICSigSys2019/blob/master/code/python_files/ICSigSys4.ipynb). Other codes are borrowed from other repositories (see on each directory).

Step to reproduce the result:  
- Download IEMOCAP data
- Run [mocap_collect_data.py](https://github.com/bagustris/SER_ICSigSys2019/blob/master/code/python_files/mocap_data_collect.py) (copyed from tripathi's repo)
- Run [save_feature.py](https://github.com/bagustris/SER_ICSigSys2019/blob/master/code/python_files/save_feature.py) (change what you need)
- Run [SER_ICSigSys2019/code/python_files/ICSigSys4.ipynb](https://github.com/bagustris/SER_ICSigSys2019/blob/master/code/python_files/ICSigSys4.ipynb)

Besides notebook, .py python files are provided.

#### Requirement
The python used is version 3.6 with latest modules for each packages (at the time of writing (July 2019)).

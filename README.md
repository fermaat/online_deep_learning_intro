# Software instalation and previous steps

## Linux machines (ubuntu)
You need to install pip3 on your system

```sudo apt install python3-pip```
#### Instal virtualenv

```pip3 install virtualenv```
#### Create environment

```virtualenv path_to_virtual_envs_location/environment_name```
##### activate virtuelenv (if needed)

```source path_to_virtual_envs_location/environment_name/bin/activate```
#### install dependences

```pip3 install -r requirements.txt```
In case you have cuda installed and configured, just replace tensorflow package with tensorflow-gpu:

```pip3 install -r requirements_gpu.txt```
#### Jupyter kernel generation
After having sourced the environment:

```ipython kernel install --user --name=environment_name```


## Windows machines

You could do it from waw python, but it can be easier if you use Anaconda. Download and install it from [here](https://www.anaconda.com/distribution/)

Create a conda environment and activate it. Help can be found [here](https://towardsdatascience.com/a-guide-to-conda-environments-bc6180fc533)

#### Requirements instalation

```conda install -r requirements_windows.txt```


### Jupyter kernel generation

In a conda prompt/powershell conda prompt, activate the environment
```conda activate_environment_name```

After the environment is active:

```ipython kernel install --user --name=environment_name```

Now Jupyter has a kernel dedicated to the environment.

#### Torch
If you want also to install torch, you need to run this line (only for cpu)

```pip install torch==1.3.1+cpu torchvision==0.4.2+cpu -f https://download.pytorch.org/whl/torch_stable.html```
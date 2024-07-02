## virtual environment && jupyter 🚀
### Step 1

Create a virtual environment to install the necessary libraries.

```bash
python3 -m venv venv
source venv/bin/activate
```

### Step 2

Install ipykernel and jupyterlab.

```bash
pip3 install ipykernel
pip3 install jupyterlab
```

### Step 3

Create a kernel. The kernel is the process that runs the code you write in the notebook cells:

```bash
python3 -m ipykernel install --user --name=<KERNEL_NAME>
```

### Step 4

If you want to uninstall a kernel:

```bash
jupyter kernelspec uninstall <KERNEL_NAME>
```

### Step 5

Initialize jupyterlab:
```bash
jupyter lab
```

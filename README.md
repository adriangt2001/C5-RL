## Previous installation

First, make sure you have Python 3.10 installed and then create a virtual environment with that python version.

```bash
python3.10 -m venv .venv
```

After that, install torch with the cuda version you need. More information on how to do that in the [Official PyTorch page](https://pytorch.org/get-started/locally/).

Once torch is installed, install the dependencies from the `requirements.txt` file.

```bash
pip install -r requirements.txt
```
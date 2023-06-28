# Neural Amp Modeler: Colab Notebooks
Example / template repo of separating Colab Notebooks from the main code.

## Google Colab notebooks

If you don't have a good computer for training ML models, you use Google Colab to train
in the cloud using the pre-made notebooks under `train`.

**Pros:**

- No local installation required!
- Decent GPUs are available if you don't have one on your computer.

**Cons:**

- Uploading your data can take a long time.
- Daily usage limit.
- The session can time out after inactivity, potentially resulting in the loss of files (more on this later)


For the very easiest experience, open 
[`easy_colab.ipynb` on Google Colab](https://colab.research.google.com/github/d-Vincent-b/NeuralAmpModeler-ColabNotebooks/blob/main/train/easy_colab.ipynb)
and follow the steps!

### Please familiarize yourself with the above notebook before trying anything else!
Listed below are some more advanced or experimental notebooks:

- This notebook is essentially the same as `easy_colab.ipynb` except for some additional Google Drive capabilities. Most importantly automatically saving `exported_models` and `lightning_logs` to your Google Drive, fixing the inactivity issue mentioned above \
[`Drive capable colab.ipynb` on Google Colab](https://colab.research.google.com/github/d-Vincent-b/NeuralAmpModeler-ColabNotebooks/blob/main/train/drivecapable_colab.ipynb)
  
- Adaptation of Mike Oliphants notebook, allows for custom model configs. (currently not working, would require changes to `train/core.py` and `train/colab.py` in the main code/repo) \
[`Custom colab.ipynb` on Google Colab](https://colab.research.google.com/github/d-Vincent-b/NeuralAmpModeler-ColabNotebooks/blob/main/train/custom_colab.ipynb)

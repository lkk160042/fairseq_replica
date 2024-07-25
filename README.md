# fairseq_replica v0.10.2
- This project is based on 0.10.2 version of **fairseq**, a sequence modeling toolkit developed by
**facebookresearch**.
- This project includes only one modification to `indexed_dataset.py` at `fairseq/data`, replacing 
*np.float* to *np.float64* to avoid deprecation error in Numpy > 1.20
- You can check the origin version at https://github.com/facebookresearch/fairseq/tree/v0.10.2

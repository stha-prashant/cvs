# CVS starter code
- To generate the preprocessed pkl file, run train.ipynb after chaing the  `train_root` path
- In main.py put your own neptune api keys and checkpoint paths
```
run = neptune.init_run(
    project="your_project_name",
    api_token="your_api_token",
)  # your credentials
save_path = 'your_save_path'
```
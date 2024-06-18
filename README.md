# CVS starter code
This starter code only uses the annotated frame as input and not any video context.

- To generate the preprocessed pkl file `single_images.pkl`, run `preprocess.ipynb` after changing the  `train_root` path
- To train, run `main.py` after you update the neptune api keys, project, and checkpoint paths
```
run = neptune.init_run(
    project="your_project_name",
    api_token="your_api_token",
)  # your credentials
save_path = 'your_save_path'
```

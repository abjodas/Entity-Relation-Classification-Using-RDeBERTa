# DeBERTa for Relation Extraction

This repository contains code for training and inference using the DeBERTa model for relation extraction on the SemEval-2010 Task 8 dataset.

## Files

- `DeBERTa_Training.ipynb`: Jupyter Notebook for training the DeBERTa model on the relation extraction dataset.
- `DeBERTa_Inference.ipynb`: Jupyter Notebook for running inference using the trained DeBERTa model.

## Requirements

To run the notebooks, install the required dependencies using:

```bash
pip install -r requirements.txt
```

## Training the Model

1. Open `DeBERTa_Training.ipynb` in Jupyter Notebook.
2. Ensure that the dataset is correctly loaded.
3. Run the notebook cells sequentially to train the model.
4. The trained model will be saved for later inference.

## Running Inference

1. Open `DeBERTa_Inference.ipynb`.
2. Load the trained model.
3. Provide input sentences for relation extraction.
4. Run the notebook to obtain predictions.

## Dataset

The model is trained on the **SemEval-2010 Task 8** dataset for relation extraction. Ensure that the dataset is preprocessed and available in the required format.

## Citation

If you use this code, please consider citing the relevant papers on DeBERTa and SemEval-2010 Task 8.

## License

This project is licensed under the MIT License.


# deployment
This is a demo made to deploy a simple machine learning
## Project Structure

```python
Deployment_XGBoost_Heart_Disease_UCI/
├── data/                # Input data folder (ignored by Git)
├── models/              # Trained models folder (ignored by Git)
├── src/                 # Source code
│   ├── data/            # Data-related modules
│   │   ├── data_loader.py       # Data loading
│   │   ├── data_splitter.py     # Splits data into train/test sets
│   │   ├── data_processor.py    # Data preprocessing and transformation
│   ├── model/           # Model-related modules
│   │   ├── trainer.py          # Model training
│   │   ├── evaluator.py        # Model evaluation
│   │   ├── saver.py            # Saves the trained model
├── main.py              # Orchestrates the training pipeline
├── .gitignore           # Specifies files and folders to ignore by Git
├── pyproject.toml       # Poetry configuration
└── README.md            # Project documentation (this file)

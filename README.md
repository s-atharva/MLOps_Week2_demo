# Iris Classification: Version-Controlled with Data Version Control
![Screenshot 2025-06-01 215433.png](Images/Screenshot%202025-06-01%20215433.png)

## 📦 Project Structure
MLOps_Week2_demo/
├── .dvc/                 # DVC internal tracking folder
├── data/                 # Folder containing the dataset
│   └── iris.csv          # Iris dataset file
├── GCS/                  # (Optional) Cloud Storage or related files
├── Images/               # Folder for storing screenshots or images
│   └── Screenshot 2025-06-01 215433.png
├── .dvcignore            # Files/folders ignored by DVC
├── .gitignore            # Files/folders ignored by Git
├── data.dvc              # DVC-tracked reference for data/iris.csv
├── model.py              # Main Python script for training and evaluation
├── README.md             # Project overview and documentation
└── requirements.txt      # Python dependencies

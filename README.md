MEDICAL DIAGNOSIS WITH ATTENTION MECHANISM
OVERVIEW:
       This project explores the use of Transformer-based models to analyze medical notes and highlight critical symptoms using attention mechanisms. It includes a Jupyter Notebook that visualizes attention heatmaps, helping to understand how the model prioritizes symptoms in different scenarios.
FEATURES:
      Uses a BERT-based model to extract attention scores from medical notes.
      Generates attention heatmaps to visualize word importance.
      Compares attention shifts when symptoms change.
      Explores rare but significant symptoms and their impact on attention.
INSTALLATION:
To run this project locally, follow these steps:
Clone the repository:
                 git clone https://github.com/your-username/your-repo.git
                 cd your-repo
Create a virtual environment (optional but recommended):
                 python -m venv venv
                 source venv/bin/activate 
Install dependencies:
                 pip install -r requirements.txt
USAGE:
1.Open the Jupyter Notebook:
jupyter notebook ASSIGNMENT_1.ipynb
2.Run the notebook to process medical notes and generate attention heatmaps.
3.Modify the text inputs to observe different attention distributions.

EXAMPLE VISUALIZATION:
A sample heatmap generated from the model:
[Insert attention heatmap image here]
CONTRIBUTING:
Feel free to fork the repository and submit pull requests for improvements.
REFERENCES:
*Hugging Face Transformers
*Matplotlib
*Seaborn

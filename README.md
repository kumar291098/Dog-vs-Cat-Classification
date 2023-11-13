# Dog-vs-Cat-Classification
Prediction of dog vs cat using  MobileNetV2transfer learning



## Requirements

- Google Colab account
- Kaggle account
- Dataset: [Cat and Dog Dataset on Kaggle](https://www.kaggle.com/c/dogs-vs-cats)

## Setup

1. **Clone this repository:**

    ```bash
    git clone https://github.com/your_username/cat-dog-classification.git
    cd cat-dog-classification
    ```

2. **Download Kaggle dataset:**
   - Visit Kaggle and download the dataset: [Cat and Dog Dataset](https://www.kaggle.com/c/dogs-vs-cats)
   - Upload the dataset to Google Colab or use Kaggle API.

3. **Open the Colab notebook:**
   - Open `Cat_Dog_Classification_MobileNetV2.ipynb` in Google Colab.

4. **Set up Kaggle API in Colab:**

    ```python
    from google.colab import files

    # Upload your Kaggle API key (kaggle.json) obtained from Kaggle account settings
    uploaded = files.upload()

    # Move the key to the correct location
    !mkdir -p ~/.kaggle && mv kaggle.json ~/.kaggle/ && chmod 600 ~/.kaggle/kaggle.json
    ```

5. **Install required libraries:**

    ```python
    !pip install kaggle tensorflow
    ```

6. **Run the notebook:**
   - Follow the steps in the notebook to train the MobileNetV2 model on the Cat and Dog dataset.

## Model Training

- The model is trained using transfer learning on MobileNetV2 with fine-tuning on the Cat and Dog dataset.

## Prediction

- Use the trained model to make predictions on new images of cats and dogs.

## Results

- The model achieves an accuracy of X% on the validation set.

## Author

- Avnish Kumar
- Contact: kumara291098@gmail.com






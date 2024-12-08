# Simio_DL
# Simio Deep Learning Prediction Model

This repository contains a deep learning model for predicting system states based on various resource utilization parameters. The model is implemented using TensorFlow and Keras, and the notebook provides a complete pipeline, including data preprocessing, model training, prediction generation, and evaluation.

## How to Use This Repository

### Step 1: Open the Colab Notebook
You can access the Colab notebook by clicking on the following link:

[Open the Colab Notebook](https://colab.research.google.com/drive/1iJVcueN1vLNft8mHX9Gmh8LN7_A86fys?usp=sharing)

### Step 2: Run the Notebook
Once you open the notebook, follow the steps outlined in the notebook for:
- **Data Preprocessing**: This includes filling missing values, encoding categorical features, and scaling the data.
- **Model Training**: The neural network model is built using TensorFlow and Keras. It includes multiple `Dense` layers and `Dropout` layers to prevent overfitting. Early stopping is used to halt training when the validation performance stops improving.
- **Prediction Generation**: After training, the model makes predictions on the test dataset, which are saved back into a new CSV file.
- **Evaluation**: The model's performance is evaluated using accuracy and confusion matrix, with visualizations such as accuracy/loss plots and a confusion matrix heatmap.

### Step 3: Analyze Results
- **Accuracy**: The model achieves high accuracy, typically above 99%, depending on the dataset used.
- **Confusion Matrix**: The confusion matrix helps visualize where the model is performing well and where it is making errors.
- **Class Distribution**: The dataset’s class distribution is visualized to understand potential imbalances and how they might impact model performance.

## Advantages of Using Google Colab
- **Free GPU/TPU**: Google Colab provides free access to GPUs and TPUs, which can significantly accelerate the training of deep learning models.
- **Cloud-based**: No setup is required, and your work is automatically saved in Google Drive, allowing easy access and collaboration.
- **Integration with Google Drive**: You can easily load and save files from/to Google Drive, ensuring seamless data management.

## Outputs of the Notebook
- **Model Accuracy**: The accuracy is computed after predicting on the test set, with the model typically achieving 99.02% accuracy.
- **Confusion Matrix**: A heatmap showing the true vs. predicted values, providing insight into misclassifications.
- **Training and Validation Loss/Accuracy**: Plots of accuracy and loss over epochs, helping to understand the model's learning progress and detect overfitting.

## Next Steps
- **Class Imbalance**: The dataset shows a class imbalance, which can affect model performance. Consider techniques like dataset balancing, oversampling, or collecting more data for underrepresented classes to improve accuracy.
- **Model Improvements**: You can experiment with different architectures, hyperparameters, or optimization techniques to improve the model’s predictive performance.

Feel free to fork the repository, explore the Colab notebook, and enhance the model!

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

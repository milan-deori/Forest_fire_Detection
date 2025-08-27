# Forest Fire Detection using Deep Learning

This project aims to detect forest fires using deep learning techniques. It is designed as an intern project to automate the identification of fire in forest images.

## Project Structure

- `Forest_Fire_Detection_using_DL.ipynb`: Main Jupyter notebook containing code for training, evaluating, and testing the fire detection model.
- `datasets/`: Directory containing image datasets organized for training, validation, and testing.
  - `train/`: Training images
    - `fire/`: Images with fire
    - `nofire/`: Images without fire
  - `val/`: Validation images
    - `fire/`: Images with fire
    - `nofire/`: Images without fire
  - `test/`: Testing images
    - `fire/`: Images with fire
    - `nofire/`: Images without fire

## Getting Started

1. **Clone the repository**  
   ```sh
   git clone <repo-url>
   cd Forest_fire_Detection
   ```

2. **Install dependencies**  
   Make sure you have Python and required libraries (e.g., TensorFlow, Keras, NumPy, Matplotlib) installed.

3. **Prepare the dataset**  
   Place your images in the respective folders under `datasets/`.

4. **Run the notebook**  
   Open `Forest_Fire_Detection_using_DL.ipynb` in Jupyter Notebook and follow the instructions to train and test the model.

## Dataset

The dataset is organized into three splits:
- **Train**: Used for training the model.
- **Validation**: Used for tuning hyperparameters.
- **Test**: Used for evaluating final model performance.

Each split contains two classes:
- `fire`: Images containing forest fire.
- `nofire`: Images without fire.

## Model

The notebook implements a deep learning model (e.g., CNN) for image classification to detect fire in forest images.

## Results

Results and evaluation metrics (accuracy, loss, confusion matrix) are displayed in the notebook after training and testing.

## Contributing

Feel free to fork the repository and submit pull requests for improvements or bug fixes.

## License

Specify your license here (e.g., MIT, Apache 2.0).

## Contact

For questions or collaboration, contact the project maintainer.


# YOLO Project
Live preview http://34.30.190.159:5000/

This project contains two main directories:
1. Training
2. Interface (for running the model)

## Training

To train the model:

1. Navigate to the YOLO directory:
   ```
   cd yolo
   ```

2. Run the training script:
   ```
   python train.py
   ```

3. After training completes, you'll find a `best.pt` checkpoint in the `runs/train` directory.

4. Copy the `best.pt` file to the `YOLO-Interface` directory.

## Running the Model

To run the model:

1. Ensure you've copied the `best.pt` file to the `YOLO-Interface` directory.

2. Navigate to the `YOLO-Interface` directory.

3. Run the application:
   ```
   python app.py




   ```

This will start the interface for using your trained YOLO model.

Images before path hole detection
![4](https://github.com/user-attachments/assets/5a32412a-38e4-4c86-8e65-58d58f2d2a48)
![1](https://github.com/user-attachments/assets/5b0264cd-ff02-4f52-910b-944bdec622d1)
![2](https://github.com/user-attachments/assets/a77a9a38-3577-433b-8d94-5d8a3c581a4f)


Results



https://github.com/user-attachments/assets/ea070cd1-96af-4419-84bf-c4521f927843



Video or camera can also be used for realtime detection

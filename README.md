# Action Recognition System

This project implements a robust action recognition system utilizing ConvLSTM and LRCN architectures. It leverages their unique capabilities for spatiotemporal feature extraction and sequence modeling, achieving high accuracy on action recognition tasks.

## Dataset

- **Dataset**: [UCF50 - Action Recognition Dataset](https://www.crcv.ucf.edu/data/UCF50.rar)
- **Action Categories**: 50
- **Videos per Action Category**: 25
- **Average Videos per Category**: 133
- **Average Number of Frames per Video**: 199
- **Average Frame Width**: 320
- **Average Frame Height**: 240
- **Average Frames Per Second**: 26
- **Model Accuracies**: 
  - ConvLSTM: 0.9795
  - LRCN: 0.9829

## Project Outline

1. **Download and Visualize the Data with Labels**
2. **Preprocess the Dataset**
3. **Split the Data into Train and Test Sets**
4. **Implement the ConvLSTM Approach**
   - Construct the Model
   - Compile & Train the Model
   - Plot Model’s Loss & Accuracy Curves
5. **Implement the LRCN Approach**
   - Construct the Model
   - Compile & Train the Model
   - Plot Model’s Loss & Accuracy Curves
6. **Test the Best Performing Model on YouTube Videos**

## Requirements

To run this project, you need to install the following libraries:
1. ```bash
    pip install youtube-dl moviepy pafy opencv-python numpy matplotlib tensorflow

## Conclusion

This project demonstrates the effectiveness of ConvLSTM and LRCN architectures in recognizing human actions in videos. The models trained on the UCF50 dataset showed impressive accuracy, making them suitable for real-time applications in various domains.

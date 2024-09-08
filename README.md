# -Enhancing-CIFAR-10-Image-Classification-with-Convolutional-Neural-Networks-
Abstract: 
This report evaluates the performance of two Convolutional Neural Networks 
(CNNs)—BasicCNN and CustomCNN—for classifying the CIFAR-10 dataset images. 
The CustomCNN model is tailored with advanced layers and regularization 
techniques, resulting in significant improvements in accuracy over the 
BasicCNN model 
Introduction: 
The CIFAR-10 dataset consisting of 32 x 32 pixel color images across 10 
classes, provides a comprehensive platform for benchmarking image 
classification algorithms. This study introduces two CNN architectures, 
BasicCNN and CustomCNN, assessing their efficacy through training and 
validation processes 
Data Processing and Augmentation: 
Here, the CIFAR-10 dataset underwent a series of transformations including 
random cropping, flipping, color adjustments and rotations to augment the 
data and prevent overfitting. This preprocessing enhanced the robustness 
of the CNN models equipping them to handle variations in new data 
effectively 
CNN Architecture and Implementation: 
• BasicCNN:  
This model included standard convolutional layers, pooling and fully 
connected layers. It served as an initial benchmark for the classification 
task 
The training and validation accuracy for the BasicCNN model is: 
The final training accuracy is: 55.66% 
The final validation accuracy is: 59.61% 
• CustomCNN: 
The CustomCNN model incorporated additional convolutional layers, batch 
normalization, ReLU activation functions, dropout layers and a final fully 
connected layer aiming to extract deeper features for improved 
classification 
The training and validation accuracy for the CustomCNN model is: 
The final training accuracy is: 82.79% 
The final validation accuracy is: 85.81% 
• Training Protocol: 
Both models were trained using the Adam optimizer and initial learning 
rates and weight decay parameters. The learning rate was adjusted using a 
scheduler to fine-tune the models during the training epochs 
Results: 
Throughout 90 epochs for CustomCNN and 20 for BasicCNN, both models 
demonstrated a decrease in loss and an increase in accuracy. However, the 
CustomCNN model exhibited superior performance with a training accuracy of 
82.79% and validation accuracy of 85.81%, illustrating its enhanced 
learning capability and effective generalization. Plots depicting the loss 
and accuracy trends for both models were included to visualize the 
learning curves and validate the model’s improvements over time 
Plots for BasicCNN: 
Plots for CustomCNN: 
Conclusion: 
The CustomCNN model’s enhanced performance highlights the value of 
advanced architecture designs and regularization techniques in deep 
learning. These findings suggest potential directions for future research 
including hyperparameter tuning, real time data augmentation and exploring 
different architecture for further accuracy improvements 

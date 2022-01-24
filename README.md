# Object-Detection (SSD MobileNet V2 FPNLite 640x640)
In this project, I had trained a custom Object Detection model (i.e. SSD MobileNet V2 FPNLite 640x640) using the TensorFlow 2 Object Detection API.
I chose this model since it provides a relatively good trade-off between performance and speed. The model was trained for 7500 epochs (achieving total loss of about 0.21 and mean AP of 0.257 on test images) using the Kangaroo dataset available on Kaggle to detect single class of object in an image. I then used TensorBoard to monitor the training job. The model was then inferred on some of the test images to detect kangaroos.

To train this Object Detection model, I took the following steps:
  -	TensorFlow Object Detection API Installation
    -	Protobuf Installation/Compilation
    -	Test the Installation
  -	Getting and processing the Kangaroo dataset available on Kaggle
    -	Create a label_map file
    -	Converting data to TFRecord
  -	Configuring a Training Job
    -	Download Pre-Trained Model
    -	Configure the Training Pipeline
    -	Training the Model
  -	Evaluating the Model
  -	Monitor Training Job Progress using TensorBoard
  -	Run Model inference on test images

The colab notebook for this project can be found [here](https://github.com/Aryan625/Object-Detection/blob/main/Object_Detection_(SSD_MobileNet_V2_FPNLite_640x640).ipynb)
or in this [google drive link](https://colab.research.google.com/drive/1rlkmqsc0_v4JLAvvoqK-yFPKNfR1lpR6?usp=sharing)

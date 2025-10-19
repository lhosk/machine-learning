### Dogs vs. Cats CNN Classifier
- Used MobileNetV2 as a pretrained base with custom top layers and sigmoid output for binary classification  
- Implemented two training pipelines: ImageDataGenerator for standard augments and a custom TensorFlow augmentation (brightness, flip, desaturation)  
- Achieved ~95% validation accuracy on 25K RGB images resized to 112×112 with a 75/25 split 

# Magis-Optics

An application for classifying stages of Diabetic Retinopathy (DR) of retina images using trained Resnet-18 Convolutional Neural Network (CNN) model.

Diabetic Retinopathy (DR) is a complication of diabetes caused by damage to the blood vessels in the retina, potentially leading to vision loss if untreated. 
The condition progresses through different stages, from mild non-proliferative abnormalities to severe proliferative retinopathy, characterized by abnormal blood vessel growth.


How It Works?

The model processes retinal images through convolutional layers and residual blocks, extracting detailed features. Using this information, it predicts the disease stage (0-4), 
assisting in both early detection and detailed diagnosis.


Instructions:

Upload a retinal image and see the model's prediction based on the 0-4 classification system.

1. Ensure the image is in JPEG or PNG format.
2. Click the "Upload an Image" button to select your retinal image.
3. Click the "Predict" button and wait for the model to process the image and display the classification stage (0-4).
4. Stage Explanation:
   
    0: No signs of DR.
   
    1: Mild stage, initial signs detected.
   
    2: Moderate stage, some vessel blockages identified.
   
    3: Severe stage, widespread vessel blockages observed.
   
    4: Proliferative stage, abnormal vessel growth detected.

Disclaimer: The predictions are for research purposes and are not a substitute for clinical diagnosis. Please consult a healthcare professional for medical advice.

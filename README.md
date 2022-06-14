# Bank Check Amounts Verification and Auto Correction System
## Business Comprehension
This application is dedicated to bank agents to help them properly detect and
categorize the check by avoiding human related errors, save time and reduce costs.
## Data Preparation

- Resizing check using CV2
- Change color & image format
- Background removal
- Image cropping
- Noise removal

## Data Modeling and Evaluation
- Traning and Fine-tuning Tesseract on new hand written fonts.
- Creating an adapted Tesseract Model.
- Testing the model on different preprocessed pics to get best result.
- Using AutoCorrect and Pyspellchecker on the result from Tesseract to get the exact value.

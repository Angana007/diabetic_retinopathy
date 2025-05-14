# Diabetic Retinopathy Detection using CNNs and Transfer learning (MobileNetV2)

Diabetic Retinopathy (DR) is one of the most common complications of diabetes and a leading cause of preventable blindness in working-age adults worldwide. It occurs when high blood sugar levels damage the small blood vessels in the retina — the light-sensitive layer at the back of the eye. This damage can cause the blood vessels to leak, swell, or close off entirely, leading to vision problems and eventually blindness if left untreated.

🤖 Why This Project Is Useful

By automating the detection of diabetic retinopathy from fundus images, this project demonstrates how AI can assist clinicians in making faster, more reliable diagnoses. Benefits include:

🔁 Scalability: Can screen thousands of images without fatigue.

⚡ Speed: Enables real-time or near-real-time detection in clinical workflows.

🎯 Consistency: Reduces inter-observer variability in manual grading.

🌍 Accessibility: Supports DR screening in underserved or remote areas where specialists are limited.

Tech Stack: Python, TensorFlow/Keras, MobileNetV2, ImageDataGenerator, NumPy, Matplotlib, scikit-learn, Jupyter Notebook

Dataset Source

The dataset used in this project is from the [Diabetic Retinopathy Detection competition on Kaggle]. The images were provided by EyePACS for the purpose of developing automated methods to identify signs of diabetic retinopathy in retinal images.

Kaggle Competition: Diabetic Retinopathy Detection

URL: https://www.kaggle.com/competitions/diabetic-retinopathy-detection

Acknowledgement: Retinal images provided by EyePACS, sponsored by the California Healthcare Foundation. For more details, you might check out this useful link: https://paperswithcode.com/dataset/kaggle-eyepacs

🔭 Future Considerations

In this project, I used MobileNetV2 due to its lightweight architecture and faster training time, which made it well-suited for local development and limited compute environments. However, EfficientNetB0 is known to deliver stronger performance in image classification tasks—especially in the medical domain—thanks to its compound scaling of depth, width, and resolution.

In future iterations, I plan to experiment with EfficientNetB0 to evaluate potential gains in accuracy and robustness for diabetic retinopathy detection.

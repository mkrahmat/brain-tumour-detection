# Brain Tumor Detection from X-ray Scans 🧠

This project uses deep learning to detect brain tumors from X-ray scan images. The model is trained using labeled image datasets and can classify whether an image contains signs of a tumor.

> ⚠️ Note: Several improvements, experiments, and evaluations can be done.
- ( GET TRAIN FOLDER FROM GOOGLE DRIVE MENTIONED IN REQUIREMENTS.txt )

## 📂 Project Structure

- `code.ipynb`: Main Jupyter Notebook for model training, evaluation, and predictions.
- `train/`: Contains labeled training X-ray scan images.
- `test/`: Contains labeled testing X-ray scan images.

Each of the `train/` and `test/` folders has subfolders like:
- gliomia_tumour
- meningioma_tumor
- pituitary_tumor
- no_tumor

# 📌 Model Details
Input: X-ray scan image of the brain

Output: Classification → Tumor / No Tumor

Frameworks Used: TensorFlow / Keras / OpenCV / NumPy

# 🧪 Dataset
The dataset consists of X-ray images organized into two categories:

tumor/: Images labeled with the presence of a tumor

no_tumor/: Images without any tumor indications

Make sure you maintain this folder structure inside both train/ and test/.

# 📌 Notes
This is a prototype model — not for real medical use.

Suggestions, improvements, or validations are welcome!

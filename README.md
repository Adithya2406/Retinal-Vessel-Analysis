## Retinal Vessel Analysis
An AI-powered pipeline for retinal vessel analysis, achieving 87.5% accuracy in detecting hypertension and predicting cardiovascular disease from fundus images. The system leverages validated biomarkers like the Arteriovenous Ratio (AVR) for early, cost-effective risk assessment.

---
## Table of Contents
- **Overview**
- **Features**
- **Application**
- **Installation**
- **Usage**
- **Project Structure**
- **Results**
- **Contributing**

---
## **Overview**
Retinal Vessel Analysis is a machine learning pipeline designed to analyze retinal fundus images for the detection of hypertension and prediction of cardiovascular disease. By extracting and quantifying vessel features such as AVR, the project enables early, non-invasive screening for cardiovascular risk, supporting clinical decision-making and public health interventions.

---
## **Features**
- Automated segmentation of retinal blood vessels from fundus images
- Calculation of key biomarkers (e.g., AVR)
- AI-based classification for hypertension and cardiovascular disease risk
- Achieves 87.5% accuracy on benchmark datasets
- Modular codebase for easy extension and experimentation

---
## **Application**
This project can be used by:
- **Healthcare professionals** for early screening of hypertension and cardiovascular disease using retinal images
- **Researchers** in medical imaging and computer vision
- **Public health initiatives** focused on scalable, cost-effective risk assessment

The tool enables early detection, potentially reducing the burden of cardiovascular diseases through timely intervention.

---

## **Installation**
1. Clone the repository:
   ```bash
   git clone https://github.com/Adithya2406/Retinal-Vessel-Analysis.git
   cd Retinal-Vessel-Analysis
   ```
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Download and prepare the dataset as described from https://www.kaggle.com/datasets/andrewmvd/drive-digital-retinal-images-for-vessel-extraction.

---
## **Usage**
1. Prepare your fundus images and place them in the appropriate directory.
2. Run the main analysis script:
   ```bash
   python main.py --input data/your_images/
   ```
3. Results (segmentation masks, AVR values, and risk predictions) will be saved in the `output/` directory.
Refer to the script and documentation for additional options and advanced usage.

---
## **Results**
- Achieved 87.5% classification accuracy for hypertension and cardiovascular disease detection on validation datasets.
- Demonstrated strong correlation between AVR and cardiovascular risk, supporting its use as a non-invasive biomarker.

---
## **Contributing**
Contributions are welcome! Please open issues or pull requests for bug fixes, improvements, or new features.

---
## **Acknowledgements**
- Based on validated clinical research in retinal imaging and cardiovascular risk assessment.
- Special thanks to the open-source medical imaging community for datasets and tools.

---
For questions or support, please open an issue on the GitHub repository.
---

![Blank diagram](https://github.com/Adithya2406/Retinal-Vessel-Analysis/blob/main/Block%20diagram.png)

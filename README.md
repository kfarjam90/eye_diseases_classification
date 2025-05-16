# Eye Disease Classification Web Application

A Flask web application that classifies eye images into four categories: **Cataract**, **Diabetic Retinopathy**, **Glaucoma**, or **Normal (healthy eye)**, using a deep learning model (ResNet50V2).

[![Watch the demo video](cover.jpg)](https://www.youtube.com/watch?v=_ZpqXNtnpQk)

- **User-friendly interface** for uploading eye images (retinal scans or fundus images)
- **Real-time classification** using a trained ResNet50V2 model
- **Detailed results** showing:
  - Predicted eye condition (or normal)
  - Confidence percentage
  - Probability distribution across all classes
- **Educational information** about each eye disease
- **Responsive design** works on both desktop and mobile devices

## Prerequisites

Before you begin, ensure you have met the following requirements:
- Python 3.7 or higher
- pip package manager
- The trained model file (`resnet50v2_eye_model.h5`) placed in the `model/` directory

## Key Features

1. **Multi-Disease Detection**: Identifies common vision-threatening conditions:
   - Cataract (clouding of the eye's lens)
   - Diabetic Retinopathy (damage to retinal blood vessels)
   - Glaucoma (optic nerve damage)
   - Normal (healthy eye)

2. **Clinical Decision Support**: Provides interpretable results to aid healthcare professionals

3. **Patient Education**: Includes explanations about each condition and recommended next steps

## Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/eye-disease-classification.git

# Navigate to the project directory
cd eye-disease-classification
```

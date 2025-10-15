# README.md
readme_text = """
# Stroke Risk Predictor 🧠

**Author:** Islam Abdul Rahim Mohamed  
**Year:** 2025  

---

## Overview
This project is a Stroke Risk Prediction Web App built using Python, Scikit-learn, and Gradio.
"""

with open("README.md", "w") as f:
    f.write(readme_text)

# requirements.txt
requirements = """
pandas
numpy
scikit-learn
xgboost
imblearn
matplotlib
seaborn
gradio
joblib
"""

with open("requirements.txt", "w") as f:
    f.write(requirements)

print("✅ README.md and requirements.txt created")

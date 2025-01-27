# Brain Tumor Classification with Grad-CAM  
### _Interpretable Deep Learning for Medical Imaging_
#### By **Daniel Hatakeyama** & **John Danekind** 
---
## Poster
![Poster](images/gradcam-poster.png)

## Overview
This project demonstrates the use of **Grad-CAM (Gradient-weighted Class Activation Mapping)** <sup><a href="https://arxiv.org/abs/1610.02391">[1]</a></sup> to interpret a **Convolutional Neural Network (CNN)** trained for brain tumor classification. The goal is to visualize which regions of the input image the model focuses on when making predictions, providing insights into its decision-making process.

We demonstrate that even with apparently strong models, CNN visualization can 

For a quick overview of the project, check out the poster above or download it [here](images/gradcam-poster.png). Alternatively, check out the full implementation in the [Jupyter Notebook](brain-tumor-classification-gradcam.ipynb).

## Key Features
- **Dataset**: Brain tumor MRI images from [Kaggle](https://www.kaggle.com/).
- **Model**: CNN trained for tumor classification.
- **Grad-CAM**: Visualizes model attention and highlights regions contributing to predictions.
- **Results**: Includes heatmaps showing model interpretability.

## Requirements
The project uses the following libraries:
- TensorFlow/Keras
- NumPy
- Matplotlib
- OpenCV

See the full list in the `requirements.txt` file.

## Results
Here are some example Grad-CAM heatmaps generated by the model:

![Grad-CAM Heatmap Ex1 Healthy](images/gradcam-heatmap-ex1.png)
![Grad-CAM Heatmap Ex4 Cancer](images/gradcam-heatmap-ex4.png)


## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Questions or Feedback?
Feel free to reach out or open an issue! Contributions and suggestions are welcome.


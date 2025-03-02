# Soybean Leaf Disease Classification

This repository implements a hybrid Sequential CNN-GNN model for detecting soybean leaf diseases. The model combines efficient local feature extraction with global relational learning, and it also provides explainability through Grad-CAM and Eigen-CAM.

---

## Dataset

**Soybean Diseased Leaf Dataset**  
A high-quality image dataset featuring soybean leaves affected by **10 different diseases**.  
Access the dataset on [Kaggle](https://www.kaggle.com/datasets/sivm205/soybean-diseased-leaf-dataset).

---

## Approach

The project follows a structured approach with two main components:

- **Hybrid Sequential CNN-GNN Model:**  
  - **MobileNetV2:** Extracts local features from soybean leaf images.
  - **GraphSAGE:** Captures inter-image relational dependencies by aggregating features from neighboring nodes.
  
- **Explainable AI (XAI):**  
  Enhances the model’s interpretability using Grad-CAM and Eigen-CAM to generate visual explanations of the classification decisions.

---

## Repository Structure

- **`sequential-cnn-gnn-benchmarking.ipynb`**  
  Contains all the code for the hybrid sequential CNN-GNN model used for disease classification (excluding XAI).

- **`seq-cnn-gnn-xai.ipynb`**  
  Includes the code and output for the XAI extensions using Grad-CAM and Eigen-CAM.
---

## Usage

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/soudeep-cse/Soybean_dataset_Paper.git


2. **Download the dataset**:

   - Ensure the **Soybean Diseased Leaf Dataset** is placed in the `data` directory.

3. **Run the Jupyter Notebook**:

   - Open the Jupyter Notebook `sequential-cnn-gnn-benchmarking.ipynb` and run the cells to preprocess the data, train the models, and evaluate the results.

## Note on Requirements

All required installations and dependencies are mentioned within each notebook. There is no need to use a separate `requirements.txt` file.


## License

This project is licensed under the **MIT License**.

## Acknowledgments

- The authors of the **Soybean Diseased Leaf Dataset** for providing valuable data for research.
- The open-source community for developing essential machine learning and deep learning tools.


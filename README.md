# Biometric User Authentication with Neural Networks

A MATLAB-based project implementing neural network models for biometric user authentication. The project includes both optimized and non-optimized neural networks for user classification, along with variance analysis scripts for feature analysis.  

## Table of Contents

1. [Project Description](#project-description)    
2. [Setup and Installation](#setup-and-installation)  
3. [Usage Instructions](#usage-instructions)  
4. [Methodology](#methodology)  
5. [Contributing](#contributing)  
6. [License](#license)
#

### 1. Project Description

This project explores the use of neural networks for biometric user authentication. It involves:

- **Variance Analysis**: Analyzing inter- and intra-user feature variance.  
- **Neural Network Models**: Developing models for user classification.  
  - **Non-Optimized Models**: Basic neural network implementations.  
  - **Optimized Models**: Neural networks fine-tuned for improved accuracy and efficiency.  

The project utilizes **MATLAB** for:
- Dataset handling.  
- Variance computations.  
- Neural network training.
#
## 2. Setup and Installation
Follow these steps to set up the project on your local machine:

### 1. Clone the Repository
Run the following commands in your terminal:

```bash
git clone https://github.com/DLSNemsara/biometric-user-auth-nn.git
cd biometric-user-auth-nn
```

### 2. Ensure MATLAB is Installed
- MATLAB **R2021b** or later is recommended.  
- Required Toolboxes:
  - **Neural Network Toolbox**  
  - **Statistics and Machine Learning Toolbox**  

### 3. Dataset Preparation
- The complete dataset (`.mat` files) is located in the `CW-Data/` folder.  
- **Optional:** To avoid MATLAB path-related issues, you may copy the dataset to the respective script directories:  
  - `Neural_Networks/non_optimized/`  
  - `Neural_Networks/optimized/`  
  - `Variance_Analysis/`
#
## 3 Running Variance Analysis
1. Open MATLAB.  
2. Navigate to the `Variance_Analysis/` folder.  
3. Run the following scripts:  
   ```matlab
   compute_intra_variance
   compute_inter_variance
   ```
### Training and Testing Neural Networks

### 1. Non-Optimized Models
- Navigate to the `Neural_Networks/non_optimized/` folder.  
- Load the dataset:  
   ```matlab
   load_dataset
   ```
### 2. Optimized Models:

- Navigate to the Neural_Networks/optimized/ folder.
- Load the dataset:
  ```
  load_dataset_optimized
  ```
- Run an optimized neural network for a specific user, e.g., User 1:
  ```
  opt_nn_user01
  ```
##
### 4 Methodology

### 1. Variance Analysis
- **Intra-Variance:** Computes the variability within a user's biometric data.  
- **Inter-Variance:** Computes the variability between different users.  

### 2. Neural Network Models
- **Non-Optimized Models:** Simple architectures used to establish baseline performance.  
- **Optimized Models:** Fine-tuned architectures with additional layers and parameters to improve results.  
#
## 5 Contributing
Contributions are welcome! Please follow these steps:

### 1. Fork this repository.
### 2. Create a new branch:
```
git checkout -b feature-name
```
### 3. Commit your changes and push the branch:
```
git push origin feature-name
```
### 4.Open a Pull Request.
#
## 6 License
This project is licensed under the MIT License. See the LICENSE file for more details.



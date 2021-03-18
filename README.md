# GSOC-2021-ATLAS-Autoencoders
Evaluation Exercise

## Steps:
>### 1. Data Manipulation (Data_Manipulation.ipynb)
>#### Converting csv to pickle along with some preprocessing:
><ul>
><li>Selecting only jet particles (id = 'j')</li>
><li>In case more than one jet particle in an event, keeping all of them</li>
></ul>

>### 2. Data Preprocessing and Visualization (Data_Analysis.ipynb)
>#### Trying different normalization methods and visualizing training data:
><ul>
><li>Standard Normalization</li>
><li>Custom Normalization</li>
></ul>

>### 3. Training and Benchmarking different autoencoder variants for data compression
><ul>
><li>Tanh Activation with no Batchnorm & Custom Normalization (AE_3D_200_Tanh.ipynb)</li>
><li>Elu Activation with no Batchnorm & Custom Normalization (AE_3D_200_Elu.ipynb)</li>
><li>Tanh Activation with Batchnorm & Custom Normalization (AE_3D_200_Tanh_BatchNorm.ipynb)</li>
><li>Elu Activation with Batchnorm & Custom Normalization (AE_3D_200_Elu_BatchNorm.ipynb)</li>
></ul>

>### 4. Visualizing reconstructions and residuals from different autoencoder variants

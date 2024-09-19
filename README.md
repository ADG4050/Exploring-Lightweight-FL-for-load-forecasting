# Light Weight-Federated-Learning-Approach-towards-Smart-Energy-Meter-Dataset

This paper was accepted at IEEE SmartGridComm 2023 and was part of the MSc Thesis at Trinity College Dublin. 

The project focuses on simulating a Federated Learning framework using the London Household smart energy meter dataset. The primary objective is to achieve comparable accuracy in load forecasting to state-of-the-art (SOTA) technologies while demonstrating the preservation of data privacy through Federated Learning (FL). Additionally, since smart meters often have limited computational power, small sequential dense neural networks (DNN) are utilized to address this constraint. The simulation is performed using TensorFlow Federated Libraries and Framework. To install TensorFlow Federated (TFF), refer to the [official TFF installation guide](https://www.tensorflow.org/federated/install).

- **IEEE SmartGridComm Paper**: [Exploring Lightweight Federated Learning for Distributed Load Forecasting](https://ieeexplore.ieee.org/abstract/document/10333889)
- **Conference Presentation**: [YouTube Video](https://www.youtube.com/watch?v=B6IFo5cdIcc&t=91s)
- **Dataset Information**: [London Smart Energy Meter Dataset](https://data.london.gov.uk/dataset/?q=energy)

## Citation

For further research and use of the code, please cite the following:

```
@INPROCEEDINGS{10333889,
  author={Duttagupta, Abhishek and Zhao, Jin and Shreejith, Shanker},
  booktitle={2023 IEEE International Conference on Communications, Control, and Computing Technologies for Smart Grids (SmartGridComm)}, 
  title={Exploring Lightweight Federated Learning for Distributed Load Forecasting}, 
  year={2023},
  volume={},
  number={},
  pages={1-6},
  keywords={Meters;Training;Energy consumption;Data privacy;Load forecasting;Federated learning;Predictive models;Federated learning;deep neural networks;Non - i.i.d distribution;data heterogeneity},
  doi={10.1109/SmartGridComm57358.2023.10333889}}
```

## Requirments
```
Python 3.x
TensorFlow Federated (tensorflow-federated)
TensorFlow (tensorflow)
Pandas (pandas)
NumPy (numpy)
Google Colab (optional, for executing the code in a cloud environment)
```

## Code Structure

The implementation of TensorFlow Federated (TFF) on the energy meter dataset is organized in the following Jupyter notebooks:
```
Weekly Analysis Code: Code/Weekly_Analysis.ipynb
Monthly Analysis Code: Code/Monthly_Analysis.ipynb
Short Term Daily Analysis Code with Custom Loss Function (Main Code): Code/Short_Term_FC_custom_LF.ipynb
```

### Other Notebooks:
```
Data Cleaning and K-Means Application: Code/datacl_kmeans_final.ipynb
Custom TFF Algorithms for Checking Global and Local Weights: Code/Customized_TFF_Functionalities.ipynb
Centralized Model Code: Code/Centralized_model.ipynb
```

## Contacts
For Queries, please contact aduttagu@tcd.ie

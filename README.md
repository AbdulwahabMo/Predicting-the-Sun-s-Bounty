# Predicting the Sun's Bounty
Developed by Mohamad Moussa & Abdulwahab AlGhamdi

# Abstract
This paper explores advanced artificial intelligence (AI) models for photovoltaic (PV) power generation prediction in Saudi Arabia. With the nation's shift towards 50% renewable energy by 2030, solar power's integration into the grid faces challenges like dust accumulation and solar irradiation variability. We examine AI models, including non-linear regression, convolutional neural networks, recurrent neural networks, and hybrid approaches, to enhance forecasting accuracy. Our study analyzes these models using real-world data, assessing their accuracy and computational efficiency, and discusses implications for grid integration and energy management. This research contributes to Saudi Arabia's renewable energy ambitions, demonstrating AI's potential in optimizing solar power utilization.

# Results
*Performance Measures*
| Model | MSE | R^2 |
|----------|----------|----------|
| LSTM    | 0.0244     | 0.745     |
| GRU    | 0.0244     | 0.7520     |
| ConvLSTM    | 0.0221     | 0.7769     |
| Time2Vec    | 0.195     | 0.7920     |
| N-Beats    | 0.188     | 0.8066     |
| Vanilla Transformer     | 0.198     | 0.7633     |
| Regression    | 0.0249     | 0.7616     |

*Sample Plots with best achieving model "ConvLSTM" (Learning Curve & Feature Importance)*
 | Training & Validation Errors Curve | Feature Importance |
|----------|----------|
| ![image](https://github.com/WahabMo/Predicting-the-Sun-s-Bounty/assets/147597043/fa1f8b0b-bba4-4b04-a038-4ad2afe6dc85)| ![image](https://github.com/WahabMo/Predicting-the-Sun-s-Bounty/assets/147597043/7a8f7d37-ecfe-4118-95b8-89f8e0c4ea00)|

# Data

Spanning several years and encompassing a vast array of input parameters, 
the used dataset, has over 88,000 data points (comulatively), 
offering a comprehensive historical record of a specific PV module. 

It will run automatically once the code is executed or you can download it from this ![link](https://github.com/WahabMo/Predicting-the-Sun-s-Bounty/blob/main/dataset.csv).

# Running the Code
Requirements:
Following are the python libraries required to run the code. 

"('pandas': '1.5.3',
 'numpy': '1.23.5',
 'matplotlib': '3.7.1',
 'scikit-learn': '1.2.2',
 'keras': '2.15.0',
 'pytorch': '2.1.0+cu121')"

# Training and Testing
To run the code, you only need to run the code ("main.py"). Accordingly, same results would appear and you may adjust the parameters if needed.

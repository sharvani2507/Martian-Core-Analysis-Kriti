# Martian Core Project

This project focuses on the study of Mars' core, utilizing seismic data to estimate and analyze its internal structure. The core radius, depth, and the behavior of seismic waves within Mars' layers are examined using a combination of theoretical models and observed data from the InSight lander. The project aims to reconcile calculated and observed core radius values, identify discrepancies, and provide an in-depth analysis of Mars' interior.

## Overview

The Martian Core Project is divided into several key modules that cover different aspects of seismic data analysis, the core-mantle boundary, and the discrepancies between theoretical models and observed data. The modules include:

- **Module 1**: Introduction to Seismic Signal Analysis
- **Module 2**: Feature Extraction and Seismic Wave Processing
- **Module 3**: Seismic Data Preprocessing and Noise Removal
- **Module 4**: Core Radius Calculation
- **Module 5**: Seismic Wave Behavior and Analysis
- **Module 6**: Conclusion and Further Insights
- **Module 7**: Radius Prediction
- **Module 8**: Anomaly Detection
- **Module 9**: PINN Implementation

Each module contributes to understanding the core structure of Mars and provides valuable insights for future exploration missions.

## Modules Overview

### Module 1: Introduction to Seismic Signal Analysis
In this module, we explore the importance of seismic signal analysis in understanding the subsurface structure of planetary bodies like Mars. Seismic signals are used to extract critical features such as amplitude, frequency, and phase characteristics, which aid in detecting different layers within the planet.

### Module 2: Feature Extraction and Seismic Wave Processing
We describe the feature extraction techniques used to analyze seismic waveforms, focusing on amplitude extraction, frequency analysis, and phase shift detection. These methods allow for better interpretation of seismic data and provide insights into the composition and structure of Mars' interior.

### Module 3: Seismic Data Preprocessing and Noise Removal
The preprocessing of seismic data plays a vital role in cleaning up raw measurements. In this module, we detail the steps to remove noise from seismic signals, ensuring that the data used for analysis is reliable and accurate.

### Module 4: Core Radius Calculation
This module covers the calculation of Mars' core radius based on the given total radius and core-mantle boundary depth. The core radius is estimated using the formula \( R_c = R - d \), where \( R \) is the total radius of Mars, and \( d \) is the depth of the core-mantle boundary.

### Module 5: Seismic Wave Behavior and Analysis
This module delves into how seismic waves behave as they travel through Mars' interior. We analyze how P-waves and S-waves interact with different layers, helping to determine the composition and depth of the core-mantle boundary.

### Module 6: Conclusion and Further Insights
In this module, we summarize the findings of the project and outline future directions. We discuss how more sophisticated models and additional seismic data could refine our understanding of Mars' core.

### Module 7: Radius Prediction
This module focuses on predicting the core radius of Mars using advanced machine learning algorithms. By analyzing seismic data and other planetary parameters, the model can estimate the core radius more accurately, helping to resolve discrepancies between theoretical calculations and observed data.

### Module 8: Anomaly Detection
In this module, we implement anomaly detection techniques to identify unusual seismic activity within Mars' interior. By applying statistical models and machine learning algorithms, the system can automatically flag potential anomalies in seismic data, which may indicate unusual core activity or structural changes.

### Module 9: PINN Implementation
The final module implements Physics-Informed Neural Networks (PINNs) to model the behavior of seismic waves in Mars' core and mantle. By incorporating physical laws directly into the neural network architecture, we aim to predict core properties and seismic wave patterns with high accuracy, even in the presence of limited data.

## Setup Instructions

To set up this project locally, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/martian-core-project.git
    cd martian-core-project
    ```

2. **Install the necessary Python packages**:
    Create a `requirements.txt` file listing all required packages, and install them:
    ```bash
    pip install -r requirements.txt
    ```

3. **Prepare your dataset**:
    Make sure your seismic data is in the appropriate format for analysis. You can find sample data in the `data/` directory.

4. **Run the analysis script**:
    The main script for seismic analysis is located in the `src/` directory. To execute it, run:
    ```bash
    python src/main.py
    ```

## Dataset

The dataset used for this project contains seismic data with columns like `arrival time`, `relative time`, and `velocity of seismic waves`. The data is used for calculating core radius and analyzing seismic wave propagation within Mars.

## Results

The project includes several analyses based on seismic data:
- Core radius calculations.
- Comparison of observed and calculated values.
- Analysis of seismic wave behavior.
- Estimations of Mars' core structure.

## Challenges and Limitations

- **Data Accuracy**: The seismic data provided by InSight may contain errors or be incomplete, which affects the results.
- **Model Limitations**: The theoretical model used to calculate core radius is simplified and may not account for all the complexities of Mars' core.
- **Seismic Wave Propagation**: Understanding how seismic waves travel through Mars' layered interior requires careful consideration of the properties of each layer.

## Future Directions

- **Real-World Seismic Data**: Use more extensive and detailed seismic data from future missions to improve the model's accuracy.
- **Advanced Models**: Incorporate advanced machine learning techniques and deep learning to analyze seismic waves in real time.
- **Core Composition**: Investigate the chemical composition of Mars' core to refine the radius estimation.
- **Global Seismic Network**: Develop a global seismic network for Mars to monitor seismic activity and better understand the core and mantle structure.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Thanks to NASA and the InSight team for providing invaluable seismic data.
- Thanks to the scientific community for their contributions to understanding planetary interiors.

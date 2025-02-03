# Martian-Core-Analysis-Kriti-Dhansiri

# Seismic Signal Analysis and Shadow Zone Classification

## Overview
This project focuses on analyzing seismic signals and classifying shadow zones using machine learning techniques. The goal is to extract meaningful features from seismic waveforms, including amplitude, frequency, and phase characteristics, to identify shadow zones. The methodology involves feature extraction, data preprocessing, and classification using machine learning models like Random Forest.

## Features
- **Amplitude Extraction**: Includes peak detection, RMS amplitude, envelope function derivation, and statistical measures like variance and standard deviation.
- **Frequency Analysis**: Utilizes Fast Fourier Transform (FFT), Power Spectral Density (PSD), and Wavelet Transforms for identifying frequency components.
- **Phase Shift Detection**: Involves using Hilbert Transform, instantaneous phase calculation, and phase spectrum analysis.
- **Data Preprocessing**: Includes normalization, dataset splitting, and cross-validation.
- **Machine Learning Classification**: Uses the Random Forest classifier for shadow zone classification, evaluated with accuracy, precision, recall, and F1 score.

## Setup Instructions

To set up this project locally, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/seismic-analysis.git
    cd seismic-analysis
    ```

2. **Install the necessary Python packages**:
    Create a `requirements.txt` file (if not already available) that lists all required packages. Install them by running:
    ```bash
    pip install -r requirements.txt
    ```

3. **Prepare your dataset**:
    Make sure your seismic signal data is in the appropriate format (with columns like amplitude, frequency, and phase information).

4. **Run the main analysis script**:
    ```bash
    python src/main.py
    ```

## Dataset
The dataset for this project should have the following columns:
- `signal_data`: Raw seismic signal data (numerical array format).
- `label`: Target classification (e.g., `0` for no shadow zone, `1` for shadow zone).

Ensure your dataset follows the required format before running the analysis.

## Model and Evaluation

### Model
The machine learning model used in this project is a **Random Forest Classifier**, which classifies seismic signals into shadow zones.

### Evaluation Metrics
The model is evaluated using:
- **Accuracy**: Overall model accuracy.
- **Precision**: Precision score for positive classifications.
- **Recall**: Recall score for identifying positive instances.
- **F1 Score**: Harmonic mean of precision and recall.

## Results
Model performance will be evaluated based on the metrics above. Additionally, representative predictions will demonstrate how amplitude, frequency, and phase characteristics affect classification.

## Challenges and Limitations

- **Data Generation**: Synthetic datasets need careful calibration to represent real-world seismic events.
- **Feature Engineering**: Feature extraction methods may require iterative refinement for optimal performance.

## Future Directions

- Expand the dataset with real-world seismic data for better model generalization.
- Explore deep learning techniques for improved performance.
- Integrate additional features like wave dispersion and attenuation properties.
- Develop a real-time seismic event detection system using the proposed methodology.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Thanks to the researchers and contributors to seismic data and analysis techniques.

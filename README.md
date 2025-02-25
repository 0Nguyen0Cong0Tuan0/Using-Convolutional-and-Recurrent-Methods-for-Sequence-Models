# Using Convolutional and Recurrent Methods for Sequence Models

This repository explores **Convolutional Neural Networks (CNNs)** and **Recurrent Neural Networks (RNNs)** for time series prediction. The project builds on deep neural networks by adding convolutional layers and experimenting with different recurrent architectures such as **Simple RNNs, GRUs, and LSTMs**.

## Features
- Application of **CNNs and RNNs** for sequence modeling.
- Experimentation with **different network architectures**.
- Hyperparameter tuning for improved accuracy.
- Real-world datasets including long-term temperature records.
- Implementation of **trend analysis, seasonality detection, and noise modeling**.

## Installation
To run the project, install the required dependencies:

```bash
pip install -r requirements.txt
```

## Usage
Run the Jupyter Notebook to explore the models:

```bash
jupyter notebook main.ipynb
```

## Code Overview
- **Data Preparation**: Functions for generating synthetic time series data, including trend, seasonality, and noise.
- **Model Building**: Implementation of CNNs, Simple RNNs, GRUs, and LSTMs.
- **Hyperparameter Tuning**: Using Keras Tuner for optimizing network performance.
- **Visualization**: Plotting time series trends and model performance.

## Results
The models demonstrate how different architectures impact the ability to predict time series data. Convolutional layers help capture patterns, while recurrent networks like GRUs and LSTMs improve long-term dependencies.

## Contributing
Feel free to open issues or submit pull requests if you’d like to contribute to this project.

## License
This project is licensed under the MIT License.


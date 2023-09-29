# Dr. Crop - Web-based ML and DL Application

![Dr. Crop Logo]

Dr. Crop is a web-based Machine Learning and Deep Learning application designed to assist farmers in making informed decisions regarding crop management. This application consists of three main modules: Crop Recommendation, Fertilizer Recommendation, and Image Disease Prediction.

## Table of Contents

- [Datasets](#datasets)
- [Modules](#modules)
  - [1. Crop Recommendation](#1-crop-recommendation)
  - [2. Fertilizer Recommendation](#2-fertilizer-recommendation)
  - [3. Image Disease Prediction](#3-image-disease-prediction)
- [Features](#features)
- [Getting Started](#getting-started)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)

## Datasets

- [Crop Recommendation Dataset]{https://www.kaggle.com/datasets/atharvaingle/crop-recommendation-dataset}
- [Fertilizer Recommendation Dataset]{https://www.kaggle.com/datasets/amankumar1007/fertilizer-recommendation}
- [Image Disease Prediction Dataset]{https://www.kaggle.com/datasets/vipoooool/new-plant-diseases-dataset}

## Modules

### 1. Crop Recommendation

The Crop Recommendation module leverages machine learning algorithms to provide farmers with personalized crop recommendations based on various factors such as soil type, climate, and historical crop performance data. It helps farmers make optimal choices when selecting the crops to cultivate, taking into account their specific conditions.

### 2. Fertilizer Recommendation

The Fertilizer Recommendation module uses data-driven approaches to suggest the appropriate types and quantities of fertilizers for a given crop and soil condition. By analyzing soil nutrient levels and crop nutrient requirements, it helps farmers maximize crop yields while minimizing fertilizer costs and environmental impact.

### 3. Image Disease Prediction

The Image Disease Prediction module employs deep learning techniques to diagnose crop diseases from images captured by farmers. It can identify common crop diseases and provide timely recommendations for disease management. This enables farmers to take proactive measures to protect their crops from diseases, ultimately increasing crop productivity.

## Features

- User-friendly web interface for easy access and interaction.
- Data-driven recommendations for crop selection and fertilizer application.
- Deep learning-powered image analysis for disease detection.
- Personalized advice based on location-specific data.
- Historical data tracking and reporting for improved decision-making.

## Getting Started

To run Dr. Crop on your local machine, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/ChaitanyaSirivuri/DrCrop
   ```

2. Navigate to the project directory:

   ```bash
   cd DrCrop
   ```

3. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Start the web application:

   ```bash
   python app.py
   ```

5. Open a web browser and access Dr. Crop at [http://localhost:8000](http://localhost:8000).

## Dependencies

Dr. Crop relies on several Python libraries and frameworks, including:

- Flask
- PyTorch
- Scikit-learn
- and more (see `requirements.txt` for a complete list).

## Contributing

We welcome contributions from the community. If you'd like to contribute to the development of Dr. Crop, please fork the repository and submit pull requests with your changes. Be sure to follow our [code of conduct](CODE_OF_CONDUCT.md).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Happy farming with Dr. Crop! 🌾🌱🚜

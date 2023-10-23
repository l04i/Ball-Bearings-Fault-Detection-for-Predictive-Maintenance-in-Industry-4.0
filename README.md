# Machine Learning Approach for Predictive Maintenance

## Description
This project focuses on predictive maintenance using machine learning techniques for bearing fault detection. The goal is to develop models that can accurately predict the occurrence of faults in the CWRU ball bearing dataset.

## Dataset
The dataset used in this project is the CWRU ball bearing dataset, which contains vibration signals from different types of bearing faults. The dataset is available [here](link_to_dataset).

## Algorithms
The following machine learning algorithms have been implemented and evaluated in this project:
1. RandomForestClassification
2. KNeighborsClassification
3. ArtificialNeuralNetworks
4. GradientBoostingClassification
5. Naive Bayes

For each algorithm, nine models have been trained and tested for different fault types:
- B007
- B014
- B021
- IR007
- IR014
- IR021
- OR007
- OR014
- OR021


## Usage
To use this project, follow these steps:
1. Clone the repository: `git clone https://github.com/your_username/your_repository.git`
2. Install the required dependencies: `pip install -r requirements.txt`
3. Run the main script: `python main.py`

## Results
The performance of each algorithm and model combination has been evaluated using various metrics, such as accuracy, precision, recall, F1-score , confusion matricies and ROC cuves. The results can be found in the `results/` directory.

## Contributing
Contributions to this project are welcome. If you find any issues or have suggestions for improvement, feel free to open an issue or submit a pull request.


## Acknowledgments
- This project is based on the CWRU ball bearing dataset provided by [Case Westren Reserve University](https://engineering.case.edu/bearingdatacenter).

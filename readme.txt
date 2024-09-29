Wholesale customers dataset
DA2-BIG DATA ANALYTICS
Priyal Alphonsa Binu 22MIS1102

#About the dataset
This dataset provides insights into clients of a wholesale distributor, detailing their annual spending across various product categories. 
It contains a total of 440 samples, where each entry represents the annual spending in monetary units (m.u.) on different types of products.

#Key Features
Channel: Type of client (e.g., Horeca or retail).
Region: Geographic region of the client.
Fresh: Annual spending on fresh products (m.u.)
Milk: Annual spending on milk products (m.u.)
Grocery: Annual spending on grocery products (m.u.)
Frozen: Annual spending on frozen products (m.u.)
Detergents_Paper: Annual spending on detergents and paper products (m.u.)
Delicassen: Annual spending on delicatessen products (m.u.)

#Requirements
Python 3.x
numpy
pandas
matplotlib
minisom

You can install the required packages using pip:
pip install numpy pandas matplotlib minisom

#project overview
This project employs Self-Organizing Maps (SOM) to analyze spending patterns of wholesale customers.
The primary goal is to visualize customer segments based on their annual spending behavior across various product categories.

#steps involved
Data Loading: Load the wholesale customers dataset.
Data Preprocessing: Extract relevant features for analysis.
SOM Initialization: Set up the SOM with specified parameters.
Training: Train the SOM using the extracted data.
Visualization: Create visual representations of the SOM distance map and customer behavior patterns.

#How to Run the Implementation
Download the dataset and place it in the same directory as the script, naming it Wholesale customers data.csv.
Run the script using the following command:
python som_analysis.py

#Hardware Requirements
Any machine capable of running Python 3.x.
A minimum of 4GB RAM is recommended for efficient execution.

#Software Requirements
Python 3.x: The programming language used for implementing the analysis.
Libraries:
NumPy: A library for numerical operations and handling arrays.
Pandas: A library for data manipulation and analysis, particularly with data frames.
Matplotlib: A plotting library for creating visualizations.
MiniSom: A library specifically for creating and training Self-Organizing Maps.

#Author
Priyal Alphonsa Binu
22MIS1102


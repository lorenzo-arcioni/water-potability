# Water Potability

### Data Analysis and Machine Learning Modeling for water potability

In this study, we conducted an analysis of a dataset containing various features related to water quality to determine the potability of the water.


- **pH value:** A parameter that evaluates the acid-base balance of water, indicating its acidic or alkaline condition. WHO recommends a pH range of 6.5 to 8.5 for water.

- **Hardness:** Caused by dissolved calcium and magnesium salts in water, which come from geological deposits. The longer water is in contact with these materials, the higher the hardness.

- **Solids (Total dissolved solids - TDS):** Water can dissolve various inorganic and organic minerals or salts, affecting its taste and appearance. High TDS values indicate high mineralization. The desirable limit for TDS in drinking water is 500 mg/L, with a maximum limit of 1000 mg/L.

- **Chloramines:** Disinfectants used in public water systems, formed by adding ammonia to chlorine for water treatment. Safe chlorine levels for drinking water are up to 4 mg/L.

- **Sulfate:** Naturally occurring substances found in minerals, soil, rocks, and various sources. Sulfate concentrations vary but generally range from 3 to 30 mg/L in freshwater. Seawater has a sulfate concentration of about 2700 mg/L.

- **Conductivity:** Pure water is a poor conductor of electricity, but increased ion concentration enhances its electrical conductivity. The WHO standard sets a maximum electrical conductivity (EC) value of 400 μS/cm.

- **Organic_carbon:** Total Organic Carbon (TOC) measures the amount of carbon in organic compounds in water. The US EPA sets a limit of < 2 mg/L in treated/drinking water and < 4 mg/L in source water for treatment.

- **Trihalomethanes:** Chemicals that can be found in water treated with chlorine. The concentration of THMs in drinking water depends on various factors. Up to 80 ppm is considered safe.

- **Turbidity:** Measures the quantity of solid matter suspended in water, affecting its light-emitting properties. Turbidity is used to indicate the quality of waste discharge. The mean turbidity value obtained for Wondo Genet Campus is lower than the WHO recommended value of 5.00 NTU.

- **Potability:** Indicates whether water is safe for human consumption, with a value of 1 meaning potable and 0 meaning not potable.

After analyzing the dataset, we utilized machine learning techniques to develop a predictive model for water potability based on the provided features. The model aims to determine the safety of water for human consumption. By training the model on a subset of the dataset and evaluating its performance, we can assess its accuracyand predictive capabilities.
The analysis involved visualizing the relationships between different features using various graphs and charts. For example, scatter plots were used to examine the correlation between pH value and potability, hardness and potability, and other relevant combinations.
Furthermore, statistical analyses were conducted to gain insights into the distribution of each feature and their impact on water potability.
To build the machine learning model, we employed various classification algorithms. The dataset was divided into training and testing sets to evaluate the model's performance accurately. The model was trained on the training set, and its predictive ability was assessed using the testing set.
Evaluation metrics such as accuracy, precision, recall, and F1-score were used to measure the model's performance. Cross-validation techniques such as k-fold cross-validation were applied to ensure the model's generalizability and robustness.

By combining the data analysis with the machine learning model, we aimed to provide a comprehensive understanding of the water quality and its potability based on the given dataset. The results obtained from this analysis can be valuable for water management authorities, policymakers, and researchers in making informed decisions regarding water treatment and ensuring the safety of drinking water for the population.

#### Pre trained model
In the models directory there are pre-trained model to use inside the Jupyter notebook. 
You have just to load them in the cells with fast load and test label!

#### Conda virtual environment
To ensure the lean execution of the notebook, i've insert a conda environment yml to use.

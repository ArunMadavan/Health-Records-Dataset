1. The dataset is a health records dataset of patients diagnosed with a certain disease, containing various categories of health records such as diseases diagnosis, tests, symptoms, and drug treatments.
2. The data is available in train and test files in parquet format
3. The problem statement aims to build a predictive model that estimates if a patient is eligible for the first prescription of the "Target Drug" in the next 30 days, to improve patient outcomes and reduce the risk of life-threatening side effects by identifying patients who can benefit from the "Target Drug" therapy.
4. The next step is to perform feature engineering using frequency-based, time-based features, and deep learning techniques to build a predictive model that identifies eligible patients.
5. Using each patient's historical data, the built model predicts if he/she is eligible for the "Target Drug" and assigns a binary value of 1 or 0, where 1 is considered eligible and 0 considered un-eligible.
6. The project was implemented using Python and various data science libraries like Pandas, NumPy, and Scikit-Learn, to preprocess the data, perform feature engineering, and build a predictive model that leverages deep learning techniques.
7. The evaluation metric used for the assignment is F1-Score, a measure of the model's accuracy in identifying eligible patients.

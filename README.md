# CDSS
Clinical Decision Support System (CDSS) for Antibiotic Resistance &amp; Dosing Prediction.
clinical-cdss-project/
│
├── data_pipeline.py    # Simulates clinical patient data (Pandas/NumPy)
├── model_engine.py     # Trains a classifier to predict resistance (Scikit-Learn)
├── dosage_solver.py    # Calculus-based clearance optimization function
└── app_orchestrator.py # Executable orchestrator combining data & models

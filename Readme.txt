🧪 **Clinical Data Processing**

This repository contains a comprehensive suite of Jupyter notebooks for clinical data preprocessing, feature engineering, and quality control. It is particularly tailored for analyzing longitudinal datasets such as those used in neurological disease progression (e.g., MS).

📌 **Overview**
The pipeline handles tasks like:

    🧬 Feature selection and generation

    🧹 Outlier detection and data cleaning

    📅 Time-based feature extraction

    📈 Disease progression tracking

    🎯 Score normalization

    ✅ Data validation and quality control

Each notebook is modular, enabling flexible use based on your analysis needs.

📂 Scripts Breakdown
🔧 Core Preprocessing & Feature Engineering
No.	Notebook	Description
1️⃣	Select_Important_Features_From_Original.ipynb	Selects key features from the raw dataset
1️⃣.5️⃣	Update_Original_Data.ipynb	Updates and integrates engineered features
2️⃣	Year_Month_DateOfVisit.ipynb	Extracts year and month from visit dates
3️⃣	Relapse_Feature.ipynb	Creates a binary relapse feature
4️⃣	Treatment.ipynb	Encodes treatment-related data
5️⃣	MSSS_Progression_Features.ipynb	Derives MSSS progression features
6️⃣	Delete_Duplicate_Age_at_Visit_Date.ipynb	Removes duplicate records by age and date
7️⃣	MSSS_Score.ipynb	Calculates MSSS scores from clinical metrics
8️⃣	Feature_Selection_for_MSSS_Data_Visualization.ipynb	Selects features for MSSS visualization
9️⃣	Season_Feature_Generation.ipynb	Generates seasonal labels (Spring, Summer, etc.)
🔟	Outlier_Detection.ipynb	Identifies statistical outliers
1️⃣1️⃣	Round_SubScores.ipynb	Rounds subscores for consistency
🛠️ Utility Notebooks
Notebook	Description
📊 __Compare_two_CSV.ipynb	Compares two CSV files side-by-side
📈 __First_Last_Obs.ipynb	Extracts first and last visits per subject
🔢 __N_Observation_per_Subject.ipynb	Counts observations per subject
🚀 Getting Started

Each notebook can be run independently, but for full reproducibility, it's recommended to follow them in order (1 → 11).

You can start by cloning the repo:

git clone https://github.com/your-username/clinical-data-processing.git

Open the notebooks in your preferred Jupyter environment (e.g., Jupyter Lab, VS Code, Google Colab).

# Cloud Privilege Escalation Attack Detection

## Overview
This project implements a machine learning system to detect and mitigate insider threats in cloud environments, focusing on privilege escalation attacks.

## Technologies Used
- **Backend:** Python
- **Machine Learning:** Scikit-learn, LightGBM, XGBoost, AdaBoost, Random Forest
- **Data Handling:** Pandas, NumPy
- **Web Framework:** Flask (optional)
- **Database:** SQLite3

## Features
- Detection of insider threats using various ML algorithms.
- Ensemble learning for improved accuracy.
- High detection accuracy (LightGBM: 97%).

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/project-repo.git
   cd project-repo
   ```
2. Set up a virtual environment (optional):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
Run the main script:
```bash
python main.py
```

## Dataset
Utilizes a customized dataset from the CERT dataset for insider threat detection.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request.

## License
This project is licensed under the MIT License.

---

Feel free to replace `yourusername` with your actual GitHub username and adjust any other details as necessary!

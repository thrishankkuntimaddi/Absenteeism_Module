# Absenteeism Module: Predicting Employee Absenteeism 📊

This repository contains a Python-based **Absenteeism Module** designed to predict employee absenteeism using machine learning techniques. The module processes employee data to forecast the likelihood of absenteeism, enabling organizations to proactively manage workforce attendance.

---

## 🔧 Features

- **Data Preprocessing**: Cleans and prepares raw absenteeism data for analysis.
- **Machine Learning Model**: Utilizes logistic regression to predict absenteeism probabilities.
- **Custom Scaler**: Implements a custom scaler for feature normalization.
- **Prediction Module**: Provides an interface to input new data and obtain absenteeism predictions.

---

## 🛠️ Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/thrishankkuntimaddi/Absenteeism_Module.git
   cd Absenteeism_Module
   ```

2. **Install dependencies**:
   Ensure Python is installed, then install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

3. **Prepare the data**:
   - Place the absenteeism dataset in the appropriate directory and update the path in the script if necessary.

4. **Run the module**:
   ```bash
   python absenteeism_module.py
   ```

---

## ⚙️ Configuration

- **Data Path**: Update the dataset path in `absenteeism_module.py` to point to the correct location of your absenteeism data.
- **Model Parameters**: Adjust model parameters such as regularization strength and feature scaling options in the script for experimentation.

---

## 📂 Project Structure

- `absenteeism_module.py` - The main script for training and predicting absenteeism.
- `data/` - Directory to store the absenteeism dataset.
- `model/` - Stores the trained machine learning model.
- `requirements.txt` - Lists dependencies required to run the project.

---

## 📈 Future Enhancements

- **Advanced Models**: Integrate additional machine learning models such as Random Forests or Gradient Boosting to improve accuracy.
- **Web Interface**: Develop a simple web interface to allow HR personnel to easily interact with the absenteeism prediction system.
- **Extended Feature Engineering**: Include more features such as employee engagement scores, work environment factors, etc., to enhance prediction quality.

---

## 🤝 Contributing

This project is open for contributions! Feel free to fork the repository, make changes, and submit a pull request. Your suggestions and enhancements are always welcome to improve the prediction module.

---

## 📞 Contact

For any questions or support, feel free to reach out to [Thrishank Kuntimaddi](https://github.com/thrishankkuntimaddi).

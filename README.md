# AutoBrain-ML
**Intelligent Automated Machine Learning Framework**

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-Latest-green)
![Status](https://img.shields.io/badge/Status-In%20Development-yellow)

## 💻 Project Overview

AutoBrain-ML is an intelligent AutoML system that automatically builds, trains, and optimizes machine learning and deep learning models based on user preferences and system capabilities. The system streamlines the entire ML workflow from data preprocessing to model deployment with minimal user intervention.

## 🎯 Key Features

✅ **User Preference Integration**
- Model type selection (Regression/Classification/Neural Networks)
- Customizable neural network architecture (hidden layers configuration)
- Performance vs Speed optimization options

✅ **Intelligent System Analysis**
- Automatic hardware detection (RAM, CPU, GPU)
- Dynamic model complexity adjustment
- Resource-optimized training

✅ **Automated Data Processing**
- Smart encoding for categorical variables
- Automatic scaling and normalization
- Intelligent missing value handling
- Feature engineering pipeline

✅ **Comprehensive Model Building**
- ML Models: Random Forest, SVM, Logistic Regression, Linear Regression
- Deep Learning: Custom neural networks with user-defined architecture
- Ensemble methods and model stacking

✅ **Advanced Optimization**
- Hyperparameter tuning with GridSearchCV
- Bayesian optimization using Optuna
- Automated feature selection

✅ **Model Evaluation & Export**
- Comprehensive performance metrics
- Model comparison and ranking
- Export best models (.pkl for ML, .h5 for DL)
- Visualization of results

## 🛠️ Technology Stack

### Core Libraries
- **NumPy** - Numerical computations
- **Pandas** - Data manipulation and analysis
- **Scikit-learn** - ML models and preprocessing
- **TensorFlow/PyTorch** - Deep learning frameworks

### System & Optimization
- **psutil** - System hardware detection
- **GPUtil** - GPU monitoring
- **GridSearchCV** - Hyperparameter tuning
- **Optuna** - Advanced optimization

### Visualization & Export
- **Matplotlib** - Data visualization
- **Seaborn** - Statistical graphics
- **Joblib** - Model serialization

## 📊 Datasets Used

### Classification Tasks
- Iris Dataset
- Titanic Dataset
- Breast Cancer Dataset
- UCI ML Repository datasets

### Regression Tasks
- Boston Housing Dataset
- California Housing Dataset
- Custom tabular datasets

### Neural Network Tasks
- MNIST Dataset
- Fashion-MNIST Dataset
- Custom image datasets

## 👥 Team Members & Responsibilities

### Disoor - Project Lead & System Integration
- Overall project architecture and coordination
- System hardware detection module
- Final integration and testing
- Documentation and deployment

### Yogi - Data Preprocessing & Feature Engineering
- Data loading and validation
- Missing value handling
- Feature scaling and normalization
- Categorical encoding

### Nesan - ML Models & Algorithm Implementation
- Scikit-learn model implementation
- Random Forest, SVM, Regression models
- Model training pipeline
- ML model evaluation

### Bharath - Neural Network Architecture
- TensorFlow/PyTorch implementation
- Custom neural network builder
- Layer configuration system
- Deep learning model training

### Arun - Hyperparameter Optimization
- GridSearchCV implementation
- Optuna integration
- Parameter tuning strategies
- Optimization result analysis

### Sanjith - Model Evaluation & Export
- Performance metrics calculation
- Model comparison framework
- Model export functionality (.pkl/.h5)
- Results visualization

## 📁 Project Structure

```
AutoBrain-ML/
├── data/                    # Dataset directory
├── src/
│   ├── preprocessing/      # Data preprocessing modules
│   ├── models/             # ML/DL model implementations
│   ├── optimization/       # Hyperparameter tuning
│   ├── evaluation/         # Model evaluation
│   └── utils/              # Utility functions
├── notebooks/              # Jupyter notebooks for testing
├── models/                 # Saved models directory
├── results/                # Results and visualizations
├── requirements.txt        # Project dependencies
├── README.md               # Project documentation
└── main.py                 # Main execution script
```

## 🚀 Installation

```bash
# Clone the repository
git clone https://github.com/DisoorS/AutoBrain-ML.git
cd AutoBrain-ML

# Create virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
```

## 📝 Usage

```python
from autobrain import AutoBrainML

# Initialize AutoBrain
auto_ml = AutoBrainML()

# Load your dataset
auto_ml.load_data('path/to/dataset.csv')

# Configure preferences
auto_ml.set_preferences(
    model_type='classification',
    optimize_for='accuracy',
    neural_layers=[128, 64, 32]
)

# Train and optimize
best_model = auto_ml.train()

# Evaluate
results = auto_ml.evaluate()

# Export best model
auto_ml.export_model('best_model.pkl')
```

## 📊 Expected Outcomes

- ✅ Fully automated ML pipeline from data to deployment
- ✅ Optimized model selection based on data characteristics
- ✅ Best performing model with highest accuracy
- ✅ Minimal user intervention required
- ✅ Export-ready models for production use
- ✅ Comprehensive performance reports

## 📝 Individual Work Files

Each team member has a dedicated work file in the `work_assignments/` directory:
- `DISOOR_WORK.md` - System Integration tasks
- `YOGI_WORK.md` - Data Preprocessing tasks
- `NESAN_WORK.md` - ML Models tasks
- `BHARATH_WORK.md` - Neural Network tasks
- `ARUN_WORK.md` - Optimization tasks
- `Sanjith_WORK.md` - Evaluation & Export tasks

## 🤝 Contributing

This is a collaborative project. Each team member should:
1. Work on their assigned module
2. Create feature branches for development
3. Submit pull requests for code review
4. Update their individual work file with progress

## 📝 License

This project is created for educational purposes as part of our M.Tech AI program at VIT Bhopal University.

## 📞 Contact

For questions or collaboration:
- GitHub Issues: [Create an issue](https://github.com/DisoorS/AutoBrain-ML/issues)
- Project Lead: Disoor

---

**Built with ❤️ by the AutoBrain-ML Team**

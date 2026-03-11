<div align="center">
<h1 style="color: #1e90ff; font-size: 2.8em; text-shadow: 2px 2px 4px rgba(0,0,0,0.2);"> Loan Approval Prediction Model</h1>
  <p style="font-size: 1.2em; color: #333; margin: 10px 0;">A Machine Learning project to predict loan application approvals based on applicant details.</p>   <p style="margin: 20px 0;">
    <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python Badge"/>
    <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas Badge"/>
    <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy Badge"/>
    <img src="https://img.shields.io/badge/Matplotlib-333333?style=for-the-badge&logo=matplotlib&logoColor=white" alt="Matplotlib Badge"/>
    <img src="https://img.shields.io/badge/Seaborn-333333?style=for-the-badge&logo=seaborn&logoColor=white" alt="Seaborn Badge"/>
    <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" alt="Scikit-learn Badge"/>
    <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter Notebook Badge"/>
  </p>
</div>

<div style="background: linear-gradient(135deg, #667eea 0%, #764ba2 100% ); color: #ffffff; padding: 30px; border-radius: 12px; text-align: center; margin: 20px 0;">
<h2 style="color: #ffffff; margin-top: 0;"> Project Overview</h2>
  <p style="font-size: 1.15em; line-height: 1.8;">
    This project leverages <strong>Machine Learning</strong> to predict whether a loan application will be <strong>approved</strong> or <strong>rejected</strong> based on various applicant details. The comprehensive dataset includes crucial features such as <strong>applicant income</strong>, <strong>loan amount</strong>, <strong>credit history</strong>, <strong>education level</strong>, and <strong>property area</strong>, enabling a sophisticated prediction model.
  </p>
</div>

<div style="background-color: #f8f9fa; padding: 25px; border-left: 5px solid #1e90ff; border-radius: 8px; margin: 20px 0;">
<h2 style="color: #1e90ff;">Technologies & Libraries</h2>
  <table style="width: 100%; border-collapse: collapse; margin-top: 15px;">
    <thead>
      <tr style="background-color: #1e90ff; color: white;">
        <th style="padding: 12px; text-align: left; border: 1px solid #ddd;">Technology</th>
        <th style="padding: 12px; text-align: left; border: 1px solid #ddd;">Purpose</th>
      </tr>
    </thead>
    <tbody>
      <tr style="background-color: #ffffff;">
        <td style="padding: 12px; border: 1px solid #ddd;"><strong>Python</strong></td>
        <td style="padding: 12px; border: 1px solid #ddd;">Primary programming language for development</td>
      </tr>
      <tr style="background-color: #f0f4ff;">
        <td style="padding: 12px; border: 1px solid #ddd;"><strong>Pandas</strong></td>
        <td style="padding: 12px; border: 1px solid #ddd;">Data manipulation, cleaning, and analysis</td>
      </tr>
      <tr style="background-color: #ffffff;">
        <td style="padding: 12px; border: 1px solid #ddd;"><strong>NumPy</strong></td>
        <td style="padding: 12px; border: 1px solid #ddd;">Numerical operations and array handling</td>
      </tr>
      <tr style="background-color: #f0f4ff;">
        <td style="padding: 12px; border: 1px solid #ddd;"><strong>Matplotlib & Seaborn</strong></td>
        <td style="padding: 12px; border: 1px solid #ddd;">Data visualization and statistical plots</td>
      </tr>
      <tr style="background-color: #ffffff;">
        <td style="padding: 12px; border: 1px solid #ddd;"><strong>Scikit-learn</strong></td>
        <td style="padding: 12px; border: 1px solid #ddd;">Machine learning models and evaluation metrics</td>
      </tr>
      <tr style="background-color: #f0f4ff;">
        <td style="padding: 12px; border: 1px solid #ddd;"><strong>Jupyter Notebook</strong></td>
        <td style="padding: 12px; border: 1px solid #ddd;">Interactive development and documentation</td>
      </tr>
    </tbody>
  </table>
</div>

<div style="background-color: #fff3cd; padding: 25px; border-left: 5px solid #ffc107; border-radius: 8px; margin: 20px 0;">
<h2 style="color: #ff9800;"> Machine Learning Models</h2>
  <div style="display: grid; grid-template-columns: 1fr 1fr 1fr; gap: 15px; margin-top: 15px;">
    <div style="background-color: #ffffff; padding: 15px; border-radius: 8px; border: 2px solid #ffc107;">
      <h3 style="color: #ff9800; margin-top: 0;"> Logistic Regression</h3>
      <p style="font-size: 0.95em;">A fundamental classification algorithm that models the probability of binary outcomes.</p>
    </div>
    <div style="background-color: #ffffff; padding: 15px; border-radius: 8px; border: 2px solid #ffc107;">
      <h3 style="color: #ff9800; margin-top: 0;"> Decision Tree</h3>
      <p style="font-size: 0.95em;">A non-parametric method for classification with interpretable decision rules.</p>
    </div>
    <div style="background-color: #ffffff; padding: 15px; border-radius: 8px; border: 2px solid #ffc107;">
      <h3 style="color: #ff9800; margin-top: 0;"> Random Forest</h3>
      <p style="font-size: 0.95em;">An ensemble method combining multiple decision trees for robust predictions.</p>
    </div>
  </div>
</div>

<div style="background-color: #e8f5e9; padding: 25px; border-left: 5px solid #4caf50; border-radius: 8px; margin: 20px 0;">
<h2 style="color: #2e7d32;">Project Workflow (Step-by-Step)</h2>
  <ol style="font-size: 1.05em; line-height: 2.2; color: #333;">
    <li><strong> Import Libraries</strong> - Loading essential libraries (NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn)</li>
    <li><strong> Load Dataset</strong> - Reading the loan prediction dataset from CSV file</li>
    <li><strong>Data Cleaning</strong> - Removing unnecessary columns and handling missing values using mode and median</li>
    <li><strong> Label Encoding</strong> - Converting categorical features (Gender, Married, Education, etc.) to numerical format</li>
    <li><strong> Data Visualization</strong> - Creating visualizations including loan status distribution and correlation heatmap</li>
    <li><strong>Feature-Target Split</strong> - Separating features (X) and target variable (y)</li>
    <li><strong> Train-Test Split</strong> - Dividing dataset into 80% training and 20% testing data</li>
    <li><strong> Feature Scaling</strong> - Normalizing numerical features using StandardScaler</li>
    <li><strong> Model Training</strong> - Training three different ML models on the training data</li>
    <li><strong>Model Evaluation</strong> - Assessing performance using Precision, Recall, F1 Score, and Accuracy</li>
    <li><strong> Results Comparison</strong> - Creating accuracy comparison visualization</li>
  </ol>
</div>

<div style="background-color: #f3e5f5; padding: 25px; border-left: 5px solid #9c27b0; border-radius: 8px; margin: 20px 0;">
<h2 style="color: #6a1b9a;"> Dataset Information</h2>
  <p style="font-size: 1.05em; color: #333;">
    The dataset used in this project is stored in the <code style="background-color: #f0f0f0; padding: 2px 6px; border-radius: 3px;">data</code> folder within the repository. It contains comprehensive information for training and evaluating the loan approval prediction models.
  </p>
  <div style="background-color: #ffffff; padding: 15px; border-radius: 8px; margin-top: 15px; border: 2px solid #9c27b0;">
    <p style="margin: 5px 0;"><strong>File:</strong> <code>loan-prediction-dataset.csv</code></p>
    <p style="margin: 5px 0;"><strong>Format:</strong> CSV (Comma-Separated Values)</p>
    <p style="margin: 5px 0;"><strong>Purpose:</strong> Training and testing machine learning models</p>
    <p style="margin: 5px 0;"><strong> Key Features:</strong> Gender, Married, Dependents, Education, Self_Employed, ApplicantIncome, CoapplicantIncome, LoanAmount, Loan_Amount_Term, Credit_History, Property_Area, Loan_Status</p>
  </div>
</div>




<div style="background-color: #e0f2f1; padding: 25px; border-left: 5px solid #009688; border-radius: 8px; margin: 20px 0;">
<h2 style="color: #00695c;">Project Structure</h2>
  <pre style="background-color: #263238; color: #aed581; padding: 15px; border-radius: 8px; font-family: 'Courier New', Courier, monospace; overflow-x: auto;">
loan-approval-prediction/
├──  data/
│   └──  loan-prediction-dataset.csv
├──  loan_model.ipynb
├──  Correlation Heatmap.png
├── accuracy_comparison.png
└── README.md
  </pre>
</div>

<div style="background-color: #fce4ec; padding: 25px; border-left: 5px solid #e91e63; border-radius: 8px; margin: 20px 0;">
<h2 style="color: #c2185b;"> Model Evaluation Metrics</h2>
  <p style="font-size: 1.05em; color: #333; margin-bottom: 15px;">
    The performance of the trained models was rigorously evaluated using the following comprehensive metrics:
  </p>
  <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 15px;">
    <div style="background-color: #ffffff; padding: 12px; border-radius: 8px; border: 2px solid #e91e63;">
      <h4 style="color: #c2185b; margin-top: 0;">Accuracy</h4>
      <p style="font-size: 0.95em;">Overall correctness of the model predictions</p>
    </div>
    <div style="background-color: #ffffff; padding: 12px; border-radius: 8px; border: 2px solid #e91e63;">
      <h4 style="color: #c2185b; margin-top: 0;"> Precision</h4>
      <p style="font-size: 0.95em;">Accuracy of positive predictions (approved loans)</p>
    </div>
    <div style="background-color: #ffffff; padding: 12px; border-radius: 8px; border: 2px solid #e91e63;">
      <h4 style="color: #c2185b; margin-top: 0;"> Recall</h4>
      <p style="font-size: 0.95em;">Coverage of actual positive cases in the dataset</p>
    </div>
    <div style="background-color: #ffffff; padding: 12px; border-radius: 8px; border: 2px solid #e91e63;">
      <h4 style="color: #c2185b; margin-top: 0;"> F1 Score</h4>
      <p style="font-size: 0.95em;">Harmonic mean of precision and recall</p>
    </div>
    <div style="background-color: #ffffff; padding: 12px; border-radius: 8px; border: 2px solid #e91e63; grid-column: 1 / -1;">
      <h4 style="color: #c2185b; margin-top: 0;"> Confusion Matrix</h4>
      <p style="font-size: 0.95em;">Detailed breakdown of true positives, false positives, true negatives, and false negatives</p>
    </div>
  </div>
</div>

<div style="background-color: #ffe0b2; padding: 25px; border-left: 5px solid #ff6f00; border-radius: 8px; margin: 20px 0;">
<h2 style="color: #e65100;"> Project Output & Visualizations</h2>   <h3 style="color: #ff6f00; margin-top: 0;"> Accuracy Comparison</h3>
  <div style="background-color: #ffffff; padding: 15px; border-radius: 8px; text-align: center; margin: 15px 0;">
    <p style="color: #666; font-size: 0.95em;">
      <em>Visual comparison of model accuracies across Logistic Regression, Decision Tree, and Random Forest</em>
    </p>
    <img src="accuracy_comparison.png" alt="Accuracy Comparison Chart" width="500" style="border-radius: 5px; margin-top: 10px;">
  </div>   <h3 style="color: #ff6f00;"> Correlation Heatmap</h3>
  <div style="background-color: #ffffff; padding: 15px; border-radius: 8px; text-align: center; margin: 15px 0;">
    <p style="color: #666; font-size: 0.95em;">
      <em>Visual representation of feature correlations in the dataset</em>
    </p>
    <img src="Correlation Heatmap.png" alt="Correlation Heatmap" width="500" style="border-radius: 5px; margin-top: 10px;">
  </div>   <h3 style="color: #ff6f00;"> Loan Status Distribution</h3>
  <div style="background-color: #ffffff; padding: 15px; border-radius: 8px; text-align: center; margin: 15px 0;">
    <p style="color: #666; font-size: 0.95em;">
      <em>Distribution of approved and rejected loan applications in the dataset</em>
    </p>
    <p style="color: #999; font-size: 0.85em;">
      <strong>Placeholder:</strong> Replace with your actual loan status distribution chart
    </p>
  </div>
</div>

<div style="background-color: #c8e6c9; padding: 25px; border-left: 5px solid #388e3c; border-radius: 8px; margin: 20px 0;">
<h2 style="color: #1b5e20;"> Key Features</h2>
  <ul style="font-size: 1.05em; line-height: 2; color: #333;">
    <li><strong>Comprehensive Data Preprocessing</strong> - Handles missing values using mode and median imputation</li>
    <li> <strong>Label Encoding</strong> - Converts categorical features to numerical format for model training</li>
    <li> <strong>Feature Scaling</strong> - Normalizes features using StandardScaler for optimal model performance</li>
    <li> <strong>Multiple ML Models</strong> - Implements three different classification algorithms</li>
    <li><strong>Detailed Evaluation</strong> - Uses multiple metrics (Precision, Recall, F1 Score, Accuracy)</li>
    <li><strong>Data Visualization</strong> - Includes correlation analysis and performance comparisons</li>
    <li><strong>Jupyter Notebook</strong> - Interactive and well-documented code with clear comments</li>
  </ul>
</div>

<div style="background-color: #bbdefb; padding: 25px; border-left: 5px solid #1976d2; border-radius: 8px; margin: 20px 0;">
<h2 style="color: #0d47a1;">How to Use</h2>
  <ol style="font-size: 1.05em; line-height: 2.2; color: #333;">
    <li><strong>Clone the Repository</strong>
      <pre style="background-color: #263238; color: #aed581; padding: 10px; border-radius: 5px; font-family: 'Courier New', Courier, monospace; overflow-x: auto;">git clone https://github.com/yourusername/loan-approval-prediction.git
cd loan-approval-prediction</pre>
    </li>
    <li><strong>Install Dependencies</strong>
      <pre style="background-color: #263238; color: #aed581; padding: 10px; border-radius: 5px; font-family: 'Courier New', Courier, monospace; overflow-x: auto;">pip install pandas numpy matplotlib seaborn scikit-learn jupyter</pre>
    </li>
    <li><strong>Place Dataset</strong> - Ensure <code>loan-prediction-dataset.csv</code> is in the <code>data</code> folder</li>
    <li><strong>Open the Jupyter Notebook</strong>
      <pre style="background-color: #263238; color: #aed581; padding: 10px; border-radius: 5px; font-family: 'Courier New', Courier, monospace; overflow-x: auto;">jupyter notebook loan_model.ipynb</pre>
    </li>
    <li><strong>Run the Cells</strong> - Execute cells sequentially to load data, train models, and evaluate performance</li>
  </ol>
</div>

<div style="background-color: #f1f8e9; padding: 25px; border-left: 5px solid #689f38; border-radius: 8px; margin: 20px 0;">
<h2 style="color: #33691e;"> Learning Outcomes</h2>
  <p style="font-size: 1.05em; color: #333; line-height: 1.8;">
    Through this project, you will gain proficiency in:
  </p>
  <ul style="font-size: 1.05em; line-height: 2; color: #333;">
    <li> <strong>Data Preprocessing Techniques</strong> - Cleaning, handling missing values, and preparing data for ML</li>
    <li> <strong>Feature Engineering</strong> - Label encoding and feature scaling for improved model performance</li>
    <li> <strong>Machine Learning Classification</strong> - Building and training multiple classification models</li>
    <li> <strong>Model Evaluation</strong> - Assessing model performance with various metrics and confusion matrices</li>
    <li> <strong>Data Visualization</strong> - Creating insightful plots, heatmaps, and comparison charts</li>
    <li> <strong>Ensemble Methods</strong> - Understanding how Random Forest combines multiple models</li>
  </ul>
</div>
<div style="background-color: #e3f2fd; padding: 25px; border-left: 5px solid #2196f3; border-radius: 8px; margin: 20px 0;">
<h2 style="color: #1565c0;"> Model Performance Summary</h2>
  <p style="font-size: 1.05em; color: #333; margin-bottom: 15px;">
    The three models are evaluated on the test dataset with the following metrics:
  </p>
  <table style="width: 100%; border-collapse: collapse;">
    <thead>
      <tr style="background-color: #2196f3; color: white;">
        <th style="padding: 12px; text-align: left; border: 1px solid #ddd;">Model</th>
        <th style="padding: 12px; text-align: center; border: 1px solid #ddd;">Precision</th>
        <th style="padding: 12px; text-align: center; border: 1px solid #ddd;">Recall</th>
        <th style="padding: 12px; text-align: center; border: 1px solid #ddd;">F1 Score</th>
        <th style="padding: 12px; text-align: center; border: 1px solid #ddd;">Accuracy</th>
      </tr>
    </thead>
    <tbody>
      <tr style="background-color: #ffffff;">
        <td style="padding: 12px; border: 1px solid #ddd;"><strong>Logistic Regression</strong></td>
        <td style="padding: 12px; text-align: center; border: 1px solid #ddd;">0.7596153846153846</td>
        <td style="padding: 12px; text-align: center; border: 1px solid #ddd;">0.9875</td>
        <td style="padding: 12px; text-align: center; border: 1px solid #ddd;">0.8586956521739131</td>
        <td style="padding: 12px; text-align: center; border: 1px solid #ddd;">0.7886178861788617</td>
      </tr>
      <tr style="background-color: #e3f2fd;">
        <td style="padding: 12px; border: 1px solid #ddd;"><strong>Decision Tree</strong></td>
        <td style="padding: 12px; text-align: center; border: 1px solid #ddd;">0.7682926829268293</td>
        <td style="padding: 12px; text-align: center; border: 1px solid #ddd;">0.7875</td>
        <td style="padding: 12px; text-align: center; border: 1px solid #ddd;">0.7777777777777778</td>
        <td style="padding: 12px; text-align: center; border: 1px solid #ddd;">0.7073170731707317</td>
      </tr>
      <tr style="background-color: #ffffff;">
        <td style="padding: 12px; border: 1px solid #ddd;"><strong>Random Forest</strong></td>
        <td style="padding: 12px; text-align: center; border: 1px solid #ddd;">0.7524752475247525</td>
        <td style="padding: 12px; text-align: center; border: 1px solid #ddd;">0.95</td>
        <td style="padding: 12px; text-align: center; border: 1px solid #ddd;">0.8397790055248618</td>
        <td style="padding: 12px; text-align: center; border: 1px solid #ddd;">0.7642276422764228</td>
      </tr>
    </tbody>
  </table>
  <p style="font-size: 0.9em; color: #999; margin-top: 10px;"></p>
</div>

<div align="center" style="background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); color: #ffffff; padding: 30px; border-radius: 12px; margin: 20px 0;">
<h2 style="color: #ffffff; margin-top: 0;"> Author</h2>
  <p style="font-size: 1.3em; font-weight: bold; margin: 10px 0;">Sonia Thakur</p>

</div>
<div align="center" style="padding: 20px; color: #666;">
<p style="font-size: 0.95em;">
    ⭐ If you found this project helpful, please consider giving it a star on GitHub!
  </p>
</div>





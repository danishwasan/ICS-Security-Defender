# ICS-Security-Defender

ICS Security Defender - An AutoML-Based Solution for Industrial Control Systems Security

Project Overview

The ICS Security Defender project aims to enhance the cybersecurity of Industrial Control Systems (ICS) using an automated approach powered by AutoML. By integrating advanced feature engineering with AutoML frameworks, this solution reduces the dependency on domain expertise, allowing non-experts to deploy effective cybersecurity measures. The project is designed to defend ICS, such as power systems and electric vehicle chargers, against cyber threats, ensuring reliable and resilient infrastructure.

Key Features

	•	Automated Machine Learning (AutoML): The system leverages AutoML to automate model selection, hyperparameter tuning, and feature engineering, making it accessible to users without extensive ML expertise.
	•	Feature Engineering: Includes preprocessing steps, feature selection, and transformation to optimize data for machine learning models.
	•	Ensemble of Algorithms: Utilizes a mix of algorithms (e.g., Generalized Linear Models, Gradient Boosting, Random Forest, Deep Learning) to create a robust defense mechanism.
	•	Evaluation on Diverse Datasets: Tested on datasets from power systems and electric vehicle chargers, demonstrating versatility across different ICS domains.
	•	Partial Dependence and Learning Curves: Provides insight into feature importance and model performance through visualization tools, improving interpretability and communication with non-technical stakeholders.

Project Structure

	•	Feature Engineering: Preprocessing steps to clean data, handle outliers, and normalize features using Robust Scaler, tailored for ICS data.
	•	AutoML Frameworks: Comparison and implementation of various AutoML frameworks (Auto-Keras, TPOT, Gluon, and H2O), with the optimal framework selected based on performance metrics.
	•	Model Training and Aggregation: Employs ensemble learning with a meta-learner to combine base models, enhancing the defense system’s prediction accuracy and robustness.
	•	Performance Evaluation: Includes detailed metrics such as accuracy, precision, recall, F1-score, and confusion matrices to assess model efficacy across different datasets and threat scenarios.

Technical Requirements

	•	Python Libraries: TensorFlow, Scikit-learn, Pandas, and Matplotlib for model training, data handling, and visualization.
	•	AutoML Frameworks: Integrates Auto-Keras, TPOT, Gluon, and H2O for automated model training and optimization.

How It Works

	1.	Data Preparation: ICS data, including power system and electric vehicle charging data, undergoes preprocessing and feature engineering.
	2.	AutoML Optimization: AutoML frameworks are applied to select the best model for each dataset, optimizing based on performance, scalability, and training time.
	3.	Ensemble Model Creation: Combines predictions from multiple algorithms to form a comprehensive defense, with a meta-learner aggregating base models for final predictions.
	4.	Evaluation and Visualization: Metrics and visualizations (ROC curves, confusion matrices) are generated to evaluate and interpret the model’s performance.

Results and Findings

	•	High Accuracy: Achieved average accuracies of 93.75%, 94.38%, and 87.12% for power systems datasets and 94.23% for the electric vehicle charging dataset, surpassing baseline AutoML frameworks.
	•	Robustness Against ICS Threats: The ICS Defender consistently outperforms other AutoML frameworks across different types of ICS data, offering a reliable solution for industrial cybersecurity.

Conclusion

The ICS Security Defender provides a powerful, automated approach to securing Industrial Control Systems. By combining AutoML with advanced feature engineering, it reduces the dependency on specialized knowledge, making ICS cybersecurity accessible to a broader audience. This project demonstrates the potential of AutoML in enhancing critical infrastructure security.


Cite This Work 

Danish Vasan, Ebtesam Jubran S. Alqahtani, Mohammad Hammoudeh, Adel F. Ahmed,
An AutoML-based security defender for industrial control systems,
International Journal of Critical Infrastructure Protection,
Volume 47,
2024,
100718,
ISSN 1874-5482,
https://doi.org/10.1016/j.ijcip.2024.100718.
(https://www.sciencedirect.com/science/article/pii/S1874548224000593)
Abstract: Securing Industrial Control Systems (ICS) against cyber threats is crucial for maintaining operational reliability and safety in critical infrastructure. Traditional Machine Learning (ML) approaches in ICS development require substantial domain expertise, posing challenges for non-experts. To address this gap, we propose and evaluate ICS-defender, a defense mechanism to enhance ICS security through Automated Machine Learning (AutoML) techniques. Our approach leverages sophisticated feature engineering and AutoML to automate model selection, training, aggregation, and optimization, thereby reducing the dependency on specialized knowledge. We evaluate ICS-defender against state-of-the-art AutoML frameworks using diverse datasets from power systems and electric vehicle chargers. Experimental results consistently demonstrate that ICS-defender outperforms existing frameworks in terms of accuracy and robustness, achieving average accuracies of 93.75%, 94.34%, and 87.12% for power systems attacks datasets and 94.23% for the electric vehicle charging station attacks dataset, surpassing baseline algorithms. This research contributes to advancing secure and resilient ICS, offering significant implications for broader applications and future enhancements in industrial cybersecurity.
Keywords: Feature engineering; Feature transformation; Automated machine learning; Industrial control system; Network traffic attacks analysis; Security defender; Reduced domain expertise

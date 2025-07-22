# Medical-Appointment-No-Show-Prediction

**Project Summary**

- This project addresses a critical inefficiency in healthcare — patients missing scheduled appointments (no-shows), which leads to wasted resources and reduced care access.
- The client, a medical ERP provider, sought a machine learning solution to integrate into their software for real-time prediction of patient attendance.
- By embedding this model within the ERP system, the project empowers healthcare providers to manage appointments proactively, boosting efficiency and service delivery.

**Techniques Used**

- **Data infrastructure:** Utilized Snowflake for secure cloud data storage and AWS SageMaker for model development and deployment. Integrated AWS Lambda and API Gateway for real-time API access.
- **Data preprocessing:** Performed feature engineering (e.g., time gap between scheduled and appointment date), encoding, normalization, and class balancing (SMOTE, downsampling, etc.).
- **Modeling & Deployment:** Evaluated multiple algorithms (Logistic Regression, Random Forest, Decision Tree, XGBoost). Final deployment of optimized XGBoost model with tuned hyperparameters through a serverless AWS setup.
  
**Results and Impact**

- Enabled appointment optimization, reduced no-show rates, and improved resource utilization, delivering measurable savings to healthcare facilities.
- Dashboards and model insights allowed for strategic decision-making, better staff allocation, and identification of high-risk no-show segments.
- Modular architecture supports future enhancements and integration across varied medical environments, ensuring continued ROI for the client.

**Conclusion**

- Deployed a real-time prediction API using AWS SageMaker, Lambda, and API Gateway, fully integrated into the client's ERP environment.
- Achieved strong AUC and F1 scores, validating the model's capability to generalize well across unseen patient data.
- Delivered not just a predictive model but a solution tailored to real-world business constraints and healthcare operational goals.

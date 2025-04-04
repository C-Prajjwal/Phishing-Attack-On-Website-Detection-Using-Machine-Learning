# Phishing-Website-Detection
The emphasis is on examining and obtainingURL-basedcharacteristics to effectively identify phishingattacksondubious websites. These characteristics aredirectlyobtained from the URL's structure, which is anessentialinformation source. A collection of rules that extracthidden patterns and relations fromthe dataset isfirstconstructed in order to guarantee the robustnessoftherules driving feature extraction. To determinetheserules,a thorough analysis of the URL structure is conducted.The features are retrieved and then mergedintoafeaturevector, which is what the models use as input.Therearea lot of machine learning classifiers used, suchtendifferent models and one ensemble model. Thisensemble model improves website classificationaccuracy by utilising the combined intelligenceofthevarious models. The optimal classifier is determinedbya thorough evaluation process using performanceindicators like accuracy and error rate. It's interestingtonote that the Ensemble Model attains anoutstandingaccuracy of 95%, while the XGBoost model emergesasthe best classifier with an incredible 97.4%accuracy

# Datasets
The dataset includes approximately11,000URLs from websites with 30 website parametersandaclass-level label indicating if a website, either 1or-1,isa phishing website. When it comes to onlinefeatures,this collection of characteristics is quite variable: URLstructure, several indicators (such as the useof HTTPS,the length of domain registration, and the existenceofsymbols or redirections), etc. There was noneedforadditional categorical encoding because everyfeaturewas encoded in integer format. Inspectionrevealedthatthe dataset is free of outliers and missing values, makingit suitable for analysis.

# List of Modules
The project has been implemented by dividing the entire project into three modules.They are as follows:

**1 Data Collection and Preprocessing.
2 Feature Extraction.
3 Classification.**

# List of Modules Used:

 Numpy
 Pandas
 Matplotlib
 Seaborn
 Beautifulsoup4
 Streamlit
 Requests
 Scikit_Learn
 Urllib3
 Streamlit option menu
 Pickle 

# List of Models

The project has been implemented by using ten different models and along with ensemble model.They are as follows:
• Gradient Boosting
• Catboost
• XGBoost
• Random Forest
• Support Vector Machine
• Multi Layer Perceptron
• Decision Tree
• K-Nearest Neighbors
• Logistic Regression
• Navie Bayes
• Ensemble 

# Conclusion
The machine learning for phishing website detection represents a significant advancement in combating the ever-evolving threat landscape of cyberattacks. Through the integration of sophisticated algorithms and comprehensive testing methodologies, machine learning models can effectively distinguish between legitimate websites and malicious phishing attempts. By harnessing the power of feature extraction, classification techniques, and ensemble learning, these models can analyze URL characteristics and user behavior patterns to identify potential threats with high accuracy. Furthermore, the development of modular and scalable solutions, coupled with rigorous testing at each stage, ensures the reliability and efficacy of the detection system. As the sophistication of phishing attacks continues to increase, the adoption of machine learning-based approaches offers a proactive and adaptive defense mechanism to safeguard users and organizations against cyber threats. By fostering collaboration between data scientists, cybersecurity experts, and industry stakeholders, we can further enhance the capabilities ofthese detection systems and fortify our digital ecosystems against malicious activities. 


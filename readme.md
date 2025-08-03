Toward-Detection-and-Attribution-of-Cyber-Attacks-in-IoT-enabled-Cyber-physical-Systems
Cyber-Attack Detection and Attribution in ICS/IIoT
This project implements a two-stage ensemble deep learning-based framework for cyber-attack detection and attribution in Industrial Control Systems (ICS), specifically addressing the challenges of imbalanced datasets and unseen attacks.

🔍 Problem Statement
Conventional machine learning approaches suffer when applied to real-world ICS data due to class imbalance and lack of attack variety. Our solution introduces a novel representation learning phase followed by decision tree-based detection and deep neural network-based attribution, ensuring better accuracy and robustness.

💡 Key Features
Two-stage detection pipeline:
Stage 1: Representation learning + Decision Tree
Stage 2: One-vs-All ensemble for attack attribution
Handles imbalanced ICS datasets without oversampling
Predicts unseen cyber-attack patterns effectively
User interface for service providers and remote users
Visualization tools: Accuracy charts, prediction insights
Built with Python, Django, MySQL, HTML/CSS/JS
⚙️ System Architecture
Architecture Diagram

🧩 Project Modules
🔐 Service Provider
Train/Test datasets
View results, download models
Manage remote users
👥 Remote User
Register/Login
Predict attack type
View profile
🛠️ Admin
Authorize users
Monitor system usage
🧪 Testing
The system is tested using:

Unit testing
Integration testing (Top-down and Bottom-up)
Output and validation checks
User acceptance testing with real and artificial datasets
📚 Software Stack
Component	Technology
Front-end	HTML, CSS, JS
Backend	Django (Python)
Database	MySQL
Libraries	NumPy, Pandas, Matplotlib, Scikit-learn
🏁 How to Run
Clone the repo:
git clone https://github.com/Anil5493/Cyber-Attack-Detection-ICS.git
Install dependencies:
pip install -r requirements.txt
Start Django server:
python manage.py runserver
📈 Results
High accuracy and recall on real ICS datasets
Robustness against class imbalance
Real-time attack attribution
📖 References
See full References list for papers and datasets used.

🙋‍♂️ Author
Anil [Gadagoni Anil]
First project – B.Tech in Artificial Intelligence & Data Science
CMR Institute of Technology, Hyderabad
Email: [gadagonianil@gmil.com] | LinkedIn: [www.linkedin.com/in/gadagoni-anil]

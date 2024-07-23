#EstiMotor

Web application that estimates the current selling price of a car based on various features such as the year, present price, kilometers driven, fuel type, seller type, transmission type, and the number of previous owners. This application uses machine learning algorithms for price prediction and provides a user-friendly interface for car owners to input their car details and get an accurate estimate.


Tech Stack
Frontend: React.js
Backend: Flask, Python
Machine Learning: Scikit-learn, TensorFlow
Database: SQLite (or any database supported by SQLAlchemy)
API: RESTful API with Flask


Installation
Follow these steps to set up the project locally.

Prerequisites
Python 3.8+

Node.js 14+

npm 6+


Backend Setup

Clone the repository:

bash
Copy code
git clone https://github.com/priya2004k/EstiMotor.git
cd EstiMotor/backend
Create and activate a virtual environment:

bash
Copy code
python3 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
Install dependencies:

bash
Copy code
pip install -r requirements.txt
Run the Flask app:

bash
Copy code
python app.py
Frontend Setup
Navigate to the frontend directory:

bash
Copy code
cd ../frontend
Install dependencies:

bash
Copy code
npm install
Start the React development server:

bash
Copy code
npm start
Usage
Ensure the Flask backend is running:

bash
Copy code
python app.py
Ensure the React frontend is running:

bash
Copy code
npm start
Open your browser and navigate to http://localhost:3000.

Input the car details in the form and click "Get Estimate" to receive the estimated selling price.

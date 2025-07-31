
**General Notes**

An `onlinecourse App`

** How to Run **

🛠️ How to Run the Project
Follow these steps to set up and run the Django project locally.

# 1. (Optional) Upgrade system packages
pip install --upgrade distro-info
pip3 install --upgrade pip==23.2.1

# 2. Install virtualenv (only once)
pip install virtualenv

# 3. Create and activate a virtual environment
virtualenv djangoenv
source djangoenv/bin/activate  # On Windows: .\djangoenv\Scripts\activate

# 4. Install dependencies
pip install -U -r requirements.txt

# 5. Apply database migrations
python3 manage.py makemigrations
python3 manage.py migrate

# 6. Run the development server
python3 manage.py runserver

After running Visit
http://127.0.0.1:8000/



**ER Diagram**


![Onlinecourse ER Diagram](https://github.com/ibm-developer-skills-network/final-cloud-app-with-database/blob/master/static/media/course_images/onlinecourse_app_er.png)

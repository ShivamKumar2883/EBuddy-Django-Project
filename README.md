Cloning the Repository
Clone the repository using the command below:
bash
Run
Copy code
git clone https://github.com/ShivamKumar2883/EBuddy.git
Move into the directory where we have the project files:
bash
Run
Copy code
cd EBuddy
Create a virtual environment:
bash
Run
Copy code
# Let's install virtualenv first
pip install virtualenv

# Then we create our virtual environment
virtualenv envname
Activate the virtual environment:
bash
Run
Copy code
envname\Scripts\activate
Install the requirements:
bash
Run
Copy code
pip install -r requirements.txt
Running the App
To run the App, we use:
bash
Run
Copy code
python manage.py runserver
⚠ Then, the development server will be started at http://127.0.0.1:8000/

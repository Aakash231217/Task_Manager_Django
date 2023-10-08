Here are the general steps:

Clone the repository:

Open your terminal/command prompt then navigate to your desired directory using the cd command. Clone the repository by using the following command:


git clone https://github.com/Aakash231217/Task_Manager_Django.git
Navigate to the cloned repository:

Use the change directory command to go into the repository:


cd Task_Manager_Django
Create a Virtual Environment:

It's best to create a virtual environment to keep your project's dependencies isolated from other Python projects. Here's how to do it:

If you're using Windows:


python -m venv env
If you're using Unix or MacOS:


python3 -m venv env
Activate the Virtual Environment:

If you're using Windows:


.\env\Scripts\activate
If you're using Unix or MacOS:


source env/bin/activate
Install Dependencies:

Given the lack of a requirements file in the repository, you may have to install Django manually with the following command:


pip install django
Run the Project:

You can start the Django development server with this command:


python manage.py runserver
After running this command, you should be able to see your application running by navigating to http://127.0.0.1:8000 in your web browser.

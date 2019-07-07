# Blog Aggregator
This is a django based web application. One need to install python, django and other dependencies to run this project. It's recommended to create a virtual environment and start contributing.
### Installation Instructions
1.Install Python3 and pip
2.Install `virtualenvwrapper` and add it to your terminal path.
3.Clone the repository and create the virtual environment
    ```
      $ git clone https://github.com/abhishekbvs/blog-aggregator.git
      $ cd blog-aggregator
      $ mkvirtualenv --python=python3 webapp
      $ workon webapp
    ```
4.Install the dependencies from `requirements.txt`
    ```
      $ pip install -r requirements.txt
    ```
### Running the Application
1.Start the virtual environment `workon webapp`
2.Set up the database
    ```
      python manage.py migrate
    ````
3.Create super user
    ```
      python manage.py createsuperuser
    ```
4.Run the project
    ```
      python manage.py runserver
    ```

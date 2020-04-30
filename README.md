# JustChat
## Installation

### Prerequisites

#### 1. Install Python
Install ```python-3.7.2``` and ```python-pip```. Follow the steps from the below reference document based on your Operating System.
Reference: [https://docs.python-guide.org/starting/installation/](https://docs.python-guide.org/starting/installation/)

#### 2. Setup virtual environment
   - python -m venv venv  
   - venv/Scripts/activate

#### 3. Clone git repository
```bash
git clone "https://github.com/nilay1221/JustChat.git"
```

#### 5. Install requirements
```bash
pip install -r requirements.txt
```

#### 6. Run the server
```bash
# Make migrations
python manage.py makemigrations
python manage.py migrate

# Make admin user
python manage.py createsuperuser

# Run the server
python manage.py runserver 

# your server is up on port 8000
```
Try opening [http://localhost:8000](http://localhost:8000) in the browser.
Now you are good to go.


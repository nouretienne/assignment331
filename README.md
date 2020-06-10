# assignment331


# Installation

"""sh
git clone https://github.com/nouretienne/assignment331.git
cd assignment331
"""


# Setup

"""sh
pipenv install
"""

Migrate the database:

"""sh
set FLASK_APP=web_app         flask db init
set FLASK_APP=web_app         flask db migrate
set FLASK_APP=web_app         flask db upgrade


# Usage
"""sh
set FLASK_APP=web_app.py
flask run
"""
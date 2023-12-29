# rp_flask_board
A practice project utilizing the Flask framework. This is a good introduction to developing with Python's Flask web framework.

## Steps to build (on Mac)
- clone this repository: git clone https://www.github.com/tcrawley2/rp_flask_board.git
- create virtual environment: python -m venv venv
- activate virtual environment: source venv/bin/activate
- download Flask: pip install flask
- download dotenv: pip install python-dotenv
- create .env file w/ ENVIRONMENT, FLASK_SECRET_KEY, and FLASK_DATABASE variables
- initialize the database: python -m flask --app board run init-db
- start local server: python -m flask --app board run --port 8000 --debug

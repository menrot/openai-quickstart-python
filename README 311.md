# OpenAI API Quickstart - Python example app - to work with 3.11

Changes required for 3.11

## Setup

1. If you don’t have Python installed, [install it from here](https://www.python.org/downloads/)

2. Clone this repository

3. Navigate into the project directory

   ```bash
   $ cd openai-quickstart-python
   ```

4. Create a new virtual environment

   ```bash
   $ python -m venv venv
   $venv\scripts\activate
   #  . venv/bin/activate
   ```

5. Install the requirements

	upgrade pip
	```bash
	$ python.exe -m pip install --upgrade pip #latest pip
	```
   Updtae requirements.txt:
   
	numpy==1.23.5
	pandas==1.5.2

   ```bash
flask   $ pip install -r requirements.txt
   ```

6. Make a copy of the example environment variables file

   ```bash
   $ copy .env.example .env
   ```

7. Add your [API key](https://beta.openai.com/account/api-keys) to the newly created `.env` file

8. Run the app

   ```bash
   $ flask run
   ```

You should now be able to access the app at [http://localhost:5000](http://localhost:5000)! For the full context behind this example app, check out the [tutorial](https://beta.openai.com/docs/quickstart).

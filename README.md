# poc-inference-ai
Proof-of-Concept for Inference API server using Flask and load some simple PyTorch image recognition model

P.S. All code are from this tutorial [DEPLOYING PYTORCH IN PYTHON VIA A REST API WITH FLASK](https://pytorch.org/tutorials/intermediate/flask_rest_api_tutorial.html).
Instruction to run was generated by ChatGPT.

# Setup and Running
To run a Python Flask project, you will need to have [Python](http://python.org) installed on your machine.

1. Open a terminal or command prompt.
2. Navigate to the root directory of your Python Flask project using the `cd` command. For example, if your project is located in a directory called "myproject," you would use the command `cd myproject`.
3. Create and activate a virtual environment by running the following commands:
```
python3 -m venv venv
source venv/bin/activate
```
This will create a virtual environment called "venv" and activate it. This is a good practice to isolate the dependencies of your project from the global Python environment.
4. Install the project dependencies by running the command `pip install -r requirements.txt`. This will read the `requirements.txt` file in your project and install any Python packages that are listed there.
5. Run the Python Flask project by using the command:
```
FLASK_ENV=development FLASK_APP=app.py flask run
```
This will start the Flask development server and run the application.

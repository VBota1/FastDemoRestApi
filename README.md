# FastDemoRestApi
Fast Demo Rest Api

## Setup Virtual Environment

1.  Create a virtual environment (replace `venv` with your preferred environment name):
    ```bash
    python -m venv venv
    ```
2.  Activate the virtual environment:
    -   On Windows:
        ```bash
        .\venv\Scripts\activate
        ```
    -   On macOS and Linux:
        ```bash
        source venv/bin/activate
        ```

## Running the API

1. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```
2. Run the API:
   ```bash
   uvicorn main:app --reload
   ```
   The API will be available at `http://127.0.0.1:8000`.

## Running Tests

1. Install test dependencies (if not already installed with the main dependencies):
   ```bash
   pip install -r requirements.txt
   ```
2. Run the tests:
   ```bash
   pytest
   ```

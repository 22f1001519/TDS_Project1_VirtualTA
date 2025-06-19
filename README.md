# TDS VirtualTA Project

This project is a FastAPI application that provides various endpoints for handling tasks, reading files, and processing data. It utilizes SQLite for database operations and includes several utility functions for data manipulation.

## Project Structure

```
TDS_Project1_VirtualTA
├── main.py          # Contains the FastAPI application and endpoint definitions
├── complete.db           # Databade File
├── requirements.txt     # Lists the Python dependencies required for the project
├──  README.md            # Documentation for the project
└──project-tds-virtual-ta-promptfoo.yaml
```

## Setup Instructions

1. **Clone the repository:**
   ```
   git clone https://github.com/22f1001519/TDS_Project1_VirtualTA.git
   cd TDS_Project1_VirtualTA
   ```

2. **Create a virtual environment (optional but recommended):**
   ```
   python -m venv venv
   source venv/bin/activate
   ```
3. **Install dependencies:**
   ```
   pip install -r requirements.txt
   ```

4. **Run the application:**
   ```
   uvicorn main:app --reload
   ```

## promptfoo test

Run the promptfoo file provided. 
```
npx -y promptfoo eval --config project-tds-virtual-ta-promptfoo.yaml
```

**The application will be accessible at** `http://localhost:8000/api`.

## Usage

Once the application is running, you can access the API endpoints defined in `main.py`. You can use tools like Postman or curl to interact with the API.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

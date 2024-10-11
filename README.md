# Python Project Template

This is a template for Python projects using VS Code.

## Project Structure

```
.
├── .vscode/
│   └── settings.json
├── docs/
├── src/
├── tests/
├── .gitignore
├── main.py
├── README.md
└── requirements.txt
```

## Setup

1. Clone this repository
2. Create a virtual environment: `python3 -m venv .venv`
3. Activate the virtual environment:
   - On Windows: `.venv\Scripts\activate`
   - On macOS and Linux: `source .venv/bin/activate`
4. Install the required packages: `pip install -r requirements.txt`

## Usage

1. Write your main application code in the `src/` directory
2. Write your tests in the `tests/` directory
3. Run your main application: `python main.py`
4. Run tests: `pytest`

## VS Code Extensions

The following VS Code extensions are recommended for this project:

- Python
- Pylance
- Python Test Explorer for Visual Studio Code
- Python Docstring Generator

## Contributing

1. Fork the repository
2. Create your feature branch: `git checkout -b feature/my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin feature/my-new-feature`
5. Submit a pull request

## License

This project is licensed under the MIT License.

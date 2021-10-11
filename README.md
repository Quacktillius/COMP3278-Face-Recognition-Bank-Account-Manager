# Face Recognition Bank Account Manager

Group Project for COMP3278 - Introduction to Database Management Systems.
## Development Setup

1. Clone this project
2. Make sure pipenv is installed. If it is not, run:
    ```bash
    pip install pipenv
    ```
3. Enter the root directory of the project.
4. Run:
    ```bash
    pipenv install
    ```
## Qt Designer Usage
### Generating a .UI file
1. Run:
    ```bash
    pipenv shell
    pyqt5-tools designer
    ```
2. Use Qt Designer

### Generating code from a .ui file
1. Run:
    ```bash
    pyuic5 -x uiFile.ui -o newOutputFile.py
    ```

## Authors

- [Ajayveer Singh](https://github.com/Quacktillius)
- [Abhigyan Kashyap](https://github.com/Kash1405)
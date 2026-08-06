# Python Markdown Generator
This project was created to make markdown files easier
## Documantation
None yet...
## Building/Running
### Dependancies
Note: all dependencies can be installed using the file in the `.dependencies` folder
#### Python (Recommended: 3.12):
| OS | Command |
| -- | ------ |
| Windows | `winget install python3.12` |
| Linux | `sudo apt-get install python3.12` |
| MacOS | `brew install python@3.12` |
#### CustomTkinter (CTk):
`pip install customtkinter`
### Running
The tool can be run using Python:
```bash
python3 main.py
```
### Building
Can be built for Windows using [py2exe](https://www.py2exe.org/)
## Changelog
### v0.0.1 Setup #2
Commit Message: `Added batchfile to get dependancies for windows` <br>
Initial Branch: `main` (merged) <br>
#### Changes:
Added a file (`.dependancies\getDependancies.bat`) to download and install Python and customTkinter
### v0.0.1 Setup #1
Commit Message: `Added main.py and basic init code` <br>
Initial Branch: `main` (merged) <br>
#### Changes:
Added main.py and made code to open a window in CTk

# python-ocr-scrapper
# Windows
py -3 -m venv .venv
Set-ExecutionPolicy Unrestricted -Scope Process
.venv\scripts\activate
python -m pip install --upgrade pip
python -m pip install flask
python -m pip install pytesseract
python -m pip install requests
python -m pip install beautifulsoup4
python -m pip install pandas
python -m pip install regex
python -m pip install Unidecode
python -m pip install jsonlib
python -m pip install image
python -m flask run


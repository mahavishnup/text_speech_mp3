# Text To Speech MP3

### Installation

1. Download the latest release
    - `git clone --single-branch --branch master --recurse-submodules https://github.com/mahavishnup/text_speech_mp3.git`
2. Within the new directory run the following
    1. `python --version`
    2. `pip --version`
    3. `pip install virtualenv`
    4. `virtualenv --version`
    5. `virtualenv .venv`
    6. `source venv/bin/activate`
    7. `pip freeze > requirements.txt`
    8. `pip install -r requirements.txt`
    9. `py manage.py migrate`
    10. `py manage.py runserver`
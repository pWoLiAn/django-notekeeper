# notepad
A pretty easy django notes app. Have a note save it!

## Features

- CRUD notes
- Copies selected text automatically
- Easily share
- Download note as PDF
- Beautiful yet simple UI
- Encrypted Data so that no one can phish it! ([using django-cryptography](https://github.com/georgemarshall/django-cryptography))

# Installation

- Clone the repository

```bash
git clone https://github.com/pWoLiAn/notepad.git
```

- Install Dependencies

```bash
cd notepad
pip3 install -r requirements.txt
```

- Go to `notepad/notekeeper/notekeeper/` Edit your `settings.py` file and enter your secret key. You can generate a key using the link - [Django Key](https://djecrety.ir/)

```
SECRET_KEY=<your_secret_key>
```

- cd into notekeeper folder

```bash
cd notekeeper
```

- Run django migrations

```bash
python3 manage.py makemigrations

python3 manage.py migrate
```

- Run django server

```bash
python3 manage.py runserver [OPTIONAL PORT ID]
```

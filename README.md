# Hacktoberfest 2021

Welcome to Hacktoberfest 2021!

## Installation
Fork the repository [tw-hacktoberfest-21](https://github.com/TelWare-Hacktoberfest-2021/tw-hacktoberfest-21)

Make sure you have the latest version of [python](https://www.python.org/downloads/) downloaded.

Create a directory called `hacktoberfest`

Clone your forked hacktoberfest repository into the `hacktoberfest` directory

Use the package manager `pip` to install the `virtualenv` 

```bash
pip install virtualenv
```

Create a directory for you environments called `environments` and create a virtual environment inside it called `env-hacktoberfest21`

```bash
virtualenv env-hacktoberfest21
```

Activate the virtual environment

```bash
env-hacktoberfest21\Scripts\activate
```

Navigate to your hacktoberfest repository and use the package manager `pip` to install dependencies.

```bash
pip install -r requirements.txt
```

Run your webservice with `flask run`.
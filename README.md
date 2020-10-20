# Simple Twitter Bot 🤖

This project focus to build a simple Twitter Bot which follow back each user that you’re not already following. And like every tweets that contain certain keywords.

## Project Structure 📂

```shell
twitter-bot/
│
├── bots/
│   └── twitter.py
├── .env
├── requirements.txt
└── Dockerfile
```

## How to start 👷‍♂️

### Step 1️⃣

```shell
$ git clone
$ cd
```

### Step 2️⃣

Store your Twitter API Authentication Credentials in **.env**. You can get from [ Twitter developer site ](https://developer.twitter.com/)

### Step 3️⃣

```shell
$ python3 -m venv env
$ .\env\Scripts\activate
$ pip3 install -r requirements.txt
$ python3 .\bots\twitter.py
```

## You can also deploy to Cloud 🚀

## Way 1️⃣

You can use docker

```shell
$ docker build . -t twitter-bot:1.0
$ docker run -d --restart always
```

## Way 2️⃣

You can use [PythonAnyWhere.com](https://www.pythonanywhere.com/) which is free and can host 24/7

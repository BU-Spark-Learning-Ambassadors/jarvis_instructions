# Jarvis

![](/images/jarvis.png)

## What is a micro-challenge?
- A micro-challenge is a task/challenge that is a small project of code that can be done in a certain amount of time. It can be any idea that comes to mind but has to specifically be innovative and promote learning in any way. It is important that the micro challenges have different difficulty levels because some people might be more experienced than others so there has to be variety in that way. Most challenges should be able to be completed within a couple of hours to 2 days.

## Difficulty = ⭐️ ⭐️ ⭐️

## What you will build:
- The backend for a simple chatbot called Jarvis inspired by Iron Man that can answer questions through natural language understanding. The frontend has been provided already to make things easier.

## How you will build it:
- Follow the instructions below to get started.

## Duration:
- 1 Day

# Instructions
## 🚀 Setup

### Clone this Repo to your local machine:
```bash
git clone https://github.com/lavaman131/jarvis.git
```

### Setup API key:
#### For example, if you want to use OPENAI:
https://elephas.app/blog/how-to-create-openai-api-keys-cl5c4f21d281431po7k8fgyol0

#### For example, if you want to use Cohere AI:
https://docs.cohere.ai/

### Setup .env file to store API key and keep safe (⚠️ never expose your API keys publicly):

> **Warning**
> Make sure to add `.env` to your `.gitignore` file

```bash
echo "API_KEY={Put Your API Key Here}" > backend/app/.env
```

### Run the backend server:

1. Go to the backend folder:
```bash
cd backend
```

2. Create virtual environment and install 🐍 Python dependencies:
```bash
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

3. Initialize the backend server:
```bash
cd app
uvicorn api:app --host 0.0.0.0 --port 8080
```

### Run the frontend:
1. Go to the frontend folder:
```bash
cd frontend
```

2. Install npm dependencies:
```bash
npm i
```

3. Initialize frontend:
```bash
npm run dev
```

### Load the website:
http://localhost:3000/

## 🏆 Challenge
1. Go to the backend and then app folder:
   
```bash
cd backend/app
```

2. Edit the `api.py` using the instructions and hints given.

## 🛟 Need Help?

Go to the [Spark! Space](https://www.bu.edu/spark/resources/space/) and ask any student employee for a **Learning Ambassador** that can help with a micro-challenge.

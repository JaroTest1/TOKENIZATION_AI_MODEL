ctr+p select create .env
pip install fastapi uvicorn
pip install httpx
pip install openai
uvicorn main:app --reload
pip install langchain
pip install -U langchain-community
pip install youtube_search
pip install --upgrade --quiet  wikipedia
open http://127.0.0.1:8000

curl -X POST "http://127.0.0.1:8000/generate-code" \
-H "Content-Type: application/json" \
-d '{"prompt": "Write a Python function to add two numbers"}'
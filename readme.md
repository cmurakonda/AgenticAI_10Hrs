-- Installation steps
1. install uv - python package manager
https://docs.astral.sh/uv/getting-started/installation/#__tabbed_1_2
powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"
uv init
uv venv
.venv\Scripts\activate

2. add requirements.txt
langchain
langchain-openai
langchain-community
langchain-groq
langchain-google-genai
python-dotenv
ipykernel
uv add -r requirements.txt

3. keys add
create .env file and add keys
# Universal-ai-tool-
Multi purpose AI tool with free API integration 
cp backend/.env.example backend/.env
# Add your free API keys:
# - Google Gemini: https://makersuite.google.com/app/apikey
# - Claude: https://console.anthropic.com/
# - Hugging Face: https://huggingface.co/settings/tokenscd backend
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install -r requirements.txt
uvicorn app.main:app --reloadcd frontend
npm install
npm startdocker-compose upuniversal-ai-tool/
├── backend/           # FastAPI backend
├── frontend/          # React frontend
├── .github/workflows/ # CI/CD
├── docker-compose.yml # Docker setup
├── Dockerfile         # Backend container
├── README.md          # Documentation
└── LICENSE           # MIT License

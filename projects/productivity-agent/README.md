This is a simple AI agent that can turn tasks written in natural language
into a daily plan that is structured.
what it does:
- extracts tasks
- asseses and assigns priorites with the given due dates
- suggests how to go about tasks ( scheudling)
- gives an output of 'daily_plan.md'

## Start


```bash
pip install -r requirements.txt
# Add your OpenAI key into .env as:
# OPENAI_API_KEY=your_key_here
python agent.py


# AI Seed 2 download

Download AI_Seed_2_Final.zip using GitHub's file download control.
The archive contains source code, Windows setup instructions, 86 passing tests on both Python 3.11 and 3.12,
and a trained narrow risk-policy model.

Offline proposals are scripted mocks; execution, evaluation and neural training
are real. Live Ollama and Windows runtime execution were not verified in cloud.
See README.md and VALIDATION.md inside the archive for setup and evidence.
## Python 3.11 installation fix

The updated ZIP selects NumPy 2.4.6 for Python 3.11 and NumPy 2.5.4 for Python 3.12. Both combinations pass all 86 tests. Windows binary dependencies were checked for both versions; Windows execution remains untested.

For an existing installation, download the requirements.lock.txt file in this branch into the project folder and rerun `.\.venv\Scripts\python.exe -m pip install -r requirements.lock.txt`, then `.\.venv\Scripts\python.exe seed.py`. Your successful Ollama download can be reused.

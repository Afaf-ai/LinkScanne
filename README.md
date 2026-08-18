This project, LinkScanner, is a Python-based malicious link detection tool. 
It uses dynamic analysis with Playwright in a sandboxed environment, and integrates with VirusTotal for external checks.
Requirements:
Python 3.10+, and it runs on Windows, macOS, and Linux. 
The system uses a local SQLite database, caches VirusTotal results, and processes checks in parallel. 
For setup, ensure Playwright is installed and run the model training script. 
Logs are saved locally, and you can test each component individually using the provided scripts. 
For support, check the logs or report issues in the GitHub repo.

# Instagram-BruteForce
Advanced Instagram brute force tool for educational use by Blackwacker DV Academy. Features password protection, resume capability, proxy support, and adjustable delays. Use responsibly and legally with permission only. Developed by Pouya Fakham.

Usage: python bruteforce.py

The tool will ask you for the following inputs step-by-step:

- Target Instagram username (required)
- Path to the password wordlist file (required)
- Proxy (optional, format: http://ip:port)
- Delay between attempts in seconds (optional, default is 1 second)

Example:

python bruteforce.py

Then enter:
Target Instagram username: example_user
Path to password wordlist file: wordlist.txt
Proxy (optional): http://127.0.0.1:8080
Delay between attempts (seconds): 1.5

---

Outputs:

- Successful passwords are saved to "success.txt"
- Progress (last tested line) saved to "resume.txt" to resume later if interrupted
- Logs saved in "bruteforce.log"

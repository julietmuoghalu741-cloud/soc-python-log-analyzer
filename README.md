 soc-python-log-analyzer
This project is a beginner-friendly SOC automation script that reads a log file and extracts suspicious IP addresses from failed login events. It also supports counting repeated failed attempts to help identify brute force behaviour.
 SOC Python Log Analyzer (Beginner Project)
Overview
This project is a beginner-friendly SOC automation script that reads a log file and extracts suspicious IP addresses from failed login events. It also supports counting repeated failed attempts to help identify brute force behavior.

What It Does
- Reads a log file (`server.log`)
- Detects lines containing "Failed login"
- Extracts the source IP address
- Prints a list of suspicious IPs
- (Optional) Counts failed attempts per IP

Skills Demonstrated
- Python fundamentals (loops, lists, dictionaries)
- File handling
- Basic detection logic (brute force patterns)
- SOC thinking: parsing logs + extracting IOCs



![IMG_1202 (1)](https://github.com/user-attachments/assets/ac0dda14-ff9b-45e3-8c30-936622de2e51)
![IMG_1203 (1)](https://github.com/user-attachments/assets/ac275a58-959f-452d-8d2a-45e675389897)


How To Run
1. Make sure `log_analyzer.py` and `server.log` are in the same folder.
2. Run:
   ```bash
   python log_analyzer.py

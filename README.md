# Web-Server-Log-Analysis---Python
Apache Log Analysis in Python 

This project parses and analyzes Apache HTTP server access logs using Python and pandas. It provides insights such as the number of unique hosts, 404 errors, bandwidth usage per day, hourly request distribution, and the most requested files.

## 📂 Log Format

This script assumes the log format is **Common Log Format (CLF)** or **Combined Log Format**, like:
| Task | Description |
|------|-------------|
| ✅ Q1 | Count of unique hosts |
| ✅ Q2 | Total 404 errors |
| ✅ Q3 | Top 5 URLs that caused 404 errors |
| ✅ Q4 | Number of 404 errors per day |
| ✅ Q5 | Total bytes transferred (excluding `-`) |
| ✅ Q6 | Top 15 file extensions causing 404 errors |
| ✅ Q7 | Total bandwidth per day for July 1995 |
| ✅ Q8 | Hourly request distribution |
| ✅ Q9 | Top 10 most requested filenames |

## 🛠 Requirements

- Python 3.8+
- pandas

### 🔧 Install

```bash
pip install pandas

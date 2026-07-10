# Nginx Log Analyser

This is a Bash script designed to analyze standard Nginx access logs directly from the command line. This project was built to practice shell scripting, log auditing, and system monitoring using core Linux utilities like `awk`, `sort`, `uniq`, and `head`.

**Project Page:** [roadmap.sh Nginx Log Analyser](https://roadmap.sh/projects/nginx-log-analyser)

## Features
The script parses an `access.log` file and outputs the following metrics:
1. Top 5 IP addresses with the most requests
2. Top 5 most requested paths
3. Top 5 response status codes
4. Top 5 user agents

## How to Run

1. Clone the repository and navigate into the directory.
2. Make the script executable:
   ```bash
   chmod +x log_analyzer.sh
   ```
3. Run the script and pass your log file as an argument:
   ```bash
   ./log_analyzer.sh nginx_access.log
   ```

## Example Output
```text
Top 5 IP addresses with the most requests:
178.128.94.113 - 1087 requests
142.93.136.176 - 1087 requests
138.68.248.85 - 1087 requests
159.89.185.30 - 1086 requests
86.134.118.70 - 277 requests
```

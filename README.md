
# IP Recon Tool

A simple and lightweight Bash tool for IP geolocation and basic OSINT reconnaissance.

## Installation & Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/jounaid-dev/ip-recon-tool.git
   cd ip-recon-tool
   ```

2. Give execution permissions to the script:

   ```bash
   chmod +x ip_finder
   ```

3. Run the tool:

   ```bash
   ./ip_finder
   ```

## Features

- Dynamic target IP input.
- Automated API queries using `curl`.
- Saves results to `output.txt`.

## Requirements

- Linux or WSL.
- Bash.
- curl.

## API

This tool uses [ip-api.com](http://ip-api.com/) for IP geolocation data.
